---

# 🗺️ MapMine – OSM Feature Extractor

MapMine is a desktop GIS application built with **Python, Tkinter, and OSMnx** that allows users to extract, visualize, and export OpenStreetMap (OSM) features such as **roads, buildings, parks, and water bodies** for any selected Area of Interest (AOI).

With its clean modern UI and interactive visualization, MapMine bridges the gap between **ease of use** and **powerful spatial data extraction**.

---

## ✨ Features

* 🔍 **Search Area of Interest (AOI)**

  * Search by **place name** (e.g., "Delhi, India")
  * Or provide **bounding box coordinates**

* 🗂️ **Select OSM Features**

  * Roads 🛣️
  * Buildings 🏠
  * Parks & Green Spaces 🌳
  * Water Bodies 💧

* 📊 **Interactive Visualization**

  * Preview extracted data using **matplotlib**
  * Toggle features on/off

* 💾 **Export Options**

  * Save data as **GeoJSON, Shapefile, or CSV**
  * Auto-organized outputs

* 🎨 **Modern User Interface**

  * Collapsible sidebar for maximizing map space
  * Tabbed interface for **AOI, Features, and Export**
  * Status bar with live progress updates

---

## 📸 Screenshots

# Main UI
<img width="773" height="939" alt="Window" src="https://github.com/user-attachments/assets/aa9bbaa8-4b7f-4e15-9fcc-1862cecb3ef4" />
# Feature Selection
<img width="738" height="408" alt="Feature" src="https://github.com/user-attachments/assets/fb3a984b-9102-4538-95b8-c8fccf3eae5f" />
# Map Preview
<img width="1918" height="1015" alt="Map preview" src="https://github.com/user-attachments/assets/d5c3a2a3-f614-49d9-85ed-e94c267e2c48" />



---

## 📦 Installation

### 1. Clone Repository

```bash
git clone https://github.com/<Sammaglin>/MapMine.git
cd MapMine
```

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate      # On Windows
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the app with:

```bash
python src/main.py
```

1. Enter **AOI name** or **bounding box coordinates**
2. Select features you want to extract
3. Click **Fetch & Visualize**
4. Save outputs in your preferred format

---

## 🛠️ Tech Stack

* **Python 3.9+**
* **Tkinter** → UI framework
* **OSMnx** → OSM data fetching
* **GeoPandas** → spatial data handling
* **Matplotlib** → map plotting
* **Requests** → API calls

---

## 🧩 Roadmap

* [ ] Add **custom polygon AOI selection**
* [ ] Integrate **Folium/Leaflet interactive maps**
* [ ] Add **multi-feature selection with filters**
* [ ] Export to **PostGIS / Spatialite databases**
* [ ] Package as **.exe / .app** for easy installation

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify it.

---

## 👨‍💻 Author

Developed by **Ansh Upadhyay** ✨
If you like this project, consider giving it a ⭐ on GitHub!

---
