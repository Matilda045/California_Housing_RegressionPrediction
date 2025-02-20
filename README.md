# California_Housing_Prediction

This project aims to develop a machine learning model to predict median house values in California using demographic and housing market data.

## Dataset

The dataset used in this project is obtained from Kaggle and contains information about various districts in California, including features like median income, housing median age, total rooms, and more.

## Methodology

1. Data Cleaning and Preprocessing: Handling missing values, removing duplicates, and addressing outliers.
2. Exploratory Data Analysis (EDA): Gaining insights into the data through descriptive statistics, correlation analysis, and visualizations.
3. Model Selection: Multi-linear regression is chosen for its suitability to the problem.
4. Model Training: The model is trained using a portion of the dataset.
5. Model Evaluation: The model's performance is evaluated using metrics like Mean Absolute Error (MAE).
6. Model Deployment: The trained model is saved and deployed using Streamlit for interactive predictions.

## Results

The trained multi-linear regression model indicates that the model generalizes well to unseen data and demonstrates good predictive power.

## Usage

To use the model for prediction:

1. Clone this repository.
2. Install the required libraries: `pip install -r requirements.txt`.
3. Run the Streamlit app: `streamlit run app.py`.
4. Enter the desired feature values in the app to get a predicted median house value.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
