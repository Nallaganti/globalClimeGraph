# Global Clime Graph

The **Global Clime Graph** is a comprehensive solution for monitoring and analyzing global climate trends. Leveraging powerful data pipelines, visualizations, and tools, this project aims to present key insights about climate change, temperature anomalies, greenhouse gas emissions, and other critical metrics that shape our understanding of the Earth's climate.

## Features

- **Interactive Dashboard**: The project includes a Power BI dashboard (`globalClimeGraph.pbix`) that provides:

  - Visualizations of historical and current climate data.
  - Trends in greenhouse gas emissions, global temperatures, and sea levels.
  - Regional climate comparisons and anomaly tracking.

- **Data Pipeline**: Built with robust data handling pipelines to ensure accurate and up-to-date information from various climate data sources.

- **Modular Design**: Organized into multiple components for easy scalability and maintenance, including data processing, visualization, and deployment configurations.

## Project Structure

```
.
├── data/                 # Raw and processed data files
├── dataset/              # Dataset configurations and schemas
├── factory/              # Pipeline and factory settings
├── globalClimeGraph.pbix # Power BI dashboard file
├── linkedService/        # Service connections for data sources
├── pipeline/             # Data processing pipeline scripts
├── publish_config.json   # Configuration for publishing and deployment
├── python-code/          # Scripts for data transformation and analysis
├── README.md             # Project documentation
```

## Requirements

- **Power BI Desktop**: To view and interact with the `globalClimeGraph.pbix` dashboard.
- **Python**: For running data processing scripts.
- **Supported Libraries**: Install dependencies using `requirements.txt` (if provided).

## Architecture

### Architecture Design

The architecture for the **Global Clime Graph** project is designed to handle data ingestion, processing, storage, and visualization. Below is the design:

#### 1. **Data Sources**
   - Various climate datasets (e.g., NOAA, NASA, IPCC).
   - APIs for real-time climate data updates.
   - Static files (CSV, JSON) for historical data.

#### 2. **Data Pipeline**
   - **Ingestion**: Scripts fetch data from APIs or upload static files.
   - **Transformation**: Python scripts process and clean raw data.
   - **Storage**: Data is saved in structured formats (e.g., databases, CSV) within the `data/` folder for further use.

#### 3. **Data Storage**
   - Local storage (`data/` directory).
   - Cloud options for scalability (e.g., AWS S3, Azure Blob Storage).

#### 4. **Deployment**
   - Publish dashboards to Power BI Service for sharing.
   - Automate data updates via scheduled pipelines or triggers.

![Architecture Diagram](A_professional_architecture_diagram_for_the_'Globa.png)

## Visualization

### Power BI Dashboard

The **Global Clime Graph** Power BI dashboard (`globalClimeGraph.pbix`) consolidates processed data into interactive and intuitive visualizations. Key features of the dashboard include:

- **Climate Trends**: Track historical and current trends in temperature, greenhouse gas emissions, and sea levels.
- **Regional Comparisons**: Compare climate data across different regions.
- **Anomaly Tracking**: Identify and analyze climate anomalies over time.

The dashboard is designed to be user-friendly, enabling stakeholders to derive actionable insights quickly and efficiently.

