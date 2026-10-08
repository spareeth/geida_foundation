# Part 3 — Online Practical Follow-up

**29 September, 8 October and 13 October 2026 · Online · 12:00–16:00 Dubai / 11:00–15:00 Jeddah**

---

Part 3 completes the Batch 2 Foundation Level programme. Across three guided online sessions of approximately four hours each, participants develop an applied GEIDA case using their own ongoing or pipeline project, with trainer support throughout.

!!! tip "Coming next — Session 2 on Thursday 8 October"
    Session 1 was delivered on 29 September; the recording is published below. The remaining sessions run on **8 October and 13 October 2026**, 12:00–16:00 Dubai / 11:00–15:00 Jeddah.

    A single Microsoft Teams link covers all three sessions.

    [:material-microsoft-teams: **Join the session**](https://teams.microsoft.com/meet/334859339838903?p=a3cun8qwwIh40p08vN){ .md-button .md-button--primary }

    A calendar invitation for the series is circulated by email to registered participants.

---

## Dates

| Session | Date | Theme |
|---|---|---|
| Session 1 | Tuesday 29 September 2026 | Project mapping, baseline and risk screening |
| Session 2 | Thursday 8 October 2026 | Implementation monitoring and results indicators |
| Session 3 | Tuesday 13 October 2026 | Case presentations, peer learning and certification |

---

## Session recordings

### Session 1 — 29 September: Project mapping, baseline and risk screening

The session was recorded in two parts.

**Part 1** — recap of the GEIDA framework, spatialising a project, the tools, and the worked case: locating the project area and building the boundary.

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/NqHpmxUdDXI"
    title="GEIDA Batch 2 — Part 3, Session 1, Part 1 — 29 September 2026"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

**Part 2** — the baseline in the eToolkit, climate and risk screening, applied work on participants' own projects, and the project data submission.

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/lAXQ_KKSCwg"
    title="GEIDA Batch 2 — Part 3, Session 1, Part 2 — 29 September 2026"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

!!! note "Recordings for Sessions 2 and 3"
    Published on this page after each session.

---

## Session 2 exercises — Moroto district, Uganda

The Session 2 exercises run in GeoLibre in your browser. The heavy processing runs on the GEIDA course server, so nothing is installed on your laptop.

!!! info "Access code"
    The access code for the course server is issued by your trainer. It is typed into the plugin only, and is not published on this site.

### Setup, about ten minutes

| Step | What to do |
|---|---|
| 1. Open GeoLibre | [web.geolibre.app](https://web.geolibre.app) — no account needed |
| 2. Install the plugin | **Settings › Manage Plugins › Settings**, paste the manifest URL under **Manifest URLs** and click **Add**. Version 0.4.0 or later |
| 3. Turn it on | **Plugins › Installed › Remote Processing**, then **Remote Processing › Server connection and files** |
| 4. Connect | Enter the server address and your access code, then **Save and connect**. The status turns green |

The server address, the manifest URL and the download are all on the server's landing page:

[:material-server-network: **Course server and setup**](https://geolibre.terrawatch.net/){ .md-button .md-button--primary }
[:material-download: **Moroto_course_data.zip**](https://geolibre.terrawatch.net/downloads/Moroto_course_data.zip){ .md-button }
[:material-book-open-variant: **Step-by-step guide**](https://geolibre.terrawatch.net/guide){ .md-button }

Unzip the course data on your laptop and open the vector files with **Add Data › Vector Layer**. The rasters are already on the server, under **Data › Shared course data**.

!!! warning "Untick Run locally (WASM)"
    In every Whitebox tool dialog, untick **Run locally (WASM)** at the top right. If it stays ticked the tool runs on your laptop and cannot read the server files, and every later step fails.

### The four exercises

| Part | Question | Main tools |
|---|---|---|
| 0 | Where in Uganda should a programme focus? | Select by Expression, Export Selected Features |
| 1 | Who lives more than 5 km from a school? | Vector Points To Raster, Euclidean Distance, Reclass, Multiply, Zonal statistics |
| 2 | Who lives far from a health centre, and from a proper one? | The same chain, with a filter on facility level |
| 3 | What would a Moroto–Tapac road upgrade cross? | Buffer, Slope, Reclass, Zonal statistics, Select by Location |
| 4 | How do I share a result as a map? | Style, Print Layout, logo on a printed map |

The projects used in the exercises are hypothetical. The data and the places are real.

### Applying it to your own project

Each exercise has an equivalent for your own operation.

| From Moroto | The same question for your project |
|---|---|
| Part 0 | Which district or region does your project cover, and how does it compare with its neighbours? |
| Part 1 | Who does your project reach, and who is left beyond a reasonable distance of it? |
| Part 2 | Does the service your project provides meet the standard, not just exist on a map? |
| Part 3 | What does your corridor, command area or site cross, and who lives in it? |
| Part 4 | One map your task team can put in the PCN, PAD or supervision report |

For the project locations submitted through the Project Data Submission Form, the trainers will prepare the equivalent population, land cover and terrain layers for your area.

### What to submit

The exercises are completed after the session.

1. The four parts on Moroto, whichever were not finished during the session
2. At least one of the four questions applied to your own project area
3. One map exported from the Print Layout, with title, legend, scale, north arrow, source and date
4. Your five slides for Session 3

Share your results in the **Batch 2 Teams channel** or by email to the trainers, **by Sunday 11 October**, so that they can be reviewed before Session 3.

### If something fails

| Symptom | What to check |
|---|---|
| The status does not turn green | The access code first, then the server address |
| A tool fails or reads nothing | **Run locally (WASM)** is still ticked |
| A raster input is rejected | The drop-down is on Layer instead of Path. Use **Copy path** in the Data tab |
| Multiply or Zonal statistics fails | The two rasters are on different grids. Rebuild from the population raster as the base |
| A selection returns unexpected counts | Missing values: some subcounties have no census figures and cannot be evaluated |

Post the problem in the Teams channel with a screenshot of the tool dialog.

---

## Cross-sector case studies

Each session uses sector-based case studies to demonstrate how EO and geospatial approaches apply across the IsDB portfolio, drawing on Agriculture, Water, Health, Education, Energy and Transport.

| Session | Illustrative sector cases |
|---|---|
| Session 1 | Agriculture and Water |
| Session 2 | Energy and Transport |
| Session 3 | Health and Education, plus participant projects |

---

## How each session runs

| Time (Dubai) | Block |
|---|---|
| 12:00–12:15 | Recap and session objectives |
| 12:15–13:15 | Guided walkthrough with the trainers |
| 13:15–13:30 | *Break* |
| 13:30–14:30 | Applied work on your own project, trainers on call |
| 14:30–14:40 | *Short break* |
| 14:40–15:30 | Self-work, trainers available in breakout rooms |
| 15:30–16:00 | Share-back, troubleshooting and assignment for the next session |

Session 3 follows the same shape, with the later blocks given over to case presentations and peer discussion.

---

## Session detail

### Session 1 — Project mapping, baseline and risk screening *(29 September)*

- Define the project location and area of influence
- Develop or refine project boundaries
- Identify relevant datasets
- Generate an initial EO / geospatial baseline
- Undertake climate, risk or site-context screening
- Identify key findings relevant to project design

**Expected output:** initial project map and EO / geospatial baseline.

### Session 2 — Site identification and site assessment *(8 October)*

Hands-on work in GeoLibre, using a real district and real data: the Uganda 2024 census, OpenStreetMap facilities, WorldPop, ESA WorldCover and the Copernicus DEM.

- Narrow national data to one district using census attributes
- Measure access to schools and to health facilities, weighted by population
- Screen a road corridor for terrain, land cover and population
- Produce a styled, sourced map for a report
- Identify EO / geospatial indicators linked to the Results Framework

**Expected output:** a site assessment for your own project area, and proposed spatial indicators.

See [Session 2 exercises](#session-2-exercises-moroto-district-uganda) below for the setup, the data and the step-by-step guide.

### Session 3 — Case presentations, peer learning and certification *(13 October)*

- Present project location and baseline
- Explain the operational issue addressed
- Present the relevant EO / geospatial analysis and findings
- Propose monitoring indicators and next steps
- Receive peer discussion and trainer feedback

**Expected output:** final participant or Hub project case presentation, and completion of the Foundation Level requirements.

---

## The applied case

Five slides, five minutes, following the structure above:

1. **The project** — title, country, stage, and the operational issue addressed
2. **Project location and baseline** — footprint and initial EO / geospatial baseline
3. **Risk screening findings** — climate, risk or site-context screening relevant to design
4. **Proposed monitoring indicators** — linked to the Results Framework
5. **Next steps** — how this will be applied in the project

---

## Key features of Part 3

| | |
|---|---|
| **Guided technical support** | Expert trainers provide structured support throughout each session |
| **Project-based learning** | GEIDA tools applied to real or pipeline IsDB projects, with practical outputs |
| **Peer learning** | Sharing experience and ideas with peers across regions and sectors |
| **Foundation Level completion** | Completing Part 3 fulfils the practical requirements of the Foundation Level |
| **Operational impact** | Strengthened geospatial decision-making across the project cycle |

**Outcome:** participants apply GEIDA tools to real projects, strengthen geospatial decision-making across the project cycle, and complete the GEIDA Foundation Staff Certification — Batch 2.

---

## Preparation

Before Session 1, confirm the single ongoing or pipeline IsDB project you will use, and have to hand:

- Location coordinates, boundary or area of influence, in whatever format is available
- Key project components
- The Results Framework and its indicators
- Project start and expected completion dates

Participants are grouped at Regional Hub level for this training, so kindly coordinate within your Hub team when selecting the project. If you have not already done so, submit your project details through the form below before Session 1.

[:material-form-select: **Project Data Submission Form**](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=CA8x2HQVG0eId0PFAyJbGrgFJg6wpgZJskdpEwAADllUNU9ZNzVJSFUwUFJDSkJINTFRTjYxT0hZTy4u){ .md-button }

Sessions 2 and 3 require no separate preparation — the output of the previous session carries forward.

Continue to use the [eToolkit](https://etoolkit.terrawatch.net) credentials issued to you earlier.

---

*Materials from each session are published on this page as the sessions are delivered.*
