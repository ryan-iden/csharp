# iden C# SDK

Current iden release: **0.0.1**. Install from `RyanIden.AspNetCore.Authentication` on NuGet.

> This project is derived from the corresponding [Logto SDK](https://github.com/logto-io). Protocol constants and established public API names such as `LogtoClient` are intentionally retained where changing them would break compatibility.


[![iden](https://img.shields.io/badge/for-iden-5B5CF6)][Website]

The SDK and samples for integrating ASP.NET Core applications with iden.

## Installation

```bash
dotnet add package RyanIden.AspNetCore.Authentication --version 0.0.1
```

The .NET namespaces remain `Logto.*` for source compatibility.

## Contents

### Packages

- [src/Logto.AspNetCore.Authentication](./src/Logto.AspNetCore.Authentication): ASP.NET Core authentication middleware for iden. The directory and namespace retain their compatibility names.
- [src/Logto.AspNetCore.Authentication.Tests](./src/Logto.AspNetCore.Authentication.Tests): Tests for the ASP.NET Core authentication middleware.

### Samples

- [sample](./samples/sample): Sample ASP.NET Core web application that shows how to use the ASP.NET Core authentication middleware.
- [sample-mvc](./samples/sample-mvc): Sample ASP.NET Core web MVC application that shows how to use the ASP.NET Core authentication middleware.
- [sample-wasm](./samples/sample-wasm): Sample Blazor WebAssembly application that shows how to use Blorc.OpenIdConnect to authenticate users with iden.
- [sample-blazor](./samples/sample-blazor): Sample Blazor Server application that shows how to use the ASP.NET Core authentication middleware.

## Resources

- [iden repository][Website]

[Website]: https://github.com/ryan-iden/iden
