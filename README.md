<h1 align="center">Laith Masri</h1>

<p align="center">
  <strong>Electrical &amp; Electronic Engineering student · Cardiff University</strong><br>
  C++ · Python · numerical methods · quantitative research
</p>

<p align="center">
  <a href="https://laithmasri.dev">laithmasri.dev</a> ·
  <a href="https://lunvexlabs.com">Lunvex Labs</a> ·
  <a href="https://linkedin.com/in/laithmasri">LinkedIn</a> ·
  <a href="mailto:admin@laithmasri.dev">Email</a>
</p>

---

I am an Electrical &amp; Electronic Engineering student trying to break into
quantitative research. Most of my current work is me getting better at
probability, numerical methods, market microstructure, C++, and the less
exciting but important part: testing whether an idea actually does what I think
it does.

I also build software and websites through Lunvex Labs. On this profile I am
mainly keeping the projects where I can show the assumptions, code, tests, and
what still needs work.

## Quant projects

### [C++ Options Pricer](https://github.com/laithm/cpp-options-pricer)

I built this small C++20 pricer to compare Black-Scholes, a CRR binomial tree,
and antithetic Monte Carlo on the same contracts. The tests check textbook
prices, put-call parity, tree convergence, American exercise, Monte Carlo
standard error, and analytic Greeks against finite differences.

It is a numerical-methods project, not production pricing infrastructure.

### Available-on-Arrival Depth (private research)

This is my main market-microstructure project. I am testing whether recent
public activity on one venue helps predict how much of an initial fixed-price
depth cohort is still displayed on another venue at a later routing horizon.

The pipeline replays public L2 data, builds chronological models, keeps failed
placebos and null results visible, and has no credentials or order entry. The
current evidence is mainly deterministic synthetic research plus bounded
read-only public-feed checks. It supports conditional prediction, not a causal
or profitable-trading claim.

### Kalman Pairs Research (private)

A small two-pair ETF study using an online Kalman filter for a changing hedge
ratio. Parameters are selected on 2011-2018 data and the saved strategy is
reported on 2019-2025 data.

The candidate-list history was not recorded and the same-close execution
assumption is optimistic, so I treat the result as something to investigate,
not evidence of a market-neutral or deployable edge. The cached market data
also stays private while its provider and redistribution rights are unclear.

### [Quantitative Finance Lab](https://github.com/laithm/quant-lab)

This is an early study log, currently one Brownian-motion notebook with 1D, 2D,
3D, and multiple-path simulations. I fixed the time grid so every path starts at
zero and added a basic terminal-variance check. I will grow it as I actually
finish each topic rather than listing a whole quant curriculum in advance.

## Other work I am proud of

### [Zenbook Duo Hyprland](https://github.com/laithm/zenbook-duo-hyprland)

Linux tooling for the ASUS Zenbook Duo: dual-screen state management, USB
events, Bluetooth reconnection, face unlock, diagnostics, rollback, and Arch
packaging. This came from wanting my own hardware to work properly and having
to understand the whole path instead of one script.

### [Kidney Transplant Food Guide](https://github.com/laithm/kidney-transplant-food-guide)

An Arabic-first bilingual offline PWA with structured data validation,
accessibility checks, Vitest, Playwright, and security headers. It is a very
different problem from quant, but probably the project with the clearest human
reason for existing.

## What I am learning next

- probability, statistics, stochastic processes, and time-series modelling;
- market microstructure, execution, and how to avoid causal overclaims;
- performance-oriented C++ and numerical computing;
- low-latency and embedded systems where my engineering degree is useful.

## Tools I use

`C++` · `Python` · `TypeScript` · `JavaScript` · `Linux` · `CMake` · `NumPy` ·
`pandas` · `pytest` · `React` · `Next.js`

I would rather show the assumptions, measurements, and failed checks than call
every backtest an edge or every notebook production-ready.
