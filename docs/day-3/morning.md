# Morning — Spatial Analysis & Use Cases

**Day 3 · 09:00–12:30 · Module 4**

---

## Session 6 — EO for Project Monitoring, Completion & Evaluation *(09:00–10:30)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/RUr6tq8nX2w"
    title="Introduction to spatial analysis for the IsDB project cycle — Day 3"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Slide deck:** [:material-file-pdf-box: Day 3 Deck 1 — IsDB Project Cycle Exercises](../assets/slides/Day3_Deck1_IsDB_ProjectCycle_Exercises.pdf)

---

### Web-based vs desktop GIS

This course uses web-based tools exclusively — no desktop GIS installation is required. This reflects the practical context of a diverse group of operations staff who need accessible, reproducible workflows.

The limitation is real: computationally intensive raster analysis (large national datasets, complex statistics) runs more efficiently in desktop GIS. QGIS — free and open-source — is the recommended next step for participants who wish to go further. See the [Video Tutorials](../resources/tutorials.md#qgis-self-study--desktop-gis) section.

### EO for PIASR — Project Supervision

- **Remote monitoring between field missions** — detect vegetation change, surface water change, and construction progress from satellite imagery between visits
- **Physical output assessment** — satellite observations can provide an independent check on claimed construction progress prior to disbursement; findings should be cross-referenced with field reports
- **Anomaly detection** — flag when conditions deviate from an expected trajectory
- **Time-series dashboards** — ETa, surface water extent, and LULC change accessible at any time

### EO for PCR — Project Completion

- **Baseline vs end-line comparison** — use the same boundary and the same EO-derived indicators established in the PAD baseline; compute change in ETa, irrigated area, surface water extent, or LULC
- **Spatial output documentation** — map the geographic extent of works delivered

These satellite-derived comparisons provide one evidential input to the Project Completion Report (PCR). They complement engineering as-built records, supervision reports, and stakeholder assessments.

### EO for PPER — Post-completion Evaluation

- **Long-term monitoring** — track vegetation, land cover, and water trends three to five years after completion using consistent satellite-derived indicators
- **Sustainability assessment** — confirm infrastructure and landscape changes have been maintained
- **Counterfactual analysis** — where a pre-project baseline was established at PCN or PAD stage, satellite observations can support a structured before/after comparison in independent evaluation

### A project in satellite imagery — illustrative example

An illustrative analysis examined an IsDB school project built during 2013–2016 using GeoLibre and satellite imagery:

- Building construction was discernible in satellite images taken during the construction period
- Ten years after completion, the structure remained visible in current imagery
- A 1 km buffer around the school was drawn; land use, flood risk, and population within the buffer were explored

This example illustrates how satellite imagery can support long-term outcome monitoring when a spatial baseline was recorded at project identification. The satellite observations indicate physical presence and broad land-use context — they do not replace operational monitoring, beneficiary surveys, or educational outcome data.

!!! question "Think about this"
    For a project of this kind — which part of the project cycle does this type of satellite analysis support? And what specific map or figure would be placed in each project document?

    *Illustrative answers: PCN/PAD for siting decisions and environmental context; PIASR for construction progress assessment; PCR and PPER for physical sustainability verification.*

### Key spatial analysis operations

| Operation | What it does | Example |
|---|---|---|
| **Overlay** | Combine two or more map layers to examine intersections | Project sites overlaid on a flood-risk layer |
| **Buffer** | Generate a zone of defined distance around a feature | 1 km buffer around a road or school |
| **Zonal statistics** | Summarise values within a defined zone | Mean ETa within a project boundary |
| **Site suitability** | Combine multiple factors to identify preferred locations | Slope, land use, and soil data combined for an irrigation scheme |

---

## Session 7 — Use Cases & Minimum Project Data Submission Form *(11:00–12:30)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/mJedHmmCkK0"
    title="Use cases and project data input forms — Day 3"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

---

### Use-Case Selection Form

Participants identified specific EO applications relevant to their own projects and sectors. The form captures:

- Which project phase the EO application relates to
- Which indicator is needed (ETa, RZSM, LULC, population, flood risk, and others)
- Which project document will use the output
- Which tool can generate it (eToolkit, WaPOR, GeoLibre, EarthMap)

This input feeds into the development of the GEIDA platform — informing which automated outputs and dashboards to prioritise.

### Minimum Project Data Submission Form

The GEIDA programme requires a minimum spatial dataset for every project onboarded into the platform. The Minimum Project Data Submission Form collects:

| Field | Description |
|---|---|
| Project name & code | As recorded in the IsDB project database |
| Administrative area | Country + region + district |
| Sector / team | Determines which EO indicators are most relevant |
| Project stage | Identification or Preparation is preferred — the earlier a project is registered spatially, the more useful the baseline |
| Boundary / corridor / point | KML, GeoJSON, or coordinate pair |
| Area of influence | Broader geographic zone affected by the project |
| Baseline year | The year the baseline should reference |
| Relevant indicators | ETa, RZSM, LULC, water, climate, population, and others as applicable |

!!! tip "Start at PCN — maintain the spatial thread"
    From PCN to PPER there can be a gap of ten or more years. Registering the project boundary and baseline in a spatial database at identification stage preserves the ability to make a before/after comparison at evaluation. The Minimum Project Data Submission Form is the starting point for that process.

---

*Continue to [Afternoon — GeoLibre & Exercise 3](afternoon.md)*
