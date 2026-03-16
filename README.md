# Felipe Cardozo

**Quantitative researcher and engineer** at the intersection of stochastic modeling, reinforcement learning, and market microstructure. Undergraduate at Emory University studying Human-Machine Interaction with concentrations in quantitative finance, computer science, and applied mathematics.

I build systems that turn mathematical structure into edge — from regime-aware portfolio allocation to real-time inventory automation via computer vision.

---

### Selected Work

**[RAMPA](https://github.com/FelipeCardozo0/RAMPA)** — Regime-Aware Multi-Agent Portfolio Allocator  
Multi-agent system combining PPO-based reinforcement learning with HMM regime classification, eigen-portfolio construction via spectral decomposition of the return covariance matrix, and a volatility oracle built on rough Bergomi dynamics (fractional kernel with Hurst exponent estimation). Agents specialize by regime; a meta-learner allocates across them.

**[Regime-Volatility-Arbitrage](https://github.com/FelipeCardozo0/Regime-Volatility-Arbitrage)** — Fourier-Based Pricing & Volatility Surface Modeling  
Characteristic function pricing under Heston and CGMY via FFT and fractional FFT methods. Implements Dupire local volatility recovery, variance swap replication, and volatility risk premium extraction. Calibration against SPX options surfaces.

**[Azure-HFT](https://github.com/FelipeCardozo0/Azure-HFT)** — Low-Latency Trading Infrastructure  
Event-driven execution engine deployed on Azure with Redis-backed tick streaming, FIX protocol integration, and sub-millisecond order routing. LightGBM alpha signals consumed in real time by a risk-managed execution layer.

**[NEXUS](https://github.com/FelipeCardozo0/nexus-underwriting)** — AI-Powered Credit Underwriting Engine  
Knowledge graph–based credit assessment system targeting structured credit products (FIDCs, ABS). Integrates alternative data pipelines with graph neural networks for borrower risk scoring and portfolio-level loss distribution modeling.

**[Veratori](https://github.com/FelipeCardozo0/veratori)** — Computer Vision for Restaurant Inventory  
YOLOv8 object detection with LiDAR depth sensing for real-time inventory quantification. Edge-deployed on NVIDIA Jetson; RL-based reorder policy optimization. In production use.

---

### What I work with

**Math & Finance:** Stochastic calculus, rough volatility, martingale pricing, PDE methods (Fourier series, heat equation), regime-switching models, portfolio optimization, risk-neutral measure theory  
**ML & RL:** PPO, actor-critic architectures, GNNs, LightGBM, spectral methods for dimensionality reduction  
**Systems:** Python, C++, Redis, Docker, Azure, FIX protocol, NVIDIA Jetson edge deployment  

---

### Currently

- Building out RAMPA's rBergomi volatility oracle with hybrid simulation schemes  
- Researching private credit structuring — Brazilian FIDCs and US ABS tranching mechanics  
- Coursework in PDEs/Fourier analysis, mathematical statistics, algorithm design, and data mining  
- Active research with PhD advisor (twice weekly) on quantitative modeling  

---

<sub>focardo@emory.edu · [LinkedIn](https://linkedin.com/in/felipecardozo-)</sub>
