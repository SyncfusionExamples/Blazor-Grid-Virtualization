# Blazor Grid Virtualization

## Overview

This repository contains sample applications that demonstrate virtualization in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). The samples show how large collections of records can be rendered efficiently by displaying only the rows currently visible within the viewport instead of rendering the entire dataset at once. The repository includes separate implementations for both Blazor Server and Blazor WebAssembly, allowing developers to explore virtualization behavior across different Blazor hosting models. These samples provide a practical reference for implementing high-performance scrolling experiences when working with large amounts of tabular data.

## Key Features

- Demonstrates Syncfusion Blazor DataGrid virtualization.
- Shows how Grid rows are rendered on demand based on the visible viewport.
- Includes examples for both Blazor Server and Blazor WebAssembly applications.
- Provides reference implementations related to DataGrid virtual scrolling.
- Includes scenarios aligned with the Syncfusion DataGrid virtualization documentation.
- References virtual scrolling and virtual mask row examples from the Syncfusion Blazor DataGrid feature set.
- Focuses on improving rendering performance when displaying large datasets.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file from either the `Virtualization_Server` or `Virtualization_Wasm` folder.
3. Restore all NuGet packages.
4. Set the selected project as the startup project if required.
5. Build the solution.
6. Run the project using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to either the `Virtualization_Server` or `Virtualization_Wasm` project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Virtualization_Server/` — contains the Blazor Server implementation demonstrating Syncfusion Blazor DataGrid virtualization.
- `Virtualization_Wasm/` — contains the Blazor WebAssembly implementation demonstrating Syncfusion Blazor DataGrid virtualization.
- `Virtualization_Server/Pages/` — contains the page that renders the virtualized DataGrid sample. 
- `Virtualization_Wasm/Pages/` — contains the page that renders the virtualized DataGrid sample. 

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/virtual-scrolling

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
