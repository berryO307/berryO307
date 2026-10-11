<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-dark.svg?v=5">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-light.svg?v=5">
  <img alt="Barinder Singh — quant development, market systems, research, and full-stack engineering" src="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/header-light.svg?v=5">
</picture>

I work across financial markets and software: building the systems that capture and present market data, and using quantitative methods to study trading and allocation problems. I also build full-stack products, from database and API design through the interface and deployment.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/work-areas-dark.svg?v=3">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/work-areas-light.svg?v=3">
  <img alt="Animated overview of Barinder's market research and software development skills" src="https://raw.githubusercontent.com/berryO307/berryO307/main/assets/work-areas-light.svg?v=3">
</picture>

## Quant & market systems

| Project | Work | Stack | Live |
| --- | --- | --- | --- |
| [L2 Market Data Gateway](https://github.com/berryO307/quant-portfolio/tree/main/project-2-L2-market-data-gateway) | Hyperliquid L2 capture and order-book reconstruction; lock-free SPSC queue, mmap data path, pinned threads, per-stage `rdtscp` timing, and a jitter canary. | C++20, Railway, Neon, Next.js | [Open dashboard](https://l2-orderbook-gateway.vercel.app/) |
| [Microgrid MDP](https://github.com/berryO307/quant-portfolio/tree/main/project-1-microgrid-mdp) | Bellman backward induction for battery dispatch across changing market regimes. **+96.17 simulated alpha lift** over a random baseline. | Python, NumPy, Pandas | — |

The microgrid result is from a seeded simulation, not a realized market return. The gateway dashboard displays stored/replayed data; the public deployment is not a continuously running exchange capture.

## Full-stack engineering

| Project | Work | Stack | Live |
| --- | --- | --- | --- |
| [Academic Hub](https://github.com/berryO307/pern-stack-preparation) | University management platform with role-based workflows, authentication, and live analytics. | TypeScript, React, Express, PostgreSQL on Neon | [Open application](https://ums-pern-stack.vercel.app) |
| [LLD Practice Platform](https://github.com/berryO307/LLD-practice-platform) | Submit a design and get rubric-based feedback on responsibility clarity, SOLID, coupling, cohesion, and extensibility. | React 19, Express 5, PostgreSQL, Neon/Drizzle, Gemini | [Try the platform](https://solidly.vercel.app/) |
| Personal Website | Custom-designed personal site; source repository remains private. | Private source | [Visit website](https://www.barinder.dev/) |

I have also deployed Linux code to an Oracle Cloud instance. The hosting cost was too high for that setup, so running my own server is planned work and is not live yet.
