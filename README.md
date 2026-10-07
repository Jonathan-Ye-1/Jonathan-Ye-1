# Hi, I'm Yixuan (Jonathan) Ye

M.S. in Electrical Engineering at **Columbia University** (expected Dec 2026) · B.E. Nuclear Engineering & B.A. English, Tsinghua University · former senior teaching researcher (4 years in education).

I build **machine-learning systems that are measured, not just demoed**: LLM agents with retrieval and guardrails, reinforcement learning for personalized learning, and deep generative models with rigorous evaluation.

**Tools:** Python · PyTorch · LangChain · Milvus · PostgreSQL · Streamlit · RAGAS · scikit-learn · XGBoost · RDKit · AutoDock Vina · GCP (BigQuery, Vertex AI)

[LinkedIn](https://www.linkedin.com/in/yixuan-ye)

## Featured projects

| Project | What it is | My role | Result |
|---|---|---|---|
| [**AI Insurance Advisor**](https://github.com/HammerNiu/Insurance-Agent) | LangChain ReAct agent (GPT-4o-mini) that routes questions to two Milvus collections built from PostgreSQL records and PDF handbooks, cites sources and refuses when context is missing | Team lead (3 people); built the Streamlit UI and the RAGAS evaluation suite | RAGAS Answer Relevancy 0.96, Context Precision 0.75 |
| [**Adaptive Question Recommendation with RL**](https://github.com/AdamQin1/RL_Adaptive_Learning_Final_Project) | Dueling/Double DQN tutor trained offline inside an LSTM Deep-Knowledge-Tracing student simulator to choose each student's next question | Team lead (5 people); proposed the idea, designed the system, implemented the DQN agent | +0.0857 knowledge gain per 20-step session vs +0.0215 rule-based; beat PPO (+0.0732) |
| [**EGFR T790M Inhibitor Design with Diffusion**](https://github.com/Jonathan-Ye-1/egfr-drug-design-eecs6895-final-project) | TargetDiff pocket-conditioned generation, cross-docking selectivity analysis and in-silico SAR optimization | Solo project | 1,987 molecules; lead compound with 6× Osimertinib's docking selectivity, QED 0.87 |
| [**Generative Market Simulation**](https://github.com/shufengc/generative-market-simulation) | Benchmarks GARCH, VAE, TimeGAN, RealNVP and DDPM on six stylized facts of 16 assets over 21 years, with VaR backtests | Built the evaluation framework, TimeGAN and the calibration study (5 people) | Best DDPM passes 5/6 facts, MMD 0.006; real data itself passes only 3/6 |
| [**Benign Overfitting Phase Diagram**](https://github.com/alice20030504/EECS-6699) | Width × label-noise sweep of CNNs on CIFAR-10 mapping benign, tempered and catastrophic overfitting | Designed the shared training pipeline and reproductions (4 people) | Fitted benign boundary w ≈ 320η over a 9 × 6 grid |

**Also:** multi-omics pan-cancer analysis on GCP (89.89% cancer-type accuracy, survival C-index 0.6645) · wildfire burned-area prediction with Hurdle and extreme-value models · comparative analysis of Bitcoin Layer-2 designs. Code or reports available on request.

<sub>Team projects link to the original repositories; the "My role" column describes my own contribution.</sub>
