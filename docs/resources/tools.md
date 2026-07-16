# Online GIS Tools

Web-based geospatial tools used in this training. All are free to use; no installation required.

---

## Tools at a glance

| Tool | Best for | Resolution | Used on |
|---|---|---|---|
| [eToolkit](#etoolkit) | Automated project reports | Multi-scale | Days 1–4 |
| [WaPOR](#fao-wapor) | Agriculture & irrigation | 20–100 m | Day 2 |
| [Google Earth Web](#google-earth-web) | Boundary drawing, imagery | Sub-metre | Day 1 |
| [GeoLibre](#geolibre) | Spatial file viewing & analysis | As loaded | Day 3 |
| [EarthMap](#earthmap) | Risk screening, population | National/basin | Day 4 |
| [Strata](#strata) | Extended risk analytics | National/basin | Day 4 |
| [GeoJSON.io](#geojsonio) | Format conversion & editing | As loaded | Reference |
| [GADM](#gadm--geoboundaries) | Admin boundaries | Country → district | Days 3–4 |
| [GeoBoundaries](#gadm--geoboundaries) | Admin boundaries | Country → district | Days 1, 3 |

---

## eToolkit

**[etoolkit.terrawatch.net](https://etoolkit.terrawatch.net)**

IsDB's browser-based geospatial platform. The primary tool for this training.

**What it does:**
- Automated EO report generation for any user-defined area
- Outputs: Land Use/Land Cover (LULC), precipitation, evapotranspiration, future climate projections, AI-powered sector recommendations
- Theme, Phase, and Country filters tailor outputs to your project context
- Export full analysis as a downloadable PDF report

**Training credentials (shared):** Username `user1` · Password `etoolkit@IsDB`

**Used in:** [Day 1 Exercise 1](../day-1/afternoon.md#exercise-1--report-generation-in-etoolkit) · [Day 2 Exercise 2](../day-2/morning.md#exercise-2--etoolkit-continued) · [Day 4 Case Study 1](../day-4/morning.md#case-study-1--eo-baseline--site-suitability)

---

## FAO WaPOR

**[data.apps.fao.org/wapor](https://data.apps.fao.org/wapor/?lang=en)**

The FAO Water Productivity Open-access Portal — high-resolution water use and vegetation data for Africa and the Near East.

**What it does:**
- Actual evapotranspiration (ETa), water productivity, biomass production, root zone soil moisture (RZSM)
- Three spatial levels: L1 continental (250 m), L2 country (100 m), L3 irrigation scheme (20 m)
- Temporal resolution: dekadal (10-day), monthly, annual
- Time series explorer for trend analysis

**Used in:** [Day 2 afternoon — Session 5](../day-2/afternoon.md#session-5--introduction-to-wapor--field-level-analysis)

---

## Google Earth Web

**[earth.google.com/web](https://earth.google.com/web)**

Free browser-based satellite imagery viewer.

**What it does:**
- Satellite and aerial imagery worldwide
- Search by location, navigate to project areas
- Draw points, lines, and polygons — save as KML projects
- Export KML files for use in eToolkit, GeoLibre, and other tools
- No account needed for viewing; Google account needed to save projects

**Used in:** [Day 1 Exercise 1A](../day-1/afternoon.md#exercise-1a--define-your-area-in-google-earth-web)

---

## GeoLibre

**[viewer.geolibre.app](https://viewer.geolibre.app)**
**Tutorial site:** [geolibre.app](https://geolibre.app)

Web-based GIS viewer and spatial analysis tool.

**What it does:**
- Open spatial files: KML, GeoJSON, GeoPackage, Shapefile (as ZIP)
- Draw buffers around features
- Overlay multiple layers
- Display population, land cover, and other raster layers
- Export map as PNG (via Print)
- Compute statistics within a drawn area

**Best for:** Vector analysis — opening boundaries, drawing buffers, exploring layers at district scale. For heavy raster analysis on large datasets, QGIS is faster.

**Used in:** [Day 3 afternoon — Session 8](../day-3/afternoon.md#session-8--spatial-analysis-using-geolibre)

---

## EarthMap

**[earthmap.org](https://earthmap.org)**

Risk analysis, land cover, population, climate, and environmental indicators at national and basin scale.

**What it does:**
- Climate risk layers: drought, flood, heat stress, precipitation variability
- Population exposure analysis
- National and basin-scale environmental context for project risk assessments
- Country-level dashboards

**Used in:** [Day 4 morning — Case Study 2](../day-4/morning.md#case-study-2--climate-risk-screening)

---

## Strata

**[strata.earthmap.org](https://strata.earthmap.org)**

Extended analytical interface built on EarthMap data, with more indicator layers and exploration tools.

**Used in:** [Day 4 morning](../day-4/morning.md#new-tools-introduced-on-day-4)

---

## GeoJSON.io

**[geojson.io](https://geojson.io)**

Simple browser tool for drawing, editing, and converting spatial data.

**What it does:**
- Draw points, lines, and polygons directly on a basemap
- Edit GeoJSON, KML, and CSV files
- Convert between spatial formats
- Useful for quick boundary editing and format conversion

---

## GADM / GeoBoundaries

Admin boundary sources — see [Data Sources](data-sources.md#admin-boundaries) for full details.

- **GADM:** [gadm.org](https://gadm.org) — ~500,000 units, GeoJSON/Shapefile/KMZ/GeoPackage
- **GeoBoundaries:** [geoboundaries.org/simplifiedDownloads.html](https://www.geoboundaries.org/simplifiedDownloads.html) — simplified downloads, GeoJSON
