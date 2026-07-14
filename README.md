# Iniyan Andrews Joseph
**Quantitative Researcher | M.Sc. Data Science | Focus: Deep Reinforcement Learning in Microstructure**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/iniyan-andrews-joseph) 
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:iniyandrews@gmail.com)

Welcome to my research portfolio. My work focuses on the intersection of Continuous State-Space Reinforcement Learning and Non-Stationary Financial Microstructures. I prioritize strict statistical rigor (Augmented Dickey-Fuller tests, Combinatorial Purged Cross-Validation, Deflated Sharpe Ratios) over simple point-estimate backtesting.

---

## 🔬 Flagship Quantitative Research

### 1. [DeepRL Limit Order Book Dynamics](https://github.com/Joeytribb/DeepRL_Microstructure)
*Project Thermic: Thermodynamic Decay of Alpha in Market-Making Agents*
- **The Problem:** Neural networks routinely fail in high-frequency trading due to non-stationarity and theoretical zero-latency assumptions.
- **The Methodology:** Engineered an execution-penalized Markov Decision Process (MDP). Enforced strict state-space stationarity using Augmented Dickey-Fuller (ADF) proofs on Order Book Imbalance (OBI) and Fractional Spread.
- **The Results:** Achieved a **Deflated Sharpe Ratio > 2.0** under maker-rebated conditions, statistically validated through Embargoed Walk-Forward Optimization to guarantee zero temporal data leakage. 
- **Read the Paper:** [Oxford Tier Pre-Print (PDF)](./portfolio/Quantitative_Research_Portfolio.pdf)

### 2. [Bithax: High-Frequency Digital Asset Trading](https://github.com/Joeytribb/bithax)
*Master's Thesis: PPO Agents in Continuous 42-Dimensional State Spaces*
- **The Problem:** Optimizing risk-adjusted returns on macro-level OHLCV data using execution friction.
- **The Methodology:** Trained a Proximal Policy Optimization (PPO) agent to navigate non-stationary regimes, utilizing Z-score standardized momentum features and a continuous reward penalty for execution drag.
- **The Results:** Generated an Out-Of-Sample **Sharpe Ratio of 1.9** and a **Profit Factor of 1.9**, vastly outperforming the buy-and-hold benchmark while maintaining strict max-drawdown constraints.

### 3. [Quantitative Risk Modeling](https://github.com/Joeytribb/Quant_Risk_Modeling)
*Project Aegis: Institutional Tail-Risk Evaluation via Monte Carlo*
- **The Methodology:** Rejected standard retail backtesting in favor of a 50,000-path Monte Carlo bootstrap to map 95% Confidence Intervals for ruin probability.
- **The Results:** Mathematically isolated left-tail vulnerability and engineered a Gamma Scalping protocol that bounds the portfolio ruin probability to $<0.1\%$.

---

## 🗄️ Past Explorations
*Archived projects in generic ML and generative AI.*
- **[HOPE (Short-Term Stock Prediction)](https://github.com/Joeytribb/HOPE):** Comparative analysis of LSTMs vs regularized Linear Models on low signal-to-noise financial data.
- **[Jaguu (Multimodal Generative AI Assistant)](https://github.com/Joeytribb/Jaguu):** Privacy-first local voice assistant integrating Llama3 for core reasoning.
- **[TMgo (Autonomous Racing)](https://github.com/Joeytribb/TMgo):** Reinforcement Learning applied to optimal control in Trackmania.
