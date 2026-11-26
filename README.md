### Naman Doshi

CS / Mathematics at **UNSW** (Sydney). Focused on machine learning, post-training, and algorithmic optimization.

[LinkedIn](https://www.linkedin.com/in/naman-d/)

#### Selected Work

- **EventPFN** *(publishing soon)* — In-context learning / prior-data fitted network modeling for event data (PyTorch).
- **[whitecircle/halo](https://github.com/whitecircle/halo) contributions** — Found, reproduced, and implemented verified fixes for three core post-training/RL bugs:
  - [#234](https://github.com/whitecircle/halo/issues/234): Temperature mismatch in GRPO first-push weight-sync parity probe (`T = rollout_temperature` vs raw `T = 1.0` engine log-probs) — [branch](https://github.com/naman-doshi/halo/compare/main...fix/push-parity-temperature)
  - [#235](https://github.com/whitecircle/halo/issues/235): SDPG chunked teacher forward ignoring `rows_forward_densely` on `mistral4`/`mistral3`/`deepseek_v4` and `flash_attention_4` — [branch](https://github.com/naman-doshi/halo/compare/main...fix/sdpg-teacher-dense-forward)
  - [#236](https://github.com/whitecircle/halo/issues/236): Eager NVFP4 empty-tensor crash (`M = 0` EP ranks) and flushed-denormal `NaN`s — [branch](https://github.com/naman-doshi/halo/compare/main...fix/nvfp4-empty-and-ftz)
- **MIT Battlecode — 1st Place (2026) & 6th Place (2025)** — High-throughput multi-agent bots engineered under strict per-turn bytecode budgets ([battlecode-2026](https://github.com/awu7/battlecode-2026), [battlecode-2025](https://github.com/naman-doshi/battlecode-2025)).
- **[packages](https://github.com/naman-doshi/packages)** — C++ competitive programming and algorithms library (min-cost max-flow, segment trees, computational geometry, FFT, DP, graphs).
- **[successive-bipartite-matching](https://github.com/naman-doshi/successive-bipartite-matching)** — C++ Network Simplex vs. Hungarian algorithm performance study and empirical distribution analysis for successive maximum-weight bipartite matchings.

*(Most of my recent commit activity is in private ML research and quantitative systems repositories.)*
