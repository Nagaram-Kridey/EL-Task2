# EL-Task2
Elevated Labs Task 2: Exploratory Data Analysis (EDA)

1. **Load and Preprocess the Data**
   - Fill missing values (`Age`, `Embarked`)
   - Drop `Cabin` due to excessive nulls
   - Encode categorical columns (`Sex`, `Embarked`)

2. **Generate Summary Statistics**
   - Used `df.describe()` to view mean, median, std, etc.

3. **Visualize Numeric Features**
   - Created histograms and boxplots for `Age`, `Fare`, `SibSp`, `Parch`

4. **Understand Feature Relationships**
   - Used `pairplot` and `correlation matrix` to explore interactions between features
   - Analyzed how survival correlates with variables like `Sex`, `Pclass`, and `Fare`

5. **Identify Patterns and Trends**
   - Observed higher survival in females and 1st class passengers
   - Found loose correlation between higher fare and survival
   - Detected outliers visually in numeric columns

6. **Interactive Plots (Optional)**
   - Used Plotly for interactive Age vs Fare scatter colored by survival


![image](https://github.com/user-attachments/assets/fddc7fee-55d7-4044-ac61-aef68e2515d6)
