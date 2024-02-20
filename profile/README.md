# Welcome to the Midas Trading System👋

The Midas Trading System is a comprehensive ecosystem designed for financial market analysis, backtesting trading strategies, and executing trades both in backtest environments and live markets. Our goal is to provide a seamless transition from strategy development to live trading with a high degree of accuracy and efficiency.

## Our Projects

### 📈 midas-backend
- **Description**: A Django REST Framework (DRF) application that stores historical price data and backtest results. It's designed for flexibility, allowing storage and retrieval of vast amounts of financial data.
- **Deployment**: While we personally run it on Heroku utilizing the PostgreSQL add-on, the application is designed to be adaptable to various environments and database systems.
- **Repository**: [midas-backend](https://github.com/anthonyb8/midas-backend)

### 🐍 midas-python
- **Description**: A Python-based backtest and live trade engine. It is crafted to ensure that backtesting mirrors live trading scenarios as closely as possible, facilitating an effortless transition to live trading. Historical data is fetched from the `midas-backend` database, while live data integration is handled through IBAPI, aligning with our choice of brokerage.
- **Repository**: [midas-python](https://github.com/anthonyb8/midas-python)

### 💻 midas-cpp
- **Description**: An emerging project aimed at replicating the functionality of `midas-python` in C++. The goal is to maintain similar system design principles, offering an alternative for those who prefer or require C++ for their trading strategies.
- **Repository**: [midas-cpp](https://github.com/anthonyb8/midas-cpp)

### 📊 midas-dashboard
- **Description**: A React application designed for local or cloud deployment. Its main function is to fetch and display backtest results from `midas-backend`, providing an intuitive interface for strategy analysis and comparison.
- **Deployment**: The dashboard can be deployed locally or on platforms like Vercel for enhanced accessibility.
- **Repository**: [midas-dashboard](https://github.com/anthonyb8/midas-dashboard)

## Getting Involved

We're excited to collaborate with the community! Whether you're interested in contributing to the development, have feedback, or are curious about using the Midas Trading System for your trading strategies, we'd love to hear from you.

- **Connect and Contribute**: If you're interested in contributing or just want to share your thoughts and feedback, please don't hesitate to reach out. You can contact me directly at [anthonybaxter819@gmail.com](mailto:your-email@example.com).



<!--
<p align="center">
  <img src="/midas_logo.jpeg" alt="Midas Trading System Logo" title="Midas Trading System">
</p>
- **Join the Conversation**: While we're still in the process of setting up formal contribution guidelines and discussion forums, your early interest and input would be invaluable in shaping the future of the Midas Trading System. 

- **Stay Tuned**: We're working on developing comprehensive documentation for each project within the ecosystem. Your feedback and questions will help us focus on the areas that matter most to our users and contributors.
-->
