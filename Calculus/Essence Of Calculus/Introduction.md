the circle approach : 

when we take a circle and we try to find its area, we see that the small concentric rings with smaller radius line up in vertical position makes almost a triangle which the area can be defined alculating its area using the standard formula gives: 

it is noted that for smaller and smaller choices of radius dr, the better the approximations we get for that area . Then area can be calculated as follows: $$\text{Area} = \frac{1}{2} \cdot \text{base} \cdot \text{height} = \frac{1}{2} \cdot R \cdot (2\pi R) = \pi R^2$$

The Pattern We See Here is : 


						Hard Problem
						     |
						     v
				  Sum of many small values
				             |
				             v
				    Area under the Graph


so many real-world problems like velocity, volume, distances can be broke down and area under graph gives solutions.

for circle we got area as $\pi R^2$, but there are many shapes that a graph can make for various problems, so lets consider a mysterious function A(x).

When you nudge $x$ by a tiny step $dx$, the change in area $dA$ is a thin rectangle of height $f(x)$ and width $dx$ : $$dA \approx f(x) \cdot dx$$ Rearranging this gives: $$\frac{dA}{dx} \approx f(x)$$
This tells us that the **derivative** (sensitivity to nudges, $\frac{dA}{dx}$) of the area function is equal to the **height of the curve** $f(x)$

Through this, we came to a conclusion that : 
  " Derivative  is a measure of how sensitive  a function is for smaller and smaller of inputs "