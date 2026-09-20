# Project Progress Log — Math Foundations of ML

Tracking concrete, verifiable milestones only (not conversation, only working artifacts).

## Week 1 — Foundations + Setup
- [x] Hand-derived gradients for Bowl, Saddle, Rosenbrock surfaces (calculus, chain rule)
- [x] `surfaces.py` — all 3 surfaces + gradients coded, numerically verified against hand calculations
- [x] Visualization: 3-surface contour plot (bowl=circles, saddle=hyperbola, rosenbrock=curved valley)
- [x] `optimizers.py` — SGD implemented from update rule
- [x] First working trajectory: SGD on bowl, (3,4) -> (0,0), 40 steps, plotted and verified

## Week 2-3 (in progress)
- [x] Momentum optimizer implemented (velocity-based update)
- [x] RMSProp optimizer implemented (squared-gradient scaling)
- [x] Adam optimizer implemented (momentum + RMSProp combined, bias-corrected)
- [x] All 4 optimizers verified converging correctly on the bowl
- [x] All 4 optimizers compared on the saddle point — RMSProp/Adam escape fastest,
      matching literature; Momentum escapes slowest (new observation, worth reporting)
- [ ] Run systematic sweep: multiple starting points + learning rates, not just one each
- [ ] Saddle-escape metric: averaged steps-to-escape across many runs (mean ± std)
- [ ] Run all 4 optimizers on Rosenbrock surface
- [ ] Results table: optimizer x surface x learning_rate -> steps, final loss

## Week 4 (not started)
- [ ] Text corpus selection + preprocessing
- [ ] Order-1, order-2, order-3 Markov chain implementation
- [ ] Transition matrix construction

## Week 5 (not started)
- [ ] Stationary distribution computation per order
- [ ] Entropy calculation per order
- [ ] Mixing time measurement per order

## Week 6 (not started)
- [ ] Results compilation across both parts
- [ ] Comparison analysis against literature gap

## Week 7 (not started)
- [ ] Final report (IEEE format)
- [ ] Final presentation update
