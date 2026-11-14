# Massaro House (Petra Island, Lake Mahopac, NY) — 4-Mode WebXR Experience

Interactive 3D, Virtual Reality (Meta Quest), 1:1 Augmented Reality, and Tabletop Dollhouse AR architectural experience of the **Massaro House** on **Petra Island, Lake Mahopac, New York** — built natively via the **Blender MCP** to the exact `135 m × 130 m` aerial site extents (`v0.1.0` progressive build).

- **Live WebXR App:** [https://spinorama.github.io/MassaroHouse/](https://spinorama.github.io/MassaroHouse/)
- **Version History:** [CHANGELOG.md](./CHANGELOG.md)

---

## ✨ Features & 4 Viewing Modes

1. **🖥️ Mode 1 · 3D View (Desktop & Phone Browser)**
   - **Phone / Touch:** **1-finger drag** orbits 360° around the current space's focal target, **2-finger pinch** zooms smoothly in and out, and **2-finger drag** pans.
   - **Desktop:** Left-drag look, right-drag (or `Shift`+drag) pan, scroll wheel zoom, and `WASD` / Arrow keys + `E`/`Q` vertical fly.
2. **🥽 Mode 2 · Quest VR (`immersive-vr`)**
   - Aim controller laser at any floor, deck, terrace, dock, or terrain surface to reveal the cyan teleport reticle and pull Trigger/Grip to teleport, or walk with the left thumbstick and snap-turn with the right thumbstick.
3. **📱 Mode 3 · 1:1 AR Walk (`immersive-ar`)**
   - Full-scale 1:1 architectural walkthrough in your physical space. Tap any room pill to re-anchor yourself inside that space at 1:1 scale.
4. **🏡 Mode 4 · Tabletop AR (`immersive-ar` Dollhouse)**
   - Scales the entire Petra Island estate (`135 m × 130 m` extents including Lake Mahopac shoreline, main cantilevered residence, dock, and 1951 Chahroudi Guest Cottage) to fit your table or screen. Use **2-finger pinch** to smoothly change scale and **1-finger drag** to rotate.

---

## 🎛️ Architectural Controls

- **🏠 Roof (`Roof_Group`):** Toggle the cantilevered roof fascia, 27 triangular skylight coffers, helipad, and interior ceilings on/off for a Dollhouse cutaway view.
- **🌳 Context (`Context_Group`):** Toggle Lake Mahopac water, Petra Island outer terrain, boat dock, 1951 Chahroudi Guest Cottage, outbuildings, and woodland canopy on/off.
- **✏️ Lines (`[L]` Hotkey):** Toggle subtle **Hidden-Line CAD rendering** (`EdgesGeometry` architectural linework over warm paper-tinted surfaces).
- **📐 Style (`[T]` Hotkey):** Switch between **German DIN 1451 E-Ink Technical Specification** (default) and **Star Trek LCARS Telemetry** with procedural Web Audio sound effects.
- **📋 Changelog Modal:** Inspect progressive Blender MCP construction milestones live in-app.
