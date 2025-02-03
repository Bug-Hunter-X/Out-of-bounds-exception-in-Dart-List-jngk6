# Out-of-bounds exception in Dart List

This repository demonstrates an example of an out-of-bounds exception in Dart, which occurs when you try to access an element in a list using an index that is not within the valid range (0 to length - 1).

## Bug
The `bug.dart` file contains code that attempts to access an element in a list using an index that is out of bounds. This results in a runtime exception.

## Solution
The `bugSolution.dart` file shows how to avoid this error by using appropriate checks to ensure that the index is within the valid range before accessing the list element.  This might involve using a try-catch block to handle the exception or checking the index prior to access.