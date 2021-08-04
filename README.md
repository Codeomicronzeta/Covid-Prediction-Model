# Covid-Prediction-Model
A Python project in which techniques involving Time Series Analysis along with Polynomial Regression, Autoregressive Time Series models and Holt Smoothing Techniques to forecast the daily number of citizens testing positive for Corona Virus for the next 15 days.<br>
The forecasting has been made on the Bengaluru Urban district, Karnataka, India on the data for Wave 2 of Coronavirus Pandemic from mid-February to mid-June.<br>
The data has been scraped from the official site of Karnataka Government https://covid19.karnataka.gov.in/govt_bulletin/en and stored in the csv files mentioned in the repository.<br>

<img width="739" alt="Screenshot 2021-08-04 at 9 27 08 PM" src="https://user-images.githubusercontent.com/63745797/128213973-ae43677b-c66e-43b7-87ff-2e3caa2acdab.png">

# Description
`Bengaluru_Urban_data.csv` contains data from 2020-07-01 to 2021-06-03.<br><br>
`Bengaluru_Urban_data_val.csv` contains data from 2020-07-01 to 2021-06-15. This dataset is used to validate and evaluate the forecasted values made by the models.<br><br>
`TSA.ipynb` is the python notebook consisting of code for data preparation and model creation required for creating the forecasting models.<br>
