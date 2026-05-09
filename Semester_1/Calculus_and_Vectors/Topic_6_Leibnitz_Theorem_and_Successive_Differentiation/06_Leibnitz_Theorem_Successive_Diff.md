# 🧮 Topic 6: Successive Differentiation & Leibnitz's Theorem

This topic extends basic differentiation to higher orders. It is essential for understanding series expansions and analyzing the local curvature of functions.

## 📺 Top Tutorials
*   **[Successive Differentiation - Step-by-Step](https://www.youtube.com/results?search_query=successive+differentiation+calculus)**
*   **[Leibnitz's Theorem Proof and Applications](https://www.youtube.com/results?search_query=leibnitz+theorem+differentiation+problems)**

## 📑 Key Concepts
*   **Successive Differentiation:** Finding the $n$-th derivative of a function (denoted $y_n$ or $\frac{d^n y}{dx^n}$).
*   **Leibnitz's Theorem:** Used to find the $n$-th derivative of a product of two functions, $u$ and $v$:
    $$(uv)_n = u_n v + \binom{n}{1} u_{n-1} v_1 + \binom{n}{2} u_{n-2} v_2 + \dots + \binom{n}{r} u_{n-r} v_r + \dots + u v_n$$
    *   *Analogy:* It is the calculus equivalent of the Binomial Theorem expansion.
*   **Tangent and Normal:**
    *   *Tangent slope:* $m = \left.\frac{dy}{dx}\right|_{(x_0, y_0)}$
    *   *Normal slope:* $m' = -\frac{1}{m}$

## 🛠️ Practice These Problems
1.  Find the $n$-th derivative of $y = e^{ax} \sin(bx + c)$.
2.  If $y = (d + cx)^{-1}$, prove that $y_n = (-1)^n n! c^n (d + cx)^{-(n+1)}$.
3.  Use Leibnitz's Theorem to find the $n$-th derivative of $y = x^2 e^{3x}$.
4.  Find the equations of the tangent and normal to the curve $y = x^3 - 2x^2 + 4$ at the point $(2, 4)$.

---
> **💡 Pro Tip:** When using Leibnitz's Theorem, always choose the polynomial term as $v$ because its derivatives will eventually become zero, terminating the expansion and saving you a massive amount of algebra!
