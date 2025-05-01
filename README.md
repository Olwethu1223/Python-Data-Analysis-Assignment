# Python-Data-Analysis-Assignment
# Data Exploration and Visualization

This project explores and visualizes the **Iris dataset** using Python libraries like `pandas`, `matplotlib`, and `seaborn`. The goal is to demonstrate fundamental data analysis and visualization techniques in preparation for deeper work in data analytics.

---

## 📌 Assignment Tasks

### ✅ Task 1: Load and Explore the Dataset
- Loaded the Iris dataset using `sklearn.datasets.load_iris()`.
- Converted it into a Pandas DataFrame.
- Inspected the dataset using `.head()`, `.info()`, and `.isnull().sum()`.
- Verified data types and confirmed no missing values.

### ✅ Task 2: Basic Data Analysis
- Computed basic statistics using `.describe()`.
- Grouped the data by the `species` column and calculated the mean of `petal length (cm)` for each group.
- Noted key differences and insights between the species.

### ✅ Task 3: Data Visualization
Four customized visualizations were created:
1. **Line Chart** - Showing cumulative measurements across the dataset.
2. **Bar Chart** - Comparing average petal length by species.
3. **Histogram** - Showing the distribution of petal lengths.
4. **Scatter Plot** - Visualizing the relationship between petal length and width, colored by species.

All plots include:
- Titles
- Axis labels
- Legends (where applicable)

---

## 🛠️ Tools & Libraries Used
- Python 3.x
- Jupyter Notebook (via Anaconda)
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- `sklearn` for loading the Iris dataset

---

## ⚠️ Error Handling
- Handled column access carefully by checking `df.columns`.
- Ensured no missing data issues.
- Used descriptive error messages and print statements to debug issues.

---

## 📈 Insights
- Each species of iris flower has distinct average petal dimensions.
- Clear separations between species can be visualized through scatter plots.
- Iris is a clean dataset ideal for beginner-level analysis and visualization practice.

---

## 📂 File Structure


---

## 🙋‍♀️ Author
**Amahle “Yaniik” Mathebula — Aspiring Data Analyst**

---

## 💡 License
This project is for educational purposes and follows open educational standards.

