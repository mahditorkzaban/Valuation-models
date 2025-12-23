# Valuation Engine (Executable)

A production quality **financial valuation engine** supporting multiple industrystandard valuation models, designed for **DCF, relative valuation, asset based valuation, and advanced use cases**.

This repository provides a **ready to run executable** with **JSON driven inputs**, allowing users to run professional valuation models **without access to the source code**.


## Key Features
Executable valuation engine no Python knowledge required)
JSON based input for full reproducibility
14+ valuation model implemented
Suitable for finance, consulting, PE, IB, and academic use

  **Source code is kept private**.  
 This repository is designed to demonstrate functionality, architecture, and outputs — not to distribute proprietary logic.

## Supported Valuation Models

 **FCFF DCF** Free Cash Flow to Firm
 **FCFE DCF** Free Cash Flow to Equity
 **Dividend Discount Model (DDM)** Single & Multistage

### Relative Valuation (Multiples)
 P/E
 EV / EBITDA
 EV / Sales
 P/B
 PEG Ratio

### AssetBased Valuation
 Book Value
 Adjusted Book Value
 Liquidation Value

### Advanced / Special Models
 **Real Options** (BlackScholes)
 **Sum of the Parts (SOTP)**
 **LBO IRR Analysis**


## How to Use

### 1.Download reprisotery

### 2.Run the Executable with a JSON File (you can modify the Json file based on your needs or run the program without json file)
```bash
chmod +x Valuation
./Valuation examples/fcff_example.json
```

The engine will:
	Load the JSON inputs/ Validate assumptions/ Run the selected valuation model/ Print professionalgrade results to the terminal
