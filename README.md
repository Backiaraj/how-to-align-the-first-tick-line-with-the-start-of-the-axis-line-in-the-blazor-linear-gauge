# Blazor Linear Gauge - Align First Tick with Axis Line

A sample Blazor application demonstrating how to align the first tick line with the start of the axis line in the [Blazor Linear Gauge](https://www.syncfusion.com/blazor-components/blazor-linear-gauge) component.

## Overview

This project showcases a practical technique for fine-tuning the appearance of the Blazor Linear Gauge. By leveraging JavaScript interop and the gauge's SVG rendering capabilities, you can programmatically adjust tick line positions to achieve custom layouts that may not be available through standard component configuration alone.

The sample uses the Blazor Linear Gauge component with customization applied during the component's [Loaded](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.LinearGauge.LinearGaugeEvents.html#Syncfusion_Blazor_LinearGauge_LinearGaugeEvents_Loaded) event, ensuring proper alignment after the gauge renders.

## Features

- **Blazor Linear Gauge Component** - Production-ready gauge with smooth animations and responsive design
- **Tick Line Repositioning** - Practical technique to align first major tick with axis line start without workarounds
- **Horizontal Gauge Orientation** - Demonstrates horizontal layout with opposed axis position for alternative data visualization
- **Configurable Tick Marks** - Major ticks (20-unit intervals) and minor ticks (10-unit intervals) for granular value display
- **Dynamic Pointer Rendering** - Animated bar-type pointer with customizable color, width, and positioning
- **Event-Driven Customization** - Leverages Blazor's `Loaded` event for reliable post-render customization

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone and Setup

```bash
git clone https://github.com/SyncfusionExamples/how-to-align-the-first-tick-line-with-the-start-of-the-axis-line-in-the-blazor-linear-gauge.git
cd how-to-align-the-first-tick-line-with-the-start-of-the-axis-line-in-the-blazor-linear-gauge
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation** - https://blazor.syncfusion.com/documentation/linear-gauge/axis

**Online examples** - https://blazor.syncfusion.com/demos/linear-gauge/default-functionalities?theme=fluent2