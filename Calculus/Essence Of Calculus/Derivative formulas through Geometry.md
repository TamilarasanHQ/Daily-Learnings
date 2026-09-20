Core Derivative Philosophy : 
How a output of the function changes to smallest inputs. ( How sensitive is the function).

Finding the derivative of a function like $x^2$  might be easy by finding slope of tangent. But we need derivatives of more and more complex trigonometric , Logarithmic, polynomial, exponential functions in real world applications.
 
**The Power Rule via Geometry**

- $x^2$ **(Area of a Square)**:

    - A square with side length $x$ has an area of $x^2$.
    - Nudging $x$ by a tiny step $dx$ adds **two thin rectangular bars** (each with area $x \cdot dx$) and one tiny corner square (area $dx^2$).
    - The tiny corner $dx^2$ is negligibly small and dropped.
    - Dividing the main new area ($2x \cdot dx$) by $dx$ gives the derivative: $\frac{d}{dx}(x^2) = 2x$.
- $x^3$ **(Volume of a Cube)**:
- ![Derivative of x²](x3-geometry.png)
    - A cube with side length $x$ has a volume of $x^3$.
    - Nudging $x$ by $dx$ adds **three thin square faces** (each with volume $x^2 \cdot dx$) plus tiny edge and corner slivers.
    - Ignoring the higher-order $dx$ slivers leaves $3x^2 \cdot dx$, giving the derivative: $\frac{d}{dx}(x^3) = 3x^2$.
- **General Power Rule (**$x^n$**)**:
    - Expanding $(x + dx)^n$ yields $x^n$ plus $n$ **dominant terms** of size $x^{n-1} \cdot dx$. All other terms contain $dx^2$ or higher powers and drop out as $dx \to 0$.
    - This geometrically proves the general formula: $\frac{d}{dx}(x^n) = n x^{n-1}$
    

**Trigonometric Derivatives (**$\sin\theta$**)**
![sin x derivative|322](sinx1.png)![sin x derivative|390](sinx3.png)
![sin x derivative|234](sinx4.png)
![sin x derivative|383](sinx5.png)

- On a **unit circle** (radius 1), traversing an arc length $\theta$ places you at a height of $\sin\theta$.
- Taking a tiny step $d\theta$ along the circle forms a tiny right triangle where the hypotenuse is $d\theta$ and the vertical height change is $d(\sin\theta)$.
- Zooming in, this tiny triangle is similar to the main angle triangle, making the ratio of height change to step size: $$\frac{d(\sin\theta)}{d\theta} = \frac{\text{adjacent}}{\text{hypotenuse}} = \cos\theta$$ Therefore, $\frac{d}{d\theta}(\sin\theta) = \cos\theta$