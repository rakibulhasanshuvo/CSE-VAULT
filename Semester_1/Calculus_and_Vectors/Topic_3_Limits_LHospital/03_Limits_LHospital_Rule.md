# 🛑 Topic 3: Limits & L'Hospital's Rule (Week 3)

The most important topic for scoring easy marks in the mid-term.

## 📺 Top Tutorials
*   **[Limits for Beginners (One Shot)](https://www.youtube.com/results?search_query=calculus+limits+crash+course)**
*   **[L'Hospital's Rule Step-by-Step](https://www.youtube.com/results?search_query=l%27hospital+rule+examples+calculus)**
*   **[Indeterminate Forms (0/0 and ∞/∞)](https://www.youtube.com/results?search_query=indeterminate+forms+calculus+explained)**

## 📑 Key Rules
*   **Direct Substitution:** Try plugging in the value first. If you get a number, you're done!
*   **L'Hospital's Rule:** If you get `0/0` or `∞/∞`, take the derivative of the top and the derivative of the bottom separately:
    *   `lim [f(x)/g(x)] = lim [f'(x)/g'(x)]`

## 🛠️ Practice These Problems
1.  Evaluate `lim (x→2) [ (x² - 4) / (x - 2) ]`.
2.  Use L'Hospital's Rule for `lim (x→0) [ sin(x) / x ]`.
3.  Solve a limit where you have to apply L'Hospital's Rule **twice**.

---
> **💡 Pro Tip:** L'Hospital's Rule **only** works for `0/0` or `∞/∞`. If you get `5/0`, it's an asymptote (Undefined/Infinity), not a L'Hospital problem!

---

## 📖 Deep Research Study Guide

## **Topic 3: Limits, Continuity, and L'Hôpital's Rule**

### **Theoretical Framework and Rules**

The concept of a mathematical limit fundamentally resolves the asymptotic behavior of a function as it approaches an undefined singularity or infinity. Limits formalize the notion of continuity, ensuring that a function exhibits no breaks, jumps, or asymptotic disruptions. However, evaluating limits often yields indeterminate forms such as ![](../assets/image93.png) or ![](../assets/image94.png). In these scenarios, L'Hôpital's Rule provides an elegant analytical rescue, dictating that ![](../assets/image95.png).15 The profound theoretical trend here is the reduction of geometric limits to a pure comparison of independent infinitesimals. By assessing the instantaneous rates of change of the numerator against the denominator, one determines which component dominates the asymptotic expansion.16 If the oscillating frequencies of the expressions fail to stabilize, L'Hôpital's fails, necessitating alternative Taylor expansions or squeeze theorems.16

### **Foundational Problem Set**

| Problem | Theory, Formula, and Solution |
| :---- | :---- |
| **1\. Compute ![](../assets/image96.png).** 17 | **Rule:** Direct substitution yields indeterminate form ![](../assets/image97.png). **Solution:** Using L'Hôpital's Rule, derive top and bottom: ![](../assets/image98.png). |
| **2\. Compute ![](../assets/image99.png).** 17 | **Rule:** Fundamental trigonometric limit, ![](../assets/image97.png) form. **Solution:** Apply L'Hôpital's Rule: ![](../assets/image100.png). |
| **3\. Compute ![](../assets/image101.png).** 17 | **Rule:** Exponential vs. polynomial growth, ![](../assets/image102.png) form. **Solution:** Apply L'Hôpital's Rule: ![](../assets/image103.png). Since the numerator grows unbounded, the limit is ![](../assets/image104.png). |
| **4\. Compute ![](../assets/image105.png).** 18 | **Rule:** Repeated L'Hôpital for persistent ![](../assets/image97.png). **Solution:** First derivative: ![](../assets/image106.png), still ![](../assets/image97.png). Second derivative: ![](../assets/image107.png). |
| **5\. Compute ![](../assets/image108.png).** 19 | **Rule:** ![](../assets/image97.png) form requiring multiple iterations. **Solution:** First derivative: ![](../assets/image109.png) (still ![](../assets/image97.png)). Apply again: ![](../assets/image110.png). |
| **6\. Evaluate ![](../assets/image111.png).** 15 | **Rule:** Convert ![](../assets/image112.png) into a fractional indeterminate form. **Solution:** Rewrite as ![](../assets/image113.png) (Form ![](../assets/image114.png)). Apply L'Hôpital: ![](../assets/image115.png). |
| **7\. Compute ![](../assets/image116.png).** 19 | **Rule:** Convert ![](../assets/image117.png) to fraction. **Solution:** Rewrite as ![](../assets/image118.png) (![](../assets/image102.png)). Apply L'Hôpital twice: ![](../assets/image119.png). |
| **8\. Evaluate ![](../assets/image120.png).** 20 | **Rule:** ![](../assets/image102.png) form comparing logarithm and polynomial. **Solution:** Apply L'Hôpital: ![](../assets/image121.png). As ![](../assets/image122.png), the fraction approaches ![](../assets/image123.png). |
| **9\. Compute ![](../assets/image124.png).** 15 | **Rule:** ![](../assets/image97.png) form with product rule in numerator. **Solution:** L'Hôpital: ![](../assets/image125.png). |
| **10\. Compute ![](../assets/image126.png).** 15 | **Rule:** Form ![](../assets/image127.png), use natural logarithms. **Solution:** Let ![](../assets/image27.png) be the limit. ![](../assets/image128.png). L'Hôpital: ![](../assets/image129.png). Thus, ![](../assets/image130.png). |
