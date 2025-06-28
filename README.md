Poloniex API – Crypto Arbitrage Detection
Overview:

This Python and JavaScript project is designed to identify triangular arbitrage opportunities in the cryptocurrency market using data from both centralized exchanges (CeFi) like Poloniex and decentralized exchanges (DeFi) such as Uniswap V3.

Objectives:
Gain a deep understanding of crypto arbitrage, with a focus on triangular arbitrage.

Develop and implement arbitrage logic using Python and JavaScript.

Detect and map all valid triangular arbitrage pair cycles.

Compute both surface rates and real arbitrage rates (accounting for market depth).

Integrate Poloniex REST APIs for CeFi data and Web3/Ethers.js with Uniswap V3 SDK for DeFi data access.

Key Features:
Triangular Arbitrage Detection: Automatically find profitable trading loops across three pairs.

Surface & Real Rate Analysis: Compute theoretical profits and validate with order book depth.

API Integration: Fetch live data using REST APIs (Poloniex) and blockchain data via Web3.

Cross-Platform Arbitrage: Supports both CeFi (Poloniex) and DeFi (Uniswap V3).

Uniswap V3 SDK Support: Leverages SDK for routing and slippage-aware calculations.

Technologies Used:
Python – Core arbitrage logic and rate calculations.

JavaScript – Pair cycle generation and blockchain interactions.

Poloniex API – Live market data for centralized exchange analysis.

Web3 & Ethers.js – Blockchain interaction for DeFi pricing.

Uniswap V3 SDK – DeFi pool routing and depth-based price checks.

Getting Started:
Prerequisites:

Basic understanding of cryptocurrencies.

No prior knowledge of arbitrage or programming is required.

Setup Instructions:

bash
Copy
Edit
# Clone the repository
git clone https://github.com/salin1771/poloniex_api.git
cd poloniex_api

# Install JavaScript dependencies
npm install
Run the Python arbitrage logic:

bash
Copy
Edit
python func_arbitrage.py
The JavaScript module includes logic to identify and visualize all possible pair cycles for triangular arbitrage.

Acknowledgments:
This project was created as a hands-on exploration of triangular arbitrage strategies in both centralized and decentralized crypto markets. It offers a practical framework to understand arbitrage workflows, API integration, and cross-market price discrepancies.
