# my-pandaa

## 🧹 Data Cleaning and Exploratory Data Analysis (EDA)

### 📁 Dataset

The dataset used is `expenses.csv`, which contains information such as:
* Age
* BMI
* Children
* Smoker
* Charges

### 🔍 Project Workflow

1. **Data Import**

   * Loaded `.csv` file using `pandas.read_csv()`

2. **Initial Exploration**

   * `df.info()` and `df.describe()` used to understand data types and distributions

3. **Missing Values Handling**

   * Verified using `df.isnull().sum()`
   * Dropped missing values using `df.dropna()` (if any)

4. **Removing Irrelevant Columns**

   * Removed columns like `sex`, `region` (if not useful for analysis)

5. **Outlier Detection & Removal**

   * Used IQR method to detect and remove outliers from numerical columns

6. **Data Visualization**

   * Used `matplotlib` and `seaborn` to visualize:

     * Burnout Level by Gender
     * Sleep vs Stress
     * Job Satisfaction vs Burnout

### 🛠 Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook



