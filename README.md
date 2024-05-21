# StockSage: AI-Driven Financial Forecasting

## Overview
StockSage is an advanced stock market prediction system that utilizes Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks. This project leverages deep learning techniques to model and forecast stock prices, capturing complex temporal dependencies in financial data. It was designed to understand the limitations of RNNs with varying window sizes and to delve into the detailed architecture and mathematical foundations of both RNNs and LSTMs.

## Features
- **Time Series Modeling**: Utilizes RNN and LSTM networks for accurate stock price prediction.
- **Data Processing**: Integrates R for data visualization and Python for modeling. Includes normalization, feature extraction, and windowing.
- **High Accuracy**: Achieves up to 98.6% accuracy with LSTM models for a 5-day window and 92.03% for a 14-day window. RNN models reach up to 91.8% accuracy.
- **Overcoming Challenges**: Addresses vanishing and exploding gradients by transitioning to LSTM networks.
- **Deployment**: Deployed on Google Cloud Platform (GCP) Virtual Machine using Flask for real-time data processing and model inference.
- **Visualization and Interaction**: Provides interactive visualizations with R, allowing intuitive exploration of stock trends and prediction results.

## Research Focus
- **RNN vs. LSTM Performance**: The project was significantly designed to understand how and why RNN performance degrades with larger window sizes, while LSTM models remain robust.
- **Architectural Insights**: In-depth study of the architecture and mathematical foundations of RNNs and LSTMs, including their equations and mechanisms to handle temporal dependencies.
  
![image](https://github.com/soniaditi098/AI-Driven-Financial-Forecasting/assets/41970334/d4ebfa44-4c4b-4acf-9b61-0f9f16d59445)

- **Mathematical Understanding**: Explored the underlying mathematics, such as gradient calculations, to understand the challenges like vanishing and exploding gradients faced by RNNs and how LSTMs overcome these issues.
![image](https://github.com/soniaditi098/AI-Driven-Financial-Forecasting/assets/41970334/e540163a-4d9b-45f1-afc5-ad348b1aa233)

![image](https://github.com/soniaditi098/AI-Driven-Financial-Forecasting/assets/41970334/dd138535-4154-47c5-a282-bec204c0ec60)


## Usage
- **Data Preprocessing**: Use the provided scripts to preprocess stock market data.
- **Model Training**: Train RNN and LSTM models using the training scripts.
- **Prediction**: Use the trained models to predict stock prices and visualize the results.

## Results
- **LSTM Accuracy**: Up to 98.6% for a 5-day window, 92.03% for a 14-day window.
- **RNN Accuracy**: Up to 91.8% for shorter sequence dependencies.
- **Interactive Visualizations**: Explore stock trends and predictions through interactive R visualizations.

## Acknowledgements
- **Google Cloud Platform**: For providing the infrastructure to deploy the application.
- **Open Source Libraries**: Thanks to the developers of R, Python, Flask, and other libraries used in this project.
