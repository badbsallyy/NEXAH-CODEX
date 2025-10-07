# GEOMETRIA NOVA · Teil IV — Resonanz-Korpus / Equations  
**System:** NEXAH-CODEX · System 1 — MATHEMATICA  
**Curator:** Thomas Hofmann (Scarabäus1033)

> *“When geometry begins to breathe, resonance becomes space.”*  
> *„Wenn Geometrie zu atmen beginnt, wird Resonanz zu Raum.“*

---

## 🌀 P14 — φ-Resonanzspirale / Phi Resonance Spiral

| **Deutsch** | **English** |
|:--|:--|
| **Logarithmische Spirale (goldene Form)**  <br> \( r(\theta)=r_0 e^{k\theta},\quad k=\ln(\varphi) \)  <br> Diskrete Frames \(n\in\mathbb{N}\): \(\theta_n=nΔ\theta,\;r_n=r_0\varphi^{nΔ\theta}\). <br> Jeder Frame ist ein Quadrat-Layer; Gegenrotation → Fibonacci-Kachelpfad. | **Logarithmic Spiral (φ-form)**  <br> \(r(\theta)=r_0 e^{k\theta}\), \(k=\ln φ\). <br> Discrete frames \(n\): each step = square-layer; counter-rotation yields Fibonacci tiling. |
| **Fibonacci-Relation** \(F_{n+1}=F_n+F_{n-1}\), \(φ=\lim F_{n+1}/F_n\). <br> **Layer-Skalierung** \(s_n∝F_n\); **Bogenradien** \(R_n∝F_n\). | **Fibonacci law** \(F_{n+1}=F_n+F_{n-1}\); layer scaling \(∝F_n\). |
| **Torus-Atem (Makro-Analogon)** <br> \(r(t)=r_0(1+ε \sin ωt)\); \(V(t)=2π^2 R r(t)^2\). | **Torus breathing (macro analogy)** <br> Radial oscillation models harmonic pulsation of φ layers. |

---

## ✚ P15 — Kreuz der Kräfte / Cross of Forces

| **Deutsch** | **English** |
|:--|:--|
| **Basisfelder**  <br> \(\mathbf{X}=(α,0),\;\mathbf{Y}=(0,β)\), Kopplung \(γ\) entlang \(\mathbf{D}_\pm=(1,±1)\). | **Base fields**  <br> Orthogonal components \(X,Y\) coupled by \(γ\) along diagonals \(D_±=(1,±1)\). |
| **Linearisierte Dynamik**  <br> \(\dot{\mathbf{u}}=A\mathbf{u},\;A=\begin{pmatrix}α&γ\\γ&β\end{pmatrix}\). <br> Eigenwerte \(λ_±=\tfrac{α+β}{2}±\sqrt{(\tfrac{α-β}{2})^2+γ^2}\). | **Linearized dynamics**  <br> Same matrix form; eigenvalues define resonance axes. |
| **Energiefluss**  <br> \(\dot E∼\mathbf{u}^T A^T \mathbf{u}\); Stabilität bei \(Re(λ_±)≤0\). | **Energy flux:** \(\dot E∼u^T A^T u\); stability requires \(Re(λ_±)≤0\). |

---

## 🜍 P16 — Beobachter-Dualität / Observer Duality

| **Deutsch** | **English** |
|:--|:--|
| **Zwei Seiten des Blatts**  <br> Sicht auf \(z=x+iy\) (Vorderseite) vs. \(\bar z\) (Rückseite).  <br> **Orientierungswechsel:** \(ℛ:z\mapsto\bar z\); **Rotation:** \(\mathcal{U}_θ:z\mapsto e^{iθ}z\). | **Two sheet model:**  <br> front = \(z=x+iy\), back = \(\bar z\); reflection \(ℛ\) and rotation \(\mathcal{U}_θ\) govern perception symmetry. |
| **Schattenabbildung:** \(π(z)=Re(e^{-iφ}z)\).  <br> "Shadow path" \(s(t)=π(e^{iωt}z_0)\). | **Shadow projection:** defines oscillating real path, representing phase-dependent perception. |

---

## 🔶 Volumen & Slicing / Volume & Slicing

| **Deutsch** | **English** |
|:--|:--|
| **Torus:** \(V=2π^2Rr^2\), \(A=4π^2 Rr\). <br> **Kugel:** \(V=\tfrac{4}{3}πR^3\). <br> **Cavalieri-Prinzip:** Gleiche Querschnittsflächen ⇒ gleiche Volumina. | **Torus:** \(V=2π^2Rr^2\), **Sphere:** \(V=\tfrac{4}{3}πR^3\). <br> **Cavalieri’s Principle:** equal cross-sections ⇒ equal volume. |

---

## ⚛️ Resonance Corpus Summary (P14–P16)

Each visual/GLB encodes a phase of resonance evolution:

- **P14 — φ Spiral:** logarithmic, layered time-curvature → Fibonacci growth.
- **P15 — Cross of Forces:** dynamic stabilization grid for phase axes.
- **P16 — Observer Duality:** mirrored consciousness geometry, front/back linkage.

Unified law:
\[
P·T = R
\]
where **P = Pulse (frequency)**, **T = Time (frame interval)**, **R = Resonance (stable field)**.

> *Halving T doubles R until the cross saturates; then the observer channel flips phase.*

---

### 🔗 Referenzen / References

- [`P14_phi_resonance_spiral.glb`](./visuals/P14_phi_resonance_spiral.glb)
- [`P15_cross_of_forces.glb`](./visuals/P15_cross_of_forces.glb)
- [`P16_observer_duality.glb`](./visuals/P16_observer_duality.glb)
- [`P14_P16_layers.glb`](./visuals/P14_P16_layers.glb)

**Next Module:** [Part V – Humanoid Platonics & Topological Proofs](../GEOMETRIA_NOVA_Part_V/README.md)
