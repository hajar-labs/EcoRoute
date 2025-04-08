# 🌍 Supply Chain Optimization & Sustainability Tracker

**EcoRoute** is a powerful **supply chain optimization and sustainability tracking tool** built for modern logistics. It helps companies streamline routes, cut fuel costs, and reduce environmental impact by leveraging real-time data and intelligent optimization algorithms.

## 🚀 Project Overview

This platform integrates multiple APIs and tools to provide:
- Real-time route and weather insights
- Fuel price analysis
- Carbon emissions calculations
- AI-driven optimization recommendations
- A real-time dashboard with actionable sustainability metrics

## ✨ Key Features

### 📍 Route Optimization
- Calculates optimal routes using the **TomTom API**.
- Provides distance, estimated travel time, and CO₂ emissions based on truck weight.

### 🌦️ Weather Integration
- Real-time weather data from the **Open-Meteo API**.
- Tracks temperature, wind speed, and conditions affecting logistics operations.

### ⛽ Fuel Price Analysis
- Scrapes up-to-date diesel and gasoline prices from **GlobalPetrolPrices.com**.
- Supports multi-currency pricing and cost estimation for trips.

### ♻️ Carbon Emissions Calculation
- Calculates total emissions and carbon efficiency (kg CO₂/km).
- Helps monitor and compare environmental impact.

### 📊 Report Generation
- Generates comprehensive reports with route details, weather, fuel prices, emissions, and sustainability recommendations.
- Optional **AI-driven suggestions** for improving cost-efficiency and eco-friendliness.

### 🖥️ Real-Time Dashboard
- Interactive UI built with **Streamlit**.
- Displays live data on routes, traffic, weather, fuel costs, and environmental metrics.
- Visualizes routes and KPIs with **Plotly** and **Folium**.

### ⚙️ Optimization Recommendations
- Uses **Google OR-Tools** to propose route improvements.
- Offers smart suggestions like eco-driving tips, timing optimization, and equipment upgrades.

### 🌍 Sustainability Insights
- Assesses carbon offset needs and sustainability performance.
- Compares transport modes (truck, train, ship, air) for emissions benchmarking.

## 🧰 Tech Stack

- **Python**: Core language
- **APIs**:
  - TomTom (routing)
  - Open-Meteo (weather)
- **Web Scraping**: BeautifulSoup
- **Dashboard**: Streamlit
- **Optimization**: Google OR-Tools
- **Visualization**: Plotly, Folium
- **Environment Management**: `.env` for secure API key handling

## 🔄 Workflow

1. **Input**: User enters start/end locations, truck weight, etc.
2. **Data Collection**: Route, weather, and fuel prices are fetched.
3. **Analysis**: Emissions, costs, and optimization strategies are calculated.
4. **Optimization**: Route + cost + emissions
5. **Output**: Results shown in dashboard or saved as reports.

## 💼 Use Cases

Perfect for:
- **Logistics companies** aiming to cut delivery costs.
- **Supply chain managers** seeking efficiency.
- **Sustainability teams** tracking environmental performance.
- Any team making **data-driven logistics decisions**.

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/hajar-labs.git
cd hajar-labs
pip install -r requirements.txt
```

Create a .env file in the root directory to securely store your API keys:
```bash
TOMTOM_API_KEY=your_tomtom_api_key
OPEN_METEO_API_KEY=your_open_meteo_api_key
```

---

## 🚦 Running the Streamlit Dashboard
To launch the real-time dashboard, run:
```bash
streamlit run main.py
```
This will open the interactive dashboard in your default web browser where you can:

- Enter route parameters

- View optimized logistics data

- Generate and download sustainability reports


https://github.com/user-attachments/assets/4463e19b-6690-4f54-b218-5b65f238c43c

