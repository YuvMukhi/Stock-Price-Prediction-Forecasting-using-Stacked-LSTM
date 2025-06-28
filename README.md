# Stock-Price-Prediction-Forecasting-using-Stacked-LSTM
This project focuses on building a deep learning model using Stacked Long Short-Term Memory (LSTM) networks to predict and forecast stock prices based on historical data. It is designed to help understand market patterns and anticipate future stock movements, which is a crucial component in algorithmic trading and financial analysis.

By leveraging sequential modeling capabilities of LSTMs, the project captures temporal dependencies in time-series data — a key requirement for predicting stock price trends. The model is trained and tested using daily closing prices, and provides a foundation for real-world forecasting scenarios.

Project Objectives   
1.Develop a robust deep learning model capable of accurately predicting stock prices.  
2.Apply LSTM layers in a stacked configuration to enhance learning capacity over sequential time-series data.  
3.Explore the use of data preprocessing techniques for preparing financial time-series data.  
4.Visualize both model training behavior and prediction performance for interpretability.  


Technologies & Libraries Used  
1.Python – Core programming language for data processing and modeling  
2.NumPy & Pandas – For data manipulation and handling time-series formats  
3.Matplotlib – To create insightful visualizations of predictions vs actual values  
4.Scikit-learn – Used for scaling and splitting datasets  
5.TensorFlow / Keras – To implement and train the stacked LSTM neural network  


Sample Outputs                                                                             
1.Line graphs showing predicted vs actual stock prices                                                                           
2.Loss curves for model training and validation   
3.Highlighted trend shifts captured by the LSTM architecture


Future Enhancements  
1.Integrate technical indicators (e.g., RSI, MACD) to enrich feature space     
2.Use multi-variate LSTM with additional inputs like volume and open/high/low prices    
3.Deploy the model using Streamlit or Flask for real-time forecasting dashboard  
4.Extend to other financial assets such as cryptocurrency or indices

