# Used Car Price Predictor

## Project Aim

This project sets out to accurately predict the price of a used car by considering various parameters such as the car's company name, model name, year of purchase, and other relevant factors.

![Car Price Prediction](https://github.com/pri-ya-singh/Car-Price-Predictor/blob/main/demo.png)

## How to Use

To get started with this project, follow these steps:

1. **Clone the Repository:** Download the project repository to your local machine.
2. **Install Required Packages:** Use the `requirements.txt` file to install all necessary packages. Some of the key packages include:
   - `numpy`
   - `pandas`
   - `scikit-learn`
3. **Run the Application:** Execute the `application.py` file, and you're all set to make predictions!

## Project Description

### What Does This Project Do?

This project leverages various parameters of a used car—such as the company name, model name, year of purchase, fuel type, and the number of kilometers driven—to predict its possible price. For instance, the following example demonstrates the predicted price for a Hyundai Grand i10.
![Car Price Prediction](https://github.com/pri-ya-singh/Car-Price-Predictor/blob/main/predict.png)


### How Does This Project Work?

1. **Data Collection:** The initial dataset was sourced from [Quikr.com](https://quikr.com). You can access the data [here](https://github.com/pri-ya-singh/Car-Price-Predictor/blob/main/quikr_car.csv).

2. **Data Cleaning:** The data underwent extensive cleaning and analysis to ensure accuracy and reliability.

3. **Model Building:** A Linear Regression model was built on the cleaned data, achieving an impressive R² score of 0.92. You can explore the model and its analysis in this [notebook](https://github.com/pri-ya-singh/Car-Price-Predictor/blob/main/Quikr%20Predictor.ipynb).

4. **Web Integration:** The project was transformed into a web application using Flask, where the Linear Regression model is utilized to make predictions based on user input.

## Example Usage

Provide an example of how to use your application. You can show the input parameters and the predicted price.

```python
# Example code snippet
company = "Hyundai"
model = "Grand i10"
year = 2015
fuel_type = "Petrol"
kilometers_driven = 40000

predicted_price = predict_price(company, model, year, fuel_type, kilometers_driven)
print(f"The predicted price of the car is: {predicted_price}")
