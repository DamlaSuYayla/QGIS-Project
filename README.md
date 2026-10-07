# Per-Capita Electricity Consumption Map of Türkiye (QGIS)

A choropleth map showing total electricity consumption per person (kWh) for each province of Türkiye, built in QGIS.

## What it does

- Combines a per-capita electricity consumption layer with Türkiye's province boundaries
- Colours each province by consumption level, so regional differences in electricity use are visible at a glance

## Files

| File | Description |
| :--- | :--- |
| `DamlaSuYayla_20yöbi1033.qgz` | QGIS project file |
| `Türkiyeİlsınırları.*` | Province boundary layer (shapefile) and its styling (`.qml`) |
| `KişiBaşınaToplamElektrikTüketimi(kWh).*` | Per-capita electricity consumption layer (shapefile) |

## How to open

Download the repository and open the `.qgz` file in **QGIS 3.34** or later. Keep all shapefile parts (`.shp`, `.shx`, `.dbf`, `.prj`, `.cpg`) in the same folder.

## Skills used

QGIS · shapefiles · choropleth mapping · spatial data visualisation
