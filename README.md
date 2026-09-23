# Create Blazor Maps using Blazor Server App in 10 Minutes  

## Overview

This sample demonstrates how to create and configure the Syncfusion [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-map) component in a Blazor Server application. The implementation visualizes geographic regions and introduces core mapping features including legends, data labels, and tooltips. It serves as a practical getting-started example for developers who need to display geographic information, highlight map regions, and enrich map interaction with contextual data presentation.

**Example**: https://blazor.syncfusion.com/demos/maps/default-functionalities

**Documentation**: https://blazor.syncfusion.com/documentation/maps/getting-started

## Key Features

- Demonstrates rendering the Syncfusion Maps component in a Blazor Server application.
- Visualizes geographic regions using map shape data.
- Displays a map legend to provide context for rendered data.
- Configures data labels to display information directly on map regions.
- Uses tooltips to display additional contextual information during user interaction.
- Shows how to initialize and configure map rendering within a Razor page.
- Demonstrates a basic geographic visualization workflow suitable for location-based applications.
- Uses the implementation hosted in `Pages/Index.razor` as the primary sample page

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `AddingMapsComponent.sln`

3. Restore NuGet packages.
4. Ensure the startup project is:

   `AddingMapsComponent`

5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the directory containing `AddingMapsComponent.csproj`.

```bash
dotnet restore
dotnet run
```

## Project Structure

`Pages/Index.razor` — contains the primary Syncfusion Maps implementation, map configuration, legend setup, data-label configuration, and tooltip rendering.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://help.syncfusion.com/chart-sdk/blazor/maps/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.