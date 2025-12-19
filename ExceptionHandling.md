Exceptional Handling:
Exception Handling in Java is a mechanism to handle runtime errors so that the normal flow of the program can be maintained.
An exception is an unwanted or unexpected event that occurs during the execution of a program and disrupts its normal flow.

Java provides a robust, object-oriented exception handling framework using the **Throwable class hierarchy**.

Why Exception Handling is Needed?
1.Prevents program termination due to runtime errors
2.Separates error-handling code from business logic
3.Improves program reliability and maintainability
4.Allows graceful recovery instead of abrupt failure

Throwable
 ├── Error
 └── Exception
      ├── Checked Exceptions
      └── Unchecked Exceptions (RuntimeException)

1. Checked Exceptions:Checked at compile time. Must be handled using try-catch or throws

Examples:
IOException
SQLException
FileNotFoundException

2. Unchecked Exceptions: Occur at runtime Not checked by compiler
Examples:
NullPointerException
ArrayIndexOutOfBoundsException
ArithmeticException

3. Errors:Serious problems not meant to be handled by applications
Example: OutOfMemoryError, StackOverflowError

