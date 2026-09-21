1. Combining Functions :
		3 fundamental operations
		Addition, Multiplication, Computation
	Understanding how tiny input nudges (dx) interact with these combinations and how they derive formulas 
2. Sum Rule :
		The derivative of a sum is the sum of its derivatives: $\frac{d}{dx}[f(x) + g(x)] = \frac{df}{dx} + \frac{dg}{dx}$]
		![[Pasted image 20260921204312.png]]
		-> a graph made by sum of outputs of 2 functions
		-> a tiny nudge in both functions in total height.
		-> that tells us that the total change in height is the sum of the individual changes ($df_1 + df_2$), so dividing by $dx$ gives the sum of their individual derivatives

3.  Product Rule :
		The derivative of a product is $\frac{d}{dx}[g(x) \cdot h(x)] = g(x)\frac{dh}{dx} + h(x)\frac{dg}{dx}$ ("Left $d$Right + Right $d$Left")
		![[Pasted image 20260921205014.png]]
		![[Pasted image 20260921205059.png]]
		-> consider product as area of adjustable sides of a rectangle with lengths as 2 functions that is to be multiplied.
		-> Nudging $x$ expands the box by adding **two thin rectangular strips** along the edges
		-> one of area $g \cdot dh$ and one of area $h \cdot dg$. Tiny corner is omitted as dx -> 0.
4.  The Chain Rule :
		The derivative of a composite function $g(h(x))$ is the derivative of the outer function evaluated at the inner function, multiplied by the derivative of the inner function: $\frac{d}{dx}[g(h(x))] = \frac{dg}{dh} \cdot \frac{dh}{dx}$
		![[Pasted image 20260921205717.png]]
		![[Pasted image 20260921205745.png|291]]
		![[Pasted image 20260921205816.png]]
		-> Picture **three parallel number lines** representing $x$, $h(x)$, and $g(h(x))$
		-> A tiny nudge $dx$ on line 1 causes a nudge $dh$ on line 2, which in turn causes a nudge $dg$ on line 3
		-> The overall sensitivity depends on **the product of the individual sensitivities at each step (**$\frac{dg}{dh} \cdot \frac{dh}{dx}$**), where the intermediate nudge** $dh$ **cancels out to leave the overall ratio** $\frac{dg}{dx}$.
		
		
**Image & Visual Credit:** Screenshots and visual diagrams belong to **3Blue1Brown (Grant Sanderson)** from the _Essence of Calculus_ series. Used for personal educational notes.
Link : https://youtu.be/YG15m2VwSjA