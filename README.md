# Empty List Error with reduce() method in Dart

This repository contains a simple Dart program that demonstrates an uncommon error that can occur when using the `reduce()` method with an empty list. The `reduce()` method in Dart throws a `StateError` exception if the list it is called on is empty. This is because the `reduce()` method requires at least one element in the list to start the reduction process. If the list is empty, there is nothing to reduce, so the method throws an error.

## Bug

The bug is demonstrated in the `bug.dart` file. The program attempts to use the `reduce()` method on an empty list, which results in a `StateError` exception being thrown.

## Solution

The solution to this bug is to check if the list is empty before calling the `reduce()` method. If the list is empty, you can return a default value, or handle the empty list in a different way. The corrected code is shown in the `bugSolution.dart` file.
