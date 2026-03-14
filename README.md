<img src="banner.png" width="100%" height="200" style="object-fit: cover" align="center">

<div align="center">

<h1> 🚦 Road Accident Dashboard</h1>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://road-accident-dashboard.vercel.app/)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)](https://road-accident-dashboard.vercel.app/)

**A high-performance, real-time dashboard for analyzing road accident trends and hotspots.**

</div>

---

## 📖 Introduction

This project utilizes **Microsoft Excel** to analyze and visualize road accident data from **Kaggle**. By identifying patterns in timing, location, and contributing factors, it provides a live, interactive Excel dashboard designed to help stakeholders make data-driven decisions to improve road safety and infrastructure.

---

## 📂 Source of Dataset

The dataset used in this analysis was sourced from **Kaggle**, a platform for data science and machine learning.

**Data Source Link**: [Road Accident United Kingdom (UK) Dataset](https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk)

The dataset contains detailed information about road accidents, including:

- 📅 **Date and time** of the accident
- 📍 **Location** (latitude, longitude, or area)
- ☁️ **Road conditions** (e.g., weather, lighting)
- 🚗 **Vehicle type** and number of vehicles involved
- 🚑 **Number of casualties** (fatalities and injuries)
- 👥 **Driver demographics** (e.g., age, gender)
- ⚠️ **Contributing factors** (e.g., speeding, alcohol)

---

## 🌟 Key Features

- **🚀 Real-Time Analytics**: Live synchronization with Excel Online for up-to-the-minute data visualization.
- **🖥️ Full-Screen Experience**: Optimized for high-resolution displays with a sleek, immersive layout.
- **📍 Interactive Hotspots**: Identify accident-prone areas using dynamic mapping and data clustering.
- **📱 Responsive Design**: Seamlessly adapts to different screen sizes for accessibility on the go.
- **📊 Dynamic Filtering**: Real-time interactivity with Excel slicers and interactive charts.

---

## 🛠️ Built With

The project leverages a modern web stack to ensure speed and reliability:

- 🧱 **HTML5**: Semantic structure for better SEO and accessibility.
- 🎨 **CSS3**: Custom glassmorphism-inspired UI and responsive grids.
- 📉 **Microsoft Excel**: Robust data processing and live interactive visualization via OneDrive embedding.
- ⚡ **OneDrive Cloud**: Hosting for real-time data persistence.
- 🚀 **Vercel**: Deployment and cloud hosting for the web application.

---

## 📂 Folder Structure

The repository is organized as follows:

- `index.html`: Main entry point for the web dashboard.
- `Project_Details.txt`: Comprehensive documentation on development work, tools, and methodology.
- `Road-Accident-Dashboard.xlsx`: The core Excel workbook containing data and analysis.
- `banner.png` & `favicon.png`: Graphic assets for the UI.
- `Screenshot...`: Visual preview of the dashboard.

---

## ⚙️ Dataset Preprocessing

Effective preprocessing is essential for extracting accurate and meaningful insights. The following steps were carried out using **Microsoft Excel**:

- **🧹 Removal of Blank and Irrelevant Data**: Blank rows and non-essential columns were removed using Excel’s *Filter* and *Go To Special → Blanks → Delete* functionalities.
- **📏 Data Standardization**: Attributes such as road conditions, vehicle type, and accident severity were cleaned and standardized (e.g., ensuring consistency in text formatting).
- **➕ Creation of Helper Columns**: New columns were created to support deeper analysis:
  - **Time of Day**: Morning, Afternoon, Evening, Night (extracted from time).
  - **Day of the Week**: Extracted from the accident date.
  - **Accident Severity**: Categorized based on the number of casualties.
- **🔣 Data Type Formatting**: Dates, times, and numerical values were correctly formatted. Duplicate entries were removed to avoid skewed results.
- **📊 Pivot Tables & Aggregation**: Dynamic pivot tables and slicers were used to summarize patterns and prepare data for the dashboard.

---

## 🔍 Analysis & Insights

This analysis aims to identify key factors contributing to road accidents and highlight high-risk areas to develop safety strategies.

### 🎯 Specific Objectives

- Identify common causes of road accidents.
- Analyze trends by time, day, and month.
- Determine high-risk locations.
- Examine the impact of road conditions on severity.

### 📈 Analysis Results

- **Common Causes**: Speeding (30%), drunk driving (25%), and distracted driving (20%).
- **Temporal Trends**:
  - Accidents are most frequent during **evening (40%)** and **night (30%)** hours.
  - **Friday and Saturday** exhibit the highest accident rates.
  - Trends show an increase during **June and July**.
- **Road Conditions**: Accidents are more severe in **rainy** (Severity Index: 2.5) and **foggy** (Severity Index: 3.0) conditions compared to clear skies.
- **Vehicle Involvement**: Passenger cars (60%) and motorcycles (20%) are most frequently involved.

---

## 🖼️ Visualizations

The following visualizations were implemented to present the analysis results:

- **📊 Bar Charts**: Number of accidents by contributing cause.
- **📈 Line Charts**: Monthly accident trends over the year.
- **🗺️ Heat Maps**: Accident frequency by location (High-risk areas).
- **📦 Box Plots**: Distribution of accident severity by road condition.
- **🍕 Pie Charts**: Percentage of accidents by vehicle type.
- **📍 Interactive Map**: Geographical distribution with filters for date and severity.
- **🎴 KPI Cards**: Real-time display of accident and fatality rates.

---

## 🚀 Getting Started

To run this project locally, follow these simple steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ajaygangwar945/Road-Accident-Dashboard.git
   ```

2. **Open the Dashboard**:
   Simply open the `index.html` file in any modern web browser.

   ```bash
   cd Road-Accident-Dashboard
   start index.html
   ```

---

## 📸 Dashboard Preview

<div align="center">
  <img src="Screenshot 2026-03-14 195429.png" alt="Accident Analysis Live Dashboard" width="100%">
  
</div>

---

## 🚀 Live Dashboard

View the live interactive Excel analysis dashboard.

[![View Dashboard](https://img.shields.io/badge/Excel-View_Dashboard-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://road-accident-dashboard.vercel.app/)

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 Supporting Documentation

For a more in-depth look at how this project was conceived and built, please refer to the [Project_Details.txt](Project_Details.txt) file. It contains:
- Detailed development workflow.
- In-depth tool descriptions.
- Conceptual "Why" behind the analysis.

---

---

<div align="center">
  Developed with ❤️ by <a href="https://github.com/ajaygangwar945">Ajay Gangwar</a>
</div>
