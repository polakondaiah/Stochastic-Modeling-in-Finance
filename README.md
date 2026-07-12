# Stochastic Modeling in Finance

The projects span two major areas of quantitative finance:

- **Computational Derivatives & Stochastic Volatility**
- **Quantitative Portfolio Management & Regime-Switching Models**

## Project 1 – Advanced Option Pricing & Interest Rate Modeling

Implemented and compared multiple stochastic models for pricing financial derivatives and modeling interest rates.

**Highlights:**
- Heston Stochastic Volatility Model
- Bates Jump-Diffusion Model
- Lewis (2001) Fourier Pricing
- Carr-Madan (1999) FFT Pricing
- Asian Option Pricing
- Monte Carlo Simulation
- CIR Interest Rate Model
- Yield Curve Construction
- Cubic Spline Interpolation
- Model Calibration using Market Option Prices

---

## Project 2 – Regime-Based Portfolio Allocation

Designed and evaluated a volatility-driven asset allocation strategy using probabilistic state models.

**Highlights:**
- Markov Chains
- Hidden Markov Models (HMM)
- VIX Regime Detection
- Transition Matrix Estimation
- Expectation-Maximization (EM)
- ETF Rotation Strategy
- Portfolio Backtesting
- Performance Evaluation
- Sharpe Ratio
- Maximum Drawdown
- Regime-Based Investment Strategy

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
