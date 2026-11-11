# Project checklist

All items are unimplemented. Ownership remains with the team's existing arrangements; the proposal does not define an implementation ownership map.

- [ ] Agree on environment, dependencies and repository workflow.
- [ ] Define chronological train/validation/test periods and data provenance.
- [ ] Add BTC-USD market-data pipeline and baseline policy families.
- [ ] Specify shared-capital allocator, costs, accounting and limits.
- [ ] Implement pairwise payoff experiments and deviation-gain metrics.
- [ ] Add the four conditions: fixed agents, fixed mixture, selection only, selection + mutation.
- [ ] Evaluate new variants before admission.
- [ ] Measure net returns, drawdown and turnover against cash/buy-and-hold.
- [ ] Track population shares and best responses over time.
- [ ] Add tests and reproducibility checks with the implementation.
- [ ] Collect forward shadow observations; evaluate pilot feasibility separately.
- [ ] Compare simulated and actual fills only if actual fills are available.
- [ ] Produce payoff tables, evolution curves, IEEE report and demo.

## Proposal milestones

Week 1: exchange feed and baselines. Week 2: allocator and payoff experiments. Weeks 3–4: selection, mutation and forward trials. Week 5: capped spot pilot if feasible. Final: analysis, report and demo.

These are relative milestones, not calendar deadlines. Capital limits, cadence, cost settings, mutation rules and safety controls remain team decisions; none are invented here.
