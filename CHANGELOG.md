# Changelog — Massaro House · Petra Island, Lake Mahopac, NY (`MassaroHouse`)

All progressive Blender MCP construction milestones and WebXR updates are documented in this file.

---

## [v2.1.0] — 2026-11-18 (As-Built Exterior Overhaul & Rev P03.1 Δ3 Redlined Construction Drawing Set — 903 Elements)
### Added & Field-Verified
- **As-Built Exterior Reality-Capture Overhaul (`massaro_house.blend`, `massaro_house.glb`, `massaro_bim_metadata.json` — `903` Mesh Elements)**:
  - **Mitered 16° Outward-Battered Warm Buff-Stucco Cantilever Parapets (`RL-04`)**: Deleted the unauthentic 2-story glass curtain wall and SW Prow glass railing (`Railing_SW_Glass_*`); installed continuous mitered outward-battered warm peach-buff stucco cantilever parapets (`Cantilever_Buff_Parapet_*` & `Railing_SW_Parapet_1..4`, `EL +2.86m to +4.75m`) and 14-bay African Mahogany casement ribbon windows (`EL +4.48m to +7.38m`) matching `reference/02` and `reference/03`.
  - **Mitered 18° Outward-Battered Standing-Seam Copper Roof Fascia & Dark Olive Deck (`RL-06` & `RL-07`)**: Replaced the flat vertical roof edge with a seamless mitered outward-battered weathered bronze/copper fascia (`Roof_Fascia_Edge_1..18`) with 3D vertical standing seams every `0.58m` (`Roof_Copper_Standing_Seams`), `1.35m` tongue-and-groove mahogany eave soffit, dark charcoal-olive elastomeric roof membrane, 4 polygonal Desert-Rubblestone chimneys with bronze flue caps, and a raised white-curbed 27-skylight platform (`Roof_Skylight_Curb_Platform`) with white exterior structural ribs and 3 north vaulted mechanical hoods (`reference/01`).
  - **Hexagonal Lake Support Pier, Mid-NW Rubblestone Wall, Whale Rock Cliff & Red Boat Gangway (`RL-01` & `RL-05`)**: Built the massive hexagonal Desert-Rubblestone Lake Support Pier (`Pier_Cantilever_Lake_Main`, `EL +0.10m..+2.95m`) rising from the shoreline boulders beneath the SW cantilever, the full-height Mid-NW Desert-Rubblestone wall (`Masonry_NW_Lake_Wall`) with the iconic conical green juniper tree (`Ctx_Coastal_Conifers_Shrubs`), the stratified exterior NW Whale Rock cliff (`Rock_Whale_NW_Cliff`) & 3 stepped stone entry piers (`Pier_WhaleRock_NW_1..3`), and the battered NW stone bastion wall (`Masonry_NW_Bastion_Wall`) with its steep Cherokee-Red concrete stair & floating red finger pier (replacing the unauthentic white boathouse canopy).
  - **40+ Fractured Shoreline Granite Boulders, SE Rock Peninsula & Upper Lawn Ruin (`RL-02` & `RL-03`)**: Added `Ctx_Shoreline_Granite_Boulders` across the under-cantilever water's edge and South-East rocky peninsula, plus the historic stone-ringed foundation ruin (`Ctx_Lawn_StoneRuin_1..6`) on the upper lawn clearing.
  - **1951 FLW Chahroudi Guest Cottage Exterior Overhaul (`RL-08`)**: Updated Cottage hipped roof to weathered silver-grey cedar shingles (`Mat_Cottage_Shingle_Grey`) with Cherokee-Red eave fascia trim (`Roof_Cottage_RedFascia_1..6`), and replaced protruding round stone knobs with flush 5-sided angular fieldstone slabs across the polygonal NW bastion, both tall chimney shafts, and the battered planter wall (`reference/15`).
  - **New Exterior Verification Renders (`renders/`)**: Added `10_exterior_aerial_island_overview.png`, `11_exterior_lakefront_cantilever.png`, and updated `07_chahroudi_cottage_exterior.png`.
- **Rev P03.1 (`Δ3`) Redlined Architectural Construction Drawing Set (`drawings/` & `A-000`–`A-501`)**:
  - Added scalloped CAD redline revision clouds, `Δ3` delta tags, leader callouts, strike-throughs of superseded specs, title-block redline stamps, and an interactive 12-item Redline & Field Verification Log (`RL-01`–`RL-12`) in `drawings/index.html`.

---

## [v2.0.0] — 2026-11-18 (ISO 19650 / IFC4 Contractor BIM Coordination Viewer & 10-Sheet Construction Drawing Set)
### Added
- **Dedicated Contractor BIM Coordination & Federation Viewer (`bim.html` + `massaro_bim_metadata.json`)**:
  - **ISO 19650-2 Information Container (`MAS-THH-ZZ-ZZ-M3-A-0001`)**: Suitability `S4 — For Construction Coordination`, Revision `P02.1`, Schema `IFC4 ADD2 TC1`.
  - **1:1 Federated BIM Metadata (`massaro_bim_metadata.json`)**: Extracted exact world-space bounding boxes, dimensions, datum elevations, surface areas (`m²`/`sq ft`), volumes (`m³`/`cu ft`), deterministic IFC4 `GlobalId`s, `IfcClass`, `PredefinedType`, CSI MasterFormat 2020 codes, Uniformat II, Uniclass 2015, and contractor specification notes for all `834` mesh elements (`858` total Blender scene nodes).
  - **Spatial Hierarchy & Trade Filtering**: Filter, hide, or 1-click isolate by `IfcBuilding` (`BLDG-01` Main Residence, `BLDG-02` 1951 Chahroudi Cottage, `BLDG-03` Marine/Outbuildings, `SITE-01` Petra Island), `IfcBuildingStorey` (`L00`–`L04`), 18 `IFC4` Entity Classes, and CSI MasterFormat subcontractor trade packages (`Div 03` through `Div 35`).
  - **6 Federation Color Modes**: `PBR Realistic`, `By IFC4 Class`, `By CSI Trade`, `By Storey`, `By ISO 19650 Discipline`, and `CAD Wireframe`.
  - **Interactive 6-Plane 3D Section Box & Laser Tape Measure `[M]`**: Live X/Y/Z clipping planes with architectural cut presets (`Plan Cut L02 +4.3m`, `Plan Cut L01 +2.8m`, `Section A-A`, `Section B-B`, `Cottage Cutaway`), Perspective/Orthographic camera toggle `[O]`, and point-to-point 3D laser measurement ($\Delta X, \Delta Y, \Delta Z$, Metric & Imperial).
  - **Right-Docked IFC4 Property Inspector & Live BOQ Spreadsheet**: Inspect `Pset_ISO19650_Identification`, `Pset_Classification`, and `Qto_ElementBaseQuantities`, plus in-browser `.IFC` (ISO 10303-21 STEP) and `.CSV` (Excel BOQ) exports.
- **Full 10-Sheet Architectural Construction Drawing Set (`drawings/index.html` & `A-000`–`A-501`)**:
  - Generated 10 contractor-grade Vector SVG architectural sheets (`A-000_Cover_Index.svg`, `A-100_Master_Site_Plan.svg`, `A-101_Main_Floor_Plan.svg`, `A-102_Roof_Skylight_Plan.svg`, `A-103_Reflected_Ceiling_Plan.svg`, `A-104_Chahroudi_Cottage_Plans.svg`, `A-201_Exterior_Elevations.svg`, `A-301_Building_Sections.svg`, `A-401_Interior_Elevations_Details.svg`, `A-501_BIM_Schedules_QTO.svg`) and an interactive pan/zoom blueprint binder (`drawings/index.html`).

---

## [v1.2.0] — 2026-11-17 (Photo-Accurate Massaro Interiors & 1951 Chahroudi Guest Cottage Overhaul)
### Added & Rebuilt
- **Archival Reference Library (`reference/` & `renders/`)**: Curated 21 architectural photography plates (`reference/00`–`20`) of the Massaro House and 1951 Chahroudi Guest Cottage plus 9 verified Blender verification renders (`renders/01`–`09`).
- **1951 Frank Lloyd Wright Chahroudi Guest Cottage Complete Overhaul (`Cam_15` & `Cam_16`)**:
  - **Exposed Hexagonal Timber Rafter Ceiling (`Roof_Cottage_Exposed_Rafters`)**: 30+ radiating redwood/mahogany ridge, hip, and common rafters beneath the shingled hipped roof (linked into `Roof_Group` so `🏠 Roof` reveals both houses in Dollhouse cutaway mode).
  - **Monumental Battered Concrete Fireplace Hood**: Floor-to-ceiling desert-concrete chimney mass with the iconic diagonal gold/tan granite slab cast into the upper hood face, tall firebox, and black mesh fire screen.
  - **Cottage Living, Dining, Bedroom Alcove & Galley Kitchen**: 2 X-frame cord-slung Wright chairs, polygonal cruciform-pedestal dining table, vertical board-and-batten mahogany partition wall with framed interior window, folding accordion doors opening to the bedroom alcove (clerestory ribbon windows, triangular corner desk, powder-blue bed), and NW galley kitchen with hexagonal geometric stained-glass window & vintage red stove.
  - **Exterior Terrace & Desert-Rubble Wing**: Battered desert-rubble NW wing & south planter walls with 3D embedded fieldstones, 4 mahogany-framed glass French doors, glowing spherical globe eave pendant, 3-step Cherokee-red concrete terrace, triangular lakeside reflection pool, and 2 sculpted wood lounge chairs.
- **Photo-Accurate Massaro House Interior & Exterior Overhaul (`Cam_02`–`Cam_12`)**:
  - **Exterior Copper Fascia & Desert-Rubble Piers**: Patinaed standing-seam bronze/copper roof fascia (`Mat_Copper_Fascia`) over mahogany soffits, plus procedural 3D angular fieldstones (`Masonry_Desert_Rubble_Stones`) across piers, fireplace cores, and walls.
  - **27-Skylight Atrium, Whale Rock & Crane Screen Mural (`Cam_07`)**: Stepped pale-granite `Rock_Whale_Main` strata, stepped concrete/mahogany skylight coffers, horizontal mahogany HVAC frieze, built-in banquette with 2 hexagonal side tables, cantilevered rock bar shelf, suspended bronze ceremonial gong, and 4.4 m vertex-colored **Japanese Pine & Crane Screen Mural (`Mural_Atrium_Cranes_Pines`)**.
  - **Whale-Rock Kitchen (`Cam_08`)**: Scribed honed bluestone L-counter & peninsula around `Rock_Tail_Kitchen`, **5 bright red enameled Le Creuset Dutch ovens & skillets** on the rock ledge, terracotta-red mosaic tile backsplash, 4 flush-slab mahogany upper cabinets with top LED uplight cove, stainless pyramid hood, cooktop, wall oven, and microwave.
  - **Dining Room (`Cam_09`) & Cantilevered Great Room (`Cam_04`)**: Boat-shaped mahogany dining table with **8 tall slatted-back FLW dining chairs**, buffet credenza, suspended chandelier, hexagonal Usonian geometric rugs, 14 m cream banquette with under-seat LED cove & triangular end tables, recessed triangular ceiling downlights, and prow easel painting.
  - **Master Suite (`Cam_10`), Rock Shower En-Suite (`Cam_11`) & Study (`Cam_12`)**: Full-width mahogany headboard credenza with warm LED uplight washing the fieldstone wall, corner stone fireplace with iron screen, stepped diagonal mahogany tray ceiling, crimson silk bed, tall cutout-back Wright chair, stepped granite shower boulder cascade + 3 upper wall stones, and frosted FLW geometric chevron motif on the frameless glass shower door.

---

## [v1.0.0] — 2026-11-14 (Final Release: Waypoints, Cottage Interior & Full QA)
### Added
- **Explicit `Waypoints_Group` Navigation Markers (`WP_01`–`WP_18`)**: Embedded 18 named Empty markers under `Set_house -> Waypoints_Group` synchronized 1:1 with the WebXR room switcher and VR teleport elevations.
- **1951 Chahroudi Guest Cottage Interior Polish**: Added Cherokee-red interior floor cap, Wrightian banquette sofa, low mahogany table, and warm upright lamp glow visible through the perimeter glass ribbon.
- **End-to-End Blender & glTF QA**: Verified clean glTF 2.0 export (`massaro_house.glb`, `2.12 MB`, `625` meshes across `House_Group`, `Roof_Group`, `Context_Group`, and `Waypoints_Group`), Blender visual camera/cutaway inspections, and `index.html` module script validation.

---

## [v0.4.0] — 2026-11-14 (Full Island Context: Boat Dock, 1951 Chahroudi Cottage & Woodland Canopy)
### Added
- **Lakeside Boat Dock, Covered Slip & Runabout Boat (`Context_Group`)**: Timber pile jetty pier extending into Lake Mahopac, cantilevered buff/mahogany boathouse canopy, moored V-hull white runabout with navy cockpit & windshield, terracotta lakeside seawall apron, stepped promenade linking dock to the main entry terrace, and sloped bluestone island walkway.
- **1951 Frank Lloyd Wright Chahroudi Guest Cottage**: Full Wrightian butterfly/diamond cedar-shingle hipped roof with beveled eaves, dual Hudson masonry chimneys, horizontal mahogany dado, ribbon glass clerestories, and hexagonal terracotta lake-view terrace.
- **NE Utility Compounds**: Pyramid-hipped utility shed (`635, 136`), woodland dark shed (`734, 114`), trailered white boat, and utility props seated cleanly on terrain pads.
- **Procedural Island Forest (`Mat_Tree_VCol`)**: ~120 faceted 3-lobe deciduous trees batched into 4 WebXR-optimized meshes (`Ctx_Trees_Specimen_Grove`, `Ctx_Forest_North_Cove`, `Ctx_Forest_East_Woods`, `Ctx_Forest_SE_Woods`) preserving the exact open clearing & sightlines seen in the aerial extents (`2.12 MB` GLB).
- **18 Verified Cameras**: Added North Prow Study, South Lake Terrace, Cove Boat Dock & Slip, 1951 Chahroudi Cottage, and Island Clearing & Woods.

---

## [v0.3.0] — 2026-11-14 (Mahogany Glazing, Wrightian Interiors & Smooth Shoreline)
### Added
- **Perimeter Mahogany Curtain Glazing & Mullions (`House_Group`)**: Floor-to-ceiling cantilevered lakeside glass walls (`NW_Living_Main`, cantilevered prows, `South_Balc_Door1/2`, `SW_Prow_Door`, `NE_Entry_Door`, and `East_Wing_N/S`), clerestory transoms, and mitered corner mullions.
- **Bespoke Wrightian Interiors & Furnishings**:
  - **Cantilevered Great Room & Prow**: Geometric Usonian area rug, lakeside built-in banquette seating with ochre/rust cushions, open-front barrel/origami armchairs, coffee table, glossy ebony baby grand piano with keys & bench, upright glowing Taliesin lamps, and SW outdoor deck loungers.
  - **Atrium, Kitchen & Dining**: Integrated natural Tail-Rock kitchen island, range & cabinets, bar stools, hexagon mahogany dining table with 6 armchairs, and North Prow study desk & shelving.
  - **East Wing Master Suite & Rock-Wall En-Suite Bath**: Master platform bed & rug, twin-sink mahogany vanity, soaking tub, frameless glass shower partition embracing an interior granite boulder.
  - **Minimalist Blocky Cat Gallery (`m_cat_art_vcol`)**: Entry corridor Usonian cat reliefs, Master Suite horizon cat relief, and fireplace hearth tuxedo cat sculpture.
- **Smooth Shoreline Vertex Blending (`Context_Group`)**: Replaced stepped discrete terrain zones with per-vertex `Col` blending (`Ctx_Island_Terrain`) plus sculpted granite coastal boulders.
- **13 Verified Camera Views**: Added SW Prow Deck, Cantilever Great Room, Double Hearth Lounge, Whale Rock & Entry, Tail Rock Kitchen, Dining Alcove, East Master Suite, and Rock Wall En-Suite.

---

## [v0.2.0] — 2026-11-14 (Structural Shell, Cantilevers, 27 Skylights & Helipad Roof)
### Added
- **Cantilevered Living Wing & Split-Level Slabs (`House_Group`)**: Cherokee-red concrete floor slabs (`Z = 3.20 m` cantilevered SW living room + `Z = 3.80 m` split-level upper wing) linked by 4 broad atrium steps, deep post-tensioned under-deck concrete girders, shoreline masonry piers, SW Prow Balcony with glass/concrete parapet railings, and Recessed South Lake Terrace.
- **Monumental Double-Sided Granite Hearth & Shear Walls**: Hudson Valley granite masonry piers, double-sided living/terrace firebox with glowing embers, chimney rising to `Z = 10.12 m`, and interior Kitchen "Tail Rock" outcrop.
- **Signature 27-Skylight Roof & Helipad (`Roof_Group`)**: Cantilevered Wrightian stucco fascia, mahogany ceiling soffits, exact 27-triangle coffered skylight lattice with translucent pyramidal prisms, diagonal skylight roof bridge, rooftop circular `H` Helipad, US Flag deck inlay, and mechanical hatch — all cleanly toggleable via `🏠 Roof`.
- **5 Updated Camera Presets**: Exterior 3Q, Over-Water Cantilever, Skylight Atrium Look-Up, Rooftop Helipad Deck, and Aerial Extents.

---

## [v0.1.0] — 2026-11-14 (Site Extents, Petra Island Terrain & Massing)
### Added
- **Exact Site Extents (`134.55 m × 129.75 m`)**: Calibrated directly to the Lake Mahopac / Petra Island aerial extents (`0.15 m/px` across `897 × 865 px`).
- **Lake Mahopac & Petra Island Terrain (`Context_Group`)**: Sculpted shoreline bluffs, exposed granite headland, central island lawn, organic eastern forest floor transition, and solid museum plinth border.
- **Whale Rock & South Bluff Outcrops (`House_Group`)**: 18 m (60 ft) diagonal granite Whale Rock spine and south shoreline granite ledge anchoring the cantilevered footprint.
- **Preliminary House Massing (`House_Group` & `Roof_Group`)**: Cherokee-red structural slab, SW cantilevered prow balcony massing, and toggleable roof silhouette block.
- **4-Mode WebXR Viewer (`index.html`)**: Desktop 3D, Phone 1-finger orbit/pinch, Quest VR floor teleport, 1:1 AR Walk, Tabletop AR full-extent scaling, Hidden-Line CAD `[L]`, DIN 1451 / LCARS `[T]`, and live Changelog modal.
