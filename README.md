# Currency Converter

A Windows Presentation Foundation (WPF) desktop application for converting an entered amount between a small set of currencies. The current conversion values are hard-coded in the application and are not live exchange rates.

## Requirements

- Windows
- .NET 10 SDK
- Visual Studio 2026 with the .NET desktop development workload (optional)

## Build and run

From the project folder, restore dependencies and build:

```powershell
dotnet restore .\CurrsencyConverter_Static.csproj
dotnet build .\CurrsencyConverter_Static.csproj
```

Run the application with:

```powershell
dotnet run --project .\CurrsencyConverter_Static.csproj
```

Alternatively, open `CurrsencyConverter_Static.slnx` in Visual Studio, select the WPF project as the startup project, and press **F5**.

NuGet dependencies are restored as part of the build. The project currently uses the `FontAwesome.WPF` package.
