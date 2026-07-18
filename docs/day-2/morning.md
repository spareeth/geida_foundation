# Morning — Spatialising IsDB Projects (PCN–PCR)

**Day 2 · 09:00–12:30 · Modules 2 & 3**

---

## Session 4 — Spatialising IsDB Projects from PCN to PCR *(09:00–10:30)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/jurndr4gNMM"
    title="Spatializing IsDB projects from PCN to PCR — GEIDA Foundation Training Day 2"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Slide decks — three worked examples of the same framework:**

- [:material-file-pdf-box: Day 2 Deck 1v1 — Demo Area](../assets/slides/Day2_Deck1_EO_Geoinformatics_Project_Phases_DemoArea_v1.pdf)
- [:material-file-pdf-box: Day 2 Deck 1v2 — Irrigated Agriculture Project](../assets/slides/Day2_Deck1_EO_Geoinformatics_Project_Phases_IrrigatedArea_v2.pdf)
- [:material-file-pdf-box: Day 2 Deck 1v3 — Road Project](../assets/slides/Day2_Deck1_EO_Geoinformatics_Project_Phases_RoadProject_v3.pdf)

---

### The spatialisation procedure: PCN to PCR

Day 2 introduced a step-by-step procedure for spatialising a project through its full lifecycle. The same boundary and data approach applies regardless of sector — agriculture, water, infrastructure, health, education.

**What to collect at each stage:**

| Stage | Document | What to collect | How to get it |
|---|---|---|---|
| **Identification** | PCN | Site coordinates / rough boundary · feasibility layers | Google Earth Web · GADM · GeoBoundaries |
| **Preparation** | PPRR | Refined boundary · area of influence | Google Earth KML export · admin boundary download |
| **Design** | PAD / RRM | Detailed boundary · hazard/land-use/climate layers | eToolkit · WaPOR · EarthMap |
| **Supervision** | PIASR | Same boundary + monitoring period | eToolkit (same boundary, new time window) |
| **Completion** | PCR | Same boundary + end-line date | eToolkit baseline vs end-line comparison |
| **Post-evaluation** | PPER | Same boundary + 3–5 years post-completion | Long-term trend from eToolkit / GEIDA platform |

!!! tip "Why the same boundary matters"
    From PCN to PPER there can be a gap of ten or more years. Without a stored spatial boundary in a project database, a consistent before/after comparison at evaluation is not possible. The Minimum Project Data Submission Form (introduced on Day 3) begins to address this.

### Three worked examples

The three versions of the Day 2 slide deck demonstrate the same approach for:

=== "Demo area"
    A generic project area used to introduce the methodology — shows how to go from a text description to a boundary, then to an eToolkit report, step by step.

=== "Irrigated agriculture"
    An irrigation scheme project: boundary corresponds to the command area. Key EO-derived indicators: actual evapotranspiration (ETa), relative root zone soil moisture (RZSM), surface water extent, Land Use / Land Cover (LULC). Relevant documents: PAD (environmental baseline, water availability), PIASR (crop status, irrigation efficiency), PCR (irrigated area change before/after). These satellite-derived indicators complement, rather than replace, field measurements and engineering records.

=== "Road project"
    A road corridor project: the spatial element is a line plus a buffer zone (e.g. 1–5 km). Key indicators: land cover within buffer, flood risk, population exposure, settlement density. Relevant documents: PCN (feasibility, hazard screening), PAD (alignment options, environmental assessment), PCR (construction progress assessment), PPER (infrastructure condition, economic activity change).

---

## Bio-physical EO analysis *(10:00–10:30)*

Earth Observation provides a range of bio-physical indicators that map onto IsDB sectors:

| Indicator | What it measures | Relevant sector(s) |
|---|---|---|
| **RZSM** (Relative Root Zone Soil Moisture) | Soil moisture availability in the root zone, as a fraction of saturation | Agriculture · Water · Environment |
| **ETa** (Actual Evapotranspiration) | Water consumed by vegetation and bare soil through evaporation and plant transpiration | Agriculture · Water · Irrigation |
| **Surface water extent** | Mapped water bodies and change over time | Water · WASH · Flood risk |
| **Land Use / Land Cover (LULC)** | Classification of surface types | All sectors |
| **Topography / DEM** (Digital Elevation Model) | Elevation and slope | Infrastructure · Flood risk · Agriculture |
| **Nighttime-light intensity** | Emitted light at night — indirect proxy for electrification and economic activity | Energy · Urban · Economic development |
| **Precipitation trends** | Rainfall patterns over time | Agriculture · Water · Climate |
| **Surface temperature change** | Land surface temperature trends | Climate · Health · Infrastructure |

These are satellite-derived or modelled products. Each has associated accuracy characteristics, temporal depth, and geographic coverage that should be checked against project requirements.

---

## Exercise 2 — eToolkit Continued *(11:30–12:30)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/g13DxL7sEGQ"
    title="Hands-on exercise — eToolkit continued, Day 2"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

Building on Exercise 1, participants applied the eToolkit to a more specific project-relevant area — selecting the correct Theme for their sector and a relevant Phase to obtain outputs aligned to an actual project document.

**Key difference from Exercise 1:** move from a generic exploration to a sector-specific analysis:

- Agriculture project → select **Agriculture** theme → ETa, RZSM, and water productivity outputs become more relevant
- Infrastructure project → select **Infrastructure** → LULC, flood risk, and climate projections are emphasised
- Water project → select **Water** → surface water, precipitation, and groundwater trend outputs are highlighted

Participants also explored using a project boundary downloaded from GADM (as GeoJSON, imported into eToolkit) rather than drawing one manually.

!!! tip "Quality check before interpreting results"
    Confirm the displayed boundary matches your project area, the time range shown is correct, and results panels are complete before drawing conclusions from the report.

---

*Continue to [Afternoon — GEIDA Opening & WaPOR](afternoon.md)*
