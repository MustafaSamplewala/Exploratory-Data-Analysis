# Exploratory-Data-Analysis
Titanic Dataset - Exploratory Data Analysis (EDA)
📋 Task Objective
Perform Exploratory Data Analysis (EDA) on the Titanic Dataset to understand the data using statistics and visualizations.

🛠 Tools Used
Python

Pandas for data handling

Matplotlib and Seaborn for data visualization

NumPy for numerical operations

📈 Steps Performed
Data Loading:

Loaded the Titanic dataset (Titanic-Dataset.csv) using Pandas.

Initial Exploration:

Displayed the first few rows.

Checked dataset information (data types, null values).

Summary Statistics:

Generated summary statistics like mean, median, standard deviation, etc.

Missing Values:

Identified missing values in columns.

Data Visualization:

Created histograms for all numerical features.

Created boxplots to detect outliers.

Plotted a correlation matrix heatmap for numerical features.

Created pairplots to explore relationships between features.

Plotted countplots for categorical variables.

Insights:

Females had a higher survival rate than males.

1st Class passengers had better survival chances.

'Fare' feature showed right-skewness (outliers present).

Negative correlation observed between Pclass and Fare.

📂 Files Included
Titanic-Dataset.csv — The dataset used.

📌 Important Notes
Only numerical columns were selected for correlation matrix to avoid conversion errors.

Skewness in data was detected through histogram plots.

Outliers were identified using boxplots.
