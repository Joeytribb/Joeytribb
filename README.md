# Iniyan Andrews Joseph
**Quantitative Researcher | M.Sc. Data Science | Focus: Deep Reinforcement Learning in Microstructure**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/iniyan-andrews-joseph) 
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:iniyandrews@gmail.com)

Welcome to my research portfolio. My work focuses on the intersection of Continuous State-Space Reinforcement Learning and Non-Stationary Financial Microstructures. I prioritize strict statistical rigor (Augmented Dickey-Fuller tests, Combinatorial Purged Cross-Validation, Deflated Sharpe Ratios) over simple point-estimate backtesting.

---

## 🔬 Selected Research Projects

### 1. [Generative LOB Simulator (Transformer)](https://github.com/Joeytribb/Generative_LOB_Simulator)
*Autoregressive Modeling of Market-By-Order Limit Order Books*
- **The Problem:** Traditional quantitative finance struggles to generate synthetic LOB data because the order book is governed by strict physical matching rules and complex microstructural stylized facts.
- **The Methodology:** Engineered a differential data engine to tokenize continuous L3 market events. Trained an Autoregressive Causal Transformer (GPT-style) to learn the Markovian transitions and joint probability distributions of the LOB.
- **The Results:** Successfully proved the Transformer learned the underlying market physics by synthesizing 10,000 empirical events that perfectly replicated the fat-tailed Pareto Volume distribution (Stylized Facts).
- **Read the Codebase:** [Generative_LOB_Simulator](https://github.com/Joeytribb/Generative_LOB_Simulator)

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
