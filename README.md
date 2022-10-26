- [Introduction](#introduction)
- [Installation](#installation)
- [Reserved Words](#reserved-words)
- [Comment](#comment)
- [Operators](#operators)
- [Variables and Scope](#variables-and-scope)
- [Conditional structures](#conditional-structures)
- [Data types](#data-types)
- [Array](#array)
- [Hash](#hash)
- [Loop](#loop)
- [Classes](#classes)
- [Miscellaneous](#miscellaneous)
- [My C# Articles](#my-c%23-articles)
- [Books and other resources](#books-and-other-resources)
- [Bug Reports and Feature Requests](#bug-reports-and-feature-requests)
- [Contribution Guidelines](#contribution-guidelines)

# Introduction

C# (pronounced "See Sharp") is a strongly-typed programming language developed by Microsoft in 2002. 

## C# versions

```
1.0, 1.2, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 7.1, 7.2, 7.3, 8.0, 9, 10
```

# Installation

TODO


# Key Words

```cs
abstract, as, base, bool, break, byte, case, catch, char, checked, class, const, continue, decimal,
default, delegate, do, double, else, enum, event, explicit, extern, false, finally, fixed, float,
for, foreach, goto, if, implicit, in, int, interface, internal, is, lock, long, namespace, new,
null, object, operator, out, override, params, private, protected, public, readonly, ref, return,
sbyte, sealed, short, sizeof, stackalloc, static, string, struct, switch, this, throw,
true, try, typeof, uint, ulong, unchecked, unsafe, ushort, using, virtual, void, volatile, while
```

# Naming conventions


|   Name     |  Types |     Example         |
|------|------|------|
|  camelCase      |   variables, parameters     | studentName |
|  pascalCase      |   classes, methods, fields          |  StdentName | 
|  IPascalCase      |  interfaces      | IStdentName  |
| \_camelCase   |   private fields      |   \_studentName | 


# Comment


# Operators


<table>
<tr>
<th>Boolean logical operators</th>
<th>Bitwise and shift operators</th>
<th>Arithmetic operators</th>
<th>Equality operators</th>
<th>Comparison operators</th>
</tr>
<tr>

<td valign="top">

| No  | Operator |
| --- | -------- |
| 1   | &|
| 2   |  \|       |
| 3   | ^ |
| 4   | &&       |
| 5   | \|\|     |
| 6   | !        |

</td>

<td valign="top">

| No  | Operator |
| --- | -------- |
| 1   | &        |
| 2   | \|       |
| 3   | ^        |
| 4   | ~        |
| 5   | <<       |
| 6   | >>       |
| 7   | >>>       |

</td>

<td valign="top">

| No  | Operator |
| --- | -------- |
| 1   | +        |
| 2   | -        |
| 3   | \*       |
| 4   | /        |
| 5   | %        |
| 6   | \+\+     |
| 7   | \-\-     |

</td>

<td valign="top">

| No  | Operator |
| --- | -------- |
| 1   | ==        |
| 2   | !=       |


</td>

<td valign="top">

| No  | Operator |
| --- | -------- |
| 1   | >        |
| 2   | <        |
| 3   | >=       |
| 4   | <=       |


</td>

</tr></table>




# Variables and Scope


| No | Name    | Example                     | Doc                                                                                                                       | Data Type | .NET type      |
|----|---------|-----------------------------|---------------------------------------------------------------------------------------------------------------------------|-----------|----------------|
| 1  | bool    | `bool isVisible = true;`    | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/bool)                             | value     | System.Boolean |
| 2  | byte    | `System.Int32 a = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.Byte    |
| 3  | sbyte   | `System.Int32 a = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.SByte   |
| 4  | char    | `char myLetter = 'D';`      | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/char)                             | value     | System.Char    |
| 5  | decimal | `let sym = Symbol()`        | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)     | value     | System.Decimal |
| 6  | double  | `double a = 1.1;`           | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)     | value     | System.Double  |
| 7  | float   | `double a = 1.1;`           | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)     | value     | System.Single  |
| 8  | int     | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.Int32   |
| 9  | uint    | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.UInt32  |
| 10 | nint    | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.IntPtr  |
| 11 | nuint   | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.UIntPtr |
| 12 | long    | `System.Int32 b = 123;`     | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)                                                          | value     | System.Int64   |
| 13 | ulong   | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.UInt64  |
| 14 | short   | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.Int16   |
| 15 | ushort  | `System.Int32 b = 123;`     | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)           | value     | System.UInt16  |
| 16 | object  | `string a = "hello world";` | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types#the-object-type)  | value     | System.Object  |
| 17 | string  | `string a = "hello world";` | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types#the-string-type)  | value     | System.String  |
| 18 | dynamic | `dynamic dyn = 1;`          | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types#the-dynamic-type) | value     | System.Object  |


# Conditional structures

# Data types

How to check the data type

# Array

# Hash

# Loop

# Classes

# Miscellaneous

1. Format JSON

```csharp
Console.WriteLine(Newtonsoft.Json.JsonConvert.SerializeObject(data[i], Newtonsoft.Json.Formatting.Indented));
```

2.

# My C# Articles

# Books and other resources
1. https://github.com/dotnet/core

# Bug Reports and Feature Requests

# Contribution Guidelines
