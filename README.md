# Enterprise Chromium Browser

A secure, enterprise-focused Chromium-based browser implementation using Microsoft's WebView2 control.

## Features

- Full Chromium engine via WebView2
- Security-focused design
- Enterprise policy support
- Download management
- Logging and monitoring

## Requirements

- Windows 10 or later
- .NET 6.0 or later
- WebView2 Runtime

## Setup

1. Clone the repository
2. Open the solution in Visual Studio 2022
3. Restore NuGet packages
4. Build and run

## Usage

The browser can be launched directly or integrated into other applications:

```csharp
var browser = new EnterpriseBrowser.MainBrowserWindow();
browser.Show();
```

## Configuration

Edit App.config to customize:
- Start page
- Security policies
- Download settings

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request