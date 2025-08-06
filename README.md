# Red Wine Quality Prediction

## ℹ️ Info
This project investigates the quality characteristics of red wine using the popular Wine Quality dataset. The dataset contains several physicochemical properties of red wine samples, such as:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

Each wine sample is labeled with a quality score (0-10) representing the wine's perceived quality by sensory experts.

## 📌 Objective
The main objective is to predict the quality rating of red wine based on its physicochemical attributes. Accurate predictions can help wineries, distributors, and consumers make informed decisions about wine production and selection.

## ⭐ Project Steps
1. **Data Import & Exploration**
   - Load the dataset and inspect its structure.
   - Check for missing and duplicate values.
2. **Data Cleaning**
   - Remove duplicates and handle missing values if any.
3. **Feature Engineering**
   - Create a new categorical feature for quality grade (high, medium, low).
   - Encode categorical variables.
4. **Data Visualization**
   - Visualize relationships between features and wine quality using line plots, box plots, and heatmaps.
5. **Model Building**
   - Split the data into training and testing sets.
   - Train a Random Forest Classifier to predict wine quality grade.
   - Evaluate the model using accuracy, confusion matrix, and classification report.

## 🔍 Key Results
- The Random Forest Classifier achieved an accuracy of **0.85** on the test set.
- Strong relationships were found between certain chemical properties and wine quality.

## 📊 Visualizations
- Correlation heatmap of features
- Line plots for alcohol, sulphates, and volatile acidity vs. quality
- Box plots for alcohol by quality grade (before and after outlier removal)
- Distribution of wine quality levels

## 🛠️ Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 Usage
1. Place `winequality-red.csv` in the project directory.
2. Open and run the notebook `wine_quality_com.ipynb` step by step.

## 🙌 Acknowledgements
- [UCI Machine Learning Repository: Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)

---
Thank you for reviewing this project! This work demonstrates the application of machine learning techniques to real-world data and highlights the importance of data-driven decision making in the wine industry.
