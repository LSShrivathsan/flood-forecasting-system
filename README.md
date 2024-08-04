# flood-forecasting-system
flood forecasting system - prediction of extent of the inundation, impact analysis &amp; damage estimation

this model predicts the impact of flood on a particular zone based upon synthetic data provided which gives damage estimation and extent of inundation of the flood.
This system demonstrates flood forecasting using synthetic data to model and assess flood impacts. It covers data generation, exploratory data analysis, and predictive modeling for damage estimation and impact assessment.

## Contents

1. **Data Generation**:
   - Generates synthetic flood-related datasets:
     - **Rainfall** (mm)
     - **River Level** (meters)
     - **Building Density** (0 to 1)
     - **Flood Extent** (meters)
     - **Damage Estimation** (dollar value)
     - **Impact Label** ('Minor', 'Moderate', 'Severe')
   - Saves the dataset as `dummy_flood_dataset.csv`.

2. **Exploratory Data Analysis (EDA)**:
   - Displays initial data rows and statistical summaries.
   - Visualizes Rainfall vs. Flood Extent using a scatter plot.

3. **Predictive Modeling**:
   - Splits the dataset into training and testing sets.
   - Trains a Random Forest Regressor for damage estimation.
   - Trains a Random Forest Classifier for impact assessment.
   - Evaluates model performance with Mean Absolute Error (MAE) for damage estimation and accuracy with a confusion matrix for impact assessment.

4. **Visualizations**:
   - Scatter plot of Actual vs. Predicted Damage Estimation.
   - Confusion Matrix for Impact Assessment.

## Requirements

To run this notebook, install the following packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## Installation

Create a `requirements.txt` file with the following content and install dependencies using pip:

```
numpy
pandas
matplotlib
scikit-learn
```

To install dependencies, run:

```bash
pip install -r requirements.txt
```

## Usage

1. **Run the Notebook**:
   - Ensure all dependencies are installed.
   - Execute each cell to generate data, analyze it, train models, and view results.

2. **Customize**:
   - Adjust parameters or thresholds based on specific use cases.

## License

This notebook is licensed under the MIT License
