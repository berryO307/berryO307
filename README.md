<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-light.svg">
  <img alt="Barinder Singh — low-latency market data systems and quant research" src="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-light.svg">
</picture>

EE Grad | Risk Taker | Ever Learner<br>
Quant Researcher & Developer | Full-Stack Developer

## Markets and quant

Every project here starts from a trading or allocation question, not from a framework I wanted to try.

### C++20 Bybit market-data gateway

A lock-free, low-latency market-data pipeline running against live exchange data.

| | |
|---|---|
| Queueing | Lock-free SPSC ring buffer |
| Data path | mmap zero-copy |
| Timing | `rdtscp` cycle-accurate instrumentation |
| Measured latency | 7.4µs p99 queue transit across 42K live samples |
| Feed | Bybit BTC perpetual futures, V5 API |
| Threading | Pinned threads |
| Analysis | Python and Plotly |

Includes order book reconstruction. Taken from skeleton to a documented p99 on live data over a multi-week debugging cycle: V5 migration, the SPSC buffer, the mmap writer, then the measurement layer.

### Python MDP battery-dispatch optimizer

Dynamic programming applied to energy arbitrage under a regime-switching market.

| | |
|---|---|
| Method | Bellman backward induction |
| Market model | Regime-switching |
| Result | 96% improvement over random baseline |
| Alpha | +31.71 against -64.46 random |
| Documentation | Whitepaper-style README plus companion notes on dynamics, environment, simulator, and solver |

### Interests

Exotic Derivatives | Options | Futures | Algorithmic Trading

## Engineering

### Academic Hub

A production university management platform: departments, subjects, classes, users, and live analytics.

| | |
|---|---|
| Stack | PostgreSQL on Neon, Express, React, Node |
| Interface | shadcn/ui with Refine |
| Auth | Better Auth, Google and GitHub |
| Infrastructure | Arcjet rate limiting, Cloudinary, Site24x7 RUM |
| Deployment | Vercel frontend, Railway backend |

[Source](https://github.com/berryO307/pern-stack-preparation)

## What I work with

| Systems | C++20, lock-free structures, zero-copy I/O, cycle-level timing, POSIX syscalls |
|---|---|
| Quant | Market microstructure, MDPs, regime-switching models, options |
| Backend | Node, Express, REST APIs, authentication, PostgreSQL |
| Frontend | React, TypeScript |
| Tooling | Docker, Git, Linux |

Currently sharpening SQL, low-level design, and data structures for the engineering track.

## Elsewhere

Leaving GitHub from here — [Academic Hub, live](https://ums-pern-stack.vercel.app) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/berry07) &nbsp;·&nbsp; [Email](mailto:barindersinghdhanoa@gmail.com)
