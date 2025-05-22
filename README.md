# UrbanClimateTwin
# 🏙️ Urban Climate Twin

A photorealistic, interactive 3D model of real NYC neighborhoods that simulates the impact of urban greening interventions like trees, green roofs, and permeable streets — designed to fight urban heat islands and climate inequality.

## 🌍 Live Demo

[Add link here if hosted on GitHub Pages, Vercel, etc.]

---

## 🔥 Problem

Urban neighborhoods — especially low-income ones — face extreme heat and poor air quality due to lack of green infrastructure. Planning climate-friendly upgrades is difficult without clear, visual tools.

---

## 🎯 What It Does

- Visualizes a real NYC neighborhood in 3D using Google Maps Photorealistic 3D Tiles.
- Lets users simulate urban greening interventions like:
  - Tree planting
  - Green roofs
  - Permeable pavement
- Shows estimated climate impact:
  - Surface temperature reduction
  - Air quality improvement
  - Carbon offset
- Prioritizes heat-stressed and underserved communities.

---

## 🧰 Tech Stack

| Component        | Tool                        |
|------------------|-----------------------------|
| Frontend         | JavaScript + HTML/CSS       |
| 3D Maps          | Google Maps Platform (3D Tiles API) |
| Data Processing  | Python, Pandas              |
| Visualization    | MapLibre / CesiumJS / Three.js |
| Data Storage     | JSON / SQLite (for local use) |
| Optional ML      | Python (e.g. for roof/tree detection) |

---

## 🗺️ Datasets & APIs
https://developers.google.com/maps/documentation/javascript/get-api-key

### NYC-Specific
- 🌳 **[NYC Street Tree Map](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh)**
- 🏢 **[NYC Building Footprints](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh)**
- ☀️ **[NYC PLUTO Dataset](https://www.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page)** (building details, land use)
- 🌡️ **[NASA SEDAC Urban Heat Island Data](https://sedac.ciesin.columbia.edu/data/set/ulis-global-urban-heat-island)** (or NOAA)

### External APIs
- 🌐 **[Google Maps 3D Tiles API](https://developers.google.com/maps/documentation/3d-tiles/overview)**
- 🌀 **[OpenAQ](https://docs.openaq.org/) – Air Quality API**
- 🌧️ **[NOAA Climate Data Online](https://www.ncei.noaa.gov/cdo-web/webservices/v2)**

---

## 🧪 Setup Instructions


## 🎯 How to Use

1. **Zoom into a real NYC neighborhood**  
   Example: Harlem, Lower East Side, South Bronx

2. **Toggle interventions**
   - ✅ Add **street trees**
   - ✅ Install **green roofs**
   - ✅ Replace pavement with **permeable materials**

3. **View real-time environmental impact**
   - 🌡️ Estimated **temperature reduction**
   - 🌿 Estimated **carbon offset**
   - 🟩 Calculated **Green Equity Score** for the area

4. **Share or export** your customized **Urban Climate Twin**
   - Download summary
   - Screenshot map
   - (Future: Export to city planning tools)

---

## 💡 Future Ideas

- 🤖 ML model to **auto-detect rooftops** suitable for solar panels or green installations
- 🏛️ Integration with **city planner dashboards** and community outreach platforms
- 🌍 Scale to other cities: **Chicago, San Francisco, Tokyo**, etc.

---

## 🙌 Acknowledgements

- 📊 [**NYC Open Data**](https://opendata.cityofnewyork.us/) — Tree census, building footprints, PLUTO datasets  
- 🗺️ [**Google Maps Platform**](https://developers.google.com/maps/documentation/3d-tiles/overview) — Photorealistic 3D Tiles API  
- 🌡️ [**NOAA**](https://www.ncei.noaa.gov/) — Historical temperature and climate data  


---
### MIT Liscense  
## 📦 Data + Tools Recap (Quick Access)

| Source | What You'll Use | Link |
|--------|------------------|------|
| NYC Tree Census | Tree locations + species | [🔗 Link](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh) |
| NYC Building Footprints | Roofs for green roof simulation | [🔗 Link](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh) |
| PLUTO Data | Building heights, types, area | [🔗 Link](https://www.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page) |
| Google 3D Tiles API | 3D model rendering | [🔗 Docs](https://developers.google.com/maps/documentation/3d-tiles/overview) |
| OpenAQ | Real-time air quality | [🔗 API](https://docs.openaq.org/) |
| NOAA/NASA | Historical temp + climate trends | [🔗 NOAA](https://www.ncei.noaa.gov/) / [🔗 SEDAC](https://sedac.ciesin.columbia.edu/data/set/ulis-global-urban-heat-island) |

---

Would you like me to generate a file structure and sample boilerplate code next (e.g. folder tree, `index.html`, `main.js`, etc.)?

```bash
git clone https://github.com/yourusername/urban-climate-twin.git
cd urban-climate-twin
# Run frontend locally (simple Python HTTP server or use Vite/Parcel)
python3 -m http.server 8000 
