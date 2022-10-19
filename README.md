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

# Installation

TODO


# Key Words

```cs
abstract, as, base, bool, break, byte, case, catch, char, checked, class, const, continue, decimal, default, delegate, do,
double, else, enum, event, explicit, extern, false, finally, fixed, float, for, foreach, goto, if, implicit, in, int,
interface, internal, is, lock, long, namespace, new, null, object, operator, out, override, params, private, protected,
public, readonly, ref, return, sbyte, sealed, short, sizeof, stackalloc, static, string, struct, switch, this, throw,
true, try, typeof, uint, ulong, unchecked, unsafe, ushort, using, virtual, void, volatile, while
```

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


| No  | Name      | Example                                                                                                        | Doc                                                                 | Data Type          |
| --- | --------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------ |
| 1   | Number    | `let a = 17`                                                                                                   | [link](https://developer.mozilla.org/en-US/docs/Glossary/Number)    | Primitive data     |
| 2   | BigInt    | `let a = 348378344239489n`                                                                                     | [link](https://developer.mozilla.org/en-US/docs/Glossary/BigInt)    | Primitive data     |
| 3   | String    | `let a = "Hello universe"` <br/> `let a = 'Hello universe'` <br/> <code> let a = \`${Hello universe}\` </code> | [link](https://developer.mozilla.org/en-US/docs/Glossary/String)    | Primitive data     |
| 4   | Boolean   | `let a = true`                                                                                                 | [link](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)   | Primitive data     |
| 5   | Symbol    | `let sym = Symbol()`                                                                                           | [link](https://developer.mozilla.org/en-US/docs/Glossary/Symbol)    | Primitive data     |
| 6   | null      | `let a = null`                                                                                                 | [link](https://developer.mozilla.org/en-US/docs/Glossary/Null)      | Primitive data     |
| 7   | undefined | `let a = undefined`                                                                                            | [link](https://developer.mozilla.org/en-US/docs/Glossary/undefined) | Primitive data     |
| 8   | Object    | `let a = {a: 'test'}`                                                                                          | [link](https://developer.mozilla.org/en-US/docs/Glossary/Object)    | Non-primitive data |

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
