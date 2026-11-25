### Ubaid Mushtaq Mir

ML, AI and quantitative engineer from Kashmir, India. I work across data science, machine learning, AI systems and quant research, building models, data pipelines and the tooling to test them for national and international clients.

#### What I work on

- Machine learning and data science work covering feature engineering, time-series forecasting with LSTMs, graph neural networks and reinforcement learning (PPO, multi-agent RL), with careful model evaluation and statistical testing.
- Quant research on signals from momentum, volatility and time-series features, with LSTM forecasting and RL-based position sizing. Strategies are validated with walk-forward backtests that include transaction costs, Sharpe ratio and maximum drawdown. I also build automated portfolio management and trading systems, including crypto.
- AI and LLM systems built on LLM APIs, tool calling and agent workflows, plus benchmark tasks with reproducible Docker environments, reference solutions and pytest graders. 500+ tasks delivered at a 90% approval rate.
- Production ETL pipelines with dbt, Kafka and Postgres, containerised with Docker.

#### Selected projects

| Project | What it does | Highlights |
| --- | --- | --- |
| [futureleak](https://github.com/Ubaid0786/futureleak) | Black-box test for look-ahead leakage in time-series features, using truncation and perturbation | 684 indicators audited across six TA libraries. All 10 flags traced to source lines, one [reported upstream](https://github.com/bukosabino/ta/issues/374) |
| [itemaudit](https://github.com/Ubaid0786/itemaudit) | Paired significance tests and 2PL item response theory on benchmark results tables | Across 173 SWE-bench Verified submissions, no top 20 pair is separable after Holm correction. Found [two inconsistent submissions](https://github.com/SWE-bench/experiments/issues/524) |
| [recallcert](https://github.com/Ubaid0786/recallcert) | Statistical stopping rules with recall guarantees for ML-assisted document screening | A common heuristic missed 95% recall in 61.5% of 260 runs on 26 reviews |
| [DRIMAPS](https://github.com/Ubaid0786/DRIMAPS) | Multi-agent path finding with wait-for-graph deadlock detection (Tarjan SCC) and a targeted escape step, plus a Gymnasium/PettingZoo simulator | Ongoing, benchmarked on MovingAI maps |
| Algorithmic trading platform (private) | Market data ingestion, LSTM forecasting, RL position sizing and a backtesting engine with look-ahead leakage tests | Python, PyTorch, Docker, AWS |

#### Research

- [Deadlocks in Dense Lifelong MAPF, A Journey from Why to Adaptive Density Control](https://ieeexplore.ieee.org/document/11708305), IEEE ICSCSA 2026, co-author. A closed-loop controller that tunes the number of active agents from the deadlock signal alone. Code: [tay805/mapf-deadlock](https://github.com/tay805/mapf-deadlock)
- PRISMA review of energy efficiency in IoT and wireless sensor networks, co-author (manuscript). A two-axis taxonomy of 136 studies.

#### Stack

| Area | Tools |
| --- | --- |
| Languages | Python, SQL, C, C++, Java, Go, Rust, Bash, JavaScript, TypeScript |
| ML and data science | PyTorch, TensorFlow, scikit-learn, pandas, NumPy, GNNs, RL (PPO, MARL), LSTM |
| Quant | Time-series forecasting, backtesting, portfolio construction, risk metrics |
| AI systems | LLM APIs, tool calling, agent evaluation, RLHF |
| Data and infra | dbt, Kafka, Postgres, MySQL, Docker, AWS, Linux, Git, CI/CD |

#### Contact

[ubaidmushtaq0786@gmail.com](mailto:ubaidmushtaq0786@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ubaid-mushtaq-38774a2a5/)
