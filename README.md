# Iris-Dataset-EDA-Visualization
Exploratory Data Analysis (EDA) and Visualization on the Iris Dataset using Python, Pandas, Matplotlib, and Seaborn. Includes histograms, scatterplots, pairplots, boxplots, and correlation heatmap with insights for species-wise comparison.
---

📊 Iris Dataset – Exploratory Data Analysis (EDA)

This project performs a complete exploratory data analysis on the Iris Flower Dataset using Python.
It includes statistical summaries, visualizations, correlations, and species-wise comparisons to understand data patterns before any machine-learning modeling.


---

📁 Dataset

Iris Dataset (150 rows × 6 columns)

Columns included:

Id

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species


Dataset Source:
https://www.kaggle.com/datasets/uciml/iris


---

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook



---

📌 Steps Performed

1️⃣ Data Loading & Inspection

Loaded dataset with Pandas

Checked datatypes

Verified missing values (none present)

Viewed descriptive statistics



---

2️⃣ Univariate Analysis (Histograms)

Visualized distribution of each numeric column


---

3️⃣ Boxplots (Outlier Detection)

Boxplot created for all numeric variables to identify spread & outliers.



---

4️⃣ Correlation Heatmap

Correlation among numeric features visualized using seaborn heatmap.

Key observations:

PetalLength ↔ PetalWidth (Very strong correlation)

SepalWidth has weakest correlations

SepalLength correlates positively with petal measurements

---

5️⃣ Pairplot (Species-wise Feature Relationships)

This helps observe clustering among species.



---

6️⃣ Scatterplot: Sepal Length vs Petal Length

Species clearly separated visually:

Setosa tightly clustered

Versicolor & Virginica show linear trend



---

🧠 Key Insights

Iris-setosa has distinctly smaller petal measurements than other species

Petal features (length & width) are the strongest discriminators

Strong correlations exist between petal length and width

SepalWidthCm shows more variance and lower predictive strength

Dataset is clean, balanced, and easy to model



---

▶ How to Run

# Install required libraries
pip install pandas numpy matplotlib seaborn

# Launch Jupyter Notebook
jupyter notebook

Open:

Iris_Analysis.ipynb


---

📦 Project Structure

│── Iris_Analysis.ipynb
│── iris.csv
│── README.md
└── images/ (Optional folder to store visualization screenshots)


---

🔗 Author

Kishlaynath Tiwari

GitHub Profile: https://github.com/Kislaynath


---
