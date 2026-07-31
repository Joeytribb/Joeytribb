# Iniyan Andrews Joseph

**AI Research Engineer & Master's Student in Data Science**  
*Focus: Foundation World Models, Physical AI, Autoregressive Sequence Generators & Continuous Reinforcement Learning*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/iniyandrews) 
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:iniyandrews@gmail.com)

---

## 🔬 Research & Open Science Agenda

I build deep learning architectures, sequence generators, and continuous control agents from scratch in PyTorch. My research focuses on solving data scarcity in complex environments by building open generative world models, tokenizing multi-dimensional state spaces, and advancing physical autonomy.

I am a strong advocate for **Open Science** and **Agentic Research Engineering**—leveraging AI-agentic pair-programming workflows to rapidly prototype, benchmark, and deploy reproducible research codebases.

---

## 🚀 Active Open-Source Repositories

### 1. [Generative-LOB-Transformer](https://github.com/Joeytribb/Generative_LOB_Simulator)
*Autoregressive Causal World Model for Market-By-Order Limit Order Books*
- **Problem:** Real-world Level 3 (L3) order book data is paywalled by commercial providers, creating a data-scarcity bottleneck for continuous control.
- **Methodology:** Built a PyTorch differential data engine mapping continuous ask/bid prices and volume deltas into discrete latent tokens via quantile binning. Constructed a decoder-only GPT-style Causal Transformer (RoPE, causally masked self-attention, KV-caching).
- **Results:** Autoregressively generated synthetic L3 order book sequences replicating empirical heavy-tailed Pareto volume distributions without teacher forcing.
- 📁 **Repository:** [Generative_LOB_Simulator](https://github.com/Joeytribb/Generative_LOB_Simulator)

### 2. [Project Bithax (Continuous PPO Control Engine)](https://github.com/Joeytribb/bithax)
*Continuous State-Space Reinforcement Learning in Non-Stationary Environments*
- **Methodology:** Formulated a continuous state-space Markov Decision Process (MDP) and trained a Proximal Policy Optimization (PPO) agent in PyTorch.
- **Innovation:** Engineered custom dense reward functions penalizing second-order volatility and execution friction to prevent policy collapse in high-noise regimes.
- **Results:** Achieved high out-of-sample Sharpe ratios and drawdown bounds, outperforming baseline benchmarks.
- 📁 **Repository:** [Project Bithax](https://github.com/Joeytribb/bithax)

### 3. [Project Jaguu (Multimodal Vision-Language Assistant)](https://github.com/Joeytribb/Jaguu)
*Privacy-First Vision Encoder & LLM Decoder Architecture*
- **Architecture:** Connected visual encoders (vision transformers) to Llama3 decoders for zero-shot visual question answering, spatial scene understanding, and real-time reasoning.
- 📁 **Repository:** [Project Jaguu](https://github.com/Joeytribb/Jaguu)

---

## 🔮 Upcoming Research Initiatives (In Proposal Phase)

- 🏺 **Open-IVC (Computational Archaeology & 3D Spatial AI):** 
- 🤟 **Multimodal Sign Language Live Translation:**

---

## 🛠️ Technical Stack & Frameworks

- **Core ML / AI:** PyTorch, Transformers, PPO / Stable-Baselines3, OpenAI Gym, CUDA, Vision Encoders.
- **Methodology:** Differential Tokenization, Autoregressive Sequence Generation, Quantile Binning, agentic AI workflows.
- **Languages & Tools:** Python (Advanced), C++, SQL, Git, Docker, \LaTeX.

---

*Feel free to reach out via [Email](mailto:iniyandrews@gmail.com) or connect on [LinkedIn](https://linkedin.com/in/iniyandrews).*
