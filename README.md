# Trading-bot-coindcx

## Overview

This trading bot utilizes an arbitrage strategy to make a profit by exploiting the price differences between currencies on the CoinDCX broker. 

For example, if you want to buy 1 SOL (Solana) directly with INR (Indian Rupees), you get 1 SOL for 100 INR. However, if you first convert 100 INR to USD and then buy SOL with the USD, you might be able to buy 1.02 SOL, resulting in approximately 2% profit.

## Features

- **Arbitrage Strategy**: Leverages price differences between currencies for profit.
- **Real-time Trading**: Uses WebSockets for live data and Axios for API requests.
- **High Performance**: Built with TypeScript and Bun for fast and efficient execution.

## Requirements

- **Node.js**: Ensure Node.js is installed on your machine.
- **Bun**: Bun v1.0.23 or later. [Install Bun](https://bun.sh)

## Installation

To install dependencies:

```bash
bun install
  ```
## Usage
To run the trading bot:

```bash
bun run index.ts
```
## Tech Used
- TypeScript: Strongly typed programming language for JavaScript.
- Bun: Fast all-in-one JavaScript runtime.
- Axios: Promise-based HTTP client for making API requests.
- WebSockets: For real-time data streaming and trading
  ## Configuration
Ensure you have the necessary API keys and configurations set up in the config/ directory. Refer to the CoinDCX API documentation for setting up your API keys and permissions.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the existing style and includes tests where applicable.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
- CoinDCX for providing the trading platform and API.
- Bun for the JavaScript runtime.
- Axios for the HTTP client.
- WebSockets for real-time data handling
This project was created using bun init in Bun v1.0.23. Bun is a fast all-in-one JavaScript runtime.
