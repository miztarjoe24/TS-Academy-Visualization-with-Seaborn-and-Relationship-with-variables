Library Imported Pandas, Matplotlib, and Seaborn. Loaded the Titanic dataset from a local CSV file.

Explored the dataset using head(), tail(), columns, shape, dtypes, isnull().sum(), and describe(). Key finding: Age, Cabin, and Embarked columns have missing values.

Three versions of Age vs Fare scatter plots: plain Matplotlib, basic Seaborn, then an enhanced Seaborn version showing gender (hue='Sex') and passenger class (size='Pclass') in one chart.

Computed the covariance matrix, correlation matrix, and finally plotted a heatmap showing relationships between all numeric variables. Key finding: Fare and Survived have a moderate positive correlation.

The notebook is well structured and covers the key Seaborn chart types: scatter, histogram, KDE, pairplot, regression, box, violin, count, and heatmap.
