# mlb_war_clustering
# MLB WAR Analysis

This project analyzes Major League Baseball player data to explore which performance metrics are most predictive of WAR (Wins Above Replacement). It also uses clustering to group players into similar profiles based on their offensive and athletic attributes.

## Files
- `MLB_WAR_Analysis.ipynb`: Main Jupyter notebook with data cleaning, modeling, and clustering
- `WAR Stats.csv`: Dataset containing player stats used in the analysis

## Methods Used
- Linear Regression
- K-Means Clustering
- Principal Component Analysis (PCA)
- Data Visualization (Seaborn, Matplotlib)
- Feature Scaling (StandardScaler)

## Key Insights
- On-base percentage and slugging percentage were strong predictors of WAR.
- Isolated power and exit velocity were less important than expected.
- Players can be grouped into meaningful clusters representing different player types.
- PCA helped visualize these clusters in two dimensions.

## How to Run
1. Open `MLB_WAR_Analysis.ipynb` in Google Colab or Jupyter Notebook
2. Upload or ensure access to `WAR Stats.csv`
3. Run all cells from top to bottom

## Potential
- Incorporate defensive metrics and positional data
- Apply nonlinear models (e.g., Random Forest, XGBoost)
- Forecast future WAR using time series or player age trends
