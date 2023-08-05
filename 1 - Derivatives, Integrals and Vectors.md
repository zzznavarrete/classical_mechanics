
It is essential to have knowledge of Derivatives, Integrals and vectors before digging in classical mechanics. In continuation, we're going to revisit this topics.

## Derivatives

The idea of derivatives comes from a linear function. Essentially, a linear function has a linear dependence of the function and the argument (commonly called *x*).  So we have a term with a constant number *m* (slope of the linear function); times the argument *(x)* plus a constant *(n)*. 

**General linear function**
![[Pasted image 20230805183803.png]]

And so you can write down a linear function that connects any two dots in a coordinate system into any non-linear function, the line that connects the two points it's called the *secant line.*
**Secant line**
![[Pasted image 20230805183623.png]]

We could also calculate the slope of the drawed secant line, the *m* constant of the general linear function equation. 
![[Pasted image 20230805183838.png]]
The function value, at be evaluation as deltas, means that it changes according of the dependent and independent points which we're evaluating.


Another way of calculating this is including the change of the position of the two points, named *'h'*.
![[Pasted image 20230805184017.png]]
![[Pasted image 20230805184030.png]]

If we took the second point and gradually shift it into the first point, until they share essentially the same position, we convert the *secant line* into a *tangent line*.

> A tangent line is a straight line that touches a curve at a single point, representing the slope of the curve at that specific point. On the other hand, a secant line is a straight line that intersects a curve at two points, allowing us to calculate the average rate of change between these two points.
> 	- [ChatGPT (openai.com)](https://chat.openai.com/)

![[Pasted image 20230805184242.png]]

We can calculate the slope of the tangent line but pushing the right point into the left point by calculating the limit of *h* (distance between the two points) going to 0.
![[Pasted image 20230805184338.png]]

**The slope of the tangent line is the derivative**.
With the derivative we now how does a function changes at a certain point. The slope of the tangent line.

*(alternative but equivalente definition):*
![[Pasted image 20230805184418.png]]

Now, how else does this derivative manifests in the graph? it can also describe the angle of the tangent line forms with the x axis, this is also some times interesting. 


### Example

So we have this blue function that we have had in the previous figure as well, this is the third order polynomial and we can now repeat this discussion to calculate the derivative at every individual point here.
![[Pasted image 20230805184617.png]]\

If we plot the derivative of the function as well (red series), we see that we got a quadratic function, this is because, the slope (or rate of change) of the original third order degree function gradually starts to decrease until reach zero rate of change (first 0 at almost -2 in x axis), then, the function slopes start decreasing as we gradually start moving to the right side and eventually reach zero again (almost in 0 value x-axis), to finally, start increasing again, and that's the behavior of a quadratic function.

> In general, when you take the derivative of a polynomial function, the degree of the resulting polynomial decreases by one. So, a fourth-degree polynomial (quartic) will have a third-degree derivative (cubic).
> 	- [Tangent vs. Secant Lines (openai.com)](https://chat.openai.com/)


### Another example
Let's see how we could do a step by step derivative calculation if we have a Quadratic function defined by the equation:
$$ f(x) = \frac{1}{2}x^{2}+x-2 $$
(blue series)

And the derivative is the red line, defined by the equation:
$$f'(x)=x+1$$

![[Pasted image 20230805185740.png]]
But why is this the case?

How can we figure this out?

Well, let's first discuss the function x squared and then calculate the derivative.

$$f(x)=x^2$$
Following basic algebra steps, we reach into:
$$
f'(x) = \lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}
$$
$$
f'(x) = \lim_{h\rightarrow0}\frac{(x+h)^2-x^2}{h}
$$
$$
f'(x) = \lim_{h\rightarrow0}\frac{x^2+2xh+h^2-x^2}{h}
$$
$$
f'(x) = \lim_{h\rightarrow0}\frac{2xh+h^2}{h}
$$
$$
f'(x) = \lim_{h\rightarrow0}(2x+h)
$$
Evaluating at zero we got...
$$f'(x) = 2x$$

And now, we could evaluate the original function, replacing the value for the derivative's value when correspond.
$$
f(x) = \frac{1}{2}x^2+x-2
$$
then...
$$
f'(x) = \frac{1}{2}2x+1
$$
*(the linear x it is converted into 1 because of the derivative of a linear function is 1)*
*(the constant -2 disappears because the derivative of a constant is zero )*

Finally after simplification we got the function's derivative:
$$
f'(x) = x + 1
$$


### Important derivatives rules
![[Pasted image 20230805192417.png]]

![[Pasted image 20230805192538.png]]


