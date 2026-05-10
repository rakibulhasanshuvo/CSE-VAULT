# ⛰️ Topic 5: Optimization & Max/Min (Week 5)

The "final boss" of Calculus I. Turning word problems into equations.

## 📺 Top Tutorials
*   **[Finding Critical Points & Extrema](https://www.youtube.com/results?search_query=local+max+and+min+calculus+tutorial)**
*   **[Optimization Word Problems (Step-by-Step)](https://www.youtube.com/results?search_query=calculus+optimization+word+problems+tutorial)**
*   **[The Second Derivative Test](https://www.youtube.com/results?search_query=second+derivative+test+max+min)**

## 📑 Key Steps
1.  **Objective Equation:** Write what you want to maximize (e.g., `Area = L * W`).
2.  **Constraint Equation:** Write what you are "stuck" with (e.g., `Perimeter = 2L + 2W = 100`).
3.  **Substitute:** Get the Objective equation down to **one** variable.
4.  **Differentiate & Solve:** Set `f'(x) = 0` to find the critical points.

## 🛠️ Practice These Problems
1.  Find the two numbers whose sum is 20 and whose product is a maximum.
2.  Find the dimensions of a rectangle with area 100 m² that has the minimum perimeter.
3.  Use the Second Derivative Test to prove a point is a local maximum.

---
> **💡 Pro Tip:** If your derivative comes out to something impossible (like a negative length), check your **Constraint Equation** setup. Most mistakes happen in the setup, not the calculus!

---

## 📖 Deep Research Study Guide

## **Topic 5: Critical Points, Optimization, and Min/Max**

### **Theoretical Framework and Rules**

Optimization lies at the core of applied mathematics. Fermat's theorem formally dictates that the local extrema of a continuously differentiable function necessarily occur at locations where the first derivative vanishes (![](../assets/image170.png)) or becomes undefined, strictly categorizing these locales as critical points.24 Optimization protocols require isolating these critical boundaries and evaluating them against the second derivative ![](../assets/image171.png) (using the Hessian matrix in higher dimensions) or the extreme boundaries of a constrained interval to formally categorize them as local minima, maxima, or saddle points.24 The broader physical implication of this mathematics is that nature inherently optimizes parameters (e.g., the principle of least action in thermodynamics, or path minimization in optics); thus, computing critical points unveils the energetic equilibrium states within dynamic, multi-variable systems.26

### **Foundational Problem Set**

| Problem | Theory, Formula, and Solution |
| :---- | :---- |
| **1\. Maximize area of an open-top box given material constraint.** 27 | **Rule:** Optimize boundary constraint equations. **Solution:** Formulate surface area constraint ![](../assets/image172.png). Maximize over $$. ![](../assets/image173.png). Max area yields ![](../assets/image174.png). |
| **2\. Maximize ![](../assets/image175.png) given ![](../assets/image176.png) add to 100 and their product is maximal.** 25 | **Rule:** Multi-variable constrained optimization. **Solution:** Objective: Maximize ![](../assets/image177.png). Critical point calculated at ![](../assets/image178.png). Thus ![](../assets/image179.png). |
| **3\. Categorize the critical point ![](../assets/image180.png) from Problem 2\.** 25 | **Rule:** Second derivative (Hessian) test. **Solution:** Using the determinant ![](../assets/image181.png) and ![](../assets/image182.png), the point is rigorously confirmed as a local maximum. |
| **4\. Categorize the critical point ![](../assets/image183.png) for ![](../assets/image177.png).** 25 | **Rule:** Saddle point identification. **Solution:** ![](../assets/image184.png). The negative determinant indicates a saddle point. |
| **5\. Minimize the sum of two numbers if their product is fixed at ![](../assets/image185.png).** 26 | **Rule:** Constraint substitution. **Solution:** ![](../assets/image186.png), Sum ![](../assets/image187.png). ![](../assets/image188.png), leading to ![](../assets/image139.png). The numbers must be equal. |
| **6\. Maximize area of a rectangle with a given perimeter ![](../assets/image185.png).** 26 | **Rule:** Maximize area ![](../assets/image189.png). **Solution:** ![](../assets/image190.png). ![](../assets/image191.png). The shape is formally a square. |
| **7\. Find critical points of ![](../assets/image192.png).** 24 | **Rule:** Set first derivative to zero. **Solution:** ![](../assets/image193.png). |
| **8\. Classify the extrema of ![](../assets/image192.png).** 24 | **Rule:** Second derivative concavity test. **Solution:** ![](../assets/image194.png). At ![](../assets/image139.png), ![](../assets/image195.png) (Minimum). At ![](../assets/image196.png), ![](../assets/image197.png) (Maximum). |
| **9\. Find critical points for pipe corner length optimization.** 28 | **Rule:** Minimize trigonometric hypotenuse functions. **Solution:** Setting the derivative ![](../assets/image198.png) yields critical points through trigonometry, resulting in solutions equivalent to ![](../assets/image199.png). |
| **10\. Maximize area of a rectangle divided into 4 pens with fencing ![](../assets/image200.png).** 26 | **Rule:** Maximize under segmented constraint. **Solution:** ![](../assets/image201.png). Maximize ![](../assets/image189.png). Substitute ![](../assets/image202.png): ![](../assets/image203.png). ![](../assets/image204.png) gives optimal dimensions for compartmentalized geometry. |
