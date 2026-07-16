# Afternoon — Mainstreaming EO & Exercise 1

**Day 1 · 13:30–16:00 · Module 1 · Session 3 + Exercise 1**

---

## Session 3 — Mainstreaming EO in IsDB Operations *(13:30–15:00)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/N36dJpJv7mU"
    title="Mainstreaming Earth Observation and Geoinformatics in IsDB operations"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Slide decks:**

- [:material-file-pdf-box: Day 1 Deck 3 — Spatializing IsDB Projects](../assets/slides/Day1_Deck3_Spatializing_IsDB_Projects.pdf)
- [:material-file-pdf-box: Day 1 Deck 4 — Mainstreaming EO & eToolkit Use Cases](../assets/slides/Day1_Deck4_Mainstreaming_EO_eToolkit_UseCases.pdf)


---

### The IsDB project cycle and where EO fits

The six stages of the IsDB project cycle each have a concrete EO contribution:

| Stage | Document | EO contribution |
|---|---|---|
| **Identification** | PCN | Site screening · feasibility mapping · preliminary baseline · investment risk scoring |
| **Preparation** | PPRR | Appraisal context · benchmark conditions |
| **Design** | PAD / RRM | Environmental baseline · hazard assessment · land-use conflict mapping · spatial annexes |
| **Supervision** | PIASR | Remote monitoring · vegetation/water change · contractor verification |
| **Completion** | PCR | Objective baseline vs end-line comparison |
| **Post-evaluation** | PPER | Long-term outcome monitoring · sustainability verification |

### What is the eToolkit?

The eToolkit is IsDB's browser-based geospatial platform — a web GIS environment that integrates EO data, AI-powered analytics, and interactive mapping. No GIS software to install. No coding required.

**Draw a boundary → select indicators → generate a standardised EO report.**

The platform serves three roles:

- A **web GIS** — interactive maps, spatial layers, drawing tools
- A **knowledge hub** — EO case studies from IsDB projects
- A **resource centre** — datasets, training materials, and SOPs

What an automated analysis contains:

- Land Use / Land Cover (LULC)
- Precipitation trends
- Evapotranspiration trends
- Future climate projections (temperature and rainfall)
- AI-powered sector-specific recommendations

---

## Exercise 1 — Report Generation in eToolkit *(15:00–16:00)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/oNFHW5nj9fI"
    title="Hands-on exercise — eToolkit report generation"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Slide deck:** [:material-file-pdf-box: Day 1 Deck 5 — Exercise: Boundary & eToolkit](../assets/slides/Day1_Deck5_Exercise_boundary_eToolkit.pdf)

**Objective:** Capture a boundary for an area you know, bring it into the eToolkit, and generate your first automated EO analysis report.

**Checkpoint:** By the end of this exercise, you have a downloaded PDF report and can state one finding in one sentence.

---

### Exercise 1A — Define your area in Google Earth Web *(15:00–15:25)*

**Aim:** Draw a polygon boundary around your chosen area and export it as a KML file.

1. Go to **[earth.google.com/web](https://earth.google.com/web)** in your browser.
2. Search for your chosen location (district scale, ~100–2,000 km² — avoid open water or featureless terrain).
3. Click **New Project** → **Create KML file** → give it a name (e.g. `Exercise1_YourName`).
4. Click **Add to project** → **Draw line or shape** → click around your area's perimeter → double-click to close.
5. Hover the project in the left panel → click **⋮** → **Export as KML file** → save as `Exercise1_AOI.kml`.

!!! tip "Choosing a good area"
    Aim for district or watershed scale. Pick somewhere with visible variety — farmland, a river, mixed land use. Avoid large water bodies or uniform bare desert. If you work on specific IsDB projects, use a real project area.

**Alternative for admin boundaries:** download directly from [geoboundaries.org/simplifiedDownloads.html](https://www.geoboundaries.org/simplifiedDownloads.html) — select country + administrative level (ADM1 = province, ADM2 = district) → download GeoJSON.

---

### Exercise 1B — Generate an EO analysis in the eToolkit *(15:25–16:00)*

**Aim:** Load your boundary, run the analysis, and export the PDF report.

**Access:** [etoolkit.terrawatch.net](https://etoolkit.terrawatch.net) · Username: `user1` · Password: `etoolkit@IsDB`

!!! warning "Shared training credentials"
    These are shared credentials for the training environment. Do not change the password or account settings.

1. **Log in** — take the guided platform tour when prompted.
2. **Set filters** — select your Theme (sector), Phase (Identification), and Country.
3. **Load your area** — import your `Exercise1_AOI.kml` (or GeoJSON from GeoBoundaries), or draw directly on the map.
4. **Generate analysis** — click Generate analysis and wait (a few minutes for processing).
5. **Explore results** — read LULC, vegetation trend, precipitation, climate projections, and AI recommendations.
6. **Export PDF** — download the full report.

!!! question "For each section of your report, ask:"
    - What does this tell me about my area?
    - What surprised me?
    - Which finding would be most useful in a PAD or PCR for a project here?

!!! warning "Troubleshooting"
    - **Area too large / slow** → reduce the polygon and re-run. Aim for district scale.
    - **Blank or near-empty results** → your area may be mostly water or have heavy cloud cover. Try a different location.
    - **Login issues** → check credentials above; contact the facilitator.
    - **KML not accepted** → draw directly on the map instead.

---

### Group share *(last 5 min)*

Two or three volunteers share their area on screen and name one thing the report revealed. No preparation needed.

---

*Continue to [Day 2 — Spatializing Projects & WaPOR](../day-2/index.md)*
