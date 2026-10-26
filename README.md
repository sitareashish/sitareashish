<h1 align="center">Hi, I'm Ashish 👋</h1>

<p align="center">
  <a href="https://github.com/sitareashish">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=Systems+engineer+%C2%B7+low-latency+C%2B%2B;Databases%2C+VMs+and+matching+engines+from+scratch;Multi-agent+AI+systems+%7C+LangGraph+%2B+RAG;Competitive+programmer+%7C+Codeforces+%26+LeetCode" alt="typing banner" />
  </a>
</p>

<p align="center">
  <b>Dual-Degree CSE @ IIT Kharagpur</b> &nbsp;·&nbsp; Kharagpur, India
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sitareashish&style=flat-square&color=58a6ff&label=Profile+views" alt="profile views" />
</p>

---

I build systems close to the metal — **matching engines, storage engines, bytecode VMs, network servers** — and I apply that same low-latency, reliability-first toolkit to **AI and agent infrastructure**: the layer that decides whether agentic systems are fast, correct and cheap in production.

- 🤖 **Agent systems** — multi-agent orchestration (LangGraph), hybrid RAG, sandboxed tool-use, evals & tracing
- ⚙️ **Systems & low-latency C++** — lock-free data structures, `epoll`, custom allocators, share-nothing workers
- 🗄️ **Databases from scratch** — B+ Tree indexes, WAL/ARIES recovery, MVCC snapshot isolation
- 🏆 **Competitive programming** — Codeforces & LeetCode

---

## 🤖 AI & agent systems

The hard part of agentic AI in production isn't the prompt — it's the runtime: grounded retrieval, isolated tool execution, self-correction, cost control, and observability. That's what I build.

| Project | What it is |
|---|---|
| [**my_ai_issue_resolver**](https://github.com/sitareashish/my_ai_issue_resolver) | Autonomous **multi-agent** pipeline (LangGraph FSM) that turns a GitHub issue into a reviewed PR — context → developer → tester → reviewer agents with confidence-gated re-querying, a **Docker test sandbox**, a self-correcting retry loop, per-issue **token budgeting**, **Qdrant hybrid RAG** (dense + BM25, AST chunking), plus LangSmith/Prometheus tracing and an **evals harness** |

> 🔭 **Currently building:** an invisible macOS menu-bar AI assistant driven by the Claude agent bridge, and bringing agent-style tool-use into my systems projects.

## 🛠️ Systems & performance

| Project | What it is |
|---|---|
| [**femto**](https://github.com/sitareashish/femto) | Nanosecond-class limit order book & matching engine in C++20, differential-fuzzed against a Python reference |
| [**mini-sql-engine**](https://github.com/sitareashish/mini-sql-engine) | From-scratch SQL execution engine — buffer-pooled B+ Tree indexes, Volcano-model iterators, ARIES WAL, MVCC snapshot isolation |
| [**ember**](https://github.com/sitareashish/ember) | A small bytecode-compiled language: lexer, Pratt parser, stack VM with closures, tri-color mark-sweep GC |
| [**htn**](https://github.com/sitareashish/htn) · [**htn-server**](https://github.com/sitareashish/htn-server) | High-throughput epoll TCP servers in C/C++ — share-nothing workers, lock-free SPSC rings, Prometheus/Grafana. **~46K RPS at p99 < 2ms** |
| [**Stat_Arb**](https://github.com/sitareashish/Stat_Arb) | C++17 pairs-trading backtester — lock-free ingestion, Kalman-filter hedge ratio, volatility-regime detection |
| [**EcoRoute**](https://github.com/sitareashish/EcoRoute) | High-throughput C++ routing engine optimizing graph traversal for carbon emissions and AQI exposure |

---

## 🧰 Stack

![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

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
  <!-- Add these once you have them — they matter a lot for recruiters: -->
  <!-- <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> -->
  <!-- <a href="https://codeforces.com/profile/YOUR-HANDLE"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a> -->
  <!-- <a href="https://leetcode.com/YOUR-HANDLE"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a> -->
  <!-- <a href="mailto:sitareashish26@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a> -->
</p>

<p align="center"><i>Kharagpur, India</i></p>
