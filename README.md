EV Car Price Prediction (India)
This project analyzes electric vehicle (EV) data in India and builds a simple machine learning model to predict EV prices based on their specifications.

📊 Dataset
File: ev_car_india_dataset.csv
Columns:
Brand – Manufacturer name
Model – Car model
Price – Price in lakhs (₹)
Range – Driving range (km)
Power – Motor power (kW)
Battery – Battery capacity (kWh)
Size: 26 rows × 6 columns
⚙️ Workflow
Data Loading & Exploration
Read dataset with pandas
Inspect shape, info, and missing values
Preprocessing
Drop missing values in Range and Price
Select Range as feature (X) and Price as target (y)
Model Training
Split data into train/test sets (80/20)
Train a LinearRegression model
Extract slope and intercept
Prediction & Evaluation
Predict prices on test set
Compare actual vs predicted values
Visualize results with scatter plot
Compute metrics:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² (Coefficient of Determination)
📈 Results
Slope: ~0.149
Intercept: ~-39.13
Evaluation Metrics:
MAE: 1.51
MSE: 2.28
RMSE: 1.51
R²: 0.42
The model shows moderate performance, indicating that EV price is partially explained by driving range, but additional features (battery, power, brand) could improve accuracy.

🛠️ Libraries Used
pandas, numpy
matplotlib, seaborn
scikit-learn
🚀 Future Improvements
Use multiple features (Range, Battery, Power) for regression
Try advanced models (Random Forest, Gradient Boosting)
Expand dataset with more EV entries
Add interactive dashboards for visualization
👩‍💻 Author: kirithik
