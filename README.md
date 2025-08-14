
# Task 1: Exploring and Visualizing the Iris Dataset

## 📌 Objective
The objective of this task is to **load, inspect, and visualize a simple dataset** to understand data trends, distributions, and relationships between features.  
We also practice data exploration techniques using **pandas, matplotlib, and seaborn**.

---

## 📊 Dataset Used
- **Name:** Iris Dataset  
- **Source:** Built-in Seaborn dataset (`sns.load_dataset("iris")`)  
- **Description:** Contains measurements of *sepal length*, *sepal width*, *petal length*, and *petal width* for three iris species:
  - *setosa*
  - *versicolor*
  - *virginica*

---

## 🛠 Models / Methods Applied
No machine learning models were trained.  
Instead, **data exploration techniques** were applied:
1. **Data Loading & Inspection**  
   - Used `.shape`, `.head()`, `.info()`, `.describe()` to understand dataset structure and statistics.
2. **Data Visualization**  
   - **Scatter Plots**: Showed relationships between pairs of features.
   - **Pair Plots**: Multi-feature scatter plots with species separation.
   - **Histograms**: Displayed value distributions for each feature.
   - **Box Plots**: Identified possible outliers.

---

## 📈 Key Results & Findings
- **Species Separation**:  
  - *Setosa* is clearly separable from the other species using petal length and petal width.
  - *Versicolor* and *Virginica* overlap more, especially in sepal measurements.
- **Feature Distributions**:  
  - Petal measurements show more variation between species than sepal measurements.
- **Outliers**:  
  - A few mild outliers appear in sepal width.
- **Data Quality**:  
  - No missing values or obvious errors in the dataset.

---

## 📦 Requirements
```bash
pip install pandas seaborn matplotlib
