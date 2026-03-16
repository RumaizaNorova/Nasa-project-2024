# 🌍 NASA NDVI Viewer — Agricultural Insights Tool

🔗 **Live App:**  
https://nasa-project-2024.streamlit.app/

An interactive **Streamlit dashboard** that visualizes **NASA satellite vegetation data (NDVI)** to help analyze crop health and environmental conditions anywhere on Earth.

Built for the **🚀 NASA Space Apps Challenge**, this tool allows users to explore vegetation health through satellite imagery and compare regions side-by-side.


---

# 🌱 What is NDVI?

**NDVI (Normalized Difference Vegetation Index)** measures vegetation health using satellite imagery.

NDVI values range from:

| NDVI Value | Meaning |
|------------|--------|
| **-1 – 0** | Water / snow / clouds |
| **0 – 0.2** | Bare soil |
| **0.2 – 0.5** | Sparse vegetation |
| **0.5 – 1.0** | Healthy dense vegetation 🌿 |

This tool allows users to **visualize NDVI data over time** using NASA Earth observation data.

---

# ✨ Features

## 📍 Single Location Analysis
- Enter **latitude and longitude**
- Select a **date range**
- Generate **NDVI satellite overlays**
- View vegetation health over time

## 🌍 NDVI Time Series
- Analyze vegetation changes across multiple dates
- Adjustable **time intervals**
- Download NDVI imagery for analysis

## ⚖️ Location Comparison
Compare **two regions side-by-side** to analyze:
- Crop health
- Environmental differences
- Vegetation growth patterns

## 🗺 Interactive Satellite Map
- Satellite overlays rendered using **Folium**
- Interactive zoom and navigation
- NDVI visualization directly on the map

## ⬇ Download NDVI Images
Users can download satellite imagery directly from NASA.

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|--------|
| **Streamlit** | Web application framework |
| **Folium** | Interactive maps |
| **NASA Earth API** | Satellite imagery data |
| **Python** | Core application logic |
| **Requests** | API communication |
| **Pandas** | Data handling |

---

# 📡 NASA API Used

The app retrieves satellite imagery from the **NASA Earth Assets API**:

https://api.nasa.gov/planetary/earth/assets

Example request:

```
https://api.nasa.gov/planetary/earth/assets?lat=50&lon=-90&date=2022-01-01
```

---

# 🚀 How to Run Locally

## 1️⃣ Clone the repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

## 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

## 3️⃣ Run the app

```
streamlit run app.py
```

---

# 📁 Project Structure

```
.
├── app.py
├── requirements.txt
├── data_preprocessing.py
└── README.md
```

---

# 🌾 Use Cases

This project can be useful for:

- **Farmers** monitoring crop health
- **Researchers** studying vegetation trends
- **Environmental scientists**
- **Climate monitoring**
- **Agricultural planning**

---

# 🔮 Future Improvements

Possible extensions for the project:

- 🌍 Global NDVI heatmaps  
- 📊 Vegetation trend graphs  
- 🤖 Crop yield prediction using ML  
- 📡 Integration with additional NASA datasets  
- ☁ Satellite time-series storage  

---

# 🛰 Built For

🚀 **NASA Space Apps Challenge**

A global hackathon focused on solving Earth and space challenges using open NASA data.

---

# ⭐ Support

If you find this project interesting:

- ⭐ Star the repository  
- 🌍 Share the project  
- 🚀 Contribute improvements

---

**Exploring Earth from space, one pixel at a time. 🌱**
