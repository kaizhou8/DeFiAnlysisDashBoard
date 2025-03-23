# DeFi Dashboard Web Application

A Blazor WebAssembly-based DeFi data analytics dashboard that provides blockchain data visualization and analysis capabilities.

## Features

- Multi-chain data monitoring and analysis
- Real-time DeFi protocol data display
- Transaction history and trend analysis
- Portfolio management tools
- Liquidity pool data monitoring
- Yield farming analysis

## Technology Stack

- Blazor WebAssembly
- .NET 8.0
- Web3.js / Nethereum (planned)
- Chart.js / ApexCharts (planned)
- Bootstrap 5

## Development Guide

### Requirements

- .NET 8.0 SDK
- Visual Studio 2022 or VS Code
- Node.js (for frontend asset management)

### Getting Started

```bash
# Restore dependencies
dotnet restore

# Run the application
dotnet run
```

## Project Structure

- `DeFi.Dashboard.Web` - Blazor WebAssembly application
- `DeFi.Dashboard.Core` - Core business logic
- `DeFi.Dashboard.Services` - Blockchain data services
- `DeFi.Dashboard.Models` - Data models
- `DeFi.Dashboard.Shared` - Shared components and utilities

## Pages

- **Dashboard** - Overview of DeFi market metrics
- **Protocols** - Information about various DeFi protocols
- **Portfolio** - Track and manage your DeFi portfolio
- **Liquidity Pools** - Monitor liquidity pool data
- **Yield Farming** - Analyze yield farming opportunities

## Current Status

This project is in early development. Many features are currently implemented as UI mockups with placeholder data. Future updates will integrate real blockchain data services.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT