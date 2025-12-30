# Exploring and Visualizing the Iris Dataset

##  Objective
The objective of this task is to understand how to read, summarize, and visualize
a simple dataset using Python. The Iris dataset is used to perform basic data
inspection and exploratory data analysis (EDA).

---

##  Dataset
The dataset used in this task is the **Iris Dataset**, which contains measurements
of iris flowers including sepal length, sepal width, petal length, and petal width
for three different species.

### Dataset Source:
- Seaborn built-in dataset  
- CSV available from UCI Machine Learning Repository  

 Dataset Link:  
https://archive.ics.uci.edu/ml/datasets/iris

---

##  Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn


---

##  Task Workflow

### 1. Data Loading
- The dataset is loaded using the Pandas library.
- CSV file is read into a Pandas DataFrame.

---

### 2. Data Inspection
The structure of the dataset is explored using:
- `.shape` to view the number of rows and columns
- `.columns` to view column names
- `.head()` to display the first few rows of the dataset

---

### 3. Data Summarization
- Basic statistical information is obtained using `.describe()`
- This helps understand the distribution and range of values

---

### 4. Data Visualization
The following visualizations are created using **Matplotlib** and **Seaborn**:

####  Scatter Plot
- Used to analyze relationships between different variables
- Example: Sepal Length vs Sepal Width

####  Histogram
- Used to examine the distribution of numerical features
- Helps identify skewness and data spread

####  Box Plot
- Used to detect outliers and understand the spread of values
- Provides insights into median, quartiles, and extreme values

---

## 5. Results
The visualizations provide clear insights into the relationships, distribution,
and variability of the features in the Iris dataset.

---


