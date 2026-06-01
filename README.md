# Crime Analysis

This repository contains an exploratory data analysis and clustering project on crime data using **PySpark**. 

## Project Overview

The main analysis is documented in the Jupyter Notebook `crimef.ipynb`. The project processes a large dataset (`Crimes.csv`) and performs various analytical operations to uncover patterns in criminal activities. 

### Key Features:
- **Data Processing**: Leverages PySpark (`SparkSession`) to efficiently handle large-scale crime data.
- **Data Attributes Analyzed**: Includes `Primary Type`, `Description`, `Location Description`, `Arrest`, `Domestic`, `District`, `Community Area`, `Year`, `Latitude`, and `Longitude`.
- **Clustering & Visualization**: Analyzes geographical and temporal patterns, with mapping capabilities using libraries like `folium`.
- **Output**: Generates insights and clustered outputs, such as `clustered_data_windows.csv`.

## Setup and Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Apache Spark & PySpark
- Additional Python libraries (e.g., `folium`)

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/imannaswini/Crime.git
   cd Crime
   ```
2. Ensure you have the dataset `Crimes.csv` in your local directory (the dataset is excluded from this repository due to size limits).
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook crimef.ipynb
   ```
4. Run the cells to execute the PySpark analysis.

## Note
The datasets (`Crimes.csv`, `clustered_data_windows.csv`) have been added to `.gitignore` to prevent exceeding GitHub's file size limits. Ensure you download and place the data files in the correct local path before running the analysis.
