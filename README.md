# House Price Prediction using Linear Regression

This project implements a Linear Regression model to predict house prices based on various structural and geographical features. The goal is to provide a data-driven approach to estimating property values using a historical housing dataset.

## 📊 Dataset Overview
The dataset (`Housing linear regression.csv`) includes several key features that influence house prices:
* **Price**: The target variable (sale price).
* **Bedrooms/Bathrooms**: Number of rooms in the house.
* **Sqft_living**: Square footage of the interior living space.
* **Sqft_lot**: Square footage of the land space.
* **Floors**: Total floors in the house.
* **Grade**: Overall grade given to the housing unit, based on the King County grading system.
* **Yr_built/Yr_renovated**: Year the house was originally built and last renovated.
* **Location**: Latitude, longitude, and zipcode.

## 📁 Repository Structure
* `Housing linear regression.csv`: The dataset used for training and testing.
* `housing_price_linear_ML.ipynb`: The Jupyter Notebook containing the full implementation code.
* `README.md`: Project documentation.

### Key Features:
* **Target Variable**: `price` (Sale price of the house).
* **Independent Variable used in this model**: `bedrooms`.
* **Additional features available in dataset**: `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, `waterfront`, `view`, `condition`, `grade`, `sqft_above`, `sqft_basement`, `yr_built`, `yr_renovated`, `zipcode`, `lat`, and `long`.

## 🛠️ Tech Stack
The project is implemented using the following Python libraries:
* **NumPy**: For numerical calculations.
* **Pandas**: For data handling and CSV manipulation.
* **Matplotlib**: For plotting graphs.
* **Seaborn**: For advanced data visualization.
* **Scikit-Learn**: For implementing the Linear Regression model and data splitting.

## 🚀 Project Workflow
1.  **Data Loading**: Importing the dataset using `pd.read_csv()`.
2.  **Exploratory Data Analysis (EDA)**: 
    * Inspecting data structure with `df.head()` and `df.info()`.
    * Checking for missing values using `df.isnull().sum()`.
    * Analyzing price ranges and feature distributions.
3.  **Feature Selection**: Defining `bedrooms` as the independent variable ($X$) and `price` as the target variable ($y$).
4.  **Data Splitting**: Dividing the data into training (80%) and testing (20%) sets using `train_test_split`.
5.  **Model Training**: Implementing the `LinearRegression()` algorithm from Scikit-Learn and fitting it to the training data.


## 👤 Author
* **Name**: Hafiz Muhammad Faizan
* www.hafizmuhammadfaizan.site

## 📝 License
This project is open-source and available for educational purposes.
