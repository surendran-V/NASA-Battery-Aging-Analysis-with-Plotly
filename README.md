# NASA-Battery-Aging-Analysis-with-Plotly
This repository contains an analysis of the NASA Battery Dataset using interactive visualizations created with Plotly. The project focuses on understanding how battery parameters evolve over multiple charge/discharge cycles, specifically analyzing Electrolyte Resistance (Re), Charge Transfer Resistance (Rct), and Battery Impedance.

---

## Project Overview
Batteries degrade over time, and analyzing their behavior can help identify trends and predict performance. Using the NASA Battery Dataset, this project:

1.Visualizes resistance trends over time.

2.Explores relationships between key parameters.

3.Highlights individual battery performance and degradation patterns.

---

## Objective
To create visually engaging, interactive plots for analyzing:

- Re (Electrolyte Resistance)
- Rct (Charge Transfer Resistance)
The analysis reveals degradation trends, correlations, and anomalies.

---

## Dataset
The NASA Battery Dataset is used for this project. It provides charge and discharge cycle data for multiple batteries.

Steps to Download the Dataset

1.Visit the NASA Prognostics Data Repository:[ NASA Battery Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset/data).

2.Download the relevant dataset to your local machine.

---

## Project Structure
The repository is organized as follows:
```
├───Battery Visualization Assignment.ipynb
└───.ipynb_checkpoints
└───cleaned_dataset
    ├───data
    └───extra_infos
    └───metadata 
```

---

## Features and Visualizations
1. Heatmap: Resistance Trends Over Time
   
    - Displays Re for all batteries across time.
    - Useful for identifying global trends and sudden changes.
    
2. Scatter Plot Matrix: Relationships Between Variables
   
    - Visualizes relationships between Re and Rct.
    - Helps uncover correlations and spot anomalies.
  
3. Facet Plots: Individual Battery Trends
   
    - Shows Re trends over time for each battery in separate panels.
    - Enables focused analysis of individual battery performance.

---

## Technologies Used
 - Plotly for interactive visualizations
 - Jupyter Notebook for code execution and analysis

## References
1.https://peaxy.net/how-to-visualize-battery-data/

2.https://www.mathworks.com/help/predmaint/ug/data-analysis-and-feature-extraction-for-battery-raw-cycling-data.html

---

# How to Run the Project
1. Clone the repository:
   ```
   git clone https://github.com/surendran-V/NASA-Battery-Aging-Analysis-with-Plotly.git
   ```
2. Install dependencies:
    ```
    pip install plotly
    pip install matplotlib
    pip install scipy
    pip install seaborn
    ```
3. Download and add the dataset
   
4. Open the Jupyter Notebook:
   ```
   jupyter notebook
   ```
   - Run the notebook battery_analysis.ipynb to execute the analysis and view the visualizations.

## Results
Key insights derived from the analysis include:

- Global resistance trends over time using heatmaps.
- Correlations between Re and Rct using scatter plot matrices.
- Individual battery behavior and degradation patterns via facet plots.





