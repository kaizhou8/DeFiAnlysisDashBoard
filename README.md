# DeFi Data Analytics Dashboard

This is a Blazor WebAssembly-based DeFi data analytics dashboard project that provides blockchain data visualization and analysis capabilities.

## Features

- Multi-chain data monitoring and analysis
- Real-time DeFi protocol data display
- Transaction history and trend analysis
- Portfolio management tools
- Liquidity pool data monitoring
- Yield farming analysis

## Technology Stack

- Blazor WebAssembly
- .NET 7
- Web3.js / Nethereum
- Chart.js / ApexCharts
- Bootstrap 5

## Development Guide

### Requirements

- .NET 7 SDK
- Visual Studio 2022 or VS Code
- Node.js (for frontend asset management)

### Project Startup

```bash
dotnet restore
dotnet run
```

## Project Structure

- `DeFi.Dashboard.Web` - Blazor WebAssembly application
- `DeFi.Dashboard.Core` - Core business logic
- `DeFi.Dashboard.Services` - Blockchain data services
- `DeFi.Dashboard.Models` - Data models
- `DeFi.Dashboard.Shared` - Shared components and utilities