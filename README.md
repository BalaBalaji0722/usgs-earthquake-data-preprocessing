# usgs-earthquake-data-preprocessing
Preprocessing and harmonization workflow for USGS earthquake catalog data using Python for seismic analytics, visualization, and machine learning applications.
USGS Earthquake Catalog Preprocessing for Seismic Data Analysis

## Overview

This repository presents a structured preprocessing workflow for earthquake catalog data obtained primarily from the United States Geological Survey (USGS) Earthquake Catalog. The workflow is designed to support seismic data analysis, spatiotemporal studies, machine learning applications, and earthquake forecasting research.

The repository demonstrates:
- Earthquake catalog acquisition
- Data cleaning and preprocessing
- Temporal feature extraction
- Magnitude harmonization
- Spatial and temporal seismic visualization
- Preparation of earthquake catalogs for downstream analytics and machine learning workflows

The preprocessing pipeline is implemented using Python in Google Colab and is intended to provide a reproducible workflow for seismic data preparation.

---

## About USGS Earthquake Catalog

The primary earthquake data source used in this workflow is the official USGS Earthquake Catalog:

https://earthquake.usgs.gov/earthquakes/search/

The USGS catalog provides global earthquake event data with detailed seismic parameters including:
- Event time
- Magnitude
- Magnitude type
- Depth
- Latitude and longitude
- Event metadata

The catalog supports customizable filtering based on:
- Date range
- Magnitude threshold
- Geographic region
- Depth range
- Event type
- Output format

---

## Additional Seismic Data Sources

Although this repository primarily demonstrates preprocessing using USGS earthquake catalogs, similar workflows are also applicable to other global and regional seismic databases, including:

- ISC (International Seismological Centre)
- NCSS seismic catalogs
- Regional tectonic and seismic observatory datasets
- Other institutional earthquake catalogs

These multi-source seismic datasets are useful for:
- catalog homogenization,
- long-term seismicity analysis,
- interregional seismic correlation studies,
- and machine learning-based seismic forecasting.

---

## USGS Data Collection Workflow

### USGS Earthquake Catalog Search Interface

<img width="1515" height="722" alt="1  Capture" src="https://github.com/user-attachments/assets/6c7f186e-fec0-44ac-8a70-119885fbe24e" />

### Advanced Search Parameters

<img width="1524" height="922" alt="2  Capture" src="https://github.com/user-attachments/assets/1c6b73e8-8819-4aca-81e9-7854e734f923" />

### Output Configuration and Data Export

<img width="873" height="900" alt="3  Capture" src="https://github.com/user-attachments/assets/a132cd94-c3bc-415a-bc50-2d7cf674b77d" />

---

## Preprocessing Workflow

The preprocessing workflow includes the following stages:

1. Merging multiple earthquake catalog files
2. Removing unnecessary metadata columns
3. Extracting temporal information
4. Standardizing seismic parameters
5. Sorting earthquake events chronologically
6. Generating decimal year representation
7. Magnitude harmonization
8. Preparing clean seismic datasets for analysis

---

## Magnitude Harmonization

Earthquake catalogs commonly contain multiple magnitude scales such as:
- Mw (Moment Magnitude)
- Mb (Body-wave Magnitude)
- Ms (Surface-wave Magnitude)
- Ml (Local Magnitude)

To maintain consistency across the earthquake catalog, magnitude harmonization is performed using empirical conversion relationships. This improves:
- seismic comparability,
- statistical consistency,
- machine learning model reliability,
- and long-term seismic trend analysis.

---

## Spatial and Temporal Visualizations

The repository includes several exploratory seismic visualizations, including:

- Spatial distribution of earthquake events
- Magnitude variation across spatial coordinates
- Depth variation across geographical regions
- Temporal variation of earthquake magnitude

These visualizations support:
- spatiotemporal seismic analysis,
- regional seismicity interpretation,
- and earthquake pattern exploration.

---

## Applications

The processed earthquake catalogs generated through this workflow can support:

- Seismic energy analysis
- Earthquake forecasting
- Machine learning applications
- Spatiotemporal seismic analysis
- Seismic hazard assessment
- Risk analytics
- Tectonic activity studies
- Earthquake clustering analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## Outputs
<img width="4891" height="3271" alt="Depth_Variation_Long_Lat" src="https://github.com/user-attachments/assets/3177ba6c-383f-40bc-bede-0c612c05457a" />

<img width="4785" height="3271" alt="Magnitude_Variation_Long_Lat" src="https://github.com/user-attachments/assets/00e875b2-199b-488a-a075-04061f750bbf" />

<img width="5118" height="3271" alt="Spatial_Distribution_Long_vs_Lat" src="https://github.com/user-attachments/assets/16288e82-f019-4e1f-bd4b-0a1e2b567410" />

## Related Publications

1. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Machine Learning Models for Seismic Energy Forecasting and Spatial Correlation Analysis for the Himalayan and Indo-Burmese Regions*. Natural Hazards Review, 27(3). https://doi.org/10.1061/NHREFO.NHENG-2647

2. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Data-driven prediction of global annual seismic energy using machine learning models*. Journal of Earth System Science, 135(2), 60. https://doi.org/10.1007/s12040-026-02788-2

3. Bala Balaji, Y., Hema Sundara, R. V., & Kavitha, B. (2025). *Spatial Variation of Seismic Energy Release of Himachal Pradesh*. Disaster Advances, 3(19), 15. https://doi.org/10.25303/193da15023

4. Yarramsetty, B. B., & Kavitha, B. (2025). *Statistical Study on Seismicity of the Indian Tectonic Plate Interactions*. Disaster Advances, 10(18), 12. https://doi.org/10.25303/1810da012021

---

## Collaboration Opportunities

I am open to collaborations involving:
- seismic analytics,
- spatiotemporal modeling,
- earthquake forecasting,
- machine learning applications,
- geospatial intelligence,
- and AI-driven scientific data workflows.

Researchers, students, and professionals interested in collaborative work are welcome to connect and contribute.

---

## Citation

If you use this preprocessing workflow, repository structure, or methodology in your research or academic work, please consider citing the related publications listed above.

---

## Author

**Bala Balaji Y**

Applied ML Researcher | Seismic Data Analytics | Spatiotemporal Forecasting | Risk Analytics

GitHub: https://github.com/BalaBalaji0722
Gmail: Balabalaji0722@gmail.com
