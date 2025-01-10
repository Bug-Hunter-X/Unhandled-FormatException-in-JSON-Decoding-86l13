# Unhandled FormatException in JSON Decoding (Dart)

This repository demonstrates a common error in Dart applications involving asynchronous network requests and JSON decoding.  The initial `bug.dart` file showcases the unhandled exception. The `bugSolution.dart` provides a corrected version with proper exception handling.  This example highlights the importance of robust error handling in asynchronous operations to prevent unexpected app crashes.

## How to reproduce
1. Clone the repository
2. Run `bug.dart` (it will likely throw a FormatException)
3. Run `bugSolution.dart` (it handles the exception gracefully)