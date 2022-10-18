
# .NET Framework versions

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
