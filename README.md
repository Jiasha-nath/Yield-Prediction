# 🌾 Yield Prediction — Crop Yield Estimation Using Gaussian Process & Remote Sensing Indices

A machine learning pipeline that predicts agricultural crop yield using
satellite-derived spectral indices and weather data, built with a
Gaussian Process regression model in Python.

---

## 📌 Overview

This project builds a scalable crop yield prediction model using real-world
agricultural data from **Thoothukudi, Tamil Nadu**. Satellite-derived vegetation
and water indices are used as independent variables to estimate crop yield,
enabling data-driven insights for precision agriculture and farming decisions.

---

## 🎯 Variables

| Type                | Features                                      |
|---------------------|-----------------------------------------------|
| **Dependent**       | Yield                                         |
| **Independent**     | NDVI, NDWI, FAPAR, LAI, LSWI                 |

### Index Descriptions

| Index   | Full Name                                        | What It Measures                     |
|---------|--------------------------------------------------|--------------------------------------|
| NDVI    | Normalized Difference Vegetation Index           | Vegetation health & density          |
| NDWI    | Normalized Difference Water Index                | Water content in vegetation          |
| FAPAR   | Fraction of Absorbed Photosynthetically Active Radiation | Photosynthesis activity      |
| LAI     | Leaf Area Index                                  | Canopy leaf coverage                 |
| LSWI    | Land Surface Water Index                         | Soil & canopy moisture               |

---

## 🗺️ Dataset

| Parameter       | Details                                              |
|-----------------|------------------------------------------------------|
| Source          | Thoothukudi CCE with parameters and weather data     |
| Region          | Thoothukudi, Tamil Nadu, India                       |
| File            | `Thoothukudi_CCE_with_parameters_and_weather_data.xls` |
| Coverage        | 10+ agricultural regions                             |

---

## 🛠️ Tech Stack

| Category        | Tools / Libraries                          |
|-----------------|--------------------------------------------|
| Language        | Python                                     |
| ML Model        | Gaussian Process Regression (GP)           |
| Data Analysis   | Pandas, NumPy                              |
| Visualization   | Matplotlib                                 |
| Environment     | Jupyter Notebook                           |
| Data Format     | XLS (Excel), Jupyter Notebook              |

---

## 📂 Repository Structure
```
Yield-Prediction/
│
├── GP_yield.ipynb                                    # Main Jupyter notebook
├── Thoothukudi_CCE_with_parameters_and_weather_data.xls  # Raw dataset
└── README.md
```

---

## ⚙️ Setup & Installation

1. **Clone the repository**
```bash
   git clone https://github.com/Jiasha-nath/Yield-Prediction.git
   cd Yield-Prediction
```

2. **Install dependencies**
```bash
   pip install numpy pandas matplotlib scikit-learn openpyxl jupyter
```

3. **Launch Jupyter Notebook**
```bash
   jupyter notebook GP_yield.ipynb
```

---

## 💡 How It Works
```
Raw Agricultural & Weather Data (XLS)
    ↓
Data Preprocessing & Feature Extraction
    ↓
Spectral Index Features: NDVI, NDWI, FAPAR, LAI, LSWI
    ↓
Gaussian Process Regression Model
    ↓
Crop Yield Prediction
    ↓
Visualization & Analysis
```

---

## 🌱 Use Case

This project was developed as part of a **Data Science internship at NECTAR
(North-East Centre for Technology Application and Reach)**, where ML pipelines
were engineered for a crop yield estimation pilot spanning 10+ regions,
translating raw agricultural data into actionable business insights.

---

## 👤 Author

**Jiasha Nath**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jiasha--nath-blue?logo=linkedin)](https://www.linkedin.com/in/jiasha-nath-523b79211)
[![Email](https://img.shields.io/badge/Email-jiasha.nath.adtu@gmail.com-red?logo=gmail)](mailto:jiasha.nath.adtu@gmail.com)

---

## 📜 License

This project is licensed under the MIT License.
