# Evolving Trading Agents in Real Crypto Markets

Learning in Games · Fall 2026
Demetri Lopez & Anshul Mangalapalli

## Status

Barebones project scaffold based on the supplied proposal. **No research implementation, simulated results, trading logic, or live execution is included.** Work remains for the project team. This repository does not assign ownership or change teammates' responsibilities.

## Research question

Does evolutionary selection improve net trading performance after costs, and does the best strategy change as rival policies evolve?

## Proposed scope

- BTC-USD spot historical data and forward observation.
- Trend-following, mean-reversion and breakout policy families.
- Two active agents competing for a shared finite capital pool.
- Compare fixed agents, fixed policy mixture, selection only, and selection plus mutation.
- Measure pairwise payoffs, unilateral deviation gains, population dynamics, net return, drawdown, turnover and simulated-versus-actual fill gaps where actual fills exist.
- Cash and buy-and-hold BTC benchmarks.
- Versioned code/configuration, payoff tables and evolution curves, a 6+ page IEEE double-column report, and a short demo.

The proposal allows forward shadow trading when a capped spot pilot is unavailable. No exchange access or order execution is configured here.

## Structure

- `trading_game/`: placeholder for future implementation.
- `configs/`: placeholder for team-agreed experiment configurations.
- `data/`: placeholder for data; generated/downloaded files ignored.
- `results/`: placeholder for measured outputs; no results yet.
- `tests/`: placeholder for future tests.
- `docs/TODO.md`: proposal-derived checklist.

## Getting started

Clone the repository and agree on responsibilities, environment and experiment definitions with the team. There is no runnable experiment or dependency installation step yet. Add dependencies and setup instructions alongside the first implementation. No license has been selected.
