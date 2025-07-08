#✈️ Flight Price Prediction – Feature Engineering Project
Welcome to my project on Feature Engineering using the Flight Price Dataset!
As a data enthusiast and fresher in the field, this project helped me understand the real-world process of preparing data for machine learning models.

🎯 Project Goal
To clean and transform raw flight data and apply feature engineering techniques to make the dataset ready for model building — with a focus on predicting flight ticket prices.

📌 What I Learned
✅ Handling missing values
✅ Dealing with imbalanced data
✅ Removing outliers
✅ Encoding categorical data
✅ Creating new meaningful features
✅ Preparing a dataset suitable for machine learning

📊 Dataset Overview
The dataset contains flight-related information such as airline, departure time, number of stops, travel class, duration, and price.

✍️ Final Features Used:
Feature Name	Description	Type
Airline	Name of the airline company	Categorical
Flight	Unique flight number	Categorical
Source City	City of departure	Categorical
Departure Time	Grouped departure time (e.g., Morning, Evening)	Categorical
Stops	Number of stops between source and destination	Categorical
Arrival Time	Grouped arrival time (e.g., Afternoon, Night)	Categorical
Destination City	City where the flight lands	Categorical
Class	Travel class: Business or Economy	Categorical
Duration	Total time taken by the flight (in hours)	Numerical
Days Left	Days remaining from booking date to travel date	Numerical
Price	🎯 Target variable – flight ticket price	Numerical

⚙️ Feature Engineering Steps
1. 📉 Handling Missing Values
Used logical methods and statistical techniques (mean/mode) to fill missing data.

2. 📊 Handling Imbalanced Data
Applied basic resampling strategies to balance data if needed (for classification use cases).

3. 🚫 Outlier Treatment
Identified and capped/removal of extreme values using:

IQR (Interquartile Range)

Z-score

4. 🔤 Data Encoding
Converted categorical variables using:

Label Encoding

One-Hot Encoding (where needed)

5. 🛠️ Additional Features
Created Days Left from date columns

Grouped time into bins like "Morning", "Afternoon", etc.

🧰 Tools Used
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

📁 Folder Structure
sql
Copy
Edit
📦 flight-price-feature-engineering/
├── data/                  → Dataset files
├── notebook/              → Jupyter notebook with full workflow
├── images/                → EDA & processing visuals
├── README.md              → Project overview
└── requirements.txt       → Python libraries used
🚀 What's Next?
Apply regression models on this dataset

Perform hyperparameter tuning

Create a dashboard using Power BI or Streamlit

🙋‍♂️ About Me
Hi, I'm Krishna Kumar – an aspiring data analyst and Python learner.
This project helped me understand how raw data is transformed into machine-learning-ready input.
Connect with me on LinkedIn or check out my other work on GitHub.

📃 License
This project is open-source under the MIT License.

