---
source: https://youtu.be/m2MIpDrF7Es
---

# The Number e & Exponential Derivatives

> [!info] Source
> Notes on 3Blue1Brown’s exploration of the number $e$ and exponential derivatives.

## 1. The Setup: Exponential Growth and Derivatives

> [!note] The Core Function
> Starting with exponential growth like $f(x) = 2^x = y$ (representing population or mass over time $t$).

> [!note] The Derivative
> The derivative $\frac{dM}{dt}$ represents the rate at which population or mass grows for a tiny change in time ($dt$).

> [!warning] The Initial Temptation
> Looking at a chunk of time (e.g., from day 3 to day 4, where 8 creatures grow in 1 day), it looks like the rate of growth equals the population size at the start of the day.

> [!danger] The Catch
> It is “not quite right!”

## 2. Zooming In: Proportional, Not Equal

> [!important] When evaluating infinitesimal time steps
> When evaluating infinitesimal time steps ($dt \to 0$, e.g., $dt = 0.00000001$), the math reveals a scaling factor:
> $$
> \frac{2^{dt} - 1}{dt} \approx 0.6931\ldots
> $$

> [!quote] The Crucial Insight
> For smaller time steps, “the derivative is not itself, it is proportional to itself”.

> [!example] Different bases yield different constants
> Different bases yield different constants (e.g., for $3^t$, the multiplier is $1.0986\ldots$).
> $$
> \frac{d}{dt}3^t = 1.0986\ldots \cdot 3^t
> $$

## 3. The Breakthrough Question

> [!question] The Big Mystery
> “Why these constants? What does $0.6931$ have to do with $2$?”

> [!question] The Quest
> “Is there a base where that constant is $1$?”

## 4. Enter Euler’s Number (e)

> [!success] The Answer
> Yes! $e = 2.71828\ldots$

> [!important] Testing it with micro-limits
> Testing it with micro-limits shows the ratio collapses neatly to $1$:
> $$
> \lim_{dt \to 0}\frac{e^{dt} - 1}{dt} = 1
> $$

> [!success] This makes its derivative uniquely clean
> $$
> \frac{d}{dt}e^t = e^t
> $$

## 5. The Grand Analogy & Conclusion

> [!quote] The Philosophical Parallel
> “Why $e$ of all numbers have this property? Similar to asking: why $\pi$ of all nos happen to be ratio of circumference of a circle & its diameter.”

> [!summary] Final Master Summary
> - All exponential functions are proportional to their own derivative.
> - But $e$ alone is a special number so that proportionality constant is $1$, which means it equals to its own derivative.

---