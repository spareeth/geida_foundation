# Morning — EO & Geoinformatics Fundamentals

**10 September 2026 · Sessions 1 & 2 · IsDB HQ Jeddah + Online**

---

## Recording

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/ChecnQSeUOo"
    title="GEIDA Foundation Level Batch 2 — Morning, 10 September 2026"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Slide decks:**

1. [:material-file-pdf-box: Deck 1 — Why geoinformatics matters and spatialising IsDB projects](https://expocitydubai-my.sharepoint.com/:b:/g/personal/sajid_pareeth_expocitydubai_ae/IQBApBXgOCLrTJdVGJwp_y-2AYf67ndEQqWoIdWp8TpSrBU?e=iMH1BQ)
2. [:material-file-pdf-box: Deck 2 — Fundamentals of Earth Observation and geoinformatics](https://expocitydubai-my.sharepoint.com/:b:/g/personal/sajid_pareeth_expocitydubai_ae/IQD59QaS2_ziTYgBUYCrDQ_bARbJMJr5jihvaCsdQcHEjdY?e=RVcOM1)

---

## Session 1 — Why geoinformatics matters

### Why location matters for project work

Every IsDB project has a location. Once that location is recorded as spatial data rather than described in text, it can be used to screen a site before approval, to observe change during implementation, and to produce comparable evidence at completion — all against the same boundary.

Satellite data supports project management and reporting. It does not replace field visits, engineering records or engagement with ministries and beneficiaries; it provides location-based evidence alongside them.

### Worked example — an irrigation project

The session used an irrigation project as the running example: a canal command area, with the command boundary mapped and the project location shown in national context through an inset map. From that single boundary, the analysis can address questions such as how much land is irrigated, how cropping has changed over time, and how the area performed before and after the investment.

A second example, a school and cyclone-shelter programme, illustrated the same principle for infrastructure delivered across many dispersed sites.

### Standard elements of a project map

A map included in a project document should carry:

- A **legend** explaining every symbol and colour
- A **title** stating what is shown, where and when
- A **north arrow** and a **scale**
- The **data source** and the **date** of the imagery or dataset
- An **inset map** locating the project area within the country

---

## Session 2 — Fundamentals of Earth Observation

### What Earth Observation offers

Earth Observation records the state of a location at a point in time. Because satellites revisit the same place repeatedly, observations accumulate into a time series — the same area at time 1, time 2, time 3 — which is what makes change measurable rather than merely described.

Of roughly 4,000 active satellites in orbit, in the order of 1,000 are Earth Observation satellites.

### Types of satellite data

=== "Optical"

    Records reflected sunlight across visible and infrared wavelengths. Used for vegetation and crop condition, water bodies, land cover and urban mapping.

    **Limitation:** cannot see through cloud, and acquires no imagery at night.

    - **Sentinel-2** (EU/ESA) — 10 m, approximately 5-day revisit, freely available
    - **Landsat** (USGS/NASA) — 30 m, 16-day revisit, archive extending over 40 years, freely available

=== "Radar"

    Transmits its own microwave signal and records the return. Operates through cloud and in darkness. Used for surface water and flood mapping, deformation monitoring and vegetation structure.

    - **Sentinel-1** (EU/ESA) — 10 m, approximately 6-day revisit, freely available

=== "Gravimetric"

    Measures changes in the Earth's gravity field, from which variation in total water storage can be inferred — including groundwater — at basin and national scale.

    **Limitation:** very coarse spatial resolution. Informative at basin or country level, not for an individual well field or project site.

### Commercial and free imagery

Freely available optical imagery is generally at 10 m resolution or coarser. Imagery finer than 10 m is commercial and must be purchased. Consumer mapping services compile imagery bought from commercial providers; their apparent zero cost to the user does not make the underlying data free to license for institutional use.

### Vector and raster

| Type | Description | Examples |
|---|---|---|
| **Vector — point** | A single coordinate pair | A well, a school, a clinic |
| **Vector — line** | A connected sequence of points | A road, a canal, a pipeline |
| **Vector — polygon** | A closed boundary enclosing an area | A command area, a project boundary, a catchment |
| **Raster** | A grid of values covering an area | A satellite image, a rainfall map, an elevation model |

### The three resolutions

| Resolution | What it means | Example |
|---|---|---|
| **Spatial** | Ground area represented by each pixel | Sentinel-2 = 10 m |
| **Temporal** | How often a new observation is acquired | Sentinel-2 nominal revisit every 5 days |
| **Spectral** | Number of bands, and so the range of phenomena distinguishable | Sentinel-2 = 13 bands |

!!! note "Revisit versus usable imagery"
    Nominal revisit periods assume cloud-free conditions. In humid or persistently cloudy regions the frequency of usable optical imagery is considerably lower. Check availability for your area and season before committing to analysis dates.

---

## Participant discussion — how projects are monitored today

Participants described the methods currently used to follow project progress from a distance, including:

- Field coordinates collected on a phone or handheld GPS and plotted on consumer mapping services
- Fixed cameras installed at a construction site, reported as effective for a project director following works remotely from the capital
- Periodic drone flights over linear infrastructure such as irrigation canals, noting that drones carry flight permissions and recurring cost that should be budgeted within the project
- Field missions, which remain necessary for questions that imagery cannot answer

Constraints raised included access to data, the difficulty of verifying physical progress remotely, cloud cover, and the limits of imagery resolution for small features.

---

*Continue to [Afternoon — Spatial Analysis & the eToolkit](afternoon.md)*
