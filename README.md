  
---

# ✈️ Flight Price Dataset – Feature Engineering Project

This project focuses on **cleaning and transforming flight booking data** to prepare it for building a machine learning model to **predict flight prices**.

As a beginner in data science, I took this opportunity to practice important preprocessing techniques using a real-world dataset.

---

## 🎯 Project Objective

To perform **feature engineering** on flight data in order to extract meaningful features, handle data quality issues, and prepare the dataset for accurate price prediction.

---

## 🧩 Dataset Columns

Here are the raw columns in the dataset:

| Column Name       | Description                                         |
| ----------------- | --------------------------------------------------- |
| `Airline`         | Airline name                                        |
| `Source`          | City of departure                                   |
| `Destination`     | City of arrival                                     |
| `Duration`        | Full travel duration (e.g., 2h 50m)                 |
| `Total_Stops`     | Number of stops (e.g., non-stop, 1 stop)            |
| `Additional_Info` | Extra info (e.g., In-flight meal not included)      |
| `Price`           | 🎯 Target variable: flight ticket price             |
| `date`            | Travel day (extracted from booking or journey date) |
| `month`           | Travel month                                        |
| `year`            | Travel year                                         |
| `Arrival_hour`    | Extracted hour from arrival time                    |
| `Arrival_mintue`  | Extracted minute from arrival time                  |
| `Duration_hour`   | Extracted hours from duration                       |
| `departure_hour`  | Extracted hour from departure time                  |
| `departure_min`   | Extracted minute from departure time                |
| `Duration_min`    | Extracted minutes from duration                     |

---

## ⚙️ Feature Engineering Tasks

Here’s what I did step-by-step to prepare the dataset:

### 🧹 1. Handled Missing Values

* Checked each column using `.isnull().sum()` and filled missing values using appropriate logic.

### ⚖️ 2. Treated Imbalanced Data

* Observed class distribution in `Total_Stops` and `Additional_Info`. Applied resampling (if needed).

### 🚫 3. Removed Outliers

* Used **IQR** and **Z-score** to detect outliers in `Price`, `Duration_hour`, and other numerical columns.

### 🔠 4. Encoded Categorical Features

* Converted features like `Airline`, `Source`, `Destination`, `Total_Stops`, and `Additional_Info` using:

  * **Label Encoding**
  * **One-Hot Encoding** (for models that need it)

### 🧠 5. Created & Transformed Features

* Extracted date parts like `day`, `month`, `year` from datetime
* Separated `Duration` into `Duration_hour` and `Duration_min`
* Extracted `Arrival_hour`, `Arrival_mintue`, `departure_hour`, `departure_min`
* Converted all time columns into numeric format

---

## 📊 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn (for visualization)
* Scikit-learn (for preprocessing)

---

## 📁 Project Structure

```
flight-price-feature-engineering/
│
├── data/                      → Raw and cleaned datasets
├── notebook/                  → Jupyter Notebook with all steps
├── visuals/                   → Charts and graphs for EDA
├── README.md                  → Project documentation
└── requirements.txt           → Python package list
```

---

## 🧠 What I Learned

* Cleaning real-world messy data
* Extracting features from text and time columns
* Handling outliers and categorical variables
* Preparing a dataset for machine learning use

---

 

## 🙋‍♂️ About Me

Hi, I’m **Krishna Kumar**, a passionate and motivated data science learner. 
 
Connect with me on [LinkedIn](www.linkedin.com/in/krishna-k-361225277) | 
 

 
