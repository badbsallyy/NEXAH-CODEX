# GEOMETRIA NOVA · Teil IV — Equations

## P14 — φ‑Resonanzspirale

1. **Logarithmische Spirale (goldene Form)**  
   \[ r(\theta) = r_0\,e^{k\theta},\qquad k=\ln(\varphi) \]
   Diskrete Frames \(n\in\mathbb{N}\): \(\theta_n = n\Delta\theta\), \(r_n=r_0\,\varphi^{n\Delta\theta}\).  
   **Interpretation:** Jeder Frame ist ein Quadrat‑Layer; die **Gegenrotation** nach jedem Schritt erzeugt den
   bekannten Fibonacci‑Kachelpfad (Bögen als Kreissegmente).

2. **Fibonacci‑Relation**  
   \(F_{n+1}=F_n+F_{n-1}\), \(\varphi = \lim_{n\to\infty} \frac{F_{n+1}}{F_n}\).  
   **Layer‑Skalierung:** \(s_n \propto F_n\); **Bogenradien:** \(R_n\propto F_n\).

3. **Torus‑Atem (Makro‑Analogon)**  
   Torus: Haupt‑/Nebenradius \(R>r>0\). Atemmodulation:  
   \(r(t)=r_0\left(1+\epsilon\sin\omega t\right)\).  
   **Volumen:** \(V(t)=2\pi^2 R\,r(t)^2\).

---

## P15 — Kreuz der Kräfte

1. **Basisfelder**  
   \(\mathbf{X}=(\alpha,0),\ \mathbf{Y}=(0,\beta)\) mit Kopplung \(\gamma\) entlang der Diagonalen
   \(\mathbf{D}_\pm=(1,\pm 1)\).

2. **Gekoppelte Dynamik (linearisiert)**  
   \[ \dot{\mathbf{u}} = A\,\mathbf{u},\qquad 
      A=\begin{pmatrix}\alpha & \gamma \\ \gamma & \beta\end{pmatrix} \]
   Eigenwerte \( \lambda_{\pm} = \tfrac{\alpha+\beta}{2} \pm \sqrt{\left(\tfrac{\alpha-\beta}{2}\right)^2+\gamma^2}\).  
   **Deutung:** \(\gamma\neq 0\) erzeugt *Drift/Rotation* entlang der Diagonalen (Resonanzpfade).

3. **Energiefluss (Skizze)**  
   \( \dot E \sim \mathbf{u}^\top A^\top \mathbf{u}\). Stabilität erfordert \(\operatorname{Re}\lambda_\pm\le 0\).

---

## P16 — Beobachter‑Dualität (komplexe Ebene)

1. **Zwei Seiten des Blatts**  
   Sicht auf \(z=x+iy\) (Vorderseite) vs. \(\bar z\) (Rückseite).  
   **Orientierungswechsel:** \( \mathcal{R}: z \mapsto \bar z \) (Spiegel);  
   **Rotation:** \( \mathcal{U}_\theta: z \mapsto e^{i\theta}z\).

2. **Schattenabbildung**  
   Projektion \( \pi: \mathbb{C}\to\mathbb{R}\), z. B. \( \pi(z)=\Re(z) \) oder \( \pi_\phi(z)=\Re(e^{-i\phi}z)\).  
   **“Shadow path”**: \( s(t)=\pi( e^{i\omega t} z_0 )\) — Phase/Winkel steuern die sichtbare Geometrie.

---

## Volumen & Slicing (für die Galerieobjekte)

- **Torus:** \(V=2\pi^2Rr^2\), \(A=4\pi^2 R r\).
- **Kugel:** \(V=\tfrac{4}{3}\pi R^3\).  
- **Cavalieri‑Prinzip:** Gleichheit der Querschnittsflächen \(A_z\) \(\Rightarrow\) Gleichheit der Volumina \(V=\int A_z\,dz\).

**Hinweis.** Die Formeln sind minimal‑suffizient für die in Teil IV gelieferten Visuals/GLBs und lassen
sich in Teil V/VI (Humanoid Platonics, V‑Ether) erweitern.

## Resonance Corpus · Equations

- Log spiral (phi-scaled): \(\; r(\theta)=r_0\,\varphi^{\theta/(2\pi)} \;\)
- Cross-of-Forces basis: orthogonal unit axes \( \hat{x},\hat{y} \) with phase \(\phi_q\in\{0,\pi/2,\pi,3\pi/2\}\)
- Observer channel (II): sheet index \(s\in\{+1,-1\}\), puncture linking the sheets ⇒ measurable flip when \(R\) exceeds threshold
- **Time–frequency law:** \( P\,T = R \) (module-normalized)


# Resonance Corpus (P14–P16)

This closing section binds the Part IV visuals (spiral, cross of forces, observer duality) to the proof architecture and the time–frequency relation **PT = R**.

## What each GLB/GIF encodes

- **P14 – Phi Resonance Spiral** (`P14_phi_resonance_spiral.glb` / `.gif`)
  - Continuous logarithmic growth with **counter-rotating square steps** (Fibonacci tiling) – shows that a spiral is *time-layered curvature*, not merely a static arc.
  - Maps to *Corollaries* in the proof-temple: openings where time (T) and pulse (P) inject resonance (R).

- **P15 – Cross of Forces** (`P15_cross_of_forces.glb` / `.gif`)
  - Orthogonal axes with phase-locked quadrants; use it as the **momentary frame** onto which spirals attach.
  - Maps to *Lemmata*: stabilizers that carry constraints along the axes.

- **P16 – Observer Duality** (`P16_observer_duality.glb` / `.gif`)
  - Two-sided sheet (front/back) + a linking puncture (the compass pinhole) — the **II-channel** between observed and applied side.
  - Maps to *Axioms*: the pre-conditions of any viewing/measurement act.

- **Layered Combo (optional)** (`P14_P16_layers.glb`, `P14_P16_merged_static.gltf`, `P14_P16_merged_animated.gltf`)
  - Stack for presentations: toggle or animate to show build-up from spiral → cross → observer.

## Unifying relation

\[
P\cdot T = R
\]

- **P (Pulse / Frequency):** spiral step-rate (Fibonacci cadence → φ-scaling).
- **T (Time):** frame duration between steps (visible in the GIFs / animation).
- **R (Resonance):** stable pattern that survives across layers (GLB combo).

> In practice: if you halve the spiral’s step time \(T\) while keeping pulse \(P\) fixed, you double the injected resonance \(R\) until the cross (P15) saturates; beyond that, the observer channel (P16) flips side (II) and re-locks phase.

## Referencing in papers/talks

- **Static papers:** embed `P14_phi_resonance_spiral.png` and one frame from `P15` and `P16`.
- **Talks:** switch to `P14_P16_merged_animated.gltf` for a live build-up.
- **Interactive exhibits:** provide `P14_P16_layers.glb` with scene toggles.

