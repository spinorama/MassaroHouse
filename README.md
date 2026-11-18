# Massaro House & 1951 Chahroudi Cottage (Petra Island, NY) — WebXR, ISO 19650 BIM & Redlined Architectural Drawing Set

Complete digital twin, **4-Mode Interactive WebXR Experience**, **ISO 19650 / IFC4 Contractor BIM Coordination Viewer**, and **10-Sheet Redlined Architectural Construction Drawing Set (`A-000` to `A-501`, Rev `P03.1 Δ3`)** of the **Massaro House** and the **1951 Frank Lloyd Wright Chahroudi Guest Cottage** on **Petra Island, Lake Mahopac, New York** (`41.3765° N, 73.7364° W`) — built natively via the **Blender MCP** (`v2.1.0`, `903` IFC4 mesh elements calibrated to the `134.55 m × 129.75 m` aerial site extents at `0.15 m/px`).

---

## 🚀 Live Interactive Deliverables

| Deliverable | URL / Path | Standards & Capabilities |
| :--- | :--- | :--- |
| **1. 4-Mode WebXR Experience** | [**`index.html`**](https://spinorama.github.io/MassaroHouse/) | `3D View`, `Quest VR`, `1:1 AR Walk`, `Tabletop AR`, `Roof/Context` cutaways, `DIN 1451 / LCARS` telemetry |
| **2. Contractor BIM Coordination Viewer** | [**`bim.html`**](https://spinorama.github.io/MassaroHouse/bim.html) | `ISO 19650-2 (S4 · Rev P03.1 Δ3)` · `IFC4 ADD2 TC1` · `903` federated elements · CSI MasterFormat 2020 trade filters · 6-plane Section Box · Laser Tape Measure · `.IFC` & `.CSV` BOQ export |
| **3. Redlined Architectural Drawing Set** | [**`drawings/index.html`**](https://spinorama.github.io/MassaroHouse/drawings/index.html) | 10 contractor-grade Vector SVG CAD sheets (`A-000` through `A-501`) with **Rev P03.1 (`Δ3`) As-Built Redline Clouds, Callout Leaders, Superseded Strike-Throughs & 12-Item Redline Verification Log (`RL-01`–`RL-12`)** |
| **4. Federated BIM Metadata & Assets** | [`massaro_bim_metadata.json`](./massaro_bim_metadata.json) · [`massaro_house.glb`](./massaro_house.glb) · [`massaro_house.blend`](./massaro_house.blend) | `903` mesh elements (`House_Group=467`, `Roof_Group=263`, `Context_Group=173` + `18` cameras + `18` waypoints) |
| **5. Verification Renders & Archival Plates** | [`renders/`](./renders/) (`11` renders) · [`reference/`](./reference/) (`21` plates) | Exterior & interior verification renders (`01`–`11`) & real-world photography (`00`–`20`) |

---

## 🏛️ v2.1.0 As-Built Exterior Overhaul & Field Verification (`Rev P03.1 Δ3`)

Every exterior facade, structural pier, roofline, and shoreline feature has been field-verified against real-world aerial and lakefront photography ([`reference/01`](./reference/01_aerial_island_both_houses.png), [`02`](./reference/02_massaro_exterior_lake_view.png), [`03`](./reference/03_massaro_cantilever_copper_fascia.png), [`13`](./reference/13_massaro_exterior_dusk_whale_rock.png), [`15`](./reference/15_chahroudi_cottage_exterior_terrace.png)) and documented with redlines (`RL-01` through `RL-12`) across the drawing set:

1. **Mitered 16° Outward-Battered Warm Buff-Stucco Cantilever Parapets (`RL-04`):**
   - Deleted the unauthentic 2-story glass curtain wall and SW Prow glass railing (`Railing_SW_Glass_*`); installed the continuous **mitered outward-battered warm buff-stucco cantilever parapet (`Cantilever_Buff_Parapet_*` & `Railing_SW_Parapet_1..4`, `EL +2.86m to +4.75m`)** and **14-bay African Mahogany casement ribbon windows (`EL +4.48m to +7.38m`)**.
2. **Mitered 18° Outward-Battered Standing-Seam Copper Roof Fascia & Dark Olive Deck (`RL-06` & `RL-07`):**
   - Built a seamless **mitered outward-battered weathered bronze/copper fascia (`Roof_Fascia_Edge_1..18`)** with **3D vertical standing-seam ribs every `0.58 m` (`Roof_Copper_Standing_Seams`)**, a `1.35 m` tongue-and-groove mahogany eave soffit, a **dark charcoal-olive elastomeric roof membrane**, **4 polygonal Desert-Rubblestone chimneys** with bronze caps, and a **raised white-curbed 27-skylight platform (`Roof_Skylight_Curb_Platform`)** with white exterior structural ribs and 3 north vaulted mechanical hoods.
3. **Hexagonal Lake Support Pier, Mid-NW Rubblestone Wall, Whale Rock Cliff & Red Boat Gangway (`RL-01` & `RL-05`):**
   - Added the **massive hexagonal Desert-Rubblestone Lake Support Pier (`Pier_Cantilever_Lake_Main`, `EL +0.10m to +2.95m`)** rising from the shoreline boulders beneath the SW cantilever, the **full-height Mid-NW Desert-Rubblestone wall (`Masonry_NW_Lake_Wall`)** with the iconic conical green juniper tree in front of it, the **stratified exterior NW Whale Rock granite cliff & 3 stepped stone entry piers**, and the **battered NW stone bastion wall with its steep Cherokee-Red concrete stair & floating red finger pier** (replacing the unauthentic white boathouse canopy).
4. **40+ Fractured Shoreline Granite Boulders, SE Rock Peninsula & Upper Lawn Ruin (`RL-02` & `RL-03`):**
   - Armored the under-cantilever water's edge and South-East rocky peninsula with **40+ faceted granite boulder masses (`Ctx_Shoreline_Granite_Boulders`)**, coastal shrubs, and the historic stone-ringed foundation ruin on the upper lawn clearing.
5. **1951 FLW Chahroudi Guest Cottage Exterior Overhaul (`RL-08`):**
   - Updated the Cottage hipped roof to **weathered silver-grey cedar shingles (`Mat_Cottage_Shingle_Grey`)** with a **Cherokee-Red eave fascia trim (`Roof_Cottage_RedFascia_1..6`)**, and replaced protruding round stone knobs with **flush 5-sided angular fieldstone slabs** across the polygonal NW bastion, both tall chimney shafts, and the battered planter wall.

---

## 📐 10-Sheet Redlined Architectural Construction Drawing Set ([`drawings/`](./drawings/index.html))

Interactive blueprint sheet binder ([`drawings/index.html`](./drawings/index.html)) with scalloped redline revision clouds (`Δ3`), leader callouts, strike-throughs, and an interactive **Redline Log (`RL-01`–`RL-12`)**:

1. **[`A-000_Cover_Index.svg`](./drawings/A-000_Cover_Index.svg)** — Cover Sheet, Drawing Index, ISO 19650 Matrix & `Rev P03.1 Δ3` Redline Register
2. **[`A-100_Master_Site_Plan.svg`](./drawings/A-100_Master_Site_Plan.svg)** — Petra Island Master Site Plan (`1:500`, Redlines `RL-01..03`: NW Bastion, Red Gangway, SE Rock Peninsula & Cottage Path)
3. **[`A-101_Main_Floor_Plan.svg`](./drawings/A-101_Main_Floor_Plan.svg)** — Main Residence Floor Plan (`1:150`, Redlines `RL-04..06`: Battered Buff Parapet, Glass Railing Deleted, Hex Lake Pier & NW Stone Wall)
4. **[`A-102_Roof_Skylight_Plan.svg`](./drawings/A-102_Roof_Skylight_Plan.svg)** — Roof Framing & 27-Skylight Plan (`1:150`, Redlines `RL-06..07`: Mitered Battered Copper Fascia, White Skylight Curb & 4 Chimneys)
5. **[`A-103_Reflected_Ceiling_Plan.svg`](./drawings/A-103_Reflected_Ceiling_Plan.svg)** — Reflected Ceiling & Lighting Plan (`1:150`, Redline `RL-06B`: `1.35m` Mahogany Eave Soffit & Datum Verification)
6. **[`A-104_Chahroudi_Cottage_Plans.svg`](./drawings/A-104_Chahroudi_Cottage_Plans.svg)** — 1951 Chahroudi Guest Cottage Plans & Elevations (`1:75`, Redline `RL-08`: Grey Shingles, Red Fascia & Flush Fieldstones)
7. **[`A-201_Exterior_Elevations.svg`](./drawings/A-201_Exterior_Elevations.svg)** — Exterior Building Elevations (`1:200`, Redline `RL-09`: Full West, South, East & North As-Built Projections)
8. **[`A-301_Building_Sections.svg`](./drawings/A-301_Building_Sections.svg)** — Building Sections `A-A` & `B-B` (`1:150`, Redline `RL-10`: Battered Prow Parapet, Copper Fascia & Lake Pier)
9. **[`A-401_Interior_Elevations_Details.svg`](./drawings/A-401_Interior_Elevations_Details.svg)** — Enlarged Interior & Envelope Details (`1:50`, Redline `RL-11`: Sill & Soffit Datum Coordination)
10. **[`A-501_BIM_Schedules_QTO.svg`](./drawings/A-501_BIM_Schedules_QTO.svg)** — BIM Quantity Take-Off & Schedules (`TABLE`, Redline `RL-12`: Updated from `834` to `903` IFC4 Elements)
