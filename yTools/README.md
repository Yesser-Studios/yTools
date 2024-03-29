﻿# yTools
### The best library for doing and checking simple things.
---
You can start using yTools by adding this using directive: `using yTools;`

Methods have documentation comments and are categorized into multiple classes:
- Booleans - everything related to bool values.
- Doubles - everything related to double values.
- Integers - everything related to int values.
- Strings - everything related to string values.
- Vectors - 2D and 3D Vectors structs. Can be explicitly casted to `System.Numerics.Vector2/3` and implicitly casted vice-versa.
- General - Things not related to anything above.

You can browse IntelliCode suggestions to find different methods in them.

Here's a link to the GitHub repository: 
https://github.com/Yesser-Studios/yTools

You can contribute by forking the repository and submitting a pull request.

To report bugs or submit ideas, you can submit an issue in the GitHub repository. For bug reports, please specify your .NET version, OS and your output log.

Examples:

Check, if the number is prime:
```c#
Console.WriteLine(yTools.Integers.IsPrime(25) ? "True" : "False");
// Output: False
```

Get the maximum double number:
```c#
Console.WriteLine(yTools.Doubles.maxDouble.ToString());
// Output: 1,7976931348623157E+308
```

Close the app:
```c#
yTools.General.CloseApp();
// Closes the application.
```