# 🧮 Topic 14: Vector Integrals & Theorems - Green, Stokes, Gauss

This topic covers path-based, area-based, and volume-based integration of vector fields, along with the fundamental boundary theorems that link them together.

## 📺 Top Tutorials
*   **[Line Integrals, Surface Integrals, and Volume Integrals Visually](https://www.youtube.com/results?search_query=line+surface+volume+integrals+multivariable+calculus)**
*   **[Green's, Stokes's, and the Divergence Theorem - Visual Mapping](https://www.youtube.com/results?search_query=greens+stokes+divergence+theorem+essentials)**

## 📑 Key Concepts
*   **Line Integral:** $\int_C \vec{F} \cdot d\vec{r}$. Accumulates work done by vector field along path $C$.
*   **Surface Integral (Flux):** $\iint_S \vec{F} \cdot d\vec{S} = \iint_S \vec{F} \cdot \hat{n} \, dS$. Measures fluid volume flowing through surface $S$.
*   **Green's Theorem in 2D Plane:** Links line integral around loop $C$ to double integral over plane area $D$:
    $$\oint_C (P \, dx + Q \, dy) = \iint_D \left( \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} \right) dx \, dy$$
*   **Stokes's Theorem in 3D Space:** Generalizes Green's Theorem to a 3D surface $S$ bounded by a closed loop curve $C$:
    $$\oint_C \vec{F} \cdot d\vec{r} = \iint_S (\nabla \times \vec{F}) \cdot d\vec{S}$$
*   **Gauss's Divergence Theorem:** Links outward surface flux through closed surface $S$ to volume expansion inside $V$:
    $$\iint_S \vec{F} \cdot d\vec{S} = \iiint_V (\nabla \cdot \vec{F}) \, dV$$

## 🛠️ Practice These Problems
1.  Evaluate the line integral $\int_C (x^2 y \, dx + xy^2 \, dy)$ where $C$ is the line segment from $(0,0)$ to $(1,1)$.
2.  Use Green's Theorem to evaluate $\oint_C (y^2 \, dx + 3xy \, dy)$ around the boundary of the semi-circle $x^2 + y^2 \leq 4, y \geq 0$.
3.  Verify the Divergence Theorem for $\vec{F} = x\hat{i} + y\hat{j} + z\hat{k}$ over the volume of the unit sphere.
4.  Use Stokes's Theorem to evaluate $\oint_C \vec{F} \cdot d\vec{r}$ where $\vec{F} = -y^3\hat{i} + x^3\hat{j} + z^3\hat{k}$ and $C$ is the circle $x^2 + y^2 = 1, z = 0$.

---
> **💡 Pro Tip:** These boundary theorems are the ultimate dimensional "shortcuts"! Instead of doing a complex, multi-sided 3D surface integral over all six faces of a cube, use Gauss's Divergence Theorem to convert it into a single, straightforward 3D volume integral!
