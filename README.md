# Massaro House & 1951 Chahroudi Cottage (Petra Island, NY) — WebXR, ISO 19650 BIM & Architectural Drawing Set

Complete digital twin, **4-Mode Interactive WebXR Experience**, **ISO 19650 / IFC4 Contractor BIM Coordination Viewer**, and **10-Sheet Architectural Construction Drawing Set (`A-000` to `A-501`)** of the **Massaro House** and the **1951 Frank Lloyd Wright Chahroudi Guest Cottage** on **Petra Island, Lake Mahopac, New York** (`41.3765° N, 73.7364° W`) — built natively via the **Blender MCP** (`v2.0.0`, calibrated to the exact `134.55 m × 129.75 m` aerial site extents at `0.15 m/px`).

---

## 🚀 Live Interactive Deliverables

| Deliverable | URL / Path | Standards & Capabilities |
| :--- | :--- | :--- |
| **1. 4-Mode WebXR Experience** | [**`index.html`**](https://spinorama.github.io/MassaroHouse/) | `3D View`, `Quest VR`, `1:1 AR Walk`, `Tabletop AR`, `Roof/Context` cutaways, `DIN 1451 / LCARS` telemetry |
| **2. Contractor BIM Coordination Viewer** | [**`bim.html`**](https://spinorama.github.io/MassaroHouse/bim.html) | `ISO 19650-2 (S4 · Rev P02.1)` · `IFC4 ADD2 TC1` · `834` federated elements · CSI MasterFormat 2020 trade filters · 6-plane Section Box · Laser Tape Measure · `.IFC` & `.CSV` BOQ export |
| **3. Architectural Construction Drawing Set** | [**`drawings/index.html`**](https://spinorama.github.io/MassaroHouse/drawings/index.html) | 10 contractor-grade Vector SVG CAD sheets (`A-000` through `A-501`) with pan/zoom blueprint binder, 30°/60° FLW grids, sections, details & QTO schedules |
| **4. Federated BIM Metadata & Assets** | [`massaro_bim_metadata.json`](./massaro_bim_metadata.json) · [`massaro_house.glb`](./massaro_house.glb) · [`massaro_house.blend`](./massaro_house.blend) | `834` mesh elements (`858` total scene nodes including `18` cameras & `18` waypoints) |
| **5. Verification Renders & Archival Plates** | [`renders/`](./renders/) (`9` renders) · [`reference/`](./reference/) (`21` plates) | Cycles/EEVEE verification renders (`01`–`09`) & historical reference photography (`00`–`20`) |

---

## 🏗️ ISO 19650 / IFC4 Contractor BIM Viewer (`bim.html`)

Designed as a Common Data Environment (CDE) deliverable (`MAS-THH-ZZ-ZZ-M3-A-0001`, Suitability `S4 — For Construction Coordination`, Revision `P02.1`):

- **IFC4 Spatial Hierarchy (`IfcProject -> IfcSite -> IfcBuilding -> IfcBuildingStorey`):**
  - `BLDG-01` — Massaro Main Residence (FLW 1949 / Thomas A. Heinz, AIA 2003–2007)
  - `BLDG-02` — 1951 Frank Lloyd Wright Chahroudi Guest Cottage
  - `BLDG-03` — Helipad, Timber Boat Dock & Island Outbuildings
  - `SITE-01` — Petra Island Granite Bedrock, Lake Mahopac & Deciduous Forest
  - Storeys `L00` (`-4.0m..+1.5m`), `L01` (`+1.5m..+3.1m`), `L02` (`+3.1m..+4.5m`), `L03` (`+4.5m..+6.8m`), `L04` (`+6.8m..+9.0m`)
- **18 IFC4 Entity Classes:** `IfcWall`, `IfcSlab`, `IfcRoof`, `IfcBeam`, `IfcFooting`, `IfcCurtainWall`, `IfcWindow`, `IfcDoor`, `IfcMember`, `IfcChimney`, `IfcStairFlight`, `IfcRailing`, `IfcFurnishingElement`, `IfcSanitaryTerminal`, `IfcElectricAppliance`, `IfcLightFixture`, `IfcCivilElement`, `IfcGeographicElement`.
- **CSI MasterFormat 2020 Subcontractor Trade Packages:** One-click isolation and quantity rollups for `Div 03` Concrete, `Div 04` Desert Rubblestone Masonry, `Div 05` Structural Steel, `Div 06` Rough Carpentry & Custom Mahogany/Cherry Architectural Woodwork, `Div 07` Patinated Copper Roofing & 26 Skylights, `Div 08` Mahogany Curtain Wall Glazing, `Div 11` Appliances, `Div 12` Built-in Wrightian Furnishings, `Div 22` Plumbing, `Div 26` Lighting, `Div 31` Granite Bedrock Integration, and `Div 32/35` Marine Docks.
- **6 Federation Color Modes:** `PBR Realistic`, `By IFC4 Class`, `By CSI Trade`, `By Storey`, `By ISO 19650 Discipline`, and `CAD Wireframe`.
- **Interactive 6-Plane 3D Section Box & Laser Tape Measure `[M]`:** Live X/Y/Z clipping planes with architectural cut presets (`Plan Cut L02 +4.3m`, `Plan Cut L01 +2.8m`, `Section A-A`, `Section B-B`, `Cottage Cutaway`) and point-to-point 3D laser measurement ($\Delta X, \Delta Y, \Delta Z$ in metric & `ft'-in"`).
- **Right-Docked IFC4 Property Inspector & Bottom Live BOQ Schedule:** Inspect `Pset_ISO19650_Identification`, `Pset_Classification` (`CSI`, `Uniformat II`, `Uniclass 2015`), and `Qto_ElementBaseQuantities`, and export `.IFC` (ISO 10303-21 STEP) or `.CSV` (Excel BOQ) directly from the browser.

---

## 📐 Full Architectural Construction Drawing Set (`drawings/`)

Interactive blueprint sheet binder ([`drawings/index.html`](./drawings/index.html)) containing 10 vector SVG sheets generated directly from the calibrated Blender BIM geometry:

1. **[`A-000_Cover_Index.svg`](./drawings/A-000_Cover_Index.svg)** — Cover Sheet, Drawing Index, ISO 19650 Metadata Matrix, Symbols Legend & CSI Summary
2. **[`A-100_Master_Site_Plan.svg`](./drawings/A-100_Master_Site_Plan.svg)** — Petra Island Master Site & Roof Plan (`1:500`, `134.55m × 129.75m` extents, grid, contours, Main House, 1951 Cottage, Helipad & Docks)
3. **[`A-101_Main_Floor_Plan.svg`](./drawings/A-101_Main_Floor_Plan.svg)** — Main Residence Level `L01/L02` Architectural Floor Plan (`1:100`, 30°/60° triangular grid, Whale Rock & Entry Boulder penetrations, 6 stone piers, room schedule & dimensions)
4. **[`A-102_Roof_Skylight_Plan.svg`](./drawings/A-102_Roof_Skylight_Plan.svg)** — Main Residence Roof Framing, Patinated Copper Fascia & 26-Skylight Matrix Plan (`1:100`)
5. **[`A-103_Reflected_Ceiling_Plan.svg`](./drawings/A-103_Reflected_Ceiling_Plan.svg)** — Main Residence Reflected Ceiling & Lighting Plan (`1:100`, mahogany soffits, recessed coves & 6 triangular chandeliers)
6. **[`A-104_Chahroudi_Cottage_Plans.svg`](./drawings/A-104_Chahroudi_Cottage_Plans.svg)** — 1951 FLW Chahroudi Guest Cottage Floor Plan, Cathedral Rafter Framing Plan & Exterior Elevations (`1:50`)
7. **[`A-201_Exterior_Elevations.svg`](./drawings/A-201_Exterior_Elevations.svg)** — Exterior Building Elevations: South Lakefront, West Prow Cantilever, North Arrival & East Elevation (`1:125`)
8. **[`A-301_Building_Sections.svg`](./drawings/A-301_Building_Sections.svg)** — Longitudinal Section `A-A` (8.5m SW Cantilever Prow) & Transverse Section `B-B` (Entry Rock Steps & Skylight Wells) (`1:100`)
9. **[`A-401_Interior_Elevations_Details.svg`](./drawings/A-401_Interior_Elevations_Details.svg)** — Enlarged Interior Architectural Details: Entry Foyer Rock Steps, Great Room Inglenook & Chandeliers, Curved Cherry Kitchen Island, Primary Bath Copper Tub & Bedrock Wall (`1:25`)
10. **[`A-501_BIM_Schedules_QTO.svg`](./drawings/A-501_BIM_Schedules_QTO.svg)** — ISO 19650 / IFC4 Element Schedules, CSI Division Take-Off & Storey Quantities (`N.T.S.`)

---

## 🥽 4-Mode Interactive WebXR Experience (`index.html`)

- **🖥️ Mode 1 · 3D View (Desktop & Phone Browser):** Orbit, pan, zoom, and fly (`WASD` + `E/Q`) across 18 curated architectural camera stations.
- **🥽 Mode 2 · Quest VR (`immersive-vr`):** Controller laser teleportation across all interior decks, roof terraces, and island trails.
- **📱 Mode 3 · 1:1 AR Walk (`immersive-ar`):** Full-scale 1:1 walkthrough anchored to your physical space.
- **🏡 Mode 4 · Tabletop AR (`immersive-ar` Dollhouse):** Interactive tabletop scale model of Petra Island with pinch-to-scale and 1-finger rotation.
- **🎛️ Architectural Toggles:** `🏠 Roof` (`Roof_Group`), `🌳 Context` (`Context_Group`), `✏️ Lines [L]` (Hidden-Line CAD), and `📐 Style [T]` (`DIN 1451` vs `Star Trek LCARS`).
