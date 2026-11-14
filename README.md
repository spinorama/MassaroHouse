# Massaro House (Petra Island, Lake Mahopac, NY) — 4-Mode WebXR Experience

Interactive 3D, Virtual Reality (Meta Quest), 1:1 Augmented Reality, and Tabletop Dollhouse AR architectural experience of the **Massaro House** on **Petra Island, Lake Mahopac, New York** (`41.3765° N, 73.7364° W`) — built natively via the **Blender MCP** (`v1.0.0`, calibrated to the exact `134.55 m × 129.75 m` aerial site extents at `0.15 m/px`).

- **Live WebXR App:** [https://spinorama.github.io/MassaroHouse/](https://spinorama.github.io/MassaroHouse/)
- **Source Scene & Asset:** [`massaro_house.blend`](./massaro_house.blend) · [`massaro_house.glb`](./massaro_house.glb) (`2.12 MB`)
- **Version History:** [CHANGELOG.md](./CHANGELOG.md)

---

## 🏛️ Architectural Scope (`Set_house` Hierarchy)

- **`House_Group` (312 nodes):** Stepped Cherokee-red radiant slabs (`Z = 3.20 m` cantilevered SW living prow + `Z = 3.80 m` upper split-level wing), deep under-deck concrete girders, shoreline masonry piers, glass parapet balconies, monument double-sided Hudson granite fireplace & glowing hearth, integrated Whale Rock, Tail Rock & Bathroom Boulder outcrops, full-height African mahogany curtain walls & clerestories, bespoke Wrightian furniture (baby grand piano, banquettes, barrel armchairs, circular dining set, glowing Taliesin lamps, master platform bed, soaking tub & frameless shower), plus subtle minimalist blocky cat relief gallery panels & hearth sculpture (`m_cat_art_vcol`).
- **`Roof_Group` (232 nodes):** Cantilevered Wrightian concrete roof ring (`Z = 7.48–8.05 m`), mahogany interior soffits, 27 triangular coffered mahogany & glass skylight pyramids, circular `H` Helipad, US Flag deck inlay, and mechanical hatch — cleanly toggleable via `🏠 Roof`.
- **`Context_Group` (81 nodes):** Lake Mahopac reflective water surface, vertex-color blended Petra Island granite shoreline & emerald lawn clearing, coastal granite boulders, timber pile pier, covered boathouse slip & moored V-hull runabout boat, stepped arrival promenade, bluestone walkway, **1951 Frank Lloyd Wright Chahroudi Guest Cottage** (diamond cedar-shingle hipped roof, dual chimneys, ribbon glass, interior furnishings & hexagonal terrace), NE outbuildings & trailered boat, and ~120 faceted woodland trees batched into 4 WebXR-fast groves — cleanly toggleable via `🌳 Context`.
- **`Waypoints_Group` & `Cameras_Group` (18 presets):** Full tour spanning `01 · Ext Three-Quarter` through `18 · Aerial Extents`.

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
