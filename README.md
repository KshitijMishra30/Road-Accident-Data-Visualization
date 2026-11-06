# Road Accident Data Visualization & Analysis

## Overview
This project explores road accident records to understand patterns in accident frequency and severity. It uses Python-based data cleaning, exploratory data analysis (EDA), and visualizations to examine factors such as weather, road surface, vehicle type, collision type, accident area, driver age band, junction type, light conditions, and the number of vehicles and casualties involved.

## Objectives
- Clean and prepare the road accident dataset for analysis.
- Explore accident patterns across selected road, weather, vehicle, and driver-related variables.
- Visualize accident frequency and severity using charts and heatmaps.
- Summarize findings that may help inform road-safety discussions.

## Tools & Libraries
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Plotly Express

## Repository Structure
```text
Road_Accident_Data_Visualization/
├── notebooks/
│   └── road_accident_analysis.ipynb
├── data/
│   └── README.md
├── requirements.txt
├── .gitignore
└── README.md
```

## Dataset Setup
The notebook expects a CSV file named `RTA.csv` inside the `data/` folder. The dataset is not included in this repository.

1. Obtain the road accident dataset from its original source (for example, the Kaggle source cited in the notebook).
2. Save the CSV as `data/RTA.csv`.
3. Open `notebooks/road_accident_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells in order.

> Please check the dataset's license and terms before sharing it publicly. Do not upload private, restricted, or personally identifying data.

## Analysis Workflow
1. Load and inspect the dataset.
2. Review missing values and descriptive statistics.
3. Drop selected columns outside the analysis scope.
4. Handle missing values using fill strategies and labels for unknown values.
5. Identify and remove duplicate rows.
6. Perform EDA and create visualizations, including:
   - Accidents by weather conditions
   - Accident severity distribution
   - Area-wise accident counts
   - Common collision types
   - Driver age-band distribution
   - Vehicle types involved
   - Accident area versus severity heatmap
   - Junction and light-condition patterns
   - Vehicles involved versus casualties
   - Weather versus road-surface conditions
7. Summarize key observations and conclusions.

## Important Notes
- The charts describe patterns in the dataset; they do not establish causation.
- Some interpretations in the notebook are exploratory and should be validated against the dataset's definitions and collection methodology.
- The notebook currently focuses on data cleaning, EDA, and visualization. It should not be described as a trained prediction model unless a model-training and evaluation section is added.

## How to Run
Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Open `notebooks/road_accident_analysis.ipynb` and run the cells from top to bottom.

## Author
**Kshitij Mishra**

## References
- Road accident dataset source referenced in the notebook (Kaggle)
- Pandas, NumPy, Matplotlib, Seaborn, and Plotly documentation
