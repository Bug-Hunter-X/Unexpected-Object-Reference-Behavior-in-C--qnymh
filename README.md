# Unexpected Object Reference Behavior in C#

This repository demonstrates a common C# pitfall involving object references and how modifying an object through one reference affects all other references to the same object.

The `bug.cs` file shows code where assigning one object to another creates a shared reference. Changes made via one reference affect both.

The `bugSolution.cs` file provides a potential solution by creating a deep copy of the object, avoiding shared references and unintended side effects.