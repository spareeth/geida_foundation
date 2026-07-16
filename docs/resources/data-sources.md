# Data Sources

Open and public spatial data for IsDB project work. All sources listed here are free to access and use.

---

## Admin Boundaries

### GADM — Global Administrative Areas

**[gadm.org](https://gadm.org)**

~500,000 administrative units worldwide. Currently version 4.1.

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
    Always verify boundary data before using in a formal project document. Cross-check the number of administrative units against official government statistics. "Don't believe whatever is coming from it — you have to double check." — Dr Sajid Pareeth

### GeoBoundaries

**[geoboundaries.org](https://www.geoboundaries.org)** · [Simplified Downloads](https://www.geoboundaries.org/simplifiedDownloads.html)

Open, community-supported admin boundaries. The simplified downloads page gives quick access by country and administrative level. GeoJSON format — ideal for all web tools used in this training.

### OpenStreetMap

**[openstreetmap.org](https://www.openstreetmap.org)**

Community-mapped roads, buildings, infrastructure, and administrative areas. Useful for project context maps and base layers. Download via [Overpass Turbo](https://overpass-turbo.eu) or [GeoFabrik](https://download.geofabrik.de) for regional extracts.

---

## Humanitarian & Socioeconomic Data

### HDX — Humanitarian Data Exchange

**[data.humdata.org](https://data.humdata.org)**

UN OCHA's open data platform: poverty indices, population grids, census data, health facility locations, education facilities, conflict data — country by country.

Used in this training (Day 3): search for your country → download population grid → open in GeoLibre → compute population in a project buffer.

**Search tips:** Use country name as the main filter, then filter by file format (Shapefile, GeoJSON, CSV, GeoTIFF) for spatial data.

### WorldPop

**[worldpop.org](https://www.worldpop.org)**

High-resolution gridded population estimates at 100 m resolution for most countries. Useful for estimating beneficiary populations within a project boundary.

### FAO GeoNetwork

**[fao.org/geonetwork](https://www.fao.org/geonetwork)**

Agricultural land use, crop area, irrigation extent, food insecurity indicators, livestock density — all freely downloadable.

---

## Earth Observation & Climate Data

### FAO WaPOR

**[data.apps.fao.org/wapor](https://data.apps.fao.org/wapor/?lang=en)**

High-resolution (20–100 m) evapotranspiration, water productivity, biomass, and root zone soil moisture (RZSM) for Africa and the Near East. Three spatial levels: continental (L1), country (L2), irrigation scheme (L3).

Primary tool for agriculture and water projects — see [Day 2 afternoon](../day-2/afternoon.md) for the full walkthrough.

### Copernicus Dataspace

**[dataspace.copernicus.eu](https://dataspace.copernicus.eu)**

The European Space Agency's data portal for all Sentinel satellites: Sentinel-1 (radar), Sentinel-2 (optical), Sentinel-3, Sentinel-5P (atmospheric). Free download, registration required.

### USGS EarthExplorer

**[earthexplorer.usgs.gov](https://earthexplorer.usgs.gov)**

Landsat archive — 40+ years of optical imagery at 30 m resolution. Free download, USGS account required.

### Google Earth Engine

**[earthengine.google.com](https://earthengine.google.com)**

Cloud-based analysis platform with a massive satellite data archive. Used by advanced analysts; requires programming (JavaScript or Python). The data backbone behind many web tools used in this training.

### NASA POWER

**[power.larc.nasa.gov](https://power.larc.nasa.gov)**

Meteorological data for any point on Earth — temperature, precipitation, solar radiation — with no registration. Useful for project site climate profiles and baseline data.

### CHIRPS

**Climate Hazards Group InfraRed Precipitation with Station data** — rainfall data at 0.05° resolution for Africa and beyond, going back to 1981. Available through EarthMap, Google Earth Engine, and direct download from [chc.ucsb.edu/data/chirps](https://www.chc.ucsb.edu/data/chirps).

---

## Summary table

| Source | Type | Best for | Free? |
|---|---|---|---|
| GADM | Vector (admin boundaries) | Project boundaries | ✅ |
| GeoBoundaries | Vector (admin boundaries) | Quick boundary download | ✅ |
| HDX | Mixed (spatial + tabular) | Population, poverty, facilities | ✅ |
| WorldPop | Raster (population) | Beneficiary estimation | ✅ |
| FAO WaPOR | Raster (ET, RZSM, biomass) | Agriculture & water projects | ✅ |
| Copernicus Dataspace | Raster (satellite imagery) | Custom optical/radar analysis | ✅ |
| USGS EarthExplorer | Raster (Landsat) | Historical change analysis | ✅ |
| NASA POWER | Tabular (climate) | Site climate profiles | ✅ |
