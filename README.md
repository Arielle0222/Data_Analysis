# Data Analysis Repository

Welcome to the **Data Analysis Repository**, which showcases projects exploring environmental data and their implications for sustainable mobility. This repository highlights the intersection of data analysis and smart mobility, focusing on correlations between electric vehicle (EV) adoption rates and PM2.5 air pollution levels.

---

## 📂 Repository Structure

```
├── data/                     # Raw and processed datasets
├── notebooks/                # Jupyter notebooks for data analysis
├── scripts/                  # Python scripts for data preprocessing and visualization
├── results/                  # Visualizations and final results
├── README.md                 # Documentation (this file)
```

---

## 📊 Project Overview

### 1. **Correlation Between Regional EV Adoption Rates and PM2.5 Levels**
- **Objective**: Investigate the relationship between regional EV ownership and air quality (PM2.5) to evaluate the environmental impact of EV adoption.
- **Dataset**: Monthly regional air pollution data (PM2.5, PM10, etc.) and EV ownership statistics for 2023.
- **Methods**:
  - Data preprocessing: Managing missing values, detecting, and removing outliers using statistical techniques.
  - Correlation analysis: Leveraging Pearson and Spearman methods to identify significant trends.
  - Visualization: Creating interactive heatmaps and scatter plots for regional insights.
- **Highlights**:
  - Successfully cleaned and integrated data into a unified dataset.
  - Developed interactive visualizations to communicate findings effectively.

### 2. **Application to Autonomous Driving and Smart Mobility**
- **Relevance**: The findings provide a foundation for developing data-driven strategies in autonomous driving and mobility services.
- **Extension**:
  - The analysis can be extended to explore how air quality data and EV adoption influence traffic patterns, route optimization, and energy efficiency in autonomous systems.
  - Insights into urban pollution levels can guide real-time decision-making in smart mobility applications.

---

## 🛠️ Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, seaborn, folium, geopy, scipy
- **Environment**: Jupyter Notebook

---

## 🚀 How to Use

### Prerequisites
- Python 3.8 or higher
- Required libraries in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Arielle0222/Data_Analysis.git
   cd Data_Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Run Notebooks and Scripts
- Use Jupyter Notebook for interactive exploration:
  ```bash
  jupyter notebook
  ```
- Execute Python scripts for specific tasks:
  ```bash
  python scripts/<script_name>.py
  ```

---

## 📈 Key Results

- **Scatter Plot**: Demonstrates the relationship between EV ownership ratio and PM2.5 levels.
- **Heatmap**: Interactive visualization showcasing regional variations in pollution and EV adoption.
- **Regional Insights**:
  - Areas with higher EV adoption often exhibit improved air quality.
  - Highlighted urban and industrial patterns impacting PM2.5 levels.

---

## 🌐 Future Directions

- Integrating real-time air quality monitoring data with autonomous vehicle route planning.
- Exploring traffic optimization models using environmental and mobility data.
- Extending analysis to predict future trends in sustainable urban mobility.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

---

## 📧 Contact

- **GitHub**: [Arielle0222](https://github.com/Arielle0222)
- **Email**: your_email@example.com
