# Installation
Clone the repo first with git clone URl of the repo. <br>
To run the project, ensure you have the necessary dependencies installed. You can install them using pip: <br>
<h2>pip install -r requirements.txt </h2> <br>
Make sure to replace requirements.txt with the actual name of your requirements file if it differs. <br>

# Usage
To run this project, make sure you have the following dependencies installed: <br>
<ul>
  <li>yfinance</li>
  <li>alpaca_trade_api</li>
  <li>yahoo_fin</li>
  <li>pandas</li>
  <li>hvplot</li>
  <li>requests-html</li>
  <li>tensorflow</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
  <li>holoviews</li>
</ul>

# Stock Price Prediction Python Project
This Python project aims to predict stock prices using machine learning techniques. The project utilizes historical stock price data, options data, and energy commodity prices to train a predictive model. The prediction model is built using TensorFlow and Keras libraries, and the data is fetched from various sources including Alpaca API, Yahoo Finance, and Yahoo Finance Options.

# Purpose
The purpose of this project is to develop a predictive model for stock prices, specifically focusing on the energy sector represented by the ticker symbol "XLE." By analyzing historical data and employing machine learning algorithms, the project endeavors to forecast future price movements, aiding investors in making informed decisions.

# Algorithm Used
The algorithm used in this project is a deep neural network regression model implemented using TensorFlow and Keras. The model architecture consists of multiple dense layers with ReLU activation functions. The model is trained to minimize the mean squared error loss function, and the Adam optimizer is used for optimization.

# Steps Involved
1.	<h5>Data Collection:</h5> Historical stock price data is collected from the Alpaca API, options data is fetched using Yahoo Finance Options, and energy commodity prices are obtained from Yahoo Finance.
2.	<h5>Data Preprocessing:</h5> The collected data is preprocessed, which includes cleaning, scaling, and splitting into training and testing sets.
3.	<h5>Model Building:</h5> A neural network regression model is built using TensorFlow and Keras libraries. The model architecture consists of multiple dense layers.
4.	<h5>Model Training:</h5> The model is trained on the training dataset using the Adam optimizer and mean squared error loss function.
5.	<h5>Model Evaluation:</h5> The trained model is evaluated on the testing dataset to assess its performance using the mean squared error metric.
6.	<h5>Visualization:</h5> Various visualizations such as training and validation loss plots, actual vs predicted stock price plots, energy prices plots, and standard deviation plots are generated to analyze the results.

# Features
•	Data Retrieval: Utilizes APIs and libraries such as Yahoo Finance, Alpaca Trade API, and Yahoo_fin to fetch historical stock data.
•	Options Data Analysis: Extracts and analyzes options data using Yahoo_fin library to identify potential market trends.
•	Energy Prices Comparison: Compares and analyzes the spot prices of crude oil, natural gas, and coal alongside stock prices for comprehensive insights.
•	Machine Learning Model: Constructs a machine learning model using TensorFlow and Keras to predict future stock prices based on historical data.
•	Visualization: Employs visualization libraries such as Matplotlib and HoloViews to visualize stock prices, percentage changes, and standard deviations for better understanding and analysis.

1.	<h2>Set Up API Keys:</h2> Obtain API keys for services like Alpaca and ensure they are correctly configured in the environment file (alpaca.env).
2.	<h2>Run the Code:</h2>h2></h2> Execute the Python script to fetch data, train the machine learning model, and make predictions.
3.	<h2>Explore Results:</h2> Analyze the output, including predicted stock prices, visualizations, and performance metrics of the machine learning model.
 

# Contributing 
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.
# License
This project is licensed under the MIT License. See the LICENSE file for details.
# Acknowledgments
<ul>
  <li><a href="https://finance.yahoo.com/">Yahoo Finance</a></li>
  <li><a href="https://alpaca.markets/docs/">Alpaca Trade API</a></li>
  <li><a href="https://pypi.org/project/yahoo-fin/">Yahoo_fin</a></li>
  <li><a href="https://www.tensorflow.org/">TensorFlow</a></li>
  <li><a href="http://holoviews.org/">HoloViews</a></li>
</ul>

 
