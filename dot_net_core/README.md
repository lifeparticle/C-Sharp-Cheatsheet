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

## Build web app with ASP.NET Core using Blazor

https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/intro

## Create a controller-based web API with ASP.NET Core

```shell
dotnet new webapi --use-controllers -o .
dotnet add package Microsoft.EntityFrameworkCore.InMemory
dotnet dev-certs https --trust
dotnet run --launch-profile https
dotnet run --launch-profile http
```

https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-9.0&tabs=visual-studio-code
