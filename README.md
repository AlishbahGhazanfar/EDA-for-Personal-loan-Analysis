# Personal Loan Analysis



This repository contains an exploratory data analysis (EDA) of a personal loan dataset.

## Overview


The EDA aims to uncover insights and patterns within the personal loan data, identify potential issues, and prepare the data for further analysis or modeling.

## File Structure



- `EDA.ipynb`: Jupyter notebook containing the exploratory data analysis.

## Libraries Used



The analysis was conducted using the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `seaborn`: For data visualization.
- `numpy`: For numerical operations.
- `matplotlib.pyplot`: For plotting graphs.
- `scipy.stats`: For statistical operations.

## Methodology


### Outlier Detection


Outliers in the dataset were detected using the Z-score method. This method calculates the Z-score for each data point, which measures the number of standard deviations a data point is from the mean. Data points with a Z-score greater than a certain threshold (typically 3 or -3) are considered outliers.

### Handling Missing Values


Missing values in the dataset were handled using one-hot encoding. This technique converts categorical variables into a form that could be provided to ML algorithms to do a better job in prediction.

## Instructions


To run the EDA notebook, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/personal-loan-analysis.git
   ```

2. **Navigate to the repository**:
   ```bash
   cd personal-loan-analysis
   ```

3. **Install the required libraries**:
   ```bash
   pip install pandas seaborn numpy matplotlib scipy
   ```

4. **Open the Jupyter notebook**:
   ```bash
   jupyter notebook EDA.ipynb
   ```
