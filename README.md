# 🏙️ Urban Climate Twin

A photorealistic, interactive 3D model of NYC neighborhoods that simulates the impact of green infrastructure interventions — like trees, green roofs, and permeable streets — to help fight urban heat islands, reduce carbon, and promote environmental equity.

---

## 🌍 Live Demo

[👉 Add hosted link here (e.g., GitHub Pages or Vercel)]

---

## 🔥 Problem

Cities face rising temperatures and worsening air quality — especially in underserved neighborhoods with little green infrastructure. Planners lack clear, visual tools to understand and simulate the local impact of climate-friendly upgrades.

---

## 🎯 What It Does

- Visualizes NYC blocks in **photorealistic 3D** using Google Maps 3D Tiles.
- Allows simulation of:
  - 🌳 **Street tree planting**
  - 🌱 **Green roof installations**
  - 🧱 **Permeable pavement upgrades**
- Calculates environmental impact:
  - 🌡️ **Surface temperature reduction**
  - 🌿 **Carbon offset**
  - 🟩 **Green Equity Score**
- Prioritizes areas with high heat vulnerability and low green coverage.

---

## 🧰 Tech Stack

| Component        | Tool                        |
|------------------|-----------------------------|
| Frontend         | JavaScript + HTML/CSS       |
| 3D Maps          | Google Maps Platform (3D Tiles API) |
| Visualization    | MapLibre / CesiumJS / Three.js |
| Data Processing  | Python, Pandas              |
| Storage          | JSON / SQLite               |
| Optional ML      | Python + CV (e.g. rooftop detection) |

---

## 🗺️ Datasets & APIs

### NYC-Specific
- 🌳 [NYC Street Tree Census](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh)
- 🏢 [NYC Building Footprints](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh)
- 🏘️ [PLUTO Dataset](https://www.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page)

### Environmental
- 🌡️ [NASA SEDAC Urban Heat Island Data](https://sedac.ciesin.columbia.edu/data/set/ulis-global-urban-heat-island)
- 🌬️ [OpenAQ API](https://docs.openaq.org/) – Air Quality
- 🌀 [NOAA Climate Data](https://www.ncei.noaa.gov/cdo-web/)

### Visualization
- 🗺️ [Google Maps 3D Tiles API](https://developers.google.com/maps/documentation/3d-tiles/overview)

---

## 🧪 Setup Instructions

```bash
git clone https://github.com/yourusername/urban-climate-twin.git
cd urban-climate-twin

# Run a local server (Python 3)
python3 -m http.server 8000
