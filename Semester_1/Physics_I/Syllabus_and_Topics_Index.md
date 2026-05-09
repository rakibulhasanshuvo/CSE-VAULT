# 🗂️ Physics I: Master Syllabus & Topics Index
### ⚡ Course Code: 0533-101 (Electricity & Magnetism Theory)

Welcome to your structured, high-yield Physics I syllabus index! This file maps your entire theoretical curriculum (excluding practical labs) into logical, bite-sized topics optimized for a Computer Science background. 

Each topic below is translated using **computational logic** and **visual graphics analogies** (treating fields as shaders, voltage as data pipelines, and theorems as API abstractions).

---

## 🗺️ Master Topic Roadmap

### ⚡ Part I: Electricity & Circuit Architectures
*   [**Topic 1: Electrostatics Basics**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_1_Electrostatics)
    *   *Syllabus:* Charge quantization, Coulomb's Law, electrical units.
*   [**Topic 2: Fields, Potential & Dipoles**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_2_Fields_Potential_Dipoles)
    *   *Syllabus:* Lines of force, electric dipoles, dielectric polarization, potential functions.
*   [**Topic 3: Gauss's Law & Flux**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_3_Gauss_Law)
    *   *Syllabus:* Electric flux, Gauss's Law, field derivations for point, line, sheet, and sphere.
*   [**Topic 4: Intro to Networks & Divider Rules**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_4_Intro_to_Networks)
    *   *Syllabus:* Electrical components, Ohm's Law, Voltage/Current Divider Rules (VDR/CDR).
*   [**Topic 5: Advanced Circuit Analysis**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_5_Advanced_Circuit_Analysis)
    *   *Syllabus:* Kirchhoff's laws (KCL, KVL), Mesh analysis, Nodal analysis.
*   [**Topic 6: Thevenin, Norton, and Circuit Theorems**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_6_Thevenin_Norton_and_Circuit_Theorems)
    *   *Syllabus:* Superposition, Thevenin’s, Norton’s, Max Power Transfer, Wye-Delta transformations, AC/DC networks.

### 🧲 Part II: Magnetism & Electromagnetic Dynamics
*   [**Topic 7: Magnetic Fields & Flux Density**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_7_Magnetic_Fields_and_Flux_Density)
    *   *Syllabus:* Magnetic field vector ($B$), magnetic flux, scalar and vector potentials.
*   [**Topic 8: Faraday, Lenz, and Induction**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_8_Faraday_Lenz_and_Induction)
    *   *Syllabus:* Faraday's Law, Lenz's Law (feedback loops), self and mutual inductance.
*   [**Topic 9: Biot-Savart & Ampere Laws**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_9_Biot_Savart_and_Ampere_Laws)
    *   *Syllabus:* Biot-Savart Law, Ampere's Law, calculating magnetic field intensity.
*   [**Topic 10: AC Current, Voltage, and RMS**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_10_AC_Current_Voltage_and_RMS)
    *   *Syllabus:* Alternating current, wave representations, phase angles, calculating RMS values.
*   [**Topic 11: Transformer Basics & Principles**](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_11_Transformer_Basics_and_Principles)
    *   *Syllabus:* Ideal transformers, turns ratios, impedance matching, step-up/step-down.

---

## ⚡ Part I: Electricity & Circuit Architectures

### 🔋 Topic 1: Electrostatics Basics
*   **📂 Folder:** [Topic_1_Electrostatics](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_1_Electrostatics)
*   **💡 Vibe Check (High-Level Intent):** The static state variables of the physical world before any event loops trigger. Charge represents the fundamental static property, and Coulomb's Law calculates the direct distance-based transform forces between these points.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Quantization of Charge (Discrete allocations only)
    q = n * e                [Unit: Coulombs (C)]
    Where:
      e = 1.602 x 10^-19 C   (The elementary float variable)
      n = Integer (Z-value)

    // Coulomb's Law (Magnitude of mutual force vector)
    F = k * (|q1 * q2| / r^2) [Unit: Newtons (N)]
    Where:
      k = 1 / (4πε₀) ≈ 8.99 x 10^9 N·m²/C²
      ε₀ = 8.854 x 10^-12 C²/(N·m²) (Permittivity constant)
    ```
*   **⚠️ Edge Cases & Traps:** Force is a **VECTOR**. If multiple charges exist, you *cannot* just add their magnitudes together. You must resolve them into $x$ and $y$ vectors first and perform vector addition: $F_{\text{net}} = \sqrt{(\sum F_x)^2 + (\sum F_y)^2}$.

---

### 🌐 Topic 2: Fields, Potential & Dipoles
*   **📂 Folder:** [Topic_2_Fields_Potential_Dipoles](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_2_Fields_Potential_Dipoles)
*   **💡 Vibe Check (High-Level Intent):**
    *   *Electric Field:* A 3D vector shader running at every coordinate in space, returning the force vector acting on a $+1\text{C}$ test charge.
    *   *Potential:* A scalar heightmap (SDF - Signed Distance Field) of the environment. Instead of complex vectors, it tracks the work required to move coordinates.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Electric Field Vector (Point Charge)
    E = k * (q / r^2) r_hat   [Unit: N/C or V/m]

    // Scalar Potential
    V = k * (q / r)          [Unit: Volts (V) or J/C]

    // Field-Potential Gradient Relationship
    E = -∇V = -(∂V/∂x i_hat + ∂V/∂y j_hat + ∂V/∂z k_hat)

    // Dipole Moment (Vector pointing negative -> positive)
    p = q * d                [Unit: C·m]
    ```
*   **⚠️ Edge Cases & Traps:** Potential ($V$) is a **scalar**. Do not break potential into components! Just sum the numerical values directly, but **always preserve the algebraic sign of the charge** (positive charges create $+V$, negative charges create $-V$).

---

### 📐 Topic 3: Gauss's Law & Flux
*   **📂 Folder:** [Topic_3_Gauss_Law](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_3_Gauss_Law)
*   **💡 Vibe Check (High-Level Intent):** An elegant system-input/output debugger. Instead of integrating over an infinite array of charges, construct a bounding volume (Gaussian Surface) around the scene. The net vector flux piercing the boundary equals the total enclosed variables.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Electric Flux (Vector dot product of Field and Area)
    Φ_E = ∮ E · dA = E * A * cos(θ)    [Unit: N·m²/C]

    // Gauss's Law
    Φ_E = Q_enclosed / ε₀
    ```
*   **🔥 The "Big 3" Bounding Box Derivations (Learn by heart):**
    *   *Line Charge (Cylinder):* $E = \frac{\lambda}{2\pi\epsilon_0 r}$
    *   *Sheet of Charge (Pillbox):* $E = \frac{\sigma}{2\epsilon_0}$
    *   *Solid Sphere (Sphere):* $E_{\text{outside}} = \frac{kQ}{r^2}$, $E_{\text{inside}} = \frac{kQ}{R^3}r$

---

### 🔌 Topic 4: Intro to Networks & Divider Rules
*   **📂 Folder:** [Topic_4_Intro_to_Networks](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_4_Intro_to_Networks)
*   **💡 Vibe Check (High-Level Intent):** Directing the current data-bus. Resistors act as bottlenecks/limiters. Voltage is the potential pipeline pressure, and current is the flow rate of packets through the connection.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Ohm's Law
    V = I * R                 [Unit: V = A * Ω]

    // Series Resistance
    R_eq = R1 + R2 + ...      (Increases bottleneck)
    
    // Parallel Resistance
    R_eq = (R1 * R2) / (R1 + R2) (Alternative routing channels)

    // Voltage Divider Rule (VDR - Series only)
    V_x = V_source * (R_x / R_eq)

    // Current Divider Rule (CDR - Two Parallel branches)
    I_1 = I_source * (R2 / (R1 + R2))  *(Note: Other resistor is on top!)*
    ```
*   **⚠️ Edge Cases & Traps:** In current division (CDR), the current in branch 1 is proportional to the resistance of the **other** branch ($R_2$). Do not put the target branch's resistance on the numerator!

---

### ⚙️ Topic 5: Advanced Circuit Analysis
*   **📂 Folder:** [Topic_5_Advanced_Circuit_Analysis](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_5_Advanced_Circuit_Analysis)
*   **💡 Vibe Check (High-Level Intent):** System state constraints. 
    *   *Kirchhoff's Current Law (KCL):* Network traffic conservation—no packets can disappear at a junction.
    *   *Kirchhoff's Voltage Law (KVL):* Energy loop integrity—any rise in pipeline pressure must balance out around a closed cycle.
*   **📑 The Source Code (Formulas):**
    ```physics
    KCL (Junction Rule):  Σ I_in = Σ I_out          (Conservation of Charge)
    KVL (Loop Rule):      Σ V_drops = Σ V_rises     (Conservation of Energy)
    ```
*   **🛠️ Analytical Solvers:**
    *   *Mesh Analysis:* KVL loops using clockwise reference loops. Excellent for planar loops.
    *   *Nodal Analysis:* KCL junctions using a standard $0\text{V}$ Ground coordinate. Excellent for parallel nodes.

---

### 🚀 Topic 6: Thevenin, Norton, and Circuit Theorems
*   **📂 Folder:** [Topic_6_Thevenin_Norton_and_Circuit_Theorems](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_6_Thevenin_Norton_and_Circuit_Theorems)
*   **💡 Vibe Check (High-Level Intent):** The ultimate Object-Oriented paradigm for circuits. A massive, overly complex network of resistors and sources is abstracted (encapsulated) behind an API. From the perspective of any load resistor, the entire system behaves as a single simple voltage source in series with a resistor (Thevenin), or a current source in parallel with a resistor (Norton).
*   **📑 The Source Code (Formulas):**
    ```physics
    // Thevenin Equivalent Circuit
    V_load = V_th * (R_load / (R_th + R_load))

    // Norton-Thevenin Transformations (Source Transformation)
    V_th = I_n * R_n
    R_th = R_n

    // Maximum Power Transfer Theorem
    For maximum power to be delivered to the load:
    R_load = R_th
    P_max = (V_th)^2 / (4 * R_th)

    // Wye-to-Delta Transformation (Star to Triangle)
    R_delta_A = (R1*R2 + R2*R3 + R3*R1) / R2
    ```
*   **⚠️ Edge Cases & Traps:** When finding $R_{\text{th}}$, **deactivate all sources**:
    *   *Independent Voltage Sources* ➡️ Replace with a **Short Circuit** (0V wire).
    *   *Independent Current Sources* ➡️ Replace with an **Open Circuit** (cut wire).
*   **🎯 Boss Mechanics (Exam Focus):**
    1.  **Thevenin Solver:** Calculate open-circuit voltage $V_{\text{oc}}$ ($V_{\text{th}}$) across terminals $A-B$, deactivate sources to find $R_{\text{th}}$, and draw the simplified circuit.
    2.  **Maximum Power Delivery:** Find the optimal $R_L$ value for a complex circuit and calculate the maximum power dissipation.

#### ⚔️ The Exam Vault (Topic 6 Practice Problems)
##### 📝 Q1: Thevenin Circuit Reduction
*Find the Thevenin equivalent circuit across terminals $A-B$ for a circuit with a $24\text{V}$ battery connected in series with a $4\text{ }\Omega$ resistor, which is in parallel with an $8\text{ }\Omega$ resistor. The terminals $A-B$ are across the $8\text{ }\Omega$ resistor.*

**Solution:**
1.  **Find $V_{\text{th}}$:** With terminals $A-B$ open, the circuit is a simple series loop. Apply the Voltage Divider Rule across the $8\text{ }\Omega$ resistor:
    $$V_{\text{th}} = V_{\text{oc}} = 24\text{V} \times \left(\frac{8\text{ }\Omega}{4\text{ }\Omega + 8\text{ }\Omega}\right) = 24 \times \frac{8}{12} = 16\text{V}$$
2.  **Find $R_{\text{th}}$:** Turn off the $24\text{V}$ voltage source by replacing it with a short-circuit. Looking into terminals $A-B$, the $4\text{ }\Omega$ and $8\text{ }\Omega$ resistors are in parallel:
    $$R_{\text{th}} = \frac{4 \times 8}{4 + 8} = \frac{32}{12} = 2.67\text{ }\Omega$$
3.  **Result:** The Thevenin equivalent is a $16\text{V}$ source in series with a $2.67\text{ }\Omega$ resistor.

---

## 🧲 Part II: Magnetism & Electromagnetic Dynamics

### 🧲 Topic 7: Magnetic Fields and Flux Density
*   **📂 Folder:** [Topic_7_Magnetic_Fields_and_Flux_Density](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_7_Magnetic_Fields_and_Flux_Density)
*   **💡 Vibe Check (High-Level Intent):** A dynamic coordinate transformation. Magnetic fields do not exert force on stationary charges; they are **motion-listeners**. They act as an orthogonal cross-product multiplier on moving charge packets.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Lorentz Force (Magnetic component)
    F_M = q * (v × B) = q * v * B * sin(θ)  [Unit: Newtons (N)]
    Where:
      B = Magnetic flux density vector      [Unit: Tesla (T) or Wb/m²]
      v = Charge velocity vector
      θ = Angle between v and B

    // Magnetic Flux (Piercing vector density over area)
    Φ_B = ∮ B · dA = B * A * cos(θ)        [Unit: Weber (Wb)]
    ```
*   **⚠️ Edge Cases & Traps:** Because of the cross-product ($v \times B$), the magnetic force is **always perpendicular** to both the velocity of the charge and the magnetic field. Consequently, magnetic fields **do zero work** on moving charges ($W = \mathbf{F} \cdot \mathbf{d} = 0$), meaning they change the *direction* of the velocity vector but never its *magnitude* (speed).

---

### 🔁 Topic 8: Faraday, Lenz, and Induction
*   **📂 Folder:** [Topic_8_Faraday_Lenz_and_Induction](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_8_Faraday_Lenz_and_Induction)
*   **💡 Vibe Check (High-Level Intent):** The physical equivalent of a defensive state-listener or exception handler. When magnetic flux changes inside a loop, the universe throws an exception. Lenz's Law is the `catch` block: it generates an opposing current loop specifically designed to push back and preserve the initial state.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Faraday's Law (Induced EMF)
    ε = -N * (dΦ_B / dt)     [Unit: Volts (V)]
    Where:
      N = Number of coil turns
      dΦ_B/dt = Rate of flux change over time
      - (Negative sign) = Lenz's Law indicator (the pushback)

    // Self-Inductance (Voltage induced in self-coil)
    V_L = -L * (dI / dt)     [Unit: L in Henrys (H)]
    
    // Mutual Inductance (Voltage coupling across systems)
    V_2 = -M * (dI_1 / dt)
    ```
*   **⚠️ Edge Cases & Traps:** Lenz's Law direction is highly tested. If the external $B$-field is *increasing*, the induced current will create a magnetic field in the *opposite* direction to resist the change. If the external field is *decreasing*, the induced current will flow in the *same* direction to prop it up.

#### ⚔️ The Exam Vault (Topic 8 Practice Problems)
##### 📝 Q2: Calculating Induced EMF in a Coil
*A circular coil of 50 turns has a radius of $10\text{ cm}$. A magnetic field perpendicular to the coil plane changes uniformly from $0\text{ T}$ to $0.4\text{ T}$ in $0.2\text{ seconds}$. Calculate the magnitude of the induced EMF.*

**Solution:**
1.  **Calculate Loop Area $A$:**
    $$A = \pi r^2 = \pi (0.1\text{ m})^2 = 0.0314\text{ m}^2$$
2.  **Calculate Change in Flux ($\Delta \Phi_B$):** Since the field is perpendicular ($\theta = 0^\circ$, $\cos\theta = 1$):
    $$\Delta \Phi_B = \Delta B \times A = (0.4\text{ T} - 0\text{ T}) \times 0.0314\text{ m}^2 = 0.01256\text{ Wb}$$
3.  **Apply Faraday's Law:**
    $$|\varepsilon| = N \frac{\Delta \Phi_B}{\Delta t} = 50 \times \frac{0.01256\text{ Wb}}{0.2\text{ s}} = 50 \times 0.0628 = 3.14\text{ V}$$
4.  **Result:** The magnitude of the induced EMF is $3.14\text{ V}$.

---

### 📐 Topic 9: Biot-Savart and Ampere Laws
*   **📂 Folder:** [Topic_9_Biot_Savart_and_Ampere_Laws](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_9_Biot_Savart_and_Ampere_Laws)
*   **💡 Vibe Check (High-Level Intent):** Generating magnetic states. Current is just moving charge packets, and moving charge packets create magnetic fields. Biot-Savart is the brute-force integration tool (line-by-line tracing), while Ampere's Law is the elegant "Gauss-like" boundary solver for high-symmetry lines.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Biot-Savart Law (Infinite segment integration)
    dB = (μ₀ / 4π) * (I * dl × r_hat / r²)   [Unit: Tesla (T)]
    Where:
      μ₀ = 4π x 10^-7 T·m/A (Permeability constant)

    // Ampere's Law (Line integral around closed path)
    ∮ B · dl = μ₀ * I_enclosed
    ```
*   **🔥 The "Big 2" Magnetic Field Solutions to Memorize:**
    *   *Long Straight Wire:* $B = \frac{\mu_0 I}{2\pi r}$ (Derived via Amperian circle)
    *   *Inside a Solenoid Coil:* $B = \mu_0 n I$ (where $n = N/L$, turns per unit length)

#### ⚔️ The Exam Vault (Topic 9 Practice Problems)
##### 📝 Q3: Field Near a Long Straight Current-Carrying Wire
*A straight power cable carries a current of $100\text{ A}$ from east to west. Calculate the magnitude and direction of the magnetic field at a point $2\text{ m}$ vertically below the cable.*

**Solution:**
1.  **Identify the Formula:** Use Ampere's Law solution for a long straight wire:
    $$B = \frac{\mu_0 I}{2\pi r}$$
2.  **Substitute Variables:**
    $$B = \frac{(4\pi \times 10^{-7}\text{ T}\cdot\text{m/A}) \times 100\text{ A}}{2\pi \times 2\text{ m}}$$
    Simplify by cancelling $2\pi$:
    $$B = \frac{2 \times 10^{-7} \times 100}{2} = 10^{-5}\text{ T}$$
3.  **Determine Direction (Right Hand Rule):** Point your right thumb in the direction of the current (West). Your fingers curl underneath the wire pointing **South**.
4.  **Result:** The magnetic field magnitude is $10\mu\text{T}$ ($10^{-5}\text{ T}$) directed towards the **South**.

---

### 🌊 Topic 10: AC Current, Voltage, and RMS
*   **📂 Folder:** [Topic_10_AC_Current_Voltage_and_RMS](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_10_AC_Current_Voltage_and_RMS)
*   **💡 Vibe Check (High-Level Intent):** Working with oscillating vectors. In DC networks, values are constant scalar floats. In AC networks, values are dynamic, periodic wave equations ($V(t) = V_{\text{peak}}\sin(\omega t)$). Root Mean Square (RMS) is the calculation algorithm used to map a volatile, zero-average sine wave to its equivalent DC steady-state thermal power delivery value.
*   **📑 The Source Code (Formulas):**
    ```physics
    // Time-domain AC representations
    v(t) = V_peak * sin(ωt + φ)
    i(t) = I_peak * sin(ωt + φ)
    Where:
      ω = 2πf (Angular frequency in rad/s)
      φ = Phase angle displacement

    // Root Mean Square (RMS) values (For sinusoidal waves only)
    V_rms = V_peak / √2 ≈ 0.707 * V_peak
    I_rms = I_peak / √2 ≈ 0.707 * I_peak
    ```
*   **⚠️ Edge Cases & Traps:** Standard wall outlets output RMS values! If a question mentions a "$220\text{V}$ AC outlet," that is $V_{\text{rms}}$. The actual peak voltage is $V_{\text{peak}} = V_{\text{rms}} \times \sqrt{2} \approx 311\text{V}$!

#### ⚔️ The Exam Vault (Topic 10 Practice Problems)
##### 📝 Q4: Peak vs RMS Value Calculations
*An alternating current source outputs a voltage given by the equation $v(t) = 170\sin(377t)\text{ V}$. Find the peak voltage, the frequency of the source, and the RMS voltage.*

**Solution:**
1.  **Extract Peak Voltage $V_{\text{peak}}$:** Compare the equation to the standard template $v(t) = V_{\text{peak}}\sin(\omega t)$:
    $$V_{\text{peak}} = 170\text{ V}$$
2.  **Calculate Frequency $f$:**
    $$\omega = 377\text{ rad/s}$$
    $$\omega = 2\pi f \implies f = \frac{377}{2\pi} \approx 60\text{ Hz}$$
3.  **Calculate RMS Voltage $V_{\text{rms}}$:**
    $$V_{\text{rms}} = \frac{V_{\text{peak}}}{\sqrt{2}} = \frac{170\text{ V}}{1.414} \approx 120.2\text{ V}$$
4.  **Result:** $V_{\text{peak}} = 170\text{ V}$, $f = 60\text{ Hz}$, $V_{\text{rms}} \approx 120\text{ V}$ (This is standard US grid utility rating).

---

### ⚙️ Topic 11: Transformer Basics and Principles
*   **📂 Folder:** [Topic_11_Transformer_Basics_and_Principles](file:///c:/Users/CM/OneDrive/Desktop/mid=exam/Semester_1/Physics_I/Topic_11_Transformer_Basics_and_Principles)
*   **💡 Vibe Check (High-Level Intent):** The physical equivalent of a variable scaling matrix or typecast node. It maps voltage up and current down (or vice-versa) while conserving total power ($P = V \cdot I$) using magnetic flux coupling across isolation boundaries.
*   **📑 The Source Code (Formulas):**
    ```physics
    // The Transformer Equation
    V_p / V_s = N_p / N_s = I_s / I_p = a (Turns ratio)
    Where:
      p = Primary coil (input side)
      s = Secondary coil (output side)
      N = Number of coil wraps

    // Efficiency (Ideal η = 100%)
    η = P_out / P_in = (V_s * I_s * cos(θ_s)) / (V_p * I_p * cos(θ_p))
    ```
*   **⚠️ Edge Cases & Traps:** Transformers are strictly **AC-listeners**! They rely entirely on changing magnetic flux ($d\Phi_B/dt$). If you connect a $12\text{V}$ **DC battery** to the primary winding of a transformer, the output voltage at the secondary winding is **$0\text{V}$** after the initial turn-on spike, because static DC current produces no change in magnetic flux!

#### ⚔️ The Exam Vault (Topic 11 Practice Problems)
##### 📝 Q5: Step-Down Transformer Mechanics
*A step-down transformer has a turns ratio of $10:1$ ($N_p/N_s = 10$). If the primary winding is connected to a $120\text{V}$ AC power line, and the primary current is $2\text{ A}$, find the secondary voltage, secondary current, and secondary power (assuming an ideal transformer).*

**Solution:**
1.  **Calculate Secondary Voltage $V_s$:**
    $$\frac{V_p}{V_s} = \frac{N_p}{N_s} = 10 \implies V_s = \frac{V_p}{10} = \frac{120\text{ V}}{10} = 12\text{ V}$$
2.  **Calculate Secondary Current $I_s$:**
    $$\frac{I_s}{I_p} = \frac{N_p}{N_s} = 10 \implies I_s = 10 \times I_p = 10 \times 2\text{ A} = 20\text{ A}$$
3.  **Calculate Output Power $P_s$:**
    $$P_{\text{out}} = V_s \times I_s = 12\text{ V} \times 20\text{ A} = 240\text{ W}$$
    *Check via Input Power:* $P_{\text{in}} = V_p \times I_p = 120\text{ V} \times 2\text{ A} = 240\text{ W}$. (Power is conserved).
4.  **Result:** $V_s = 12\text{ V}$, $I_s = 20\text{ A}$, $P_s = 240\text{ W}$.
