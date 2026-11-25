### Ubaid Mushtaq Mir

ML, AI and quantitative engineer from Kashmir, India. I build the benchmark tasks, environments and graders that AI labs use to train and test coding agents. I also build automated trading systems and data pipelines for international clients.

#### Work

As an AI evaluation engineer on agentic coding benchmarks, I have authored 500+ tasks across Terminal-Bench (Terminus), SWE-bench style and agent evaluation (Otter) projects for Snorkel AI and Deccan AI, with a 90% approval rate. I have also done evaluation, RLHF and code review work for Handshake AI, Scale AI, Toloka AI, Mercor and Alignerr. Each task ships with a reproducible Harbor environment, an expert reference solution and a pytest grader built to resist reward hacking, and is checked with oracle, cheating-agent and frontier-model runs.

On the quant side I build portfolio management and trading systems, with walk-forward backtests that account for transaction costs, Sharpe ratio and drawdown.

Client code stays private. The repositories below are my own.

#### Open source

| Project | What it does | Result |
| --- | --- | --- |
| [itemaudit](https://github.com/Ubaid0786/itemaudit) | Statistical audit of agent benchmarks using paired tests and IRT on the results table | Across 173 SWE-bench Verified submissions, no top 20 pair is distinguishable after Holm correction. Also [reported two submissions](https://github.com/SWE-bench/experiments/issues/524) whose per-task results disagree with their score |
| [futureleak](https://github.com/Ubaid0786/futureleak) | Black-box look-ahead leakage auditor for time-series features | Audited 684 indicators in six TA libraries and traced all 10 flags to source lines, [reported upstream](https://github.com/bukosabino/ta/issues/374) |
| [recallcert](https://github.com/Ubaid0786/recallcert) | Stopping rules with recall guarantees for AI-assisted literature screening | A common heuristic missed 95% recall in 61.5% of 260 runs on 26 reviews |
| [DRIMAPS](https://github.com/Ubaid0786/DRIMAPS) | Detection-guided deadlock escape for reactive multi-agent path finding | Wait-for-graph detection with Tarjan-based cycle extraction that moves only agents in a confirmed wait cycle. Ongoing |

#### Research

- [Deadlocks in Dense Lifelong MAPF, A Journey from Why to Adaptive Density Control](https://ieeexplore.ieee.org/document/11708305), IEEE ICSCSA 2026, co-author. A closed-loop controller that tunes the number of active agents from the deadlock signal alone. Code: [tay805/mapf-deadlock](https://github.com/tay805/mapf-deadlock)
- PRISMA review of energy efficiency in IoT and wireless sensor networks, co-author (manuscript). A two-axis taxonomy of 136 studies.

#### Contact

[ubaidmushtaq0786@gmail.com](mailto:ubaidmushtaq0786@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ubaid-mushtaq-38774a2a5/)
