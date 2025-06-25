
# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

## 🎯 Objective
Perform EDA using statistics and visualizations to understand key patterns in the Titanic dataset.

## 🧰 Tools Used
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Plotly (optional for interactivity)

## 🔍 Steps Performed

### 1. Data Loading
- Loaded `titanic.csv` using pandas.

### 2. Basic Exploration
- Used `.info()`, `.describe()`, and `.isnull().sum()` to understand structure and missing values.

### 3. Data Cleaning
- Filled missing `Age` with median.
- Filled missing `Embarked` with mode.

### 4. Summary Statistics
- Calculated mean, median, std for `Age`, `Fare`, etc.

### 5. Visualization
- Histograms for distributions
- Boxplots to detect outliers
- Heatmap for feature correlation
- Pairplot to see relationships
- Countplot and barplots for survival analysis

### 6. Skewness
- Checked skewness of numeric features.

### 7. Interactive Plot
- Used Plotly for visualizing `Age` vs `Survival`.

## 📈 Key Insights
- 🚺 Women had a higher survival rate than men.
- 💰 First-class passengers were more likely to survive.
- 👶 Children and young adults had better survival odds.
- 💸 Fare and Class show a strong correlation with survival.
