# Dart reduce() Method Error Handling

This repository demonstrates a common, yet subtle error when using the `reduce()` method in Dart. The `reduce()` method throws a `StateError` if applied to an empty list, because it requires at least one element to perform the reduction.

The `bug.dart` file contains the code with the error. The `bugSolution.dart` file presents a robust solution that handles the possibility of an empty list.

## How to reproduce the error

1. Clone the repository.
2. Run the `bug.dart` file using the Dart SDK.
3. Observe the `StateError` exception.