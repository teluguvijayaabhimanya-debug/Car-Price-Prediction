#  Car Price Prediction Using Machine Learning

##  Project Overview

This project predicts the selling price of used cars using machine learning techniques. It analyzes various factors such as the car's age, present price, kilometers driven, fuel type, transmission, and ownership history to estimate the selling price accurately.

##  Objective

* Predict the selling price of used cars.
* Perform data preprocessing and feature engineering.
* Compare the performance of multiple regression models.
* Evaluate model performance using regression metrics.

##  Dataset

The dataset contains information about used cars, including:

* Car Name
* Year
* Present Price
* Selling Price
* Driven Kilometers
* Fuel Type
* Selling Type
* Transmission
* Owner

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

##  Data Preprocessing

* Checked dataset structure and missing values.
* Created a new feature (**Car_Age**) from the manufacturing year.
* Removed unnecessary columns.
* Applied one-hot encoding to categorical features.

##  Exploratory Data Analysis (EDA)

* Dataset overview and summary statistics.
* Distribution of selling prices.
* Scatter plot of Present Price vs. Selling Price.
* Correlation heatmap.
* Feature importance visualization.

##  Machine Learning Models

The following regression models were trained and compared:

* Linear Regression
* Random Forest Regressor

##  Model Evaluation

Models were evaluated using:

* R² Score
* Root Mean Squared Error (RMSE)

### Results

| Model                   | R² Score |  RMSE |
| ----------------------- | -------: | ----: |
| Linear Regression       |    0.849 | 1.866 |
| Random Forest Regressor |    0.959 | 0.966 |

The **Random Forest Regressor** achieved the best performance with a high R² score and a low RMSE.

##  Feature Importance

Feature importance analysis showed that **Present Price** was the most influential factor in predicting the selling price, followed by **Car Age** and **Driven Kilometers**.

##  Project Screenshots

Add screenshots of:

* Dataset Preview
* Selling Price Distribution
* Present Price vs. Selling Price
* Correlation Heatmap
* Actual vs. Predicted Prices
* Feature Importance Chart

Store the images in an `images/` folder and reference them here.

##  Project Structure

```text
Car-Price-Prediction/
│── Car Price Prediction.ipynb
│── README.md
│── requirements.txt
│── car data.csv
└── images/
```

##  How to Run

1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open `Car Price Prediction.ipynb` in Jupyter Notebook.
4. Run all cells to preprocess the data, train the models, and evaluate the results.

##  Key Insights

* Present Price has the strongest influence on the selling price.
* Older vehicles generally have lower selling prices.
* Cars with higher driven kilometers tend to have lower resale values.
* The Random Forest model outperformed Linear Regression for this dataset.

##  Future Improvements

* Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Apply cross-validation for more robust model evaluation.
* Save the trained model using Joblib.
* Build a web application using Flask or Streamlit for real-time price prediction.

# Screenshots

## pair plot

![pair plot]()

##correlation heatmap

![correlation heatmap]()
