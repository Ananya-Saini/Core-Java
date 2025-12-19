1️⃣ Mutable Class A mutable class is a class whose object’s state can be changed after it is created.If any field value of an object can be modified after object creation, the class is mutable.
2️⃣ Immutable Class An immutable class is a class whose object’s state cannot be changed once it is created.Any modification results in the creation of a new object instead of changing the existing one.


| Feature      | Mutable                      | Immutable                   |
| ------------ | ---------------------------- | --------------------------- |
| Object state | Can change                   | Cannot change               |
| Thread-safe  | ❌ Not inherently             | ✅ Yes                       |
| Performance  | Faster updates               | Slower (new object created) |
| Memory usage | Less                         | More                        |
| Examples     | `StringBuilder`, `ArrayList` | `String`, `Integer`         |

How to Create an Immutable Class (Very Important for Interviews ⭐)
To make a class immutable:
Declare the class as final
Make all fields private and final
Do not provide setter methods
Initialize fields via constructor only
If fields are mutable objects, return defensive copies

Why Prefer Immutable Classes? (Interview Gold ✨)
Thread-safe by default
Easy to cache
Secure (state cannot be changed)
Ideal for keys in HashMap

A mutable class allows modification of object state after creation, whereas an immutable class does not allow state changes and ensures thread safety and data integrity.
