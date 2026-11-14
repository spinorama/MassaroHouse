# Changelog — Massaro House · Petra Island, Lake Mahopac, NY (`MassaroHouse`)

All progressive Blender MCP construction milestones and WebXR updates are documented in this file.

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
