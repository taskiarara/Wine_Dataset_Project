# Classification on Wine Dataset
## Description
This project aims to apply several classification models on Wine dataset and find out which gives the best accuracy. This dataset contains the results of chemical analysis of wines.
## Titanic Dataset
Wine dataset contains the results of chemical analysis of wines grown in certain areas of Italy. This dataset consists of 178 rows and 14 columns, where 13 variables in the first column to the 13th column are the results of chemical analysis of wine content, while the 14th column is the target variable which is the type of wine and the target of clustering. The target variable is a factor with levels 0, 1, and 2 that describes the grouping of wines based on the 13 chemical analyses. The first type (class_0) has 59 wines, the second type (class_1) has 71 wines, and the third type (class_2) has 48 wines.
## Dataset
The dataset used comes from scikit-learn and can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data). 
### Key Features
- **Alcohol**: The percentage of alcohol content.
- **Malic Acid**: The concentration of malic acid (organic acid).
- **Ash**: The amount of ash found. 
- **Alcalinity of Ash**: The alkalinity (pH) of the ash.
- **Magnesium**: The concentration of magnesium.
- **Total Phenols**: The total amount of phenols.
- **Flavanoids**: The concentration of flavonoids.
- **Nonflavanoids Phenols**: The concentration of non-flavonoid phenols.
- **Proanthocyanins**: The concentration of proanthocyanins.
- **Color Intensity**: The intensity of the wine color.
- **Hue**: Color index.
- **OD280/OD315 of Diluted Wines**: The ratio between absorbance at wavelengths of 280 nm and 315 nm.
- **Proline** : The concentration of proline in wine.
- **Target**: (class_0 = Type 1, class_1 = Type 2, class_2 = Type 3)
## Methodology
1. **Data Collection**: Downloaded the dataset from [scikit-learn](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data)
2. **Pre-processing Data**:
   - Data Cleaning
   - Scaling
3. **Splitting Data**
4. **Modelling**
     - Decision Tree
     - Random Forest
     - KNN (K-Nearest Neighbors)
5. **Evaluation**

## Result
Random Forest is the best model with an accuracy value of 100%.
