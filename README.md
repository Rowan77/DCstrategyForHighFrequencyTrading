# High Frequency Trading Strategy - Directional Change Method

This repository contains a Jupyter Notebook focused on developing and analyzing a high-frequency trading strategy using the directional change method. The project involves applying quantitative finance techniques on high-frequency financial data to assess market trends and potential trading signals.

## Table of Contents
- [Introduction](#introduction)
- [Files in the Repository](#files-in-the-repository)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
- [Contributing](#contributing)
- [License](#license)

## Introduction

High-frequency trading (HFT) involves executing a large number of trades at extremely high speeds, leveraging real-time market data. This project explores the use of the directional change (DC) method, a novel approach to detecting turning points in price movements, which serves as the basis for developing trading strategies in high-frequency markets.

## Files in the Repository

- `High_Frequency_Finance_CW2.ipynb`: Main Jupyter Notebook containing the implementation of the high-frequency trading strategy using the directional change method.
- `DAT_ASCII_EURGBP_T_201606.csv`: Historical EUR/GBP high-frequency exchange rate data.
- `DAT_ASCII_EURJPY_T_201303.csv`: Historical EUR/JPY high-frequency exchange rate data.
- `DAT_ASCII_EURUSD_T_201912.csv`: Historical EUR/USD high-frequency exchange rate data.

## Features

- Analysis of high-frequency trading data using the directional change method.
- Identification of market trends and key turning points for trading signals.
- Visualization of high-frequency market data and analysis results.

## Installation

To run this notebook locally, you'll need to have Python and Jupyter Notebook installed. We also recommend using a virtual environment.

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries such as:
  - NumPy
  - Pandas
  - Matplotlib

### Setup Instructions

1. Clone this repository:
    ```bash
    git clone https://github.com/Rowan77/DCstrategyForHighFrequencyTrading.git
    cd DCstrategyForHighFrequencyTrading
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then, navigate to High_Frequency_Finance_CW2.ipynb in your browser. The notebook guides you through the process of using the directional change method on high-frequency trading data, including data preprocessing, analysis, and strategy development.

### Example
The notebook contains examples of analyzing high-frequency data for various currency pairs (EUR/GBP, EUR/JPY, and EUR/USD) using the directional change approach, highlighting key market movements and potential trading opportunities.

### Methods
The directional change (DC) method identifies significant market turning points and focuses on periods where the market reverses by a predefined threshold. This approach differs from traditional time-based analysis and provides deeper insights into market behavior, making it suitable for high-frequency trading applications.

Key aspects covered:

- Directional Change Event Detection
- Trend Analysis and Trading Signal Generation
- Data Visualization and Analysis
