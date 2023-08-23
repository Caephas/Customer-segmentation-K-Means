# Customer Clustering using k-Means Algorithm

## Overview

This project demonstrates how to use the k-Means clustering algorithm to categorize customers based on their annual income and spending score. It is implemented using Python libraries such as NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.

## Requirements

To run this project, you need:

- Python 3.x
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Data Source

The data used in this project is a CSV file named `Mall_Customers.csv`.

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the folder containing the Jupyter Notebook file (`.ipynb`).
3. Run Jupyter Notebook and open the notebook.
4. Execute the notebook cells in order.

## Steps

1. **Importing the Necessary Dependencies**: Libraries used are imported.
2. **Data Collection and Analysis**:
    - The dataset is loaded into a pandas DataFrame.
    - Initial data exploration is performed to get a feel for the dataset.
    - Checked for missing values in the dataset.
3. **Feature Selection**: Annual income and spending score columns are selected for clustering.
4. **Choosing Number of Clusters**: The elbow method is used to determine the optimal number of clusters (which is 5 in this case).
5. **Training the k-Means Model**: A k-Means model is trained on the selected features.
6. **Cluster Visualization**: A scatter plot is generated to visualize the clusters formed.

## Outputs

- **Elbow Plot**: A plot to determine the optimal number of clusters.
- **Cluster Plot**: A plot to visualize the different clusters formed.
