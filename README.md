## Prediction of Homes in California

This project focuses on predicting home prices in California using various machine learning algorithms. The dataset contains information about housing attributes, which are utilized to develop predictive models.


### Dataset

The dataset used for this project is housing.csv, which contains the following columns:

longitude: Longitude of the house location.

latitude: Latitude of the house location.

housing_median_age: Median age of the houses in the area.

total_rooms: Total number of rooms in the house.

total_bedrooms: Total number of bedrooms in the house.

population: Population of the area.

households: Number of households in the area.

median_income: Median income of the area.

median_house_value: Median house value (target variable).

ocean_proximity: Proximity to the ocean (categorical feature).

### Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/prediction-of-homes.git
cd prediction-of-homes
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Run the Jupyter notebook:

bash
Copy code
jupyter notebook "Prediction of homes.ipynb"
Follow the steps in the notebook to preprocess the data, train the models, and evaluate their performance.

Modeling
Various machine learning models are applied, including:

Linear Regression
Random Forest Regressor
XGBoost Regressor
Hyperparameter tuning is performed using Grid Search to optimize model performance.

Evaluation Metrics
The models are evaluated using:

Mean Squared Error (MSE)
R-squared (R²)
Contributing
Contributions are welcome! Please feel free to submit a pull request or raise an issue if you find any bugs or have suggestions for improvement.

