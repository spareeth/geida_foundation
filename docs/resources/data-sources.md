# Data Sources

Open and publicly accessible spatial data for IsDB project work. All sources listed here are free to access.

!!! note "Open access and open use"
    Free accessibility does not automatically mean unrestricted use. Check the licence conditions for each dataset, particularly for use in formal project documents or publications.

---

## Admin Boundaries

### GADM — Global Administrative Areas

**[gadm.org](https://gadm.org)**

Approximately 500,000 administrative units worldwide. Currently version 4.1.

- **ADM0** — National boundary
- **ADM1** — Province / state / region
- **ADM2** — District / county

**Download formats:** GeoJSON · Shapefile · KMZ (zipped KML) · GeoPackage

**How to use in this training:**
1. Go to gadm.org → Data → select your country
2. Download as GeoJSON
3. Open in GeoLibre → select your district → export
4. Import into eToolkit or WaPOR for analysis

!!! warning "Due diligence required"
    Always verify boundary data before using it in a formal project document. Cross-check the number and names of administrative units against official government statistics or national mapping agency publications. Boundary data from external repositories may not reflect the most recent administrative reorganisations. Do not assume external boundary data is authoritative without independent verification.

### GeoBoundaries

**[geoboundaries.org](https://www.geoboundaries.org)** · [Simplified Downloads](https://www.geoboundaries.org/simplifiedDownloads.html)

Open, community-supported administrative boundaries. The simplified downloads page provides quick access by country and administrative level. GeoJSON format — compatible with all web tools used in this training.

### OpenStreetMap

**[openstreetmap.org](https://www.openstreetmap.org)**

Community-mapped roads, buildings, infrastructure, and administrative areas. Useful for project context maps and base layers. Download via [Overpass Turbo](https://overpass-turbo.eu) or [GeoFabrik](https://download.geofabrik.de) for regional extracts.

---

## Humanitarian & Socioeconomic Data

### HDX — Humanitarian Data Exchange

**[data.humdata.org](https://data.humdata.org)**

UN OCHA's open data platform: poverty indices, population grids, census data, health facility locations, education facilities, conflict data — organised by country.

Used in this training (Day 3): search for your country → download population grid → open in GeoLibre → compute population within a project buffer.

Dataset quality and currency varies by country and contributor. Review metadata and source information before use.

**Search tips:** Use country name as the primary filter, then filter by file format (Shapefile, GeoJSON, CSV, GeoTIFF) for spatial data.

### WorldPop

**[worldpop.org](https://www.worldpop.org)**

Gridded population estimates at 100 m resolution for most countries, based on modelled distributions. Useful for estimating populations within a project boundary. These are modelled estimates; verify against national census data where available.

### FAO GeoNetwork

**[fao.org/geonetwork](https://www.fao.org/geonetwork)**

Agricultural land use, crop area, irrigation extent, food insecurity indicators, livestock density — freely downloadable.

---

## Earth Observation & Climate Data

### FAO WaPOR

**[data.apps.fao.org/wapor](https://data.apps.fao.org/wapor/?lang=en)**

High-resolution (20–100 m) evapotranspiration (ETa), water productivity, biomass, and relative root zone soil moisture (RZSM) for Africa and the Near East. Three spatial levels: continental L1 (250 m), country L2 (100 m, selected countries), and irrigation scheme L3 (20 m, specific command areas).

Primary tool for agriculture and water projects — see [Day 2 afternoon](../day-2/afternoon.md) for the full walkthrough.

### Copernicus Dataspace

**[dataspace.copernicus.eu](https://dataspace.copernicus.eu)**

The European Space Agency's data portal for all Sentinel satellites: Sentinel-1 (synthetic aperture radar), Sentinel-2 (multispectral optical), Sentinel-3, Sentinel-5P (atmospheric). Free download; registration required.

### USGS EarthExplorer

**[earthexplorer.usgs.gov](https://earthexplorer.usgs.gov)**

Landsat archive — over 40 years of optical imagery at 30 m resolution. Free download; USGS account required.

### Google Earth Engine

**[earthengine.google.com](https://earthengine.google.com)**

Cloud-based geospatial analysis platform with a large satellite data archive. Used by advanced analysts; requires programming in JavaScript or Python. Forms part of the data processing infrastructure behind several tools used in this training.

### NASA POWER

**[power.larc.nasa.gov](https://power.larc.nasa.gov)**

Meteorological data for any point on Earth — temperature, precipitation, solar radiation — without registration. Useful for generating site-level climate profiles and contextual baseline data.

### CHIRPS

**Climate Hazards Group InfraRed Precipitation with Station data** — a blended satellite-gauge rainfall dataset at 0.05° resolution for Africa and other regions, extending from 1981 to near-present. Available through EarthMap, Google Earth Engine, and direct download from [chc.ucsb.edu/data/chirps](https://www.chc.ucsb.edu/data/chirps).

---

## Summary table

| Source | Type | Best for | Free access? |
|---|---|---|---|
| GADM | Vector (admin boundaries) | Project boundaries (with due diligence) | Yes |
| GeoBoundaries | Vector (admin boundaries) | Quick boundary download | Yes |
| HDX | Mixed (spatial + tabular) | Population, poverty, facilities | Yes |
| WorldPop | Raster (modelled population) | Beneficiary estimation | Yes |
| FAO WaPOR | Raster (ET, RZSM, biomass) | Agriculture & water projects (Africa/Near East) | Yes |
| Copernicus Dataspace | Raster (satellite imagery) | Custom optical/radar analysis | Yes (registration required) |
| USGS EarthExplorer | Raster (Landsat) | Historical change analysis | Yes (account required) |
| NASA POWER | Tabular (climate) | Site climate profiles | Yes |
