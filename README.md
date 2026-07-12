# Stochastic Modeling in Finance

The projects span two major areas of quantitative finance:

- **Computational Derivatives & Stochastic Volatility**
- **Quantitative Portfolio Management & Regime-Switching Models**

Both projects emphasize mathematical modeling, numerical methods, statistical inference, Monte Carlo simulation, and practical financial decision-making.

## Project 1 – Advanced Option Pricing & Interest Rate Modeling

Developed a complete stochastic pricing framework for vanilla and exotic derivatives by calibrating stochastic volatility models to market option prices, pricing contracts under risk-neutral dynamics and modeling interest rates.

**Implemented Models**
- Heston Stochastic Volatility Model
- Bates Jump-Diffusion Model
- Cox-Ingersoll-Ross (CIR) Interest Rate Model

**Numerical Techniques**
- Lewis (2001) Fourier Pricing
- Carr-Madan (1999) FFT Pricing
- Monte Carlo Simulation
- Numerical Optimization
- Characteristic Functions
- Risk-Neutral Pricing

**Key Features**
- Heston model calibration
- Bates jump calibration
- Fourier transform pricing
- FFT-based option valuation
- Asian option pricing
- European option pricing
- Interest-rate term structure construction
- CIR calibration
- Euribor forecasting
- Yield curve interpolation
- Monte Carlo simulation
- Model validation
- Sensitivity analysis

**Skills Demonstrated**
- Stochastic Differential Equations
- Fourier Methods
- Characteristic Functions
- Calibration Techniques
- Numerical Integration
- Monte Carlo Methods
- Financial Engineering


---

### Project 2 – Regime-Based Portfolio Allocation using Hidden Markov Models

Designed and evaluated a dynamic asset allocation strategy that identifies hidden market regimes from VIX behavior and rotates capital across multiple ETFs.

**Implemented Models**
- Markov Chains
- Hidden Markov Models
- Gaussian HMM
- Expectation-Maximization Algorithm

**Quantitative Workflow**
- Market data collection
- Feature engineering
- Volatility regime detection
- State estimation
- Transition probability analysis
- Allocation optimization
- Portfolio backtesting
- Benchmark comparison

**Trading Strategy**
- Market regimes are inferred from VIX dynamics and translated into portfolio allocations among **SPY**, **GLD**, and **TLT** using rule-based allocation with execution lag to eliminate look-ahead bias.

**Performance Evaluation**
- Cumulative Return
- Annualized Return
- Annualized Volatility
- Sharpe Ratio
- Maximum Drawdown
- Benchmark Comparison
- Sensitivity Analysis

**Skills Demonstrated**
- Time Series Analysis
- Hidden Markov Models
- Statistical Learning
- Portfolio Construction
- Backtesting
- Quantitative Trading
- Risk Management



### Comparison
   | Feature      | Project 1                                 | Project 2                                       |
| ------------ | ----------------------------------------- | ----------------------------------------------- |
| Domain       | Derivative Pricing                        | Quantitative Portfolio Management               |
| Main Topic   | Stochastic Volatility Models              | Regime Switching Models                         |
| Objective    | Price options accurately                  | Allocate assets based on market regimes         |
| Market       | Options                                   | ETFs & Portfolio                                |
| Data         | Option chain + Interest rates             | Yahoo Finance ETF & VIX                         |
| Models       | Heston, Bates, CIR                        | Markov Chain, Hidden Markov Model               |
| Techniques   | Calibration, Fourier Pricing, Monte Carlo | State Estimation, Regime Detection, Backtesting |
| Output       | Option Prices                             | Trading Strategy                                |
| Finance Area | Quantitative Derivatives                  | Quantitative Asset Management                   |


## Highlights

| Derivatives & Stochastic Volatility | Portfolio Management & Regime Detection |
| :--- | :--- |
| Calibrated Heston and Bates models to real market option prices | Developed Hidden Markov Models for volatility regime identification |
| Implemented Lewis and Carr-Madan Fourier pricing approaches | Designed a regime-based ETF rotation strategy |
| Priced Asian and European options using Monte Carlo simulation | Evaluated strategy performance using industry-standard risk metrics |
| Built and calibrated a CIR interest-rate model for Euribor term structures | Performed model validation and sensitivity analysis |

```bash
.
├── Project_1_Option_Pricing_Using_Heston_Bates_CIR_Models
│   ├── Project_1_Option_Pricing_Using_Heston_Bates_CIR Models.ipynb
│   └── Report_Comprehensive_Analysis_of_Heston_Bates_and_CIR_Models.pdf
├── Project_2_Regime_Based_Portfolio_Allocation
│   ├── Project_2_Regime_Based_Portfolio_using_Markov Chains_Hidden Markov_Models.ipynb
│   └── Report_A_Regime_Switching_Approach_to_Tactical_Asset_Allocation_Using_VIX_and_HMM
└── requirements.txt
```
## Technologies, Topics & Skills

| Technologies | Quantitative Finance Topics | Skills Demonstrated |
| :--- | :--- | :--- |
| Python, NumPy, Pandas, SciPy | Stochastic Processes, Option Pricing, Derivative Valuation | Quantitative Modeling, Financial Mathematics |
| Matplotlib, Plotly, yfinance | Fourier Transform Methods, Monte Carlo Simulation, Jump-Diffusion Models, Interest Rate Modeling | Stochastic Calculus Applications, Numerical Methods, Model Calibration |
| hmmlearn, scikit-learn | Hidden Markov Models, Markov Chains, Regime Switching Models | Statistical Learning, Time Series Analysis |
| Jupyter Notebook | Portfolio Optimization, Quantitative Trading, Financial Engineering | Risk Analysis, Algorithmic Portfolio Design, Python for Quantitative Finance |
