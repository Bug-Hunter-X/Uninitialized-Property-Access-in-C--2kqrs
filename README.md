# Uninitialized Property Access in C#

This repository demonstrates a common C# error: attempting to access a class property that hasn't been assigned a value. This leads to a `NullReferenceException` at runtime.

## The Problem
The `bug.cs` file contains a `MyClass` with a property `MyProperty`. In `MyMethod`, we attempt to print the value of `MyProperty` without first assigning it a value.  This causes the exception.

## The Solution
The `bugSolution.cs` file shows how to fix the problem by initializing `MyProperty` either in the constructor or directly before accessing it.

## How to Run
1. Clone this repository.
2. Open `bug.cs` and `bugSolution.cs` in your C# IDE (like Visual Studio).
3. Run each file and observe the results (exception versus successful output).