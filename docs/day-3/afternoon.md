# Afternoon — GeoLibre & Exercise 3

**Day 3 · 13:30–16:00 · Module 4**

---

## Session 8 — Spatial Analysis using GeoLibre *(13:30–14:30)*

<div class="video-wrapper">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/szMTMCwb3Ec"
    title="Spatial analysis using GeoLibre for project assessments — Day 3"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

---

### What is GeoLibre?

**GeoLibre** is a web-based GIS viewer and analysis tool — no installation needed.

- App: [viewer.geolibre.app](https://viewer.geolibre.app)
- Tutorial site: [geolibre.app](https://geolibre.app)

GeoLibre can:

- Open spatial files (KML, GeoJSON, GeoPackage, Shapefile ZIP)
- Draw points, lines, and polygons on a map
- Create buffers around features
- Overlay multiple data layers
- Display population, land cover, and other raster layers
- Export maps as PNG images (via Print)
- Compute basic statistics within a drawn area

### Worked example — downloading and using a boundary from GADM

The session walked through a complete workflow using Uganda as an example:

1. Go to [gadm.org](https://gadm.org) → click **Data** → select **Uganda** → download as **GeoJSON**
2. The downloaded file contains all districts in Uganda as separate polygons
3. Open GeoLibre → load the GeoJSON file
4. Select one district from the list → isolate it → export as a separate GeoJSON
5. Import the district boundary into eToolkit → generate a report for that district

!!! tip "Due diligence on GADM boundaries"
    Always verify: how many districts does the official government statistics say Uganda has? If GADM says 136 rows and the government says 135 districts, investigate before using in a formal document. Don't accept external boundary data uncritically.

### Admin boundary sources

=== "GADM"
    **[gadm.org](https://gadm.org)** — Global Administrative Areas

    - ~500,000 administrative units worldwide
    - Version 4.1 (Version 5 planned for early 2026)
    - Country → ADM0 (national), ADM1 (province/state), ADM2 (district/county)
    - Formats: GeoJSON, Shapefile, KMZ, GeoPackage
    - Free download, no registration

=== "HDX"
    **[data.humdata.org](https://data.humdata.org)** — Humanitarian Data Exchange (UN OCHA)

    - Large collection of country-level spatial and statistical data: poverty, population, census data, health facilities, education facilities
    - Not fully structured — quality varies by country and dataset
    - Search by country → filter by file type (Shapefile, GeoJSON, CSV)
    - Used in training: download population raster → open in GeoLibre → compute population in a project buffer

=== "GeoBoundaries"
    **[geoboundaries.org/simplifiedDownloads.html](https://www.geoboundaries.org/simplifiedDownloads.html)**

    - Open admin boundaries maintained by the community
    - Simplified downloads page: quick access by country and level
    - GeoJSON format — ideal for web tools

### GeoLibre limitations

!!! note "When to use QGIS instead"
    GeoLibre is web-based — large raster datasets (e.g. a national population grid) can be slow to process. For:
    - Heavy raster statistics → use **QGIS** (free, desktop)
    - Complex spatial queries on large datasets → use **QGIS** or **Google Earth Engine**
    - Quick vector analysis (buffers, overlays, area calculations) on district-scale data → GeoLibre is fast enough

---

## Exercise 3 — Monitoring Indicators for Project Assessment *(14:30–16:00)*

**Objective:** Apply EO and spatial analysis to a monitoring or evaluation scenario for a project area you work on or know well.

**Tools:** eToolkit + GeoLibre + GADM/HDX (as needed)

---

### Part A — Create a before/after comparison in eToolkit

1. Return to your Exercise 1 or 2 area in the eToolkit.
2. Run the analysis with the **current date range** (your "after" snapshot).
3. Re-run with a **time window 3–5 years earlier** (your "before" baseline).
4. Compare the two reports:
    - LULC: has land use changed?
    - Vegetation: is green cover or biomass higher or lower? (ETa or LULC change)
    - Water: has surface water extent changed?
5. Write one sentence describing the most significant change you observe.

### Part B — Spatial analysis in GeoLibre

1. Download a district or admin boundary for your project area from GADM or GeoBoundaries.
2. Open it in GeoLibre.
3. Draw a **1–5 km buffer** around a key feature (a road, a school, a dam, an irrigation intake point).
4. Explore what is inside the buffer: land use, settlement density, visible population.
5. Export the map as a PNG (Print → Download).

### Expected result

- A before/after description (one paragraph) showing change in your project area
- A GeoLibre map image showing the project boundary and buffer zone
- A completed row in the Use-Case Selection Form for the indicator you found most useful

!!! warning "Troubleshooting"
    - **GADM downloads as ZIP** → unzip it first; then load the .geojson or .shp file in GeoLibre
    - **GeoLibre is slow with large national boundaries** → select only the relevant district and export it before doing analysis
    - **eToolkit time-window comparison** → check that the start/end dates in both runs are clearly different; the platform processes historical data going back to 2000

---

*Continue to [Day 4 — Case Studies & Closing](../day-4/index.md)*
