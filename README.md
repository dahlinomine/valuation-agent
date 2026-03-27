# Valuation Agent

![finance](https://img.shields.io/badge/finance-blue?style=flat-square) ![modeling](https://img.shields.io/badge/modeling-blue?style=flat-square) ![investment](https://img.shields.io/badge/investment-blue?style=flat-square)

Autonomous DCF (Discounted Cash Flow) modeling agent for public companies.

## Overview
Valuation Agent is an autonomous Python-based tool designed to automate the complex process of performing Discounted Cash Flow (DCF) analyses. By leveraging financial APIs and intelligent modeling logic, the agent fetches historical data, projects future cash flows, and calculates intrinsic values for publicly traded equities. It streamlines fundamental research for investors by providing a standardized, data-driven framework for company valuation.

## Features
*   **Automated Data Retrieval:** Automatically fetches balance sheets, income statements, and cash flow statements from major financial data providers.
*   **Dynamic Forecasting:** Projects free cash flows (FCF) using customizable growth rates and margin assumptions.
*   **WACC Calculation:** Computes the Weighted Average Cost of Capital by analyzing current market risk-free rates, equity risk premiums, and company-specific beta.
*   **Sensitivity Analysis:** Generates valuation ranges based on varying terminal growth rates and discount factors.

## Installation
Clone the repository and install the necessary dependencies using `pip`:

```bash
git clone https://github.com/yourusername/valuation-agent.git
cd valuation-agent
pip install -r requirements.txt
```

## Usage
Run the main script and provide a ticker symbol to initiate the valuation process:

```bash
python main.py --ticker AAPL
```

The agent will output a summary report including the calculated intrinsic value per share, the terminal value, and the discount rate used in the model.

## Contributing
Contributions are welcome! If you have suggestions for improving the forecasting logic or adding new valuation methodologies, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE).