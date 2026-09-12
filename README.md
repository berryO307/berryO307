<div align="center">

# BARINDER SINGH

### QUANT DEVELOPER · MARKETS OBSESSIVE · FULL-STACK ENGINEER

</div>

<div align="center">

```
barinder@dev:~$ whoami
berryO307

barinder@dev:~$ cat role.txt
EE grad — low-latency systems & quant research by conviction,
full-stack engineering by discipline

barinder@dev:~$ cat status.txt
B.Tech EE (Chandigarh University, 2026)
Building HFT-adjacent infra + market models, shipping full-stack
products, and reading markets for fun

barinder@dev:~$ _
```

</div>

---

## Focus Areas

**Obsessed with** market microstructure, options (vanilla & exotic barrier), regime-switching models, portfolio construction across equities/derivatives/crypto.

**Building** lock-free market-data pipelines, zero-copy IPC, sequential decision-process solvers — and shipping full production web apps end to end.

**Sharpening** C++20, low-level systems design, SQL, DSA for the engineering side of the same coin.

---

## Quant & Markets

Markets aren't a side interest — they're the reason the systems work exists. Every project below is built to answer a real trading/portfolio question, not to check a resume box.

### ⚡ C++20 Bybit Market-Data Gateway

A lock-free, low-latency market-data pipeline running against **live** exchange data.

| Capability | Implementation |
|---|---|
| Queueing | Lock-free SPSC ring buffer |
| Data path | mmap zero-copy |
| Timing | `rdtscp` cycle-accurate instrumentation |
| Measured latency | ~7.4µs p99 queue-transit across ~42K live samples |
| Data source | Live Bybit BTC perpetual futures (V5 API) |
| Analysis | Python + Plotly dashboard |
| Threading | Thread pinning |

Includes order book reconstruction, taken from skeleton to a documented p99 on live data over a multi-week debugging cycle.

### 📊 Python MDP Battery-Dispatch Optimizer

A sequential decision-making solver for energy arbitrage under a regime-switching market — dynamic programming applied to a real allocation problem.

| Capability | Implementation |
|---|---|
| Method | Bellman backward induction |
| Market model | Regime-switching |
| Result | +96% over random baseline |
| Experimental alpha | +31.71 vs. −64.46 (random) |
| Docs | Whitepaper-style README + 4 companion notes (dynamics, environment, simulator, solver) |

### Market Research Approach

Portfolio construction guided by a regime-sensitive allocation framework (Nifty P/E vs. FII flow as the decision matrix) rather than static asset weights — the same regime-aware thinking that shows up in the MDP project above, applied to my own long-horizon equity allocation across large-cap, mid-cap, and small-cap exposure.

---

## Selected Builds (Full-Stack)

### Academic Hub — University Management Dashboard

Production PERN-stack app: Home, Departments, Subjects, Classes, and Users modules with live analytics.

| Capability | Implementation |
|---|---|
| Stack | PostgreSQL (Neon) · Express · React · Node |
| UI | shadcn/ui, Refine |
| Auth | Better Auth (Google + GitHub) |
| Infra | Arcjet rate limiting, Cloudinary, Site24x7 RUM |
| Deploy | Frontend on Vercel, backend on Railway |

[Live Demo](https://ums-pern-stack.vercel.app) · [Source](https://github.com/berryO307/pern-stack-preparation)

---

## Toolkit

`C++20` · `Python` · `TypeScript` · `SQL` · `PostgreSQL` · `React` · `Node/Express` · `Docker` · `Git`

## Skill Matrix

| Domain | Skills |
|---|---|
| Quant / Markets | Market microstructure, MDPs, regime-switching models, options (vanilla & exotic barrier), portfolio construction |
| Systems | Lock-free data structures, zero-copy I/O, cycle-level timing, thread pinning |
| Full-Stack | PERN stack, REST APIs, auth, backend architecture |
| Data | SQL (in progress), Python analysis, Plotly |
| Tooling | Docker, sandboxed execution, DSA, low-level design |

---

<div align="center">

**Build → Break → Learn → Rebuild**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-berry07-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/berry07)
[![GitHub](https://img.shields.io/badge/GitHub-berryO307-181717?style=flat&logo=github&logoColor=white)](https://github.com/berryO307)

</div>
