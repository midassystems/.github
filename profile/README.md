# Welcome to the Midas Trading System 👋

The Midas Trading System is a comprehensive ecosystem for financial market analysis, strategy development, backtesting, and live trading. It is designed to provide a seamless transition from backtesting to live trading with minimal adjustments. Midas is highly extensible, offering support for custom data sources, brokers, and strategies, while ensuring smooth integration between components for an exceptional user experience.

## What's Inside

The Midas Trading System organization contains the following key repositories:

### 1. [MidasTrader](https://github.com/midassystems/midastrader)
**Core Backtesting and Live Trading Engine**
- Multi-threaded architecture for efficient processing.
- Unified workflow for both backtesting and live trading.
- Extensible design to support custom data sources and brokers.
- Strategy development using the `BaseStrategy` class.

### 2. [Midas Shell](https://github.com/midassystems/midas-shell)
**Central CLI/REPL Tool**
- Command-line interface for controlling all components of the system.
- ETL pipelines for data ingestion from sources like Databento.
- Ability to launch the GUI dashboard directly from the shell.
- File comparison and live trading capabilities.

### 3. [Midas GUI](https://github.com/midassystems/midas-gui)
**Interactive Frontend Application**
- React-based interface for financial analysis and backtest visualization.
- Real-time market data via TradingView widgets.
- Seamless integration with the `midas-server` backend.

### 4. [Midas Server](https://github.com/midassystems/midas-server)
**Backend Service**
- Provides data storage and API access for backtesting results and live trading.
- Docker-deployable for local or remote setups.
---

For questions or contributions, feel free to open issues or pull requests in the respective repositories.
