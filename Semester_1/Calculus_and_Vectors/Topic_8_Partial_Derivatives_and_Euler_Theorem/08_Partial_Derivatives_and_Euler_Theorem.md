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

---

## 📖 Deep Research Study Guide

## **Topic 8: Partial Derivatives, Homogeneous Functions, and Euler's Theorem**

### **Theoretical Framework and Rules**

In multivariate calculus, analyzing how functions scale across dimensions is critical. A function ![](../assets/image284.png) is strictly defined as homogeneous of degree ![](../assets/image285.png) if multiplying all inputs by a scalar ![](../assets/image45.png) scales the output by ![](../assets/image286.png): ![](../assets/image287.png).34 Euler's Theorem for Homogeneous Functions brilliantly demonstrates that this macroscopic structural scale invariance is intimately encoded within its localized partial derivatives via the formula ![](../assets/image288.png).34 A second-order consequence (Corollary 1\) proves mathematically that each resulting partial derivative is itself a homogeneous function, reduced to degree ![](../assets/image289.png).34 In macroeconomic theories (e.g., Cobb-Douglas production limits) and thermodynamic state equations, this exact invariance dictates whether physical parameters operate as intensive (degree 0, independent of scale like temperature) or extensive (degree 1, dependent on scale like total mass) properties.34

### **Foundational Problem Set**

| Problem | Theory, Formula, and Solution |
| :---- | :---- |
| **1\. Show ![](../assets/image290.png) is homogeneous of degree 0\.** 34 | **Rule:** Check ![](../assets/image291.png). **Solution:** ![](../assets/image292.png). Degree is 0\. |
| **2\. Prove Euler's theorem for ![](../assets/image293.png).** 35 | **Rule:** Verify ![](../assets/image294.png). **Solution:** ![](../assets/image159.png) is degree 3\. ![](../assets/image295.png). Thus, ![](../assets/image296.png). |
| **3\. Minimize ![](../assets/image297.png) subject to ![](../assets/image298.png).** 34 | **Rule:** Euler-Lagrange shortcut for degree 2 functions. **Solution:** ![](../assets/image299.png). Minimum value is exactly ![](../assets/image300.png). |
| **4\. Maximize ![](../assets/image301.png) subject to ![](../assets/image302.png).** 34 | **Rule:** Lagrange multipliers on degree 1 function. **Solution:** Function is degree 1\. Euler shortcut yields optimum parameters: ![](../assets/image303.png) and ![](../assets/image304.png). |
| **5\. Find ![](../assets/image305.png) where ![](../assets/image306.png).** 34 | **Rule:** Chain rule application for homogeneity proof. **Solution:** Applying the multivariate chain rule: ![](../assets/image307.png). |
| **6\. If ![](../assets/image308.png), show ![](../assets/image309.png).** 35 | **Rule:** Use exponential mapping ![](../assets/image310.png). **Solution:** Let ![](../assets/image311.png). ![](../assets/image312.png) is degree 3\. Euler gives ![](../assets/image313.png). Since ![](../assets/image314.png), dividing by ![](../assets/image167.png) yields 3\. |
| **7\. Prove constant elasticity function ![](../assets/image315.png) is degree 1\.** 34 | **Rule:** Insert scalar ![](../assets/image45.png). **Solution:** ![](../assets/image316.png). Degree is definitively 1\. |
| **8\. What is the degree of homogeneity for ![](../assets/image317.png) if ![](../assets/image312.png) is degree ![](../assets/image285.png)?** 34 | **Rule:** Corollary of Euler's theorem. **Solution:** Differentiating the scalar function reduces the exponent degree mathematically to ![](../assets/image289.png). |
| **9\. Deduce ![](../assets/image318.png).** 34 | **Rule:** Second-order Euler expansion. **Solution:** Differentiating Euler's first-order equation ![](../assets/image319.png) partially with respect to ![](../assets/image22.png) and ![](../assets/image27.png) and multiplying cross terms yields this identity. |
| **10\. If ![](../assets/image320.png), find ![](../assets/image321.png).** 35 | **Rule:** Sine mapping ![](../assets/image322.png). **Solution:** Let ![](../assets/image323.png). Degree is 1\. Euler: ![](../assets/image313.png). Thus, ![](../assets/image324.png). |
