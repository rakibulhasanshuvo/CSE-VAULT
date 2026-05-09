# 🧮 Topic 9: Integration Techniques & Reduction Formulas

This topic dives into the mechanics of finding indefinite integrals. Mastery of these techniques is a vital baseline for evaluating complex physical and geometric quantities.

## 📺 Top Tutorials
*   **[Integration Techniques - Substitution and Parts](https://www.youtube.com/results?search_query=integration+by+parts+and+substitution+calculus)**
*   **[Reduction Formulas for Trigonometric Powers](https://www.youtube.com/results?search_query=reduction+formulas+integration+trigonometry)**

## 📑 Key Concepts
*   **Substitution Rule (u-substitution):** Undoes the chain rule of differentiation. Let $u = g(x)$:
    $$\int f(g(x)) g'(x) \, dx = \int f(u) \, du$$
*   **Integration by Parts (IBP):** Undoes the product rule of differentiation:
    $$\int u \, dv = uv - \int v \, du$$
    *   *Rule of thumb:* Choose $u$ according to **LIATE** (Logarithmic, Inverse Trig, Algebraic, Trigonometric, Exponential).
*   **Reduction Formulas:** Recursive algebraic formulas used to integrate higher powers of trigonometric functions:
    *   Example for $\sin^n(x)$:
        $$I_n = \int \sin^n(x) \, dx = -\frac{\sin^{n-1}(x)\cos(x)}{n} + \frac{n-1}{n} I_{n-2}$$

## 🛠️ Practice These Problems
1.  Evaluate $\int x \cos(x^2) \, dx$ using substitution.
2.  Evaluate $\int x^2 \ln(x) \, dx$ using integration by parts.
3.  Derive the reduction formula for $I_n = \int \cos^n(x) \, dx$.
4.  Use reduction formulas to solve $\int \tan^4(x) \, dx$.

---
> **💡 Pro Tip:** The "Tabular Method" is an absolute game-changer for Integration by Parts when one of the functions is a polynomial (like $x^3$) and the other is easily integrated (like $e^{2x}$). It saves you from writing nested parentheses and messing up your signs!
