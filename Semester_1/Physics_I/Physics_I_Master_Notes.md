# 🚀 Physics I: Comprehensive Midterm Notes

---

# ⚡ Topic 1: Electrostatics Basics (Week 1)

## 📌 Key Concepts
* **Electric Charge:** Fundamental property of matter. Understand nature, quantization, and conservation.
* **Vector Superposition Principle:** Essential for solving problems with 3 or more charges. To find net force, add individual force vectors.

## 📑 High-Yield Formulas
* **Coulomb’s Law:** `F = k * (|q1 * q2| / r²)`
  * Coulomb's constant `k = 8.99 x 10⁹ N·m²/C²`
  * Permittivity of free space `ε₀ = 8.85 x 10⁻¹² C²/(N·m²)`
  * Relationship: `k = 1 / (4πε₀)`
* **Quantization of Charge:** `q = n * e`
  * Elementary charge `e = 1.602 x 10⁻¹⁹ C`

## 🎯 Exam Practice Focus
1. Calculate the force between two point charges separated by a distance.
2. Find the net force on a charge at the center of a triangle/square of charges.
3. Calculate how many electrons are in a given amount of Coulomb charge.

---
> **💡 Pro Tip:** Force is a **VECTOR**. If charges are in 2D, you **must** resolve them into x and y components before adding.

---

# 🌐 Topic 2: Fields, Potential & Dipoles (Week 2)

## 📌 Key Concepts
* **Electric Fields:** The space surrounding charges visualized by field lines. It represents force per unit charge.
* **Electric Potential vs Potential Energy:** Potential is a scalar representation of the electric field's effect (energy per unit charge).
* **Electric Dipoles:** A pair of equal and opposite charges.
* **Dielectrics:** Insulators that can be polarized by an applied electric field, reducing the internal field.

## 📑 High-Yield Formulas
* **Electric Field (Point Charge):** `E = k * (|q| / r²)` (Vector)
* **Electric Potential:** `V = k * (q / r)` (Scalar)
* **Field-Potential Relation:** `E = -∇V = -(dV/dx i + dV/dy j + dV/dz k)`
* **Dipole Moment:** `p = q * d` (Vector pointing from -q to +q)
* **Dipole Potential:** `V = (k * p * cosθ) / r²`

## 🎯 Exam Practice Focus
1. Find the electric field at a point between two opposite charges.
2. Calculate the potential at a specific distance from a dipole.
3. Explain how a dielectric material changes the electric field inside a capacitor.

---
> **💡 Pro Tip:** Potential is a **SCALAR**. You can just add the values together without worrying about angles! Remember to include the **sign** (+ or -) of the charge when calculating scalar potential.

---

# 📐 Topic 3: Gauss's Law (Week 3)

## 📌 Key Concepts
* **Electric Flux (ΦE):** Measure of the electric field passing through a given surface. `ΦE = E * A * cosθ`
* **Gaussian Surface:** A closed imaginary surface in 3D space through which the flux is calculated.

## 📑 High-Yield Formulas
* **Gauss's Law:** `ΦE = ∮ E · dA = Q_enc / ε₀`

## 📑 The "Big 4" Derivations to Memorize
*You MUST be able to derive E for these from scratch using Gauss's Law:*
1. **Point Charge:** `E = kQ / r²` (Spherical surface)
2. **Infinite Line Charge:** `E = λ / (2πε₀r)` (Cylindrical surface)
3. **Infinite Sheet of Charge:** `E = σ / (2ε₀)` (Pillbox surface)
4. **Uniformly Charged Sphere:**
   * Outside (`r ≥ R`): `E = kQ / r²`
   * Inside (`r < R`): `E = (kQ / R³) * r`

## 🎯 Exam Practice Focus
1. Define Electric Flux and its units (`N·m²/C`).
2. Derive the electric field for an infinite sheet of charge using a "pillbox" Gaussian surface.
3. Calculate the flux through a cube with a charge at its center.

---
> **💡 Pro Tip:** Choosing the right **Gaussian Surface** is the key. For lines, use a cylinder. For sheets, use a pillbox. For spheres, use a sphere. Always exploit symmetry!

---

# 🔌 Topic 4: Intro to Networks (Week 4)

## 📌 Key Concepts
* **Networks:** Master the "Divider Rules" to save time during circuit calculations.
* **Series & Parallel Resistors:** How to simplify complex networks into a single equivalent resistance.

## 📑 High-Yield Formulas
* **Ohm's Law:** `V = I * R`
* **Equivalent Resistance:**
  * Series: `Req = R1 + R2 + ... + Rn`
  * Parallel: `1/Req = 1/R1 + 1/R2 + ... + 1/Rn` (For two: `Req = (R1*R2)/(R1+R2)`)
* **Voltage Divider Rule (VDR - Series):** `Vx = Vs * (Rx / Req)`
* **Current Divider Rule (CDR - Two Parallel Resistors):** `I1 = Is * (R2 / (R1 + R2))` *(Note: The OTHER resistor is on top!)*
* **Power:** `P = V*I = I²R = V²/R`

## 🎯 Exam Practice Focus
1. Simplify a complex network of 5-6 resistors into one `Req`.
2. Find the voltage across a specific resistor using VDR.
3. Find the current through a parallel branch using CDR.

---
> **💡 Pro Tip:** In CDR, the current through one branch is proportional to the **other** branch's resistance. Don't mix them up!

---

# ⚙️ Topic 5: Advanced Circuit Analysis (Week 5)

## 📌 Key Concepts
* **Kirchhoff's Voltage Law (KVL - Loop Rule):** Sum of voltage drops and rises in a closed loop equals zero (`ΣV = 0`). Based on Conservation of Energy.
* **Kirchhoff's Current Law (KCL - Junction Rule):** Sum of currents entering a junction equals sum of currents leaving (`ΣI_in = ΣI_out`). Based on Conservation of Charge.
* **Mesh Analysis:** Solving circuits using loop currents and KVL.
* **Nodal Analysis:** Solving circuits using node voltages and KCL.

## 📑 Key Analytical Steps
**Mesh Analysis:**
1. Assign loop currents (i1, i2...) in the same direction (e.g., clockwise).
2. Write KVL equations for each loop.
3. Solve the system of linear equations.

**Nodal Analysis:**
1. Pick a Ground (0V) reference node.
2. Assign node voltages (V1, V2...) to the other junctions.
3. Write KCL equations at each non-reference node.

## 🎯 Exam Practice Focus
1. Solve a 2-loop circuit using Mesh Analysis.
2. Find the node voltages in a circuit with 3 nodes.
3. Apply Kirchhoff's Laws to find an unknown current in a bridge circuit.

---
> **💡 Pro Tip:** If a circuit has many parallel branches, **Nodal Analysis** is usually faster. If it has many series loops, **Mesh Analysis** is better. Picking the right one saves you 10 minutes in the exam!

---

# 🚀 Topic 6: Thevenin, Norton & Circuit Theorems (Week 6)

## 📌 Key Concepts
* **Thevenin’s Theorem:** Any linear circuit can be simplified to an equivalent single voltage source ($V_{th}$) in series with an equivalent resistor ($R_{th}$).
* **Norton’s Theorem:** Any linear circuit can be simplified to an equivalent single current source ($I_n$) in parallel with an equivalent resistor ($R_n$).
* **Maximum Power Transfer:** A load resistor ($R_L$) connected across a circuit absorbs maximum power when its resistance equals the source's internal resistance ($R_L = R_{th}$).
* **Wye-Delta (Y-Δ) Transformations:** A structural tool to simplify resistor bridges that are neither purely in series nor in parallel.

## 📑 High-Yield Formulas
* **Source Transformation:** `V_th = I_n * R_th` (where `R_th = R_n`)
* **Maximum Power Delivery:** `P_max = (V_th)² / (4 * R_th)`
* **Wye to Delta (R_A, R_B, R_C from R1, R2, R3):**
  * `R_A = (R1*R2 + R2*R3 + R3*R1) / R2` (Opposite node division)

## 🎯 Exam Practice Focus
1. Calculate open-circuit voltage ($V_{oc} = V_{th}$) and short-circuit current ($I_{sc} = I_n$) across a load junction.
2. Find $R_{th}$ by deactivating all independent sources (short voltage sources, open current sources).
3. Determine the optimal load resistance $R_L$ for maximum power transfer and calculate the output wattage.

---
> **💡 Pro Tip:** Thevenin is the ultimate abstraction boundary. When finding $R_{th}$, replace all batteries with wires (shorts) and all current sources with gaps (open circuits).

---

# 🧲 Topic 7: Magnetic Fields & Flux Density (Week 7)

## 📌 Key Concepts
* **Magnetic Fields ($B$):** Fields created by moving charge packets. Measured in Tesla ($T$) or Webers per square meter ($Wb/m²$).
* **Lorentz Force:** The mechanical steering force acting on charges traversing a magnetic field.
* **Magnetic Flux ($\Phi_B$):** The measure of the magnetic field passing through a given surface area.

## 📑 High-Yield Formulas
* **Magnetic Force (Moving Point Charge):** `F_m = q * (v × B) = q * v * B * sin(θ)`
* **Magnetic Force (Current-Carrying Wire):** `F_m = I * (L × B) = I * L * B * sin(θ)`
* **Magnetic Flux:** `Φ_B = ∫ B · dA = B * A * cos(θ)` [Unit: Weber (Wb)]

## 🎯 Exam Practice Focus
1. Use the Right-Hand Rule to determine the direction of force, velocity, or $B$-field vectors.
2. Calculate the radius of circular path motion of a charge injected into a uniform $B$-field: `r = (m * v) / (q * B)`.
3. Calculate the net magnetic flux piercing a slanted loop area.

---
> **💡 Pro Tip:** Magnetic fields do **zero work** ($W = 0$) on free charges because the force is always perpendicular to motion! It can steer a particle in circles but can never speed it up.

---

# 🔁 Topic 8: Faraday, Lenz & Induction (Week 8)

## 📌 Key Concepts
* **Faraday’s Law:** A changing magnetic flux over time induces an electromotive force (EMF) voltage inside a loop.
* **Lenz’s Law:** The induced current always flows in a direction that opposes the change in flux that created it (equilibrium preservation listener).
* **Inductance ($L$, $M$):** Self-induction creates a back-EMF in the same coil; mutual induction couples voltage across nearby loops.

## 📑 High-Yield Formulas
* **Faraday’s Law of Induction:** `ε = -N * (dΦ_B / dt)`
* **Self-Induced EMF:** `V_L = -L * (dI / dt)`
* **Coil Inductance:** `L = (N * Φ_B) / I`

## 🎯 Exam Practice Focus
1. Calculate the induced EMF voltage in a coil placed in a decaying or rising magnetic field.
2. Determine the clockwise or counter-clockwise direction of induced current when a bar magnet is moved closer to or further from a loop.
3. Calculate self-inductance and the energy stored in an inductor's magnetic field: `U_B = 0.5 * L * I²`.

---
> **💡 Pro Tip:** Lenz's Law is a physical "Newton's Third Law" for electromagnetism. If flux goes up, the loop fights it. If flux goes down, the loop tries to prop it up.

---

# 📐 Topic 9: Biot-Savart & Ampere Laws (Week 9)

## 📌 Key Concepts
* **Biot-Savart Law:** The mathematical "syntax" for calculating the exact $B$-field vector generated by a small segment of wire.
* **Ampere’s Law:** An elegant line integral relationship linking the tangential $B$-field around a closed loop to the net current passing through it.

## 📑 High-Yield Formulas
* **Biot-Savart Equation:** `dB = (μ₀ / 4π) * (I * dl × r_hat) / r²` (where `μ₀ = 4π x 10⁻⁷ T·m/A`)
* **Ampere’s Circuital Law:** `∮ B · dl = μ₀ * I_enclosed`
* **Common Closed-Form Solvers:**
  * **Long Straight Wire:** `B = (μ₀ * I) / (2π * r)`
  * **Solenoid Winding:** `B = μ₀ * n * I` (where `n = N / L`)

## 🎯 Exam Practice Focus
1. Derive the magnetic field of a long straight wire using Ampere's Law from scratch.
2. Calculate the magnetic field at the center of a circular current-carrying arc using Biot-Savart.
3. Find the attractive or repulsive force per unit length between two parallel current-carrying wires.

---
> **💡 Pro Tip:** Parallel currents flowing in the **same direction attract** each other; currents flowing in **opposite directions repel**.

---

# 🌊 Topic 10: AC Current, Voltage & RMS (Week 10)

## 📌 Key Concepts
* **Alternating Current (AC):** Currents and voltages that cycle sinusoidally over time rather than remaining constant.
* **Root Mean Square (RMS):** The effective scalar value of an AC wave. It represents the equivalent DC voltage that would dissipate the exact same thermal power in a resistor.

## 📑 High-Yield Formulas
* **Sinusoidal Waveform:** `v(t) = V_peak * sin(ωt + φ)`
* **Angular Frequency:** `ω = 2πf = 2π / T`
* **Effective RMS Voltage:** `V_rms = V_peak / √2 ≈ 0.707 * V_peak`
* **Effective RMS Current:** `I_rms = I_peak / √2 ≈ 0.707 * I_peak`

## 🎯 Exam Practice Focus
1. Convert between peak, peak-to-peak, and RMS values for alternating currents and voltages.
2. Write the time-domain equation $v(t)$ given a graphical oscilloscope waveform displaying frequency, peak voltage, and phase shift.
3. Calculate the average power consumed by a resistive AC circuit: `P_avg = V_rms * I_rms`.

---
> **💡 Pro Tip:** Standard household voltage (e.g., 120V or 220V) is always given as an **RMS** value. The actual physical peak of a 120V grid signal is $120 \times \sqrt{2} \approx 170\text{V}$!

---

# ⚙️ Topic 11: Transformer Basics & Principles (Week 11)

## 📌 Key Concepts
* **Transformers:** Devices that transfer electrical energy between circuits through electromagnetic induction, allowing voltage and current to be scaled.
* **Turns Ratio:** The ratio of winding wraps in the primary coil to those in the secondary coil, determining step-up or step-down factors.

## 📑 High-Yield Formulas
* **The Ideal Transformer Equation:** `V_p / V_s = N_p / N_s = I_s / I_p = a`
* **Impedance Scaling:** `Z_p = a² * Z_s`
* **Efficiency (η):** `η = (P_out / P_in) * 100% = (V_s * I_s * cos(θ_s)) / (V_p * I_p * cos(θ_p))`

## 🎯 Exam Practice Focus
1. Calculate the secondary voltage and secondary current of a transformer given the turns ratio and primary input parameters.
2. Solve step-up and step-down ratios to match source impedance to load impedance for maximum power transfer.
3. Explain why connecting a DC battery to a transformer primary coil results in $0\text{V}$ output on the secondary coil.

---
> **💡 Pro Tip:** Transformers only run on **AC**! Static DC currents create a static magnetic field, which means $d\Phi_B/dt = 0$, producing zero output on the secondary winding.

---
> **💡 Pro Tip:** If a circuit has many parallel branches, **Nodal Analysis** is usually faster. If it has many series loops, **Mesh Analysis** is better. Picking the right one saves you 10 minutes in the exam!
