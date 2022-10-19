
# .NET Framework

.NET Framework is a technology developed by Microsoft, in 13 February 2002 that supports building and running Windows applications and web services.

[Source](https://learn.microsoft.com/en-us/dotnet/framework/get-started/overview)

## .NET Framework versions

|   Version Name              |
|-----------------------------|
| .NET Framework 4.8.1        |
| .NET Framework 4.8          |
| .NET Framework 4.7.2        |
| .NET Framework 4.7.1        |
| .NET Framework 4.7          |
| .NET Framework 4.6.2        |
| .NET Framework 4.6.1        |
| .NET Framework 4.6          |
| .NET Framework 4.5.2        |
| .NET Framework 4.5.1        |
| .NET Framework 4.5          |
| .NET Framework 4            |
| .NET Framework 3.5          |
| .NET Framework 3.0          |
| .NET Framework 2.0          |
| .NET Framework 1.1          |
| .NET Framework 1.0          |

[Source](https://learn.microsoft.com/en-us/dotnet/framework/migration-guide/versions-and-dependencies#version-information)

# .Net Core

Developed by Microsoft in June 27, 2016.

## .Net Core versions

|   Version Name      |
|---------------------|
| .NET Core 3.1       |
| .NET Core 3.0       |
| .NET Core 2.2       |
| .NET Core 2.1       |
| .NET Core 2.0       |
| .NET Core 1.1       |
| .NET Core 1.0       |

[Source](https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core)

# .Net

Developed by Microsoft in November 10, 2020.

## .Net versions

|   Version Name      |
|---------------------|
| .NET 6              |
| .NET 5              |

# Data types

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






#####

1. Format JSON

```csharp
Console.WriteLine(Newtonsoft.Json.JsonConvert.SerializeObject(data[i], Newtonsoft.Json.Formatting.Indented));
```

2.
