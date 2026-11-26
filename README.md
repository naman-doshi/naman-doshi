### Naman Doshi

CS & Mathematics at **UNSW** (Mike Cannon-Brookes Scholar). Incoming **Quantitative Trading Intern at Jane Street** & **AlgoDev Intern at Hudson River Trading**; previously **QT Intern at IMC**.

[LinkedIn](https://www.linkedin.com/in/naman-d/)

#### ML & Systems

- **EventPFN** *(publishing soon)* — Prior-data fitted network / in-context learning for event data (PyTorch).
- **[whitecircle/halo](https://github.com/whitecircle/halo) contributions** — Reproduced and implemented verified fixes for three core post-training / RL bugs:
  - [#234](https://github.com/whitecircle/halo/issues/234): GRPO first-push weight-sync parity probe temperature mismatch (`T = rollout_temperature` vs raw `T = 1.0` engine log-probs) — [branch](https://github.com/naman-doshi/halo/compare/main...fix/push-parity-temperature)
  - [#235](https://github.com/whitecircle/halo/issues/235): SDPG chunked teacher forward ignoring `rows_forward_densely` on `mistral4`/`mistral3`/`deepseek_v4` and `flash_attention_4` — [branch](https://github.com/naman-doshi/halo/compare/main...fix/sdpg-teacher-dense-forward)
  - [#236](https://github.com/whitecircle/halo/issues/236): Eager NVFP4 empty-tensor crash (`M = 0` EP ranks) and flushed-denormal `NaN`s — [branch](https://github.com/naman-doshi/halo/compare/main...fix/nvfp4-empty-and-ftz)
- **Live ML Trading Systems** *(private — accounts for recent commit activity)* — Low-latency tick-data pipelines, custom backtester, and 1–5s horizon gradient-boosted models (600+ features, purged CV, 0.15 OOS $R^2$) deployed live on colocated infrastructure.
- **[successive-bipartite-matching](https://github.com/naman-doshi/successive-bipartite-matching)** — Closed bounds, empirical distribution analysis, and C++ Network Simplex vs. Hungarian benchmarks for successive maximum-weight bipartite matchings.
- **[AutoFlow-v2](https://github.com/naman-doshi/AutoFlow-v2)** — Space-time road-network pathfinding & 150 km² traffic simulation (Python/C++/C#; 20% faster trips, 26% lower emissions; 1st / 2,500 teams at Uber Global Hackathon).
- **[packages](https://github.com/naman-doshi/packages)** — C++ algorithms library (min-cost max-flow, segment trees, computational geometry, FFT, DP, graphs).

#### Selected Awards

- **MIT Battlecode:** 1st / 600+ teams (2026, [repo](https://github.com/awu7/battlecode-2026)); 5th + Most Adaptive Strategy (2025, [repo](https://github.com/naman-doshi/battlecode-2025))
- **Simon Marais Mathematics Competition:** 3rd in Australia, 15th globally (2025)
- **IMC Prosperity:** Top 0.5% internationally — peaked 2nd / 12,600 (2025), 42nd / 13,500 solo (2024)
- **Regeneron ISEF** Team Australia (2025) · **Australian Informatics Olympiad** Gold & IOI Selection Schools (2024) · **Citadel Terminal Asia** 5th, seeded 1st (2025) · **AMT** Informatics Problemsetter
