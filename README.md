 Overview
This project was completed as part of the British Airways Data Science Virtual Experience Program on Forage (June 2025). The objective was to explore customer booking data and build a predictive model to identify factors that influence whether a customer is likely to purchase a holiday package, enabling British Airways to proactively target these customers before they travel.

📊 Project Goals
Explore and clean the provided customer booking dataset

Engineer features and prepare data for modelling

Train a Random Forest Classifier to predict holiday bookings

Evaluate model performance through cross-validation and metrics

Interpret model results via feature importance visualizations

Summarize business insights and recommendations for future strategy

📁 Project Structure
cpp
Copy code
📦 British-Airways-Holiday-Booking-Prediction
 ┣ 📑 customer_booking.csv
 ┣ 📑 Getting Started.ipynb
 ┣ 📑 BA_Customer_Holiday_Booking_Prediction.ipynb  ← (final notebook)
 ┣ 📊 Visualizations/
 ┣ 📑 BA_Customer_Holiday_Booking_Summary.pptx
 ┗ 📄 README.md
📈 Key Results
Achieved 85% accuracy on test data

Cross-validation score: 49%, indicating overfitting and room for model improvement

Top predictive features influencing holiday bookings:

Purchase Lead

Flight Duration

Trip Type

Wants In-Flight Meals

Wants Extra Baggage

📌 Business Insights
Early bookers and long-haul travelers show higher interest in holiday packages.

Round-trip and premium service customers (meals, baggage) are key target segments.

Future marketing should prioritize these segments for personalized holiday offers.

🛠️ Tech Stack & Tools
Python

Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

Jupyter Notebook

PowerPoint (for business presentation)

📊 Future Improvements
Balance class distribution for improved model generalizability.

Hyperparameter tuning (GridSearchCV) for RandomForest.

Explore alternate models like Gradient Boosting (XGBoost).

Feature engineering with additional behavioral or transaction data.

📄 License
This project was developed as part of the Forage Virtual Experience Program and is for educational and portfolio purposes only.# British-Airways
