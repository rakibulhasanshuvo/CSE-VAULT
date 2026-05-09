# Calculus & Vectors: Comprehensive Master Revision Notes

---

## 🧮 Topic 1: Functions, Domain & Range (Week 1)

### Key Concepts
*   **Domain:** The set of all input values ($x$) for which the function is mathematically defined.
*   **Range:** The set of all resulting output values ($y$) after applying the domain inputs.
*   **Indeterminate/Undefined Rules:**
    *   Fractions: Denominator cannot equal zero.
    *   Square Roots: Values inside $\sqrt{x}$ must be $\geq 0$. If in a denominator, strictly $> 0$.

### High-Yield Formulas
*   Linear: $y = mx + c \implies$ Domain: $\mathbb{R}$, Range: $\mathbb{R}$.
*   Quadratic: $y = ax^2 + bx + c \implies$ Domain: $\mathbb{R}$, Range depends on the vertex coordinates: $[-\frac{D}{4a}, \infty)$ if $a > 0$.

### Exam Practice Focus
1.  Find the domain of $f(x) = \frac{1}{\sqrt{x^2 - 9}}$.
2.  Find the range of $g(x) = x^2 - 4x + 5$.

---

## 📈 Topic 2: Graphing & Parametric Equations (Week 2)

### Key Concepts
*   **Graph Transformations:**
    *   Horizontal shifts: $f(x - c)$ shifts right; $f(x + c)$ shifts left.
    *   Vertical shifts: $f(x) + c$ shifts up; $f(x) - c$ shifts down.
    *   Reflections: $-f(x)$ reflects over $x$-axis; $f(-x)$ reflects over $y$-axis.
*   **Parametric Equations:** Expressing coordinate variables $x$ and $y$ independently in terms of an auxiliary parameter $t$.

### High-Yield Formulas
*   *Circle Parametric Form:* $x = h + r\cos(t)$, $y = k + r\sin(t)$ for $t \in [0, 2\pi]$.
*   *Parabola Parametric Form:* $x = at^2$, $y = 2at$.

### Exam Practice Focus
1.  Sketch the graph of $y = |x - 2| + 1$ using transformation techniques.
2.  Eliminate the parameter $t$ from $x = 3\cos(t)$, $y = 3\sin(t)$ to find its Cartesian equation.

---

## ⚡ Topic 3: Limits, Continuity & L'Hospital's Rule (Week 3)

### Key Concepts
*   **Limits:** The value a function approaches as the input approaches a specific point.
*   **Continuity:** A function $f(x)$ is continuous at $x = c$ if:
    1. $f(c)$ is defined.
    2. $\lim_{x \to c} f(x)$ exists.
    3. $\lim_{x \to c} f(x) = f(c)$.
*   **L'Hospital's Rule:** Used when evaluating limits that result in indeterminate forms ($0/0$ or $\infty/\infty$).

### High-Yield Formulas
*   $$\lim_{x \to 0} \frac{\sin(x)}{x} = 1$$
*   **L'Hospital's Rule:**
    $$\lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f'(x)}{g'(x)} \quad \text{if limit is of form } \frac{0}{0} \text{ or } \frac{\infty}{\infty}$$

### Exam Practice Focus
1.  Evaluate $\lim_{x \to 0} \frac{e^x - 1 - x}{x^2}$.
2.  Determine the value of $k$ that makes $f(x) = \begin{cases} \frac{\sin(2x)}{x} & x \neq 0 \\ k & x = 0 \end{cases}$ continuous at $x = 0$.

---

## 📐 Topic 4: Differentiation and Tangent Curves (Week 4)

### Key Concepts
*   **Derivative Geometric Meaning:** Represents the instantaneous slope of the tangent line to the curve at any given point.
*   **Chain Rule:** Differentiating composite functions (nested functions).
*   **Implicit Differentiation:** Differentiating variables $y$ directly w.r.t $x$ when $y$ is not explicitly isolated.

### High-Yield Formulas
*   *Tangent Equation:* $y - y_0 = f'(x_0)(x - x_0)$
*   *Normal Equation:* $y - y_0 = -\frac{1}{f'(x_0)}(x - x_0)$
*   *Chain Rule:* $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$

### Exam Practice Focus
1.  Find the equation of the tangent line to $y = x^3 - 3x + 2$ at the point $(2, 4)$.
2.  Compute $\frac{dy}{dx}$ using implicit differentiation for $x^2 + y^2 = xy + 7$.

---

## 🎯 Topic 5: Optimization & Max/Min (Week 5)

### Key Concepts
*   **Critical Points:** Points where $f'(x) = 0$ or is undefined.
*   **First Derivative Test:** Determines local extrema by looking at slope sign changes around critical values.
*   **Second Derivative Test:** If $f'(c) = 0$:
    *   $f''(c) > 0 \implies$ Local Minimum.
    *   $f''(c) < 0 \implies$ Local Maximum.

### High-Yield Formulas
*   *Critical Value Condition:* $f'(x) = 0$
*   *Point of Inflection Condition:* $f''(x) = 0$ where concavity changes.

### Exam Practice Focus
1.  Find the local maximum and minimum values of $f(x) = 2x^3 - 3x^2 - 12x + 5$.
2.  An open box is made from a $12 \times 12$ square sheet of metal by cutting equal squares from the corners and folding up the sides. Find the maximum volume.

---

## 🔗 Topic 6: Successive Differentiation & Leibnitz's Theorem (Week 6)

### Key Concepts
*   **Successive Differentiation:** Taking multiple sequential derivatives of a function ($y_1, y_2, \dots, y_n$).
*   **Leibnitz's Theorem:** A generalized product rule to find the $n$-th derivative of two multiplying functions $u$ and $v$.

### High-Yield Formulas
*   *Leibnitz's Formula:*
    $$(uv)_n = u_n v + n u_{n-1} v_1 + \frac{n(n-1)}{2!} u_{n-2} v_2 + \dots + u v_n$$
*   *Standard $n$-th Derivatives:*
    *   $\frac{d^n}{dx^n}(e^{ax}) = a^n e^{ax}$
    *   $\frac{d^n}{dx^n}(\sin(ax + b)) = a^n \sin\left(ax + b + \frac{n\pi}{2}\right)$
    *   $\frac{d^n}{dx^n}\left(\frac{1}{ax+b}\right) = \frac{(-1)^n n! a^n}{(ax+b)^{n+1}}$

### Exam Practice Focus
1.  If $y = \sin(m \sin^{-1} x)$, prove that $(1-x^2)y_{n+2} - (2n+1)xy_{n+1} + (m^2 - n^2)y_n = 0$.
2.  Use Leibnitz's Theorem to find the $n$-th derivative of $y = x^2 \cos(3x)$.

---

## 📝 Topic 7: Mean Value Theorems & Taylor-Maclaurin Series (Week 7)

### Key Concepts
*   **Rolle's Theorem:** Guaranteed zero-slope points between equal boundaries.
*   **Mean Value Theorem (Lagrange):** Instantaneous rate of change equals average rate of change on an interval.
*   **Power Series Expansion:** Approximating transcendental curves using polynomials.

### High-Yield Formulas
*   *Lagrange MVT:* $f'(c) = \frac{f(b) - f(a)}{b - a}$
*   *Maclaurin Series:*
    $$f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!}x^3 + \dots$$
*   *Common Expansions:*
    *   $e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots$
    *   $\sin(x) = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \dots$

### Exam Practice Focus
1.  Find the value of $c$ that satisfies Lagrange's MVT for $f(x) = \ln(x)$ on $[1, e]$.
2.  Find the first four non-zero terms of the Taylor series expansion for $f(x) = \cos(x)$ centered at $x = \pi/4$.

---

## 🧊 Topic 8: Partial Derivatives & Euler's Theorem (Week 8)

### Key Concepts
*   **Partial Derivatives:** Derivatives of multivariable functions where one variable changes while the others are held constant.
*   **Homogeneous Functions:** Functions where scaling all inputs by a factor $t$ results in scaling the output by $t^n$.

### High-Yield Formulas
*   *Euler's Theorem on Homogeneous Functions:*
    $$x \frac{\partial u}{\partial x} + y \frac{\partial u}{\partial y} = nu \quad \text{where } u \text{ is homogeneous of degree } n$$
*   *Euler's Generalization:*
    $$x^2 \frac{\partial^2 u}{\partial x^2} + 2xy \frac{\partial^2 u}{\partial x \partial y} + y^2 \frac{\partial^2 u}{\partial y^2} = n(n-1)u$$

### Exam Practice Focus
1.  Compute the first-order partial derivatives for $z = \ln(x^2 + y^2)$.
2.  If $u = \sin^{-1}\left(\frac{x+y}{\sqrt{x} + \sqrt{y}}\right)$, prove that $x \frac{\partial u}{\partial x} + y \frac{\partial u}{\partial y} = \frac{1}{2}\tan(u)$.

---

## 🔄 Topic 9: Advanced Integration & Reduction (Week 9)

### Key Concepts
*   **u-Substitution:** Simplifies integrals by replacing variables with their derivatives.
*   **Integration by Parts (IBP):** Decomposing the integral of a product.
*   **Reduction Formulas:** Recursive integration of trigonometric powers.

### High-Yield Formulas
*   *Integration by Parts:* $\int u \, dv = uv - \int v \, du \quad$ *(LIATE rule)*
*   *Trigonometric Reduction Formulas:*
    *   $$\int \sin^n(x) \, dx = -\frac{\sin^{n-1}(x)\cos(x)}{n} + \frac{n-1}{n} \int \sin^{n-2}(x) \, dx$$
    *   $$\int \cos^n(x) \, dx = \frac{\cos^{n-1}(x)\sin(x)}{n} + \frac{n-1}{n} \int \cos^{n-2}(x) \, dx$$

### Exam Practice Focus
1.  Evaluate $\int e^x \sin(x) \, dx$ using dual-stage integration by parts.
2.  Derive the reduction formula for $I_n = \int \tan^n(x) \, dx$.

---

## 📊 Topic 10: Definite Integrals & Beta-Gamma Functions (Week 10)

### Key Concepts
*   **Fundamental Theorem of Calculus:** Evaluates accumulated net area.
*   **Gamma Function ($\Gamma(n)$):** Continuous interpolation of factorial for real numbers.
*   **Beta Function ($B(m,n)$):** Advanced trigonometric/polynomial integral scaling.

### High-Yield Formulas
*   *Gamma Definition:* $\Gamma(n) = \int_0^\infty e^{-x} x^{n-1} \, dx \quad \implies \Gamma(n) = (n-1)!$
*   *Beta Definition:* $B(m,n) = \int_0^1 x^{m-1} (1-x)^{n-1} \, dx = \frac{\Gamma(m)\Gamma(n)}{\Gamma(m+n)}$
*   *Trigonometric Beta Relationship:*
    $$\int_0^{\pi/2} \sin^p(x) \cos^q(x) \, dx = \frac{1}{2} B\left(\frac{p+1}{2}, \frac{q+1}{2}\right) = \frac{\Gamma\left(\frac{p+1}{2}\right)\Gamma\left(\frac{q+1}{2}\right)}{2\Gamma\left(\frac{p+q+2}{2}\right)}$$

### Exam Practice Focus
1.  Evaluate the Gamma value $\Gamma(9/2)$ using continuous reduction.
2.  Solve the definite integral $\int_0^{\pi/2} \sin^5(x) \cos^3(x) \, dx$ using the Beta-Gamma method.

---

## 🌀 Topic 11: Geometric Applications of Integration (Week 11)

### Key Concepts
*   **Rectification:** Calculating the exact geometric length of a curve segment.
*   **Solid of Revolution Volume:** Revolving regions around coordinate axes.
*   **Surface Area of Revolution:** Calculating boundary area of revolved volumes.

### High-Yield Formulas
*   *Planar Area:* $A = \int_a^b (y_{top} - y_{bottom}) \, dx$
*   *Arc Length (Rectification):* $s = \int_a^b \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx$
*   *Volume of Revolution (Revolved around x-axis):*
    $$V = \int_a^b \pi y^2 \, dx$$
*   *Surface Area of Revolution (Revolved around x-axis):*
    $$S = \int_a^b 2\pi y \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx$$

### Exam Practice Focus
1.  Find the area of the region bounded by $y^2 = 4x$ and $y = x$.
2.  Find the volume of the solid generated by revolving the circle $x^2 + y^2 = a^2$ around the $x$-axis (sphere proof).

---

## 🗺️ Topic 12: Vector Operations & Calculus (Week 12)

### Key Concepts
*   **Vector Products:** Quadruple products and triple products.
*   **Linear Independence:** Determining if a set of vectors has unique directional paths.
*   **Vector Function Derivative:** Instantaneous velocity vector along a curve.

### High-Yield Formulas
*   *Scalar Triple Product:* $\vec{a} \cdot (\vec{b} \times \vec{c}) = \begin{vmatrix} a_x & a_y & a_z \\ b_x & b_y & b_z \\ c_x & c_y & c_z \end{vmatrix}$
*   *Vector Triple Product:* $\vec{a} \times (\vec{b} \times \vec{c}) = (\vec{a}\cdot\vec{c})\vec{b} - (\vec{a}\cdot\vec{b})\vec{c}$
*   *Derivative of Cross Product:* $\frac{d}{dt}[\vec{u}(t) \times \vec{v}(t)] = \vec{u}'(t) \times \vec{v}(t) + \vec{u}(t) \times \vec{v}'(t)$

### Exam Practice Focus
1.  Determine if $\vec{A} = \hat{i} + \hat{j} + \hat{k}$, $\vec{B} = 2\hat{i} - \hat{j} + 3\hat{k}$, and $\vec{C} = \hat{i} - 2\hat{j} + 2\hat{k}$ are coplanar (Scalar Triple Product equals 0).
2.  Find the tangent unit vector $\hat{T}(t)$ for $\vec{r}(t) = \cos(t)\hat{i} + \sin(t)\hat{j} + t\hat{k}$ at $t = \pi/2$.

---

## 🌪️ Topic 13: Vector Operators - Grad, Div, Curl (Week 13)

### Key Concepts
*   **Gradient:** Creates a vector field pointing to steepest spatial growth.
*   **Divergence:** Determines localized expansion source/sink rates.
*   **Curl:** Measures rotational vortices in fluid fields.

### High-Yield Formulas
*   *Del Operator:* $\nabla = \hat{i}\frac{\partial}{\partial x} + \hat{j}\frac{\partial}{\partial y} + \hat{k}\frac{\partial}{\partial z}$
*   *Gradient:* $\text{grad } \phi = \nabla \phi = \left(\frac{\partial \phi}{\partial x}, \frac{\partial \phi}{\partial y}, \frac{\partial \phi}{\partial z}\right)$
*   *Divergence:* $\text{div } \vec{F} = \nabla \cdot \vec{F} = \frac{\partial F_x}{\partial x} + \frac{\partial F_y}{\partial y} + \frac{\partial F_z}{\partial z}$
*   *Curl:* $\text{curl } \vec{F} = \nabla \times \vec{F}$

### Exam Practice Focus
1.  Find the directional derivative of $\phi = 2x^2 y - 3yz^2$ at $(1, 2, -1)$ in the direction of vector $2\hat{i} - \hat{j} - 2\hat{k}$.
2.  Prove that $\vec{F} = (y^2 - z^2 + 3yz - 2x)\hat{i} + (3xz + 2xy)\hat{j} + (3xy - 2xz)\hat{k}$ is solenoidal ($\nabla \cdot \vec{F} = 0$).

---

## 🛞 Topic 14: Vector Integrals & Boundary Theorems (Week 14)

### Key Concepts
*   **Line Integral:** Integral of force components tangential to a path curve.
*   **Gauss's Divergence Theorem:** Converts surface integrals to volume integrals.
*   **Stokes's Theorem:** Converts loop integrals to open surface curl integrals.

### High-Yield Formulas
*   *Green's Theorem:*
    $$\oint_C (P\,dx + Q\,dy) = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right) dx \, dy$$
*   *Gauss's Theorem:*
    $$\iint_S \vec{F} \cdot \hat{n} \, dS = \iiint_V (\nabla \cdot \vec{F}) \, dV$$
*   *Stokes's Theorem:*
    $$\oint_C \vec{F} \cdot d\vec{r} = \iint_S (\nabla \times \vec{F}) \cdot \hat{n} \, dS$$

### Exam Practice Focus
1.  Use Green's Theorem to evaluate $\oint_C (xy + y^2)\,dx + x^2\,dy$ where $C$ is bounded by $y = x$ and $y = x^2$.
2.  Verify the Divergence Theorem for $\vec{F} = 4xz\hat{i} - y^2\hat{j} + yz\hat{k}$ over the unit cube $x,y,z \in [0, 1]$.
