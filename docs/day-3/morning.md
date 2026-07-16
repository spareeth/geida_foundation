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

### Recap: web-based vs desktop GIS

A key point Dr Sajid emphasised on Day 3: this course uses **web-based tools exclusively** — no desktop GIS installation required. This is a deliberate choice for a diverse group of operations staff.

> "We are not trying to do traditional GIS training. What we are trying to do, and it is complex, is to make everything work in web-based tools to make it easy." — Dr Sajid Pareeth

However, the limit is real: very heavy raster analysis (large national datasets, complex statistics) runs faster in desktop GIS. **QGIS** — free, open-source — is the recommended next step for anyone who wants to go further. See the [Video Tutorials](../resources/tutorials.md#qgis-self-study--desktop-gis) section.

### EO for PIASR — Project Supervision

- **Remote monitoring between missions** — detect vegetation change, surface water change, and construction progress from satellite imagery without a field visit
- **Contractor verification** — satellite check on claimed physical outputs before disbursement
- **Anomaly alerts** — flag when conditions deviate from expected trajectory
- **Remote dashboards** — ETa, surface water extent, and LULC change viewed at any time

### EO for PCR — Project Completion

- **Objective before/after comparison** — use the same boundary and same EO indicators from the PAD baseline; compute change in ETa, irrigated area, surface water, LULC
- **Spatial output documentation** — map the extent of works delivered

### EO for PPER — Post-completion Evaluation

- **Long-term monitoring** — track vegetation, land cover, and water trends 3–5 years after completion at near-zero cost
- **Sustainability verification** — confirm infrastructure and landscape changes have persisted
- **Counterfactual analysis** — the PCN/PAD baseline becomes the reference point for before/after comparison in independent evaluation

### A real IsDB project in satellite imagery

In Session 7 (transcript), a group examined an IsDB school project built 2013–2016 using GeoLibre and satellite imagery:

- Building construction was visible in satellite images during 2013–2016
- 10 years after completion, the school is intact — visible in current imagery
- Analysis: 1 km buffer drawn around the school; explored flood risk, land use, and population within the buffer

!!! question "Think about this"
    If you have this kind of satellite analysis for a school or road project — which part of the project cycle does it contribute to? And what specific map or figure would you put in that project document?

    *Answers from participants: PCN/PAD for siting decisions; PIASR for progress verification; PCR/PPER for outcome verification and sustainability.*

### Key spatial analysis operations

| Operation | What it does | Example |
|---|---|---|
| **Overlay** | Combine two or more map layers | Project sites overlaid on a flood-risk layer |
| **Buffer** | Zone of set distance around a feature | 1 km buffer around a road or school |
| **Zonal statistics** | Summarise values within a zone | Average ETa within a project boundary |
| **Site suitability** | Combine factors to find best locations | Slope + land use + soil for an irrigation scheme |

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
- Which indicator is needed (ETa, RZSM, LULC, population, flood risk…)
- Which project document will use the output
- Which tool can generate it (eToolkit, WaPOR, GeoLibre, EarthMap)

This input feeds into the development of the GEIDA platform — informing which automated outputs and dashboards to build next.

### Minimum Project Data Submission Form

The GEIDA programme requires a minimum spatial dataset for every project onboarded into the platform. The Minimum Project Data Submission Form collects:

| Field | Description |
|---|---|
| Project name & code | As in IsDB project database |
| Administrative area | Country + region + district |
| Sector / team | Determines which EO indicators are relevant |
| Project stage | Ideally Identification or Preparation — the earlier, the better |
| Boundary / corridor / point | KML, GeoJSON, or coordinate pair |
| Area of influence | Broader geographic zone affected by the project |
| Baseline year | The year the baseline should reference |
| Relevant indicators | ETa, RZSM, LULC, water, climate, population… |

!!! tip "Start at PCN — keep the thread"
    The key insight: from PCN to PPER there can be a gap of 10+ years. If you don't register the project boundary and baseline in a spatial database at the start, the connection between identification and evaluation is lost forever. The Minimum Project Data Submission Form starts that process.

---

*Continue to [Afternoon — GeoLibre & Exercise 3](afternoon.md)*
