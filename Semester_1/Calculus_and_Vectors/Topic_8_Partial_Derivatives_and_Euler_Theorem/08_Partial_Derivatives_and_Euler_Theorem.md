# 🧮 Topic 8: Multivariable Calculus, Partial Derivatives & Euler's Theorem

This topic transitions from single-variable calculus to functions of multiple variables ($z = f(x,y)$), which is essential for multivariable systems, 3D graphics, and machine learning gradients.

## 📺 Top Tutorials
*   **[Introduction to Partial Derivatives](https://www.youtube.com/results?search_query=partial+derivatives+introduction)**
*   **[Euler's Theorem on Homogeneous Functions](https://www.youtube.com/results?search_query=eulers+theorem+homogeneous+functions+calculus)**

## 📑 Key Concepts
*   **Functions of Two or More Variables:** Represent surfaces in 3D space.
*   **Partial Differentiation:** Differentiating with respect to one variable while treating all other variables as constants.
    *   $\frac{\partial f}{\partial x}$ or $f_x$: Slope in the $x$-direction.
    *   $\frac{\partial f}{\partial y}$ or $f_y$: Slope in the $y$-direction.
*   **Homogeneous Function of Degree $n$:** A function $f(x,y)$ such that $f(tx, ty) = t^n f(x,y)$.
*   **Euler's Theorem:** If $u = f(x,y)$ is a homogeneous function of degree $n$, then:
    $$x \frac{\partial u}{\partial x} + y \frac{\partial u}{\partial y} = nu$$

## 🛠️ Practice These Problems
1.  Find the partial derivatives $f_x$ and $f_y$ for $f(x,y) = x^3 y^2 + \sin(xy)$.
2.  Verify Euler's Theorem for the homogeneous function $u = \frac{x^3 + y^3}{x + y}$.
3.  If $u = \tan^{-1}\left(\frac{x^3 + y^3}{x - y}\right)$, show that $x \frac{\partial u}{\partial x} + y \frac{\partial u}{\partial y} = \sin(2u)$.
4.  Compute $\frac{\partial^2 u}{\partial x \partial y}$ and $\frac{\partial^2 u}{\partial y \partial x}$ for $u = x^2 \ln(y)$ and show they are equal.

---
> **💡 Pro Tip:** To find the degree $n$ of a complicated fraction, replace $x$ and $y$ with $tx$ and $ty$. Factor out $t$ from the numerator and denominator to find the net exponent of $t$.
