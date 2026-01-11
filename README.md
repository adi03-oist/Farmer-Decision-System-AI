🧠 Farmer Decision Support System using AI
An AI-powered system that analyzes Indian mandi price data (2023–2025) to predict vegetable prices and help farmers decide the best time to sell their produce.
📌 Problem
Indian farmers often sell vegetables at the wrong time due to lack of price trend information.
This leads to heavy losses even when market demand is high.
This project solves that problem by using machine learning to predict prices and provide Sell/Wait decisions.
📊 Dataset
Source: Indian mandi wholesale price data
Period: 2023 – 2025
Features used:
State
District
Market
Commodity
Price Date
Min, Max, and Modal Price
🧠 Machine Learning Model
We used Random Forest Regressor to learn price patterns based on:
Day of the year
Month
The model predicts the future modal price of vegetables.
🌱 Vegetables Analysed
Due to data availability and quality, the system automatically selected:
Tomato
Onion
Potato
These vegetables had sufficient historical data for reliable predictions.
📈 Visualizations
The project includes:
All-India vegetable price trends
30-day moving average
Actual vs AI predicted price graphs for:
Tomato
Onion
Potato
These graphs show how closely AI follows real market behavior.
⚖️ Decision Logic
The system gives a simple farmer-friendly decision:
Copy code

If predicted price > today’s price → WAIT  
Else → SELL
This helps farmers decide when to sell to maximize profit.
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
🚀 How to Run
Open AI_Mandi_Price_Prediction.ipynb
Make sure the dataset file is in the same folder
Run all cells in Jupyter Notebook
View predictions and graphs
📌 Project Output
The system predicts vegetable prices and visually compares them with actual mandi prices, helping farmers make smarter selling decisions.
📍 Future Scope
Add more vegetables
Use weather & demand data
Deploy as a web or mobile app
🔥 This project demonstrates how AI can be used to support farmers with real-world data and intelligent predictions.
