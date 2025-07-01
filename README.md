# Finance Analysis Project

A comprehensive analysis of major bank stocks during and after the 2008 Financial Crisis with interactive visualizations.

## Project Overview

This project analyzes the performance of six major U.S. banks during the 2008 Financial Crisis period and extends the analysis to recent years. The analysis focuses on:

- **Stock Price Evolution**: How bank stocks performed during the crisis
- **Risk Analysis**: Volatility patterns and risk metrics
- **Correlation Analysis**: Relationships between different bank stocks
- **Crisis Impact**: Quantitative assessment of crisis effects
- **Recovery Patterns**: Post-crisis performance comparison

### Banks Analyzed

| Bank | Ticker | Full Name |
|------|--------|-----------|
| BAC | Bank of America | Bank of America Corporation |
| C | CitiGroup | Citigroup Inc. |
| GS | Goldman Sachs | The Goldman Sachs Group, Inc. |
| JPM | JPMorgan Chase | JPMorgan Chase & Co. |
| MS | Morgan Stanley | Morgan Stanley |
| WFC | Wells Fargo | Wells Fargo & Company |

## Key Features

### Technology Stack
- **Data Source**: `yfinance`
- **Visualizations**: Interactive Plotly charts
- **Analysis**: Advanced statistical metrics and risk analysis
- **Code Quality**: Type hints, proper documentation, error handling

### Interactive Visualizations
- **Price Evolution Chart**: Interactive timeline of stock prices
- **Returns Distribution**: Histogram analysis with normal distribution overlay
- **Correlation Heatmap**: Interactive correlation matrix
- **Volatility Analysis**: Rolling volatility with crisis period highlighting
- **Normalized Performance**: Base-100 comparison chart

## Project Structure

```
── Finance_Analysis.ipynb.zip              # Main analysis notebook
── README.md                               # This file
modernized_finance_project/
├── bank_prices_evolution.html          # Interactive price chart
├── returns_distribution.html           # Returns analysis chart
├── correlation_heatmap.html            # Correlation visualization
├── volatility_analysis.html            # Volatility chart
├── normalized_performance.html         # Performance comparison
└── extended_performance.html           # Long-term analysis
```

## Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Quick Start

1. **Clone or download the project**
   ```bash
   git clone <repository-url>
   cd  finance_project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Finance_Analysis.ipynb
   ```

4. **Run all cells** to execute the complete analysis


## Key Findings

### Financial Crisis Impact (2007-2009)
- All major banks experienced significant declines during the crisis
- **CitiGroup (C)** was hit hardest with the largest drawdown
- **JPMorgan Chase (JPM)** showed relatively better resilience
- Peak volatility occurred during September-October 2008

### Correlation Patterns
- High correlation between bank stocks indicating systemic risk
- Correlations increased during crisis periods
- Goldman Sachs showed slightly different patterns from other banks

### Recovery Analysis
- Different recovery speeds post-crisis
- Some banks never fully recovered to pre-crisis levels in the analyzed period
- JPMorgan and Goldman Sachs showed stronger long-term recoveries

### Risk Characteristics
- Banking sector exhibited high volatility clustering
- Returns distributions showed fat tails (non-normal distribution)
- Crisis periods demonstrated extreme volatility spikes

## Technical Improvements

This project includes several enhancements over traditional finance analysis:

### Data Handling
- Modern `yfinance` API (reliable and maintained)
- Robust error handling for data fetching
- Automatic data validation and cleaning

### Visualizations
- Interactive Plotly charts with hover information
- Zoom and pan capabilities
- Professional styling and annotations
- Exportable HTML charts for sharing

### Analysis Depth
- Rolling volatility analysis
- Crisis impact quantification
- Extended time period analysis (2006-2024)
- Normalized performance comparison

### Code Quality
- Type hints for better documentation
- Comprehensive function documentation
- Modern Python practices
- Modular and reusable code structure

## Sample Outputs

The analysis generates several interactive HTML charts:

1. **Bank Prices Evolution**: Shows how all bank stocks performed over time with crisis period highlighting
2. **Returns Distribution**: Histogram analysis comparing actual returns to normal distribution
3. **Correlation Heatmap**: Interactive matrix showing relationships between bank stocks
4. **Volatility Analysis**: Rolling 30-day volatility with crisis period shading
5. **Performance Comparison**: Normalized charts showing relative performance

## Educational Value

This project demonstrates:
- **Financial Data Analysis**: Real-world application of data science to finance
- **Crisis Analysis**: Understanding systemic risk and market behavior
- **Modern Python**: Current best practices and libraries
- **Interactive Visualization**: Professional-grade chart creation
- **Risk Management**: Quantitative risk assessment techniques

## Disclaimer

This project is for **educational and analytical purposes only**. The analysis and findings should not be considered as financial advice. Always consult with qualified financial professionals before making investment decisions.

## Contributing

Contributions are welcome! Areas for enhancement:
- Additional risk metrics (VaR, CVaR)
- Machine learning predictions
- Sector comparison analysis
- Real-time data integration
- Additional visualization types

## License

This project is open source and available under the MIT License.

## Resources

- [yfinance Documentation](https://pypi.org/project/yfinance/)
- [Plotly Python Documentation](https://plotly.com/python/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Financial Crisis of 2008 - Wikipedia](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308)

---

**Built with ❤️ using Python**
