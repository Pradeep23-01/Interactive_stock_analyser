# Interactive_stock_analyser

Interactive_stock_analyser is a web application designed to help users view their existing stocks and get future forecasts using machine learning algorithms. The application is accessible via the following link: https://stock-pred-analyzer.herokuapp.com/ (Currently not active, but the code is usable)

## Context:
The application is built using Streamlit, which is a Python library used for building web applications. Streamlit allows developers to easily build interactive and customizable web applications using Python code.

The Interactive_stock_analyser application is deployed using Streamlit, which makes it easy for users to interact with the application through their web browser. The application allows users to input their stock portfolio data and view various analytics and visualizations related to their portfolio. The application also provides future forecasts for their portfolio based on machine learning algorithms.

The application uses machine learning algorithms such as Linear Regression and ARIMA to forecast the future values of stocks. These algorithms analyze the historical data of stocks and use this data to make predictions about future trends. The predictions are then visualized using various graphs and charts to help users understand the trends and make informed decisions.

## Libraries:

- Yahoo Finance is a popular platform used to obtain financial data and stock prices of publicly traded companies. It provides historical stock prices, financial statements, news, and other financial information on a wide range of assets, including stocks, bonds, and exchange-traded funds (ETFs). Yahoo Finance also allows users to download historical stock price data in a CSV file format, which can be used for further analysis.

- Facebook Prophet is an open-source forecasting tool developed by Facebook's Data Science team. It is designed to make accurate forecasts of time-series data, such as stock prices, sales data, and weather data. Prophet is a Bayesian forecasting model that decomposes the time-series data into its trend, seasonality, and holidays components, and then predicts the future values based on these components. The model is highly customizable and allows users to incorporate external regressors such as economic indicators, social media metrics, or other relevant data.

By using Yahoo Finance historical stock price data, one can apply Facebook Prophet to create a forecast of future stock prices. The Prophet model can be trained on historical data to learn the underlying patterns in the data, and then predict the future prices based on these patterns. The model can also generate a range of potential outcomes or scenarios, along with their probabilities, which can be used for risk management and decision-making.

Overall, Interactive_stock_analyser is a useful tool for investors and traders who want to view their existing stocks and make informed decisions about their future investments. The application provides an easy-to-use interface and powerful machine learning algorithms to help users get insights into their stock portfolio.
