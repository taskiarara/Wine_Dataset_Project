# Classification of Wine Dataset
## Description
This project aims to apply several classification models on Wine dataset and find out which gives the best accuracy. This dataset contains the results of chemical analysis of wines.
## Titanic Dataset
Wine dataset contains the results of chemical analysis of wines grown in certain areas of Italy. This dataset consists of 178 rows and 14 columns, where 13 variables in the first column to the 13th column are the results of chemical analysis of wine content, while the 14th column is the target variable which is the type of wine and the target of clustering. The target variable is a factor with levels 0, 1, and 2 that describes the grouping of wines based on the 13 chemical analyses. The first group (0) has 59 wines, the second group (1) has 71 wines, and the third group (2) has 48 wines.
## Dataset
The dataset used comes from Kaggle and can be found [here](https://www.kaggle.com/c/titanic/data). 
### Key Features
- **Alcohol**
- **Malic Acid**
- **Ash**
- **Alcalinity of Ash**
- **Magnesium**
- **Total Phenols**
- **Flavanoids**
- **Nonflavanoids Phenols**
- **Proanthocyanins**
- **Color Intensity**
- **Hue**
- **OD280/OD315 of Diluted Wines**
- **Proline**
- **Target**: (0 = Type 1, 1 = Type 2, 2 = Type 3)
## Methodology
1. **Data Collection**: Downloaded the dataset from ...
2. **Pre-processing Data**:
   - Checked the missing values.
3. **Splitting Data**: Split the dataset into training data and testing data.
4. **Modelling**: Using classification algorithms such as:
     - Decision Tree
     - Random Forest
     - KNN
5. **Evaluation**: Calculating the accuracy of the model

## Result
Random Forest is the best model with an accuracy value of 100%.
