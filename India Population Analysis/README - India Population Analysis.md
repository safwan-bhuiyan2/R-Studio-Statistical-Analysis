
# 🇮🇳 Indian District-Wise Population Change Analysis (2001-2011)

## 📊 Project Overview

This project analyzes **district-level population changes in India between the 2001 and 2011 census periods** using statistical methods, clustering, and geospatial analysis in **R with Jupyter Notebook**. It provides a deep dive into demographic trends, helping uncover hidden patterns related to urbanization, migration, and regional disparities.

### Objectives

- Calculate district-wise population growth rates.
- Identify top and bottom growing districts.
- Explore geographic distribution of growth.
- Perform spatial clustering to detect growth patterns.
- Analyze average growth trends across Indian states.
- Predict 2021 district populations using linear extrapolation.

## 🛠️ Tools and Libraries Used

- **R** (IRKernel in Jupyter)
- tidyverse
- ggplot2
- sf
- cluster
- leaflet
- dendextend

## 📥 Dataset

The dataset used includes:

- State
- District
- Latitude & Longitude (district centroid)
- Population in 2001
- Population in 2011

_Source: [Kaggle and Indian Census Data_](https://www.kaggle.com/datasets/sirpunch/indian-census-data-with-geospatial-indexing/data)

## 🚦 Key Findings

### District-level Insights

- Population growth varied widely across districts.
- High growth districts were **not exclusively urban** — many rural and semi-urban districts showed rapid growth.
- Low growth was seen in both rural and urban regions, often due to aging populations or saturation.

### Spatial Clustering

- **Red Cluster**: High-growth districts (urbanizing or rural expansion)
- **Green Cluster**: Moderate growth (balanced population change)
- **Blue Cluster**: Low or negative growth (aging or migration outflows)

### State-wise Analysis

- Some of the highest growth states (e.g., Meghalaya) were **not highly urbanized**, driven more by birth rates and local dynamics.
- Urbanized states (e.g., Kerala, Goa) saw slower growth due to lower fertility and saturation effects.

### Correlation Insights

- Weak correlation between latitude/longitude and growth → geography alone does not explain population growth patterns.
- Socio-economic and demographic factors are primary drivers.

### Prediction (Bonus)

- Linear extrapolation for 2021 populations was performed.
- Forecasts should be treated cautiously as they do not include migration, policy changes, or economic shifts.

## 📍 Visualizations Included

- Top/Bottom Growing District Bar Plots
- Scatter Plot (Growth vs. Latitude)
- Spatial Cluster Map (ggplot)
- Interactive Cluster Map (Leaflet)
- State-wise Average Growth Bar Plot

## 🚀 How to Run

1. Install required R libraries:

```r
install.packages(c("tidyverse", "ggplot2", "sf", "cluster", "leaflet", "dendextend", "IRkernel"))
IRkernel::installspec(user = TRUE)
```

2. Install Jupyter Notebook (if not installed):

```bash
pip install notebook jupyter_client
```

3. Launch Jupyter Notebook and open the `.ipynb` file.

```bash
jupyter notebook
```

4. Choose `R` kernel and run the notebook cells sequentially.

## 📌 Conclusion

This project highlights how population change is driven by:

- Fertility and natural growth (not just urbanization)
- Migration trends (inward and outward)
- Socio-economic factors and regional disparities

By combining statistical analysis, clustering, and geospatial visualization, this project offers a nuanced and insightful view into India’s demographic landscape. It serves as a powerful portfolio project demonstrating data analysis, visualization, and geographic insights with R and Jupyter Notebook.

---

**Author**: Safwan Bhuiyan  
**Year**: 2025  
**License**: MIT

Feel free to fork, use, and adapt this notebook for your own analytical explorations 🚀
