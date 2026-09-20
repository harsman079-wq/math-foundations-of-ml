# Project Progress Log — Math Foundations of ML

Tracking concrete, verifiable milestones only (not conversation, only working artifacts).

## Week 1 — Foundations + Setup
- [x] Hand-derived gradients for Bowl, Saddle, Rosenbrock surfaces (calculus, chain rule)
- [x] `surfaces.py` — all 3 surfaces + gradients coded, numerically verified against hand calculations
- [x] Visualization: 3-surface contour plot (bowl=circles, saddle=hyperbola, rosenbrock=curved valley)
- [x] `optimizers.py` — SGD implemented from update rule
- [x] First working trajectory: SGD on bowl, (3,4) -> (0,0), 40 steps, plotted and verified

## Week 2-3 (in progress)
- [ ] Momentum optimizer
- [ ] RMSProp optimizer
- [ ] Adam optimizer
- [ ] Run all 4 optimizers on all 3 surfaces (systematic sweep, not just bowl)
- [ ] Saddle-escape metric: steps-to-escape, averaged across multiple runs/learning rates
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
