# 🧮 Topic 10: Definite Integrals & Beta-Gamma Functions

This topic explores definite integrals, their mathematical properties, and advanced special functions used to solve integrals that cannot be expressed in terms of elementary functions.

## 📺 Top Tutorials
*   **[Definite Integrals - Properties and Tricks](https://www.youtube.com/results?search_query=properties+of+definite+integrals)**
*   **[Beta and Gamma Functions Explained Simply](https://www.youtube.com/results?search_query=beta+and+gamma+functions+calculus)**

## 📑 Key Concepts
*   **Fundamental Theorem of Calculus (FTC):**
    $$\int_a^b f(x) \, dx = F(b) - F(a) \quad \text{where } F'(x) = f(x)$$
*   **Symmetry & Properties:**
    *   $\int_a^b f(x) \, dx = -\int_b^a f(x) \, dx$
    *   If $f(x)$ is odd ($f(-x) = -f(x)$): $\int_{-a}^a f(x) \, dx = 0$
    *   If $f(x)$ is even ($f(-x) = f(x)$): $\int_{-a}^a f(x) \, dx = 2\int_0^a f(x) \, dx$
*   **Gamma Function $\Gamma(n)$:** Generalization of factorial to real/complex numbers:
    $$\Gamma(n) = \int_0^\infty e^{-x} x^{n-1} \, dx \quad (n > 0)$$
    *   *Properties:* $\Gamma(n+1) = n\Gamma(n)$, $\Gamma(n+1) = n!$ (for integer $n$), and $\Gamma(1/2) = \sqrt{\pi}$.
*   **Beta Function $B(m, n)$:**
    $$B(m, n) = \int_0^1 x^{m-1}(1-x)^{n-1} \, dx = \frac{\Gamma(m)\Gamma(n)}{\Gamma(m+n)}$$

## 🛠️ Practice These Problems
1.  Evaluate $\int_{-2}^2 (x^5 + 3x^2) \, dx$ using definite integral properties.
2.  Evaluate $\int_0^{\pi/2} \sin^6(x) \cos^4(x) \, dx$ using Beta and Gamma functions.
3.  Compute $\Gamma(5)$ and $\Gamma(7/2)$ using continuous factorial properties.
4.  Prove that $B(m, n) = B(n, m)$ (symmetry property).

---
> **💡 Pro Tip:** Trigonometric integrals on the interval $[0, \pi/2]$ of the form $\int_0^{\pi/2} \sin^p(x) \cos^q(x) \, dx$ can be solved instantly in one line using Beta/Gamma substitution:
> $$\int_0^{\pi/2} \sin^p(x) \cos^q(x) \, dx = \frac{1}{2} B\left(\frac{p+1}{2}, \frac{q+1}{2}\right)$$
