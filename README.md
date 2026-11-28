### Yevhenii Kolesnyk (`razin-core`)

Medical student (VNMU) building applied AI systems, FastAPI backends, real-time tracking pipelines, and programmatic guardrails for CLI agents.

| Project | Highlights | Stack | CI |
| :--- | :--- | :--- | :--- |
| **[krokflow](https://github.com/razin-core/krokflow)** | Production KROK-1 / ЄДКІ exam platform ([live](https://krokflow.pp.ua), 2,570 verified Qs) — offline clinical triggers (0 runtime LLM spend), `FTS5` + `SM-2`, exam timers, PWA, automated SQLite backups | `FastAPI`, `SQLite WAL/FTS5`, `Pytest` | [![CI](https://github.com/razin-core/krokflow/actions/workflows/ci.yml/badge.svg)](https://github.com/razin-core/krokflow/actions/workflows/ci.yml) |
| **[bayes-track-core](https://github.com/razin-core/bayes-track-core)** | Real-time geospatial tracking & fusion core — vectorized `IMM-EKF` (Huber + OOSM guard), Yager-Dempster fusion, SHA-256 content cache, zero-trust API auth | `Python`, `NumPy`, `H3`, `FastAPI` | [![CI](https://github.com/razin-core/bayes-track-core/actions/workflows/ci.yml/badge.svg)](https://github.com/razin-core/bayes-track-core/actions/workflows/ci.yml) |
| **[agent-safety-guard](https://github.com/razin-core/agent-safety-guard)** | Zero-dependency `PreToolUse` safety hook blocking destructive DB/systemd/FUSE/rm/heredoc commands before execution (`fail-closed` ready) | `Python`, `CLI`, `JSON Policy` | [![CI](https://github.com/razin-core/agent-safety-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/razin-core/agent-safety-guard/actions/workflows/ci.yml) |

**Core stack:** `Python` · `FastAPI` · `SQLite (WAL / FTS5)` · `NumPy` · `Pytest` · `Linux (ARM64)` · `Cloudflare Tunnels`
