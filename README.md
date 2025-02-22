### **Information Visualization**
A Multiview Visualization System for Car Accident Data

---

## **Project Overview**
This project presents an interactive **Information Visualization System** for analyzing **U.S. traffic accident data (2016–2023)**. The system provides **multiview visualization techniques** to explore accident trends across different geographical regions, weather conditions, and temporal factors.

The visualizations aim to:
- Identify accident hotspots.
- Analyze correlations between weather and accident severity.
- Investigate temporal patterns to detect peak accident hours.
- Provide interactive, user-friendly data exploration.

---

## **Dataset**
- **Source:** Kaggle - [US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Attributes Analyzed:**
  - **Geographical Factors:** County, city, and state.
  - **Temporal Factors:** Time of the day, year, and seasonality.
  - **Weather Conditions:** Rain, fog, snow, and temperature.
  - **Road Conditions:** Intersection, highway type, and urban vs. rural areas.
  - **Accident Severity:** Categorical classification from minor to major accidents.

---

## **Visualization Systems**
The project implements three distinct **visualization systems** to explore the dataset:

### **System A - Temporal Analysis**
- **Focus:** Accident frequency over time.
- **Key Features:**
  - Interactive zooming and filtering based on time of the day.
  - Strip plots and jitter effects to represent severity.
  - A slider to adjust temporal resolution dynamically.

### **System B - Geographic & Environmental Analysis**
- **Focus:** Spatial distribution of accidents.
- **Key Features:**
  - Interactive **map visualization** with color-coded accident markers.
  - Dropdown filters for road conditions, weather conditions, and severity.
  - Brushing interactions to refine spatial queries.

### **System C - Weather Impact on Accidents**
- **Focus:** Correlation between weather conditions and accident severity.
- **Key Features:**
  - **Heatmap** representation of accident density in major cities.
  - **Scatter Plot Matrix (SPLOM)** to explore weather-accident relationships.
  - **Interactive bar charts** for road condition-based filtering.

---

## **Design & Interaction Features**
- **Multi-view Visualization:** Combines spatial, temporal, and weather-based analyses.
- **Interactivity:** Users can filter, zoom, and brush through different datasets.
- **Comparative Analysis:** Systems allow direct comparison between different views of the dataset.
- **Data Filtering:** Users can explore data subsets based on accident severity, weather, and location.

---

## **Installation & Setup**
1. Clone this repository:
   ```bash
   git clone https://github.com/Mejorarsim/Information-Visualization.git
   cd Information-Visualization
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy vega_datasets altair
   ```
3. Run the visualization tool:
   ```bash
   python main.py
   ```

---

## **Project Contributors**
- **Simran Garg**
- **Anjali Gedam**
- **Shirisha Mahesh**
- **Zhihao Yan**
- **Yumeng Zhang**
