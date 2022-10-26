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


| No  | Name      | Example                                                                                                        | Doc                                                                 | Data Type          |    .NET type  |
|------|------|------|------|------|------|
| 1   | bool | `let a = 17`                                                                                                   | [link](https://developer.mozilla.org/en-US/docs/Glossary/Number)    | value          |   System.Boolean     |
| 2   | byte    | `let a = 348378344239489n`                                                                                     | [link](https://developer.mozilla.org/en-US/docs/Glossary/BigInt)    | value     |  System.Byte      |
| 3   | sbyte | `let a = "Hello universe"` <br/> `let a = 'Hello universe'` <br/> <code> let a = \`${Hello universe}\` </code> | [link](https://developer.mozilla.org/en-US/docs/Glossary/String)    | value          | 	System.SByte       |
| 4   | char | `let a = true`                                                                                                 | [link](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)   | value          |   	System.Char     |
| 5   | decimal    | `let sym = Symbol()`                                                                                           | [link](https://developer.mozilla.org/en-US/docs/Glossary/Symbol)    | value          |  System.Decimal      |
| 6   | double | `let a = null`                                                                                                 | [link](https://developer.mozilla.org/en-US/docs/Glossary/Null)      | value          |  	System.Double      |
| 7   | float | `let a = undefined`                                                                                            | [link](https://developer.mozilla.org/en-US/docs/Glossary/undefined) | value          |  	System.Single      |
| 8   | int    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.Int32      |
| 9   | uint | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.UInt32      |
| 10   | nint | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |   	System.IntPtr     |
| 11   | nuint | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.UIntPtr      |
| 12   | long    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      | 	System.Int64       |
| 13   | ulong | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |   	System.UInt64     |
| 14  | short    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.Int16      |
| 15   | ushort| `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |    	System.UInt16    |
| 16  | object    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.Object      |
| 17   | string    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |   	System.String     |
| 18   | dynamic| `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | value      |  	System.Object      |
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
