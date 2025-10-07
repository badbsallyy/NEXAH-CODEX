# GEOMETRIA NOVA · Teil IV — Resonanz‑Platonics & Dynamische Volumina

**Scope.** Teil IV schließt den Bogen von P1–P16: von der Ebene zur Dynamik. Wir übersetzen die Postulate **P14–P16**
in *bewegte* Geometrie (GIF/GLB) und koppeln sie an Volumina, Schnitte und Topologie.

- **P14 – φ‑Resonanzspirale.** Fibonacci‑Schichtung als Zeit‑Sequenz (Frames → Frequenz). Ergebnis: *Spiral‑Layer*,
  die als Torus‑Atem gelesen werden können (Innen–Außen‑Wechsel).
- **P15 – Kreuz der Kräfte.** Zwei orthogonale Vektorfelder \(X,Y\) plus *diagonale Kopplungen*. Ergebnis:
  eine minimale Kopplung von Antrieb/Rotation/Drift.
- **P16 – Beobachter‑Dualität.** Innen/außen, Blattvorder‑/rückseite; Modellierung via komplexer Ebene
  \(z=x+iy\) und Spiegel \(\bar z\). Ergebnis: *Schatten‑/Licht‑Pfad* als Orientierung des Beweises.

Zusätze (optional sichtbar in der Galerie):

- **Torus‑Breathe (φ‑Atem):** periodische Verdickung/Verjüngung des Torus als makroskopisches Pendant zu P14.
- **Topologische Skizzen:** Kugel↔Torus (Lochzahl \(g\)), Slicing (Cavalieri), Schicht‑Animationen.

**Dateien in diesem Modul** (Auswahl):
- `P14_phi_resonance_spiral.gif / .png / .obj / .glb`
- `P15_cross_of_forces.gif / .obj / (optional .glb)`
- `P16_observer_duality.gif / .obj / (optional .glb)`
- `P14_P16_layers.glb` — *Layered Merge* (für AR/3D‑Demonstration)
- `Visual_Gallery_Part_IV.pdf` — kuratierte Bildübersicht

**Didaktischer Faden.**
1. *Welle → Form:* φ‑Sequenz als Zeitreihe (Frames) statt Standbild ⇒ “Matroschka” der Quadrate/Bögen.
2. *Form → Kopplung:* Kreuz der Kräfte koppelt Richtungen und erzeugt stabilisierte Drift.
3. *Kopplung → Beobachter:* Orientierung (CW/CCW) und Spiegelachse bestimmen, **welche** Seite des Beweises sichtbar wird.
4. *Volumen/Topologie:* Slicing und Genus führen über die reine Metrik hinaus.

**Ausblick.** Teil V bündelt “Humanoid Platonics” (Tetra, Hexa, Okta, Dodeka, Ikosa + Spine) als skulpturale Proof‑Architektur. 
Teil VI skizziert das **V‑Ether** als übergeordnete Schicht (Medien, Stoffe, Feldkopplungen).

*Build:* 2025-09-22T19:06:01.856156Z


---

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

