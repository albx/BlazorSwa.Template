# BlazorSwa.Template
A project template for creating a Blazor WebAssembly app and, optionally, an Azure Function api which will be hosted on Azure Static Web Apps.

## Requirements
.NET 8 SDK with Azure workload and Azure Functions v4 runtime must be installed.

## Installation
You can install the package from [NuGet](https://www.nuget.org/packages/BlazorSwa.Template/) using this command from the .NET CLI:
```
dotnet new --install BlazorSwa.Template
```

## Usage
Execute the following command from the .NET CLI:
```
dotnet new blazorswa -n <YourProjectName>
```
to create a project containing a Blazor WebAssembly client and a simple Azure Function project with isolated runtime.

If you prefer Visual Studio to create the project, search *Blazor static web app* in the *Search for templates* bar and follow the wizard.

### Options
The following option is available:
- **--include-api**: specifies whether add the azure function project (isolated runtime). The default value is **false**.

### Examples
To create a Blazor WebAssembly project with an Azure Function project with isolated runtime, execute the following command from the .NET CLI:
```
dotnet new blazorswa --include-api -n <YourProjectName>
```

### Some tips
In order to debug locally the project you can install the **Static Web Apps CLI**.
The project is available on GitHub at this link: [https://github.com/Azure/static-web-apps-cli](https://github.com/Azure/static-web-apps-cli).

To create a Static Web App resource on Azure, please follow the Microsoft documentation at this link: [https://docs.microsoft.com/en-us/azure/static-web-apps/get-started-portal?tabs=blazor&pivots=github#create-a-static-web-app](https://docs.microsoft.com/en-us/azure/static-web-apps/get-started-portal?tabs=blazor&pivots=github#create-a-static-web-app).

## Contributing

Contributions are always welcome!

If you want to submit any issues or new features, please [follow these few and simple guidelines](CONTRIBUTING.md).
