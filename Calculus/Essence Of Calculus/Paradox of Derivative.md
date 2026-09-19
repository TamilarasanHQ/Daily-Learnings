The Contradiction in "Derivative measures instantaneous change" : 
	1. Change --> happens btw 2 points in time
	2. Single instant --> has no need of change

Example we've taken : velocity/speedometer
1. we think speedometer measures velocity at that instant.
2. but it measures dist btw say, t=3sec & t=3.01sec.
3. computes, small distance/0.01sec
4. it never measures at one instant.

this drags us to a conclusion that, derivative is :

	a tiny change in the value of function/a tiny change in the input that caused it

and importantly, this derivative doesn't define correctly if the tiny nudge in input is a constant value. it is, whatever the ratio approaches, as the in change input  approaches 0.

The slope : 
 ![[Paradox of Derivative 2026-09-19 19.18.04.excalidraw]]
the two points are diff values at diff interval of time(change in time we've taken). when the dt approaches zero, the points get nearer and collide into one point. the slope of that tangent passing through the single point is the derivative of the function at that instant (t).

Best to think of Derivative as , "Best constant approximation around a point"

**How Derivative Formulas Are Derived (Example:** $s(t) = t^3$**)**

**1. Set up the change ratio**

To find the rate of change at time $t$, measure the change in distance over a tiny time step $dt$20: $$\frac{ds}{dt} = \frac{s(t + dt) - s(t)}{dt} = \frac{(t + dt)^3 - t^3}{dt}$$

**2. Expand and simplify**

Expand $(t + dt)^3$ using algebra: $$\frac{(t^3 + 3t^2 \cdot dt + 3t \cdot dt^2 + dt^3) - t^3}{dt}$$

The $t^3$ terms cancel out: $$\frac{3t^2 \cdot dt + 3t \cdot dt^2 + dt^3}{dt}$$

Divide every term by $dt$: $$3t^2 + 3t \cdot dt + dt^2$$

**3. Let** $dt \to 0$

To see what this ratio approaches as $dt$ shrinks to zero, plug in $0$ for $dt$22: $$3t^2 + 3t(0) + (0)^2 = 3t^2$$