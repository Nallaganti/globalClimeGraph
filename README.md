# Global Clime Graph

The **Global Clime Graph** is a comprehensive solution for monitoring and analyzing global climate trends. Leveraging powerful data pipelines, visualizations, and tools, this project aims to present key insights about climate change, temperature anomalies, greenhouse gas emissions, and other critical metrics that shape our understanding of the Earth's climate.
## Goals
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

- **Microsoft Azure Account**: Project Building.
- **Power BI Desktop**: To view and interact with the `globalClimeGraph.pbix` dashboard.
- **Steps to follow**: `projectSetup.txt`.

## Architecture
![image](https://github.com/user-attachments/assets/494f60d3-d81b-4846-8ff8-2a83e233f4c8)

## Services Used
- Azure Data Factory
- Azure DataLake Gen2
- Azue Synapse Analytics
- Azure Databricks
- 
## Power BI Dashboard
![image](https://github.com/user-attachments/assets/91f9000b-62c0-49dc-98e3-d2408fe65753)
![image](https://github.com/user-attachments/assets/5f958aff-1ed5-427d-ab36-b90e214204c2)
![image](https://github.com/user-attachments/assets/92db4e72-de4a-4ec3-be13-60be599d10f0)


