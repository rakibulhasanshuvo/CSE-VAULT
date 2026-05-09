# 🧮 Topic 7: Rolle's Theorem, Mean Value Theorem, and Series

This topic explores the fundamental existence theorems of calculus and the expansion of functions into infinite series.

## 📺 Top Tutorials
*   **[Rolle's & Lagrange's Mean Value Theorem Visualized](https://www.youtube.com/results?search_query=mean+value+theorem+visualization)**
*   **[Taylor Series and Maclaurin Series - 3Blue1Brown Style](https://www.youtube.com/results?search_query=taylor+series+3blue1brown)**

## 📑 Key Concepts
*   **Rolle's Theorem:** If $f(x)$ is continuous on $[a,b]$, differentiable on $(a,b)$, and $f(a) = f(b)$, then there exists at least one $c \in (a,b)$ such that:
    $$f'(c) = 0$$
*   **Mean Value Theorem (Lagrange):** Under the same continuity and differentiability conditions, there exists at least one $c \in (a,b)$ such that the instantaneous slope equals the average slope:
    $$f'(c) = \frac{f(b) - f(a)}{b - a}$$
*   **Maclaurin Series:** Approximation of a function $f(x)$ centered at $x=0$:
    $$f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \dots + \frac{f^{(n)}(0)}{n!}x^n + \dots$$
*   **Taylor Series:** General approximation centered at $x=a$:
    $$f(x) = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \dots$$

## 🛠️ Practice These Problems
1.  Verify Rolle's Theorem for $f(x) = x^2 - 4x + 3$ on the interval $[1, 3]$.
2.  Find the value of $c$ that satisfies the Mean Value Theorem for $f(x) = x^3 - x$ on $[0, 2]$.
3.  Find the Maclaurin series expansion of $e^x$, $\sin(x)$, and $\cos(x)$.
4.  Expand $f(x) = \ln(x)$ as a Taylor series centered at $x = 1$ up to the third-degree term.

---
> **💡 Pro Tip:** Think of Taylor expansions as floating-point lookup table alternatives in gaming physics or graphic shaders. GPUs use polynomial expansions internally to calculate complex functions like sine or cosine!
