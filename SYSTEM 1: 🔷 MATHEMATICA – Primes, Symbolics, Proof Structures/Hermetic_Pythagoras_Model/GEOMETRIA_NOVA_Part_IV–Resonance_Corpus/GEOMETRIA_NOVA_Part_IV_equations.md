# GEOMETRIA NOVA · Part IV — Resonance Corpus · Equations

## P14 — ϕ-Resonance Spiral / Logarithmic Growth

| Deutsch | English |
|:--|:--|
| $$ r(\theta) = r_0 e^{k\theta}, \quad k = \ln(\varphi) $$<br/>Diskrete Frames: $$\theta_n = n\Delta\theta, \quad r_n = r_0\,\varphi^{n\Delta\theta}$$<br/>**Interpretation:** Jeder Frame ist ein Quadrat-Layer; die Gegenrotation erzeugt den Fibonacci-Pfad. | $$ r(\theta) = r_0 e^{k\theta}, \quad k = \ln(\varphi) $$<br/>Discrete frames: $$\theta_n = n\Delta\theta, \quad r_n = r_0\,\varphi^{n\Delta\theta}$$<br/>**Meaning:** Each frame forms a square-layer; counter-rotation yields Fibonacci tiling. |

| Deutsch | English |
|:--|:--|
| **Fibonacci-Relation**<br/>$$ F_{n+1}=F_n+F_{n-1}, \quad \varphi = \lim_{n\to\infty} \frac{F_{n+1}}{F_n} $$<br/>Layer-Skalierung: $$s_n \propto F_n$$, Bogenradien: $$R_n \propto F_n$$ | **Fibonacci relation**<br/>$$ F_{n+1}=F_n+F_{n-1}, \quad \varphi = \lim_{n\to\infty} \frac{F_{n+1}}{F_n} $$<br/>Layer scaling: $$s_n \propto F_n$$, arc radius: $$R_n \propto F_n$$ |

| Deutsch | English |
|:--|:--|
| **Torus-Atem (Makro-Analogon)**<br/>$$r(t)=r_0(1+\epsilon\sin\omega t)$$<br/>$$V(t)=2\pi^2 R r(t)^2$$ | **Torus breathing (macro analogy)**<br/>$$r(t)=r_0(1+\epsilon\sin\omega t)$$<br/>$$V(t)=2\pi^2 R r(t)^2$$ |

---

## P15 — Kreuz der Kräfte / Cross of Forces

| Deutsch | English |
|:--|:--|
| **Basisfelder**<br/>$$\mathbf{X}=(\alpha,0), \; \mathbf{Y}=(0,\beta), \; \mathbf{D}_\pm=(1,\pm 1)$$<br/>Kopplung (\(\gamma\)) entlang der Diagonalen. | **Base fields**<br/>$$\mathbf{X}=(\alpha,0), \; \mathbf{Y}=(0,\beta), \; \mathbf{D}_\pm=(1,\pm 1)$$<br/>Coupling (\(\gamma\)) along diagonals. |

| Deutsch | English |
|:--|:--|
| **Linearisiert:**<br/>$$\dot{\mathbf{u}} = A\mathbf{u}, \quad A = \begin{pmatrix}\alpha & \gamma \\ \gamma & \beta\end{pmatrix}$$<br/>Eigenwerte: $$\lambda_{\pm} = \tfrac{\alpha+\beta}{2} \pm \sqrt{(\tfrac{\alpha-\beta}{2})^2 + \gamma^2}$$ | **Linearized dynamics:**<br/>$$\dot{\mathbf{u}} = A\mathbf{u}, \quad A = \begin{pmatrix}\alpha & \gamma \\ \gamma & \beta\end{pmatrix}$$<br/>Eigenvalues: $$\lambda_{\pm} = \tfrac{\alpha+\beta}{2} \pm \sqrt{(\tfrac{\alpha-\beta}{2})^2 + \gamma^2}$$ |

| **Deutsch** | **English** |
|---|---|
| **Energiefluss:** $\dot E \sim \mathbf u^{\mathsf T} A^{\mathsf T} \mathbf u$  <br/> **Stabilität, wenn** $\Re(\lambda_{\pm}) \le 0$ | **Energy flux:** $\dot E \sim \mathbf u^{\mathsf T} A^{\mathsf T} \mathbf u$  <br/> **Stable if** $\Re(\lambda_{\pm}) \le 0$ |
---

## P16 — Beobachter-Dualität / Observer Duality

| Deutsch | English |
|:--|:--|
| **Zwei Seiten des Blatts:**<br/>Vorderseite $$z=x+iy$$, Rückseite $$\bar{z}$$.<br/>Orientierungswechsel: $$\mathcal{R}: z \mapsto \bar{z}$$<br/>Rotation: $$\mathcal{U}_\theta: z \mapsto e^{i\theta}z$$ | **Two-sheet model:**<br/>Front: $$z=x+iy$$, back: $$\bar{z}$$.<br/>Reflection: $$\mathcal{R}: z \mapsto \bar{z}$$<br/>Rotation: $$\mathcal{U}_\theta: z \mapsto e^{i\theta}z$$ |

| Deutsch | English |
|:--|:--|
| **Schattenabbildung:** $$\pi(z)=\Re(e^{-i\phi}z)$$<br/>Schattenpfad: $$s(t)=\pi(e^{i\omega t}z_0)$$<br/>Phase/Winkel steuern sichtbare Geometrie. | **Shadow projection:** $$\pi(z)=\Re(e^{-i\phi}z)$$<br/>Shadow path: $$s(t)=\pi(e^{i\omega t}z_0)$$<br/>Phase and angle control visible geometry. |

---

## Volumen & Slicing (für Galerieobjekte) / Volume & Slicing (for Gallery Objects)

| Deutsch | English |
|:--|:--|
| **Torus:** $$V=2\pi^2Rr^2,\; A=4\pi^2 R r$$<br/>**Kugel:** $$V=\tfrac{4}{3}\pi R^3$$<br/>**Cavalieri-Prinzip:** Gleichheit der Querschnittsflächen $$A_z$$ ⇒ Gleichheit der Volumina $$V=\int A_z\,dz$$ | **Torus:** $$V=2\pi^2Rr^2,\; A=4\pi^2 R r$$<br/>**Sphere:** $$V=\tfrac{4}{3}\pi R^3$$<br/>**Cavalieri principle:** Equal cross-sections $$A_z$$ imply equal volume $$V=\int A_z\,dz$$ |

---

## Resonance Corpus Summary

Unified field relation:
$$ P \cdot T = R $$

**Pulse (P):** Spiral step rate (φ scaling)  
**Time (T):** Frame duration between steps  
**Resonance (R):** Stable harmonic pattern across layers
