# 🧮 Topic 12: Vector Operations & Vector Calculus Basics

This topic bridges vector algebra and vector calculus. It covers multi-vector multiplication, linear vector dependencies, and operations of calculus (limits, continuity, derivatives, integrals) performed on vector functions $\vec{r}(t)$.

## 📺 Top Tutorials
*   **[Vector Triple Product and Quadruple Product](https://www.youtube.com/results?search_query=scalar+triple+product+and+vector+triple+product)**
*   **[Linear Dependence and Independence of Vectors](https://www.youtube.com/results?search_query=linear+dependence+and+independence+vectors)**
*   **[Vector Calculus - Limits, Derivatives, Integrals](https://www.youtube.com/results?search_query=calculus+of+vector+valued+functions)**

## 📑 Key Concepts
*   **Scalar Triple Product:** $\vec{a} \cdot (\vec{b} \times \vec{c})$. Yields a scalar representing the volume of a parallelepiped.
    *   $\vec{a} \cdot (\vec{b} \times \vec{c}) = \begin{vmatrix} a_x & a_y & a_z \\ b_x & b_y & b_z \\ c_x & c_y & c_z \end{vmatrix}$
*   **Vector Triple Product:** $\vec{a} \times (\vec{b} \times \vec{c}) = (\vec{a} \cdot \vec{c})\vec{b} - (\vec{a} \cdot \vec{b})\vec{c}$ *(BAC-CAB rule)*.
*   **Linear Independence:** A set of vectors is independent if $c_1 \vec{v}_1 + c_2 \vec{v}_2 + c_3 \vec{v}_3 = \vec{0}$ forces $c_1 = c_2 = c_3 = 0$. Otherwise, they are linearly dependent (coplanar in 3D).
*   **Vector Differentiation:** Derivative of a space curve vector $\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j} + z(t)\hat{k}$:
    $$\frac{d\vec{r}}{dt} = \frac{dx}{dt}\hat{i} + \frac{dy}{dt}\hat{j} + \frac{dz}{dt}\hat{k}$$
    *   *Application:* Velocity $\vec{v}(t) = \vec{r}'(t)$, acceleration $\vec{a}(t) = \vec{r}''(t)$.

## 🛠️ Practice These Problems
1.  Verify the vector triple product expansion for $\vec{a} = \hat{i} - 2\hat{j} + \hat{k}$, $\vec{b} = 2\hat{i} + \hat{k}$, and $\vec{c} = \hat{j} - \hat{k}$.
2.  Determine if the vectors $\vec{u} = (1, 2, 1)$, $\vec{v} = (2, 9, 0)$, and $\vec{w} = (3, 3, 4)$ are linearly independent.
3.  A particle moves along the path $\vec{r}(t) = t^2\hat{i} + 2t\hat{j} + \ln(t)\hat{k}$. Find its velocity, speed, and acceleration at $t=1$.
4.  Evaluate the vector integral $\int_0^1 \left( 3t^2 \hat{i} + e^t \hat{j} + \sin(\pi t)\hat{k} \right) \, dt$.

---
> **💡 Pro Tip:** Remember the "BAC-CAB" mnemonic for the vector triple product: $\vec{a} \times (\vec{b} \times \vec{c}) = \vec{b}(\vec{a}\cdot\vec{c}) - \vec{c}(\vec{a}\cdot\vec{b})$. This expansion identity turns cross products into simple scalar dot product scaling operations!
