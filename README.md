# Visualization of Deforestation in the Amazon

## Description
This project aims to visualize the evolution of deforestation in the Legal Amazon through interactive maps and informative dashboards. It will use **Geopandas** and **Fiona** to manipulate geospatial data and **Folium** to generate interactive maps. In addition, a **Dashboard in Power BI** will be developed to display the deforestation rate in the region.

## Features
- Display of the Legal Amazon with states, boundaries, municipalities, conservation units and indigenous lands.
- Interactive map using **Folium**.
- Implementation of a **slider** to visualize the evolution of deforestation over time.
- Analysis of the deforestation rate through a **dashboard in Power BI**.

## 🛠 Technologies Used 
- **Python**: Geopandas, Fiona, Folium
- **Power BI**: For data visualization and analysis

## Data Source
The data used in the project are obtained from [TerraBrasilis](http://terrabrasilis.dpi.inpe.br/), which provides detailed information on deforestation in the Amazon region.

## Project Structure
```bash
/Project-Deforestation-Amazon
├── data/ # Data files (shapefiles, geojson, etc.)
├── notebooks/ # Jupyter notebooks for data exploration and analysis
├── scripts/ # Python scripts for data processing and map generation
├── dashboards/ # Power BI files
├── README.md # Project documentation
```

## How to Use
1. **Download the TerraBrasilis database**.
2. **Process geospatial data** with Geopandas and Fiona.
3. **Generate interactive maps** with Folium.
4. **Visualize the evolution of deforestation** using the slider.
5. **Explore the dashboards** developed in Power BI.

## Next Steps
- [ ] Download and process data from TerraBrasilis.
- [ ] Implement the loading and manipulation of geospatial data.
- [ ] Create the interactive map interface with Folium.
- [ ] Build the dashboard in Power BI.

