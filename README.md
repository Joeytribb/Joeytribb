# Hi there, I'm Iniyan Andrews Joseph 👋

<p align="left">
  <strong>AI Research Engineer & Doctoral Applicant</strong><br/>
  <em>Focus: Embodied AI, Biomechanical Digital Twins, Geometric Deep Learning & Foundation World Models</em>
</p>


[![LinkedIn](https://img.shields.io/badge/LinkedIn-iniyandrews-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iniyandrews)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iniyandrews@gmail.com)

---

## 🔬 About Me & Research Vision

I am an AI research engineer with an **M.Sc. in Computer Science (Data Science)** from the National Institute of Electronics & Information Technology (NIELIT), Calicut. 

My research operates at the intersection of **continuous physical dynamics and discrete foundation language models**:
* **Physical & Embodied AI:** Grounding neural generative models on explicit musculoskeletal manifolds, inverse kinematics (IK), and non-linear topological constraints to eliminate hallucinations.
* **Geometric Deep Learning & Diffusion:** Formulating manifold-projected residual diffusion ($\Pi_{\mathcal{M}}$) and inference-time scene-graph guidance for complex 3D human articulation.
* **Continuous Reinforcement Learning & World Models:** Designing stochastic optimal control policies (PPO) and autoregressive sequence generators over high-dimensional state spaces.
* **Open Science & Community Co-Design:** Engineering reproducible, open-access research codebases developed under ethical community stewardship (e.g., *Viittomakielilaki 359/2015* with the Finnish Association of the Deaf).

---

## 🌟 Flagship Research Project

### 🤟 [Project BiSign: A Bidirectional Foundation Pipeline for Continuous Sign Language AI](https://github.com/Joeytribb/sign-language-kinematics)

> **Doctoral Research Proposal & Open-Source Biomechanical Digital Twin**  
> *Target Lab: Dr. Azade Farshad (Department of Computer Science, Aalto University & ELLIS Institute Finland)*  
> 🌐 **Full Research Portal:** [joeytribb.github.io/sign-language-kinematics](https://joeytribb.github.io/sign-language-kinematics/)  
> 🎮 **Live WebGL 3D Demo:** [Interactive Kinematic Synthesizer @ 60 FPS](https://joeytribb.github.io/sign-language-kinematics/04_Procedural_Engine_PoC/anatomical_hand.html)  
> 📄 **Doctoral Proposal:** [15-Page Verified Proposal PDF](https://joeytribb.github.io/sign-language-kinematics/Bidirectional_PhD_Proposal_Aalto_ELLIS.pdf)  

* **The Problem:** Sign language is an unwritten, 4D continuous phenomenon $(\mathbb{R}^3 \times \mathbb{R})$. Unconstrained diffusion models produce severe bone stretching ("rubber fingers") and joint dislocations that smear centimeter-scale minimal pairs (e.g., inverting *MOTHER* at the chin into *FATHER* at the forehead), while sliding temporal windows cause spatial memory collapse.
* **The Innovation:** A tripartite closed-loop architecture:
  1. **Articulatory Perception Channel:** Monocular 20-DOF hand tracking (HaMeR) + 50 FLAME blendshapes + 3D gaze rays, maintaining an external $\mathcal{O}(1)$ Causal Spatial Memory Bank ($M_t$) with $SO(3)$ Deictic Perspective Rotation ($\mathbf{R}_y(\pi)$).
  2. **BiSign-LLM Core:** Llama 3.1 8B foundation adaptation pre-trained on EuroHPC LUMI (AMD MI250X, PyTorch FSDP + ROCm) via spatial-lexical vocabulary expansion ($\mathcal{V}_{\text{extended}} = \mathcal{V}_{\text{base}} \cup \mathcal{V}_{\text{sign}}$) with Dual-Rate Streaming (1–2 Hz macro-tokens $\leftrightarrow$ 60 Hz kinematics).
  3. **Embodied Biomechanical Actuator:** Closed-form analytical circle swivel IK + manifold-projected residual diffusion ($\Pi_{\mathcal{M}}$) across 30 articulated phalangeal joints.
* **Demonstrated Feasibility:** Deployed a client-side WebGL engine running at 60 FPS ($<0.5$\,ms compute) with **100% rigid bone-length invariance ($\Delta \equiv 0.000\text{ cm}$)**, soft-body phalanx repulsion, and zero finger collisions across all 2,723 signs in ASL-LEX 2.0.

---

## 🚀 Other Featured Open-Source Research Repositories

### 📈 [Project Bithax (Continuous PPO Control Engine)](https://github.com/Joeytribb/bithax)
*Continuous State-Space Reinforcement Learning in Non-Stationary Environments (M.Sc. Thesis Research)*
* **Focus:** Continuous-action Markov Decision Processes (MDPs), stochastic optimal control, and stability bounds under Proximal Policy Optimization (PPO).
* **Innovation:** Formulated dense reward objectives penalizing second-order volatility and transaction friction, rigorously stress-tested against look-ahead bias and non-stationary distribution shifts.
* **Results:** Outperformed standard baselines in out-of-sample Sharpe ratios and maximum drawdown constraints.
* 📁 **Repository:** [Joeytribb/bithax](https://github.com/Joeytribb/bithax)

### 📊 [Generative-LOB-Transformer](https://github.com/Joeytribb/Generative_LOB_Simulator)
*Autoregressive Causal World Model for Market-By-Order Limit Order Books*
* **Focus:** Overcoming commercial data paywalls in high-frequency market microstructure by synthesizing realistic Level 3 (L3) order book streams.
* **Methodology:** PyTorch differential data engine mapping continuous price-volume deltas into discrete latent tokens via quantile binning. Built a decoder-only GPT-style Causal Transformer with Rotary Position Embeddings (RoPE) and KV-caching.
* **Results:** Generated realistic synthetic order book dynamics faithfully replicating empirical heavy-tailed Pareto volume distributions without teacher forcing.
* 📁 **Repository:** [Joeytribb/Generative_LOB_Simulator](https://github.com/Joeytribb/Generative_LOB_Simulator)

### 👁️ [Project Jaguu (Multimodal Vision-Language Assistant)](https://github.com/Joeytribb/Jaguu)
*Privacy-Preserving Vision-Language Architecture for Spatial Scene Understanding*
* **Architecture:** Connected open-weight Vision Transformers (ViT) to quantized Llama decoders for edge-device visual question answering, spatial scene reasoning, and environmental grounding.
* 📁 **Repository:** [Joeytribb/Jaguu](https://github.com/Joeytribb/Jaguu)

---

## 🛠️ Technical Arsenal

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Physical AI & Kinematics** | Three.js, WebGL, Analytical Circle Swivel IK, Forward Kinematics, SMPL-X, Biomechanical Constraints |
| **Deep Learning & GenAI** | PyTorch, Hugging Face Transformers, Latent Diffusion Models (LDM / DiT), Graph Neural Networks (GCN) |
| **Reinforcement Learning** | PPO, Continuous MDPs, Stochastic Optimal Control, Stable-Baselines3, OpenAI Gym / Gymnasium |
| **HPC & Distributed Training**| EuroHPC LUMI (AMD Instinct MI250X), ROCm 6.x / HIP, PyTorch FSDP, Mixed-Precision (bf16), DeepSpeed |
| **Languages & Tools** | Python (Advanced), Modern JavaScript (ES6+), C++, SQL, Git, Docker, LaTeX / TikZ, Linux |

---

## 📬 Get in Touch

* 🌐 **Research Dossier & Live Demos:** [joeytribb.github.io/sign-language-kinematics](https://joeytribb.github.io/sign-language-kinematics/)
* 💼 **LinkedIn:** [linkedin.com/in/iniyandrews](https://www.linkedin.com/in/iniyandrews)
* 📧 **Email:** [iniyandrews@gmail.com](mailto:iniyandrews@gmail.com)
* 🐙 **GitHub:** [@Joeytribb](https://github.com/Joeytribb)
