# Market Regime Detection System

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A Python-based tool for identifying and visualizing market regimes (Bull, Bear, and Sideways) in historical stock data.

This project uses machine learning and technical indicators to classify different market environments, helping traders and analysts gain a deeper understanding of market dynamics.

## Table of Contents

- [Methodology](#methodology)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Methodology

1.  **Data Acquisition**: Downloads historical price data for a given stock ticker using yfinance.
2.  **Feature Engineering**: Calculates a variety of technical indicators, including:
    -   Rolling Volatility
    -   Moving Averages
    -   Momentum Indicators (e.g., RSI)
3.  **Regime Classification**: Employs K-Means clustering (with an option for Hidden Markov Models) to classify market regimes based on return and volatility patterns.
4.  **Visualization**: Generates a clear and informative plot of the stock price, with the background shaded to represent the detected market regime.

## Features

-   **Automated Regime Detection**: Identifies Bull, Bear, and Sideways market conditions.
-   **Flexible Model**: Easily adaptable to use different machine learning models.
-   **Clear Visualization**: Professional and easy-to-understand plots with a clear legend.
-   **Clean Codebase**: Modular and production-style code for easy maintenance and extension.

## Tech Stack

-   Python
-   yfinance
-   pandas
-   numpy
-   scikit-learn
-   matplotlib

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AbhiramSharma/Market-Regime-Detection-System.git
    cd Market-Regime-Detection-System
    ```

2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the market regime detection system, execute the following command:

```bash
python main.py
```

## File Structure

-   `main.py`: The main entry point for running the system and generating visualizations.
-   `regime_model.py`: Contains the logic for feature engineering and regime classification.
-   `requirements.txt`: A list of the Python dependencies for the project.
-   `README.md`: This file.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Abhiram Sharma - ab23.ar39@gmail.com

Project Link: [https://github.com/AbhiramSharma/Market-Regime-Detection-System](https://github.com/AbhiramSharma/Market-Regime-Detection-System)
