# Morning — Spatializing IsDB Projects (PCN–PCR)

**Day 2 · 09:00–12:30 · Modules 2 & 3**

---

## Session 4 — Spatializing IsDB Projects from PCN to PCR *(09:00–10:30)*

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
    From PCN to PPER there can be a gap of 10+ years. If you don't store the same spatial boundary in a project database, you lose the ability to make a before/after comparison at evaluation. The Minimum Project Data Submission Form (introduced on Day 3) is the first step to fixing this.

### Three worked examples

The three versions of the Day 2 slide deck demonstrate the same approach for:

=== "Demo area"
    A generic project area used to introduce the methodology — shows how to go from a text description to a boundary, then to an eToolkit report, step by step.

=== "Irrigated agriculture"
    An irrigation scheme project: boundary corresponds to the command area. Key indicators: ETa (actual evapotranspiration), root zone soil moisture (RZSM), surface water extent, LULC. Relevant documents: PAD (environmental baseline, water availability), PIASR (crop status, irrigation efficiency), PCR (irrigated area change before/after).

=== "Road project"
    A road corridor project: the spatial element is a line plus a buffer (e.g. 1–5 km). Key indicators: land cover within buffer, flood risk, population exposure, settlement density. Relevant documents: PCN (feasibility, hazard screen), PAD (alignment options, environmental assessment), PCR (construction verification), PPER (infrastructure intact, economic activity change).

---

## Bio-physical EO analysis *(10:00–10:30)*

Earth Observation provides a range of bio-physical indicators that map directly onto IsDB sectors:

| Indicator | What it measures | Relevant sector(s) |
|---|---|---|
| **RZSM** (Relative Root Zone Soil Moisture) | Soil moisture availability in the root zone | Agriculture · Water · Environment |
| **ETa** (Actual Evapotranspiration) | Water used by vegetation and bare soil | Agriculture · Water · Irrigation |
| **Surface water extent** | Mapped water bodies and change over time | Water · WASH · Flood risk |
| **Land Use / Land Cover (LULC)** | Classification of surface types | All sectors |
| **Topography / DEM** | Elevation and slope | Infrastructure · Flood risk · Agriculture |
| **Nighttime lights** | Human activity, electrification | Energy · Urban · Economic development |
| **Precipitation trends** | Rainfall over time | Agriculture · Water · Climate |
| **Temperature change** | Surface temperature trends | Climate · Health · Infrastructure |

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

Building on Exercise 1, participants applied the eToolkit to a more specific project-relevant area — selecting the **correct Theme** for their sector and a **relevant Phase** to get outputs aligned to an actual project document.

**Key difference from Exercise 1:** move from a generic "identify an area" to a sector-specific analysis:

- Agriculture project → select **Agriculture** theme → ETa, root zone soil moisture (RZSM), water productivity outputs become more relevant
- Infrastructure project → select **Infrastructure** → LULC, flood risk, climate projections emphasised
- Water project → select **Water** → surface water, precipitation, groundwater trend outputs

Participants also explored using a **project boundary from GADM** (downloaded as GeoJSON, imported into eToolkit) rather than drawing one manually.

---

*Continue to [Afternoon — GEIDA Opening & WaPOR](afternoon.md)*
