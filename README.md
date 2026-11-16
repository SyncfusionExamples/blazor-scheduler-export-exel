# How to export appointments to Excel in Blazor Scheduler

This quick-start project demonstrates how to export appointments and calendar data from the [Blazor Scheduler](https://www.syncfusion.com/scheduler-sdk/blazor-scheduler) to Excel format. It showcases implementing export functionality with customization options, enabling users to efficiently archive, share, and manage scheduling data through Excel workbooks in Blazor applications.

## Getting Started

This sample demonstrates the Export to Excel functionality of the Blazor Scheduler component. You can export events with all their properties, custom fields, and resource information directly to Excel format for reporting and data analysis purposes.

## Prerequisites

- Visual Studio 2026 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`Scheduler_Excel_Export.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

For server,

```bash
cd blazor-scheduler-export-exel
cd Scheduler_Export_Server
dotnet restore
dotnet run
```

For WASM,

```bash
cd blazor-scheduler-export-exel
cd Scheduler_Export_Wasm
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Documentation

- **Framework Documentation**: https://blazor.syncfusion.com/documentation/introduction
- **Scheduler Component**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/getting-started-with-server-app
- **Export Feature**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/exporting#excel-exporting
- **Online Examples**: https://blazor.syncfusion.com/demos/scheduler/export-to-excel?theme=fluent2