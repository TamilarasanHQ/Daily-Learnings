---
tags: [calculus, machine-learning, math, study-notes]
aliases: [Calculus for ML]
---

# Calculus Foundations for ML

> [!info] Why this matters
> Almost every ML model is trained by adjusting parameters to minimize a loss function. Calculus — specifically derivatives and gradients — is the mathematical machinery that tells you *which direction* and *how much* to adjust them.

## 1. Single-Variable Calculus (the base layer)

- [ ] **Limits & continuity** — conceptual groundwork for derivatives; you don't need epsilon-delta proofs, just an intuitive grasp
- [ ] **Derivatives** — rate of change, slope of a tangent line. The single most important idea in ML math
- [ ] **Differentiation rules** — power, product, quotient, and especially the **chain rule**
- [ ] **Higher-order derivatives** — second derivatives → convexity checks, Hessians
- [ ] **Integrals** — less central than derivatives, but needed for probability (areas under density curves, expectation)

## 2. Multivariable Calculus

> [!note] Why
> ML models are functions of *many* parameters, so single-variable ideas need to generalize.

- [ ] **Partial derivatives** — change w.r.t. one input, holding others fixed
- [ ] **Gradients (∇f)** — vector of all partial derivatives; literally what "gradient descent" descends along
- [ ] **Jacobians** — gradients generalized to vector-valued functions
- [ ] **Hessians** — matrix of second partial derivatives; curvature, second-order optimization
- [ ] **Directional derivatives** — rate of change along an arbitrary direction
- [ ] **Multivariable chain rule** — this *is* backpropagation, mathematically

## 3. Optimization

- [ ] **Critical points** (local/global minima & maxima) — where gradient = 0
- [ ] **Convexity** — guarantees a global minimum; why some loss functions are designed to be convex
- [ ] **Gradient descent** and variants (stochastic, mini-batch, momentum, Adam)
- [ ] **Lagrange multipliers** — constrained optimization (e.g. SVMs)
- [ ] **Taylor series** — local function approximation; underlies second-order optimizers

## 4. Concept → Application Map

| Calculus concept | ML application |
|---|---|
| Derivative / gradient | Gradient descent, weight updates |
| Chain rule (multivariable) | Backpropagation in neural nets |
| Partial derivatives | Loss functions with many parameters |
| Hessian | Second-order optimizers, convergence analysis |
| Convexity | Optimization guarantees (linear/logistic regression) |
| Integrals | Expectation, probability densities, marginalization |
| Taylor series | Approximation methods, regularization theory |

## 5. Suggested Learning Order

1. Limits → derivatives → differentiation rules (single variable)
2. Chain rule mastery — unlocks backprop conceptually
3. Partial derivatives → gradients
4. Gradient descent — apply immediately to cement understanding
5. Jacobians / Hessians — for deeper optimization theory
6. Basic integral calculus — mainly for probability

> [!warning] Keep perspective
> A rough practical breakdown of ML math is often estimated as **50% probability & statistics, 35% linear algebra, 15% calculus**. Calculus is essential but not the biggest piece — study it alongside [[Linear Algebra for ML]] and [[Probability and Statistics for ML]] rather than in isolation.

---
#### Related notes
- [[Linear Algebra for ML]]
- [[Probability and Statistics for ML]]
- [[Gradient Descent]]
- [[Backpropagation]]
