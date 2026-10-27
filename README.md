<h1 align="center">Hi, I'm Ashish 👋</h1>

<p align="center">
  <a href="https://github.com/sitareashish">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=660&lines=Systems+engineer+%C2%B7+low-latency+C%2B%2B;Databases%2C+VMs+and+matching+engines+from+scratch;Multi-agent+AI+systems+%7C+LangGraph+%2B+RAG;Codeforces+Expert+(1776)+%C2%B7+ICPC+Regionalist" alt="typing banner" />
  </a>
</p>

<p align="center">
  <b>B.Tech + M.Tech Dual Degree, CSE @ IIT Kharagpur</b> &nbsp;·&nbsp; Kharagpur, India
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sitareashish&style=flat-square&color=58a6ff&label=Profile+views" alt="profile views" />
</p>

---

I build systems close to the metal — **matching engines, storage engines, bytecode VMs, network servers** — and apply that same low-latency, reliability-first toolkit to **AI and agent infrastructure**: the layer that decides whether agentic systems are fast, correct and cheap in production.

- 🤖 **Agent systems** — multi-agent orchestration (LangGraph), hybrid RAG, sandboxed tool-use, evals & tracing
- ⚙️ **Low-latency C++** — lock-free data structures, `io_uring`, `epoll`, custom allocators, kernel-bypass I/O
- 🗄️ **Databases from scratch** — B+ Tree indexes, ARIES WAL recovery, MVCC snapshot isolation
- 🏆 **Competitive programming** — Codeforces Expert, ICPC Regionalist

---

## 🏆 Highlights

- **Codeforces Expert**, peak rating **1776** — global rank **118** in Round 1105 (Div. 2)
- **ICPC Regionals 2026** qualifier
- **IICPC QuantFest 2026** — Regionals **Rank 347** (round co-titled by Optiver & Jane Street)
- **Smart India Hackathon 2024 Finalist** — Btrfs/XFS forensic tool recovering deleted inodes at ~200 MB/s

---

## 🤖 AI & agent systems

The hard part of agentic AI in production isn't the prompt — it's the runtime: grounded retrieval, isolated tool execution, self-correction, cost control, and observability. That's what I build.

| Project | What it is |
|---|---|
| [**my_ai_issue_resolver**](https://github.com/sitareashish/my_ai_issue_resolver) | Autonomous **multi-agent** pipeline (LangGraph FSM) that turns a GitHub issue into a reviewed PR — context → developer → tester → reviewer agents with confidence-gated re-querying, a **Docker test sandbox**, a self-correcting retry loop, per-issue **token budgeting**, **Qdrant hybrid RAG** (dense + BM25, AST chunking), plus LangSmith/Prometheus tracing and an **evals harness** |
| [**agentloop**](https://github.com/sitareashish/agentloop) | A from-scratch, **dependency-free agent runtime** — a `@tool` decorator that auto-generates JSON schemas from type hints, a plan→act→observe loop with retries and token budgeting, pluggable providers (Anthropic + an offline mock), and fully inspectable trajectories. 35 offline tests, ruff-clean, CI on Python 3.10–3.12 |

> 🔭 **Currently building:** an invisible macOS menu-bar AI assistant driven by the Claude agent bridge, and bringing agent-style tool-use into my systems projects.

## 🛠️ Systems & performance

| Project | Highlights |
|---|---|
| [**femto**](https://github.com/sitareashish/femto) | Real-time order-matching engine (C++20, `io_uring`, LMAX Disruptor) — lock-free intrusive book, **780 ns p99** add-order latency, p99.99 tail cut 24 µs → 4.6 µs, differential-tested over **1 B replayed events** in an ASan/UBSan CI matrix |
| [**htn**](https://github.com/sitareashish/htn) · [**htn-server**](https://github.com/sitareashish/htn-server) | Observable high-throughput service (C11, epoll, `SO_REUSEPORT`) — **42K RPS** across 1,200 live clients, lock-free SPSC ring at **1.8M ops/sec**, Prometheus + Grafana (lab under Prof. Sandip Chakraborty) |
| [**mini-sql-engine**](https://github.com/sitareashish/mini-sql-engine) | Transactional storage engine (C++17) — B+ Tree over 8 KB pages with LRU-K buffer pool (**point queries in 3 I/Os on 10 M rows**), Volcano pipelining, ARIES WAL + MVCC snapshot isolation |
| [**ember**](https://github.com/sitareashish/ember) | Language runtime (C++20) — hand-rolled lexer, Pratt parser, bytecode VM with computed-goto dispatch (**180M ops/sec**), incremental tri-color mark-sweep GC (p99 pause 1.8 ms) |
| [**Stat_Arb**](https://github.com/sitareashish/Stat_Arb) | C++17 pairs-trading backtester — lock-free ingestion, Kalman-filter hedge ratio, volatility-regime detection |
| [**EcoRoute**](https://github.com/sitareashish/EcoRoute) | High-throughput C++ routing engine optimizing graph traversal for carbon emissions and AQI exposure |

---

## 🧰 Skills

**Languages** &nbsp; Python · C++ (11/17/20) · C · Java · SQL · Bash  
**AI / ML** &nbsp; PyTorch · scikit-learn · NumPy · pandas · Matplotlib · LangGraph · RAG  
**Systems** &nbsp; Linux · POSIX threads · epoll · io_uring · lock-free programming · low-latency · storage internals  
**Data & Observability** &nbsp; PostgreSQL · SQLite · Redis · Qdrant · Prometheus · Grafana · perf  
**Testing & DevOps** &nbsp; pytest · GoogleTest · Google Benchmark · ASan/UBSan/TSan · Docker · Git · CMake · GitHub Actions

<p>
  <img src="https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square" />
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

---

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sitareashish&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="Ashish's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sitareashish&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=sitareashish&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

---

## 🤝 Reach me

<p align="center">
  <a href="https://github.com/sitareashish"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://codeforces.com/profile/aallizzwell0726"><img src="https://img.shields.io/badge/Codeforces-Expert%20(1776)-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="mailto:aallizzwell0726@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <!-- Add once you have it — recruiters look for it: -->
  <!-- <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> -->
</p>

<p align="center"><i>Kharagpur, India</i></p>
