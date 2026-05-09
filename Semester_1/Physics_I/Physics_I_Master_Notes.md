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
