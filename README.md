# Massaro House (Petra Island, Lake Mahopac, NY) — 4-Mode WebXR Experience

Interactive 3D, Virtual Reality (Meta Quest), 1:1 Augmented Reality, and Tabletop Dollhouse AR architectural experience of the **Massaro House** and the **1951 Frank Lloyd Wright Chahroudi Guest Cottage** on **Petra Island, Lake Mahopac, New York** (`41.3765° N, 73.7364° W`) — built natively via the **Blender MCP** (`v1.2.0`, calibrated to the exact `134.55 m × 129.75 m` aerial site extents at `0.15 m/px`).

- **Live WebXR App:** [https://spinorama.github.io/MassaroHouse/](https://spinorama.github.io/MassaroHouse/)
- **Source Scene & Asset:** [`massaro_house.blend`](./massaro_house.blend) (`0.99 MB`) · [`massaro_house.glb`](./massaro_house.glb) (`3.39 MB`)
- **Archival Reference & Blender Renders:** [`reference/`](./reference/) (`21` plates) · [`renders/`](./renders/) (`9` verification renders)
- **Version History:** [CHANGELOG.md](./CHANGELOG.md)

---

## 🏛️ Architectural Scope (`Set_house` Hierarchy — 858 Objects)

- **`House_Group` (421 nodes):** Stepped Cherokee-red radiant slabs (`Z = 3.20 m` cantilevered SW living prow + `Z = 3.80 m` upper split-level wing), deep under-deck concrete girders, desert-rubble stone piers & walls with procedural 3D embedded angular fieldstones, monument double-sided fireplace, stepped pale-granite Whale Rock, Kitchen Boulder, Study Boulder & Bathroom Boulder Cascade, full-height African mahogany curtain walls & clerestories, and photo-accurate interiors:
  - **Cantilevered Great Room:** Hexagonal Usonian geometric rugs, 14 m cream lakeside banquette with under-seat LED cove & triangular end tables, recessed triangular ceiling downlights, prow easel canvas, barrel armchairs, and baby grand piano.
  - **27-Skylight Atrium & Entry:** Built-in banquette, hexagonal side tables, cantilevered Whale-Rock bar shelf, 4.4 m **Japanese Pine & Crane Screen Mural**, and suspended bronze ceremonial gong.
  - **Whale-Rock Kitchen & Dining:** Scribed bluestone counters, **5 red Le Creuset Dutch ovens & skillets** on the rock shelf, red mosaic tile backsplash, flush mahogany cabinets, boat-shaped dining table with **8 tall slatted-back FLW chairs**, buffet credenza, and Wrightian chandelier.
  - **Master Suite, Rock Shower Bath & Study:** Full-width mahogany headboard credenza with warm LED uplight over stacked fieldstone, corner stone hearth, diagonal mahogany tray ceiling, crimson silk bed, tall cutout-back Wright chair, and frameless glass shower with frosted FLW chevron motif.
- **`Roof_Group` (252 nodes):** Patinaed standing-seam bronze/copper roof fascia (`Mat_Copper_Fascia`), cantilevered roof ring (`Z = 7.48–8.05 m`), mahogany interior soffits, 27 stepped concrete & mahogany coffered skylight pyramids, circular `H` Helipad, US Flag deck inlay, plus the **Chahroudi Guest Cottage hipped shingle roof & 30+ exposed hexagonal timber rafters** — all cleanly toggleable via `🏠 Roof` for a dual-house Dollhouse cutaway.
- **`Context_Group` (161 nodes):**
  - **1951 FLW Chahroudi Guest Cottage (Exterior & Full Interior):** Battered desert-rubble wing & planter walls with 3D fieldstones, 4 mahogany French doors, glowing spherical globe eave pendant, 3-step Cherokee-red terrace with triangular reflection pool & sculpted wood lounge chairs; interior with monumental battered concrete fireplace hood & embedded gold granite slab, 2 X-frame cord-slung Wright chairs, polygonal dining table, board-and-batten partition with framed window, folding accordion doors to the bedroom alcove, and galley kitchen with hexagonal stained-glass window & vintage red stove.
  - **Petra Island & Lake Mahopac:** Vertex-blended granite shoreline & emerald lawn clearing, coastal boulders, timber pile pier, covered boathouse slip & moored V-hull runabout boat, stepped arrival promenade, bluestone walkway, NE outbuildings & trailered boat, and ~120 faceted woodland trees batched into 4 WebXR-fast groves — cleanly toggleable via `🌳 Context`.
- **`Waypoints_Group` & `Cameras_Group` (18 presets):** Full tour spanning `01 · Ext Three-Quarter` through `18 · Aerial Extents` (including dedicated `15 · 1951 Chahroudi Ext` and `16 · 1951 Chahroudi Int` viewpoints).

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
