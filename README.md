# Student Social Media Addiction Prediction Model
https://github.com/user-attachments/assets/1b06fe1c-1840-4530-b85c-7af8615c0911


## 📑Dataset:
https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships

<br/>

## 🔧Utilities: 
- Jupyter Notebook

<br/>

## ⌨️Languages:
- Python
  
<br/>

## 📖Library Requirements:
In order to perform data preprocessing in the .ipynb file, first install the following library requirements.
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

<br/>

## 🔎Execution Flow:
1. Import required libraries
2. Load the Google Drive in which the dataset is located
3. Assign the designated dataset path in the Google Drive
4. Display the dataset content to ensure dataset has been loaded
5. Display the dataset information (Example: Columns, Data type, etc..)
6. Removal of unecessary data unrelated to desired analysis by utilizing Correlation Matrix
7. Check for missing values in the dataset to avoid inaccuracy, biased results, etc..
8. Checking for outliers by utilizing boxplot to avoid inaccurate results
9. Removing outliers present in the data
10. Splitting the dataset into training and testing sets
11. Training the model by using a Random Forest Regressor
12. Conduct model evaluation by utilizing testing dataset split
13. Calculate metrics such as MAE & RMSE for model insights
14. Model is interacted with user via user input
15. Model provides Social Media addiction score based on input required
16. Visualization of evaluation metrics is conducted to measure model accuracy and performance

<br/>

## 📊Visualization Methods Implemented:
- Correlation Matrix 
- Boxplot
- Scatterplot
- Histogram
- Bar Chart
