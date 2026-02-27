# GEOMETRIA NOVA · Part IV — Resonance Corpus · Equations

## P14 — ϕ-Resonance Spiral / Logarithmic Growth

### Logarithmic Spiral
$$ r(\theta) = r_0 e^{k\theta}, \quad k = \ln(\varphi) $$

Discrete frames:
$$ \theta_n = n\Delta\theta, \quad r_n = r_0\,\varphi^{n\Delta\theta} $$

**Meaning:** Each frame forms a square layer; counter-rotation yields Fibonacci tiling.

### Fibonacci Relation
$$ F_{n+1}=F_n+F_{n-1}, \quad \varphi = \lim_{n\to\infty} \frac{F_{n+1}}{F_n} $$

Layer scaling: $$s_n \propto F_n$$  
Arc radius: $$R_n \propto F_n$$

### Torus Breathing (Macro Analogy)
$$ r(t)=r_0(1+\epsilon\sin\omega t), \qquad V(t)=2\pi^2 R r(t)^2 $$

Radial oscillation models harmonic pulsation of φ layers.

---

## P15 — Cross of Forces

### Base Fields
$$ \mathbf{X}=(\alpha,0), \; \mathbf{Y}=(0,\beta), \; \mathbf{D}_\pm=(1,\pm 1) $$
Coupling (\(\gamma\)) along diagonals.

### Linearized Dynamics
$$ \dot{\mathbf{u}} = A\mathbf{u}, \quad A = \begin{pmatrix}\alpha & \gamma \\ \gamma & \beta\end{pmatrix} $$

Eigenvalues:
$$ \lambda_{\pm} = \tfrac{\alpha+\beta}{2} \pm \sqrt{\left(\tfrac{\alpha-\beta}{2}\right)^2 + \gamma^2} $$

### Energy Flux
$$ \dot E \sim \mathbf{u}^{\mathsf T} A^{\mathsf T} \mathbf{u} $$

Stable if: $$ \Re(\lambda_{\pm}) \le 0 $$

---

## P16 — Observer Duality

### Two-Sheet Model
Front: $$z = x + iy$$, Back: $$\bar{z}$$.  
Reflection: $$\mathcal{R}: z \mapsto \bar{z}$$  
Rotation: $$\mathcal{U}_\theta: z \mapsto e^{i\theta}z$$

### Shadow Projection
$$ \pi(z) = \Re(e^{-i\phi}z) $$

Shadow path: $$ s(t) = \pi(e^{i\omega t} z_0) $$

Phase and angle control visible geometry and perceived oscillation.

---

## Volume & Slicing (for Gallery Objects)

### Torus
$$ V = 2\pi^2 R r^2, \quad A = 4\pi^2 R r $$

### Sphere
$$ V = \tfrac{4}{3}\pi R^3 $$

### Cavalieri Principle
Equal cross-sections $$A_z$$ imply equal volume:
$$ V = \int A_z\,dz $$

---

## Resonance Corpus Summary

Unified field relation:
$$ P \cdot T = R $$

**Pulse (P):** Spiral step rate (φ scaling)  
**Time (T):** Frame duration between steps  
**Resonance (R):** Stable harmonic pattern across layers
