# Energy Efficiency: Simple Linear Regression Model

This project explores energy efficiency by predicting **Heating Load** using **Relative Compactness** through a simple linear regression model.

## 📊 Dataset
The dataset used is the **Energy Efficiency Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency). It contains information about building characteristics and their heating and cooling loads.

- **Features**:
  - Relative Compactness
  - Surface Area
  - Wall Area
  - Roof Area
  - Overall Height
  - Orientation
  - Glazing Area
  - Glazing Area Distribution
- **Target**:
  - Heating Load
  - Cooling Load

## 🚀 Model
The project uses **Simple Linear Regression** with `Relative Compactness` (X1) to predict `Heating Load` (y1).

## ⚡ Key Steps
1. Data inspection and visualization.
2. Splitting the data into training and test sets.
3. Building and evaluating the linear regression model.
4. Visualizing results with scatter plots and performance metrics.

## 🛠 Tools Used
- Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
- Google Colab

## 📈 Results
- **R-squared**: `0.85` (example value)
- **Mean Absolute Error**: `2.5` (example value)

### Scatter Plot: Actual vs Predicted Heating Load
![Scatter Plot](scatter_plot.png)

## 🖥️ User Input
The project allows users to input building characteristics and get predictions for heating load dynamically.

## 📂 Files
- `energy_efficiency.ipynb`: Jupyter notebook with the entire workflow.
- `FuelConsumption.csv`: Dataset file.
- `scatter_plot.png`: Visualization of actual vs predicted values.

## 🌟 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/energy-efficiency.git
