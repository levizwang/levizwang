# Hi, I'm **Levi Wang** 👋 — LLM Evaluation & Synthetic-Data Infrastructure Engineer

I build the infrastructure that makes LLM evaluation trustworthy: multi-agent pipelines that synthesize hard, document-grounded agentic benchmark tasks in expert domains (finance, consulting, law, medicine), the LLM-as-judge and adversarial-QC systems that keep that data valid, and the cloud batch orchestration that benchmarks model × harness combinations at scale.

---

## 🧰 Tech Stack

**Languages**  
[![WakaTime](https://wakatime.com/badge/user/deadb2d7-8b4f-41cd-ab96-7a8c925f1e5c.svg)](https://wakatime.com/@Shizue)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)

**AI / LLM**  
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=claude&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-0B0B0B?logo=openai&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?logo=cursor&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-111827?logo=modelcontextprotocol&logoColor=white) ![LLM-as-Judge](https://img.shields.io/badge/LLM--as--Judge-7B61FF) ![Agent-as-Judge](https://img.shields.io/badge/Agent--as--Judge-9B59B6) ![Metric Design](https://img.shields.io/badge/Metric%20Design-16A085) ![Training/Eval Data Synthesis](https://img.shields.io/badge/Training%2FEval%20Data%20Synthesis-E67E22) ![Multi-Agent Orchestration](https://img.shields.io/badge/Multi--Agent%20Orchestration-4A90E2)

**Frameworks / Platforms**  
![Harbor (eval framework)](https://img.shields.io/badge/Harbor%20eval%20framework-2F80ED) ![Daytona Sandboxes](https://img.shields.io/badge/Daytona%20Sandboxes-0DB7ED) ![Dagster](https://img.shields.io/badge/Dagster-654FF0?logo=dagster&logoColor=white)

**Tools**  
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)

---

## 🧪 Core Expertise & Projects

- **Benchmark-synthesis pipelines** — solo-architected a greenfield 18-stage multi-agent pipeline that turns expert workspaces into evidence-grounded agentic eval tasks: dual-model evidence extraction with intersection-based confirmation, DAG-structured rubrics (process/outcome typing, dependency gating, hurdle rows), and a blind-then-hinted trial-solve stage — ~28k lines of Python, 362 unit tests, end-to-end within ~27 hours of `git init`.
- **Measurable difficulty calibration** — steered a 134-question expert benchmark from mean 0.821 into a 0.5–0.7 acceptance band (final 0.648) with a leak-proof isolated eval harness and controlled experiments; "make it harder" as an experiment, not a vibe.
- **LLM-as-judge QA** — debug the judge itself (false leakage-zeroing, silently dropped rubric fields) and enforce delivery invariants like *reference answers must score full marks*, backed by minimal-change automated repair fleets (200+ workers).
- **Cloud batch-eval orchestration** — model × harness benchmark matrices on ~70 concurrent cloud sandboxes with load-balanced API routing, semantic + judge-hallucination audit workers, and per-model per-task cost accounting.
- **Agent-swarm engineering** — ran a 51-agent adversarial code review (6 independent finders → execution-verified findings with per-defect introducing-commit attribution) on a production pipeline fork.
- **Open source** — built an upstream-ready Stirrup-agent integration for [`harbor-framework/harbor`](https://github.com/harbor-framework/harbor) (runner, provider routing, trajectory capture, unit-tested), rebased cleanly onto upstream v0.17 touching only 2 registry lines.

---

### 📊 Weekly Coding Stats
<!--START_SECTION:waka-->

```txt
From: 14 July 2026 - To: 21 July 2026

Total Time: 75 hrs 55 mins

Python           35 hrs 57 mins        ████████████░░░░░░░░░░░░░   47.36 %
Markdown         25 hrs 47 mins        ████████▒░░░░░░░░░░░░░░░░   33.98 %
TypeScript       4 hrs 15 mins         █▒░░░░░░░░░░░░░░░░░░░░░░░   05.60 %
JSON             2 hrs 31 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.32 %
YAML             2 hrs 22 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.14 %
Jinja2           2 hrs 15 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.98 %
Text             1 hr 13 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.61 %
Bash             33 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.74 %
CSS              32 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.71 %
GitIgnore file   8 mins                ░░░░░░░░░░░░░░░░░░░░░░░░░   00.18 %
```

<!--END_SECTION:waka-->
