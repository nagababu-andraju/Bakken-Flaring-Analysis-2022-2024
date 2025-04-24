# Bakken-Flaring-Analysis-2022-2024
Python-based analysis to identify and categorize high-flaring well pads in the Bakken region (2022–2024), using geospatial clustering, temporal classification, and economic feasibility modeling for modular flaring mitigation technology deployment.
📁 Repository Contents
bakken_flaring_analysis.ipynb — Google Colab notebook containing the full workflow (preprocessing, clustering, threshold filtering, visualizations).

data/ — Folder for raw or processed sample datasets.

visualizations/ — Animated HTML heatmaps and monthly flaring plots.

README.md — Project overview and instructions.

🔍 Project Objectives
Cluster wells into well pads based on 30m spatial radius.

Filter well pads by flaring thresholds:

Scenario 1: ≥1896 MCF/month

Scenario 2: ≥7584 MCF/month

Categorize pads by flaring consistency across 36 months.

Identify operating companies responsible for high-flaring pads.

Recommend locations for mini or full-module technology deployment.

📊 Visualizations
Animated and interactive HTML maps of monthly flaring patterns are included in the visualizations/ folder.
Opening these files in a browser is essential for exploring spatial and temporal trends that cannot be captured through static images.

🚀 How to Use
Clone or download the repo.

Open bakken_flaring_analysis.ipynb in Google Colab or Jupyter Notebook.

Upload your own dataset or modify paths to run with existing data.

Use visualizations/*.html to explore heatmaps.

🤝 Acknowledgements
North Dakota Industrial Commission (NDIC) – Source of raw flaring data.

Developed using Google Colab and Plotly.
