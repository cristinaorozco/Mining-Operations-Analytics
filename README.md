# MINING OPERATIONS ANALYTICS

This is a data-driven project focused on uncovering operational and financial insights into key processes in the production and export chain of a company in the mining industry. The project uses synthetic datasets inspired by real mining operations and is designed to demonstrate analytical capabilities across SAP FI data, railway transport, and port logistics.


# Project Objectives

Model and visualize key performance indicators (KPIs) across mining logistics.
Automate data ingestion and transformation from SAP FI, rail, and port systems.
Detect inefficiencies in costs, transport, and loading operations.
Provide actionable insights using Python, pandas, matplotlib, and Jupyter Notebooks.

# Project Structure

# 1. Data_Pipeline_Mining_company_project.ipynb
This notebook automates the full pipeline from data loading to output generation.

Includes:

Reading and cleaning datasets from:
SAP FI (cost and tons moved by cost center)
Rail transport data
Port WMS dispatch logs

Creating KPIs:
AverageCostPerTon by CostCenter
LoadingEfficiency (Tons per Hour per Vessel)
Total TransportCost
Exporting CSV summaries for further analysis or visualization

# Outputs:

outputs/fi_summary.csv
outputs/rail_summary.csv
outputs/wms_enriched.csv

# 2. Exploratory_Analysis_Mining_company_model_project.ipynb
This notebook explores patterns, relationships and distributions from the processed data.

Includes:

Correlation analysis between:
Tons transported and cost per ton
Loaded tons and loading time
Distribution visualizations:
Loading Time per Vessel
Operational insights and comments from a logistics analyst perspective

# Datasets Used (Synthetic)

sap_fi_export.csv
rail_transport_data.xlsx
wms_dispatch_log.csv
All datasets were synthetically generated for demonstration purposes and do not reflect actual operational data.

Tools & Libraries

Python 3.11
Pandas
Matplotlib
Seaborn
Jupyter Notebook

# Key Takeaways

Operational data across rail and port logistics often shows hidden inefficiencies.
No strong correlation was found between loaded tons and loading time, revealing variance in operational processes.
Loading time distribution suggests high dispersion—worth investigating by vessel type or shift.

# Author
Cristina Orozco.
Data Scientist.
Financial and Logistics analytics.
