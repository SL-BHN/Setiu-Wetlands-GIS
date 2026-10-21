# Setiu Wetlands GIS

This GitHub repository provides geospatial data to facilitate research and spatial analysis in the **Setiu Wetlands** (Terengganu, Malaysia). The primary file is a GeoPackage (".gpkg") containing pre-packaged vector layers ready for direct use in GIS applications such as QGIS or ArcGIS.

---

## Repository Contents

**"Setiu Wetlands GIS.gpkg"** : A unified GeoPackage containing all spatial layers for the study area.

### Included Layers

1. **Mangroves**
   * **Source :** Global Mangrove Watch (2020)
   * **Description :** Extent and monitoring of mangrove ecosystems.

2. **Setiu Wetlands State Park**
   * **Source :** Taman Negeri Setiu Wetlands (2026)
   * **Description :** Official boundaries of the State Park.

3. **Water Area**
   * **Description :** Hydrological features of water in Setiu Lagoon and tributaries.

4. **Terengganu State (Costal Area)**
   * **Description :** Coastal water zone of Terengganu State.

---

## Coordinate Reference System (CRS)

All layers within this GeoPackage use the official projected coordinate system for Peninsular Malaysia:

  EPSG:3375 GDM2000 / Peninsula RSO
  **Official Reference** : https://epsg.io/3375

**WARNING** Ensure your QGIS project's CRS matches when combining these layers with global basemaps (EPSG:3375 GDM2000 / Peninsula RSO).
<span style="color:red">**WARNING** Ensure your QGIS project's CRS matches when combining these layers with global basemaps (EPSG:3375 GDM2000 / Peninsula RSO).</span>
---

## Getting Started with QGIS

1. Download the "Setiu Wetlands GIS.gpkg" file directly from this repository (or clone the repository).
2. Open **QGIS**.
3. Drag and drop the ".gpkg" file directly into QGIS, or connect to it via the **Data Source Manager** (`Vector` -> `GeoPackage`).
4. Select the layers you wish to load into your project.

---

## Citation & Attribution

**Usage:** Provided open-access for academic, research, and conservation purposes.
**Citation:** If you use these dataset layers in your publications or reports, please attribute the original sources listed above alongside this repository.

---

Sulayman Bouhassoun (2026) Universiti Malaysia Terengganu, Malaysia
Université Lumière Lyon 2, France
