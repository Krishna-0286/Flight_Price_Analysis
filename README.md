
# 🛫 Flight Price Dataset – Feature Engineering

This repository showcases the feature engineering and preprocessing steps applied to a **Flight Price Dataset** to prepare it for predictive modeling. The focus is on cleaning, transforming, and enriching the data for better machine learning performance.

---

## 📌 Objective

Prepare the dataset for flight price prediction by performing essential **data cleaning**, **feature engineering**, and **preprocessing** techniques.

---

## 🧩 Dataset Features

The final cleaned dataset includes the following features:

| Feature              | Description                                        | Type                   |
| -------------------- | -------------------------------------------------- | ---------------------- |
| **Airline**          | Name of the airline company                        | Categorical (6 values) |
| **Flight**           | Unique flight code                                 | Categorical            |
| **Source City**      | City of departure                                  | Categorical (6 values) |
| **Departure Time**   | Grouped time of departure (e.g., Morning, Evening) | Categorical (6 bins)   |
| **Stops**            | Number of stops                                    | Categorical (3 values) |
| **Arrival Time**     | Grouped time of arrival                            | Categorical (6 bins)   |
| **Destination City** | City of arrival                                    | Categorical (6 values) |
| **Class**            | Travel class: Business or Economy                  | Categorical (2 values) |
| **Duration**         | Total flight duration in hours                     | Continuous             |
| **Days Left**        | Days between booking and travel                    | Derived Continuous     |
| **Price**            | 💡 Target variable – flight ticket price           | Continuous             |

---

## ⚙️ Feature Engineering Process

### 🔍 1. Missing Value Treatment

* Handled using imputation (mean/mode) or logical inference based on context.

### ⚖️ 2. Imbalanced Data Handling

* Techniques like **resampling** or **class weighting** used where necessary.

### 🚫 3. Outlier Detection and Removal

* Used **IQR method** and **Z-score** to detect and cap/remove extreme values.

### 🔠 4. Encoding Categorical Features

* Applied **One-Hot Encoding** and **Label Encoding** to convert categories into numerical format.

### 🧠 5. Other Transformations

* Extracted new features like `Days Left`, grouped time into bins, and ensured feature consistency.

---

## 🛠️ Tools & Libraries

* **Python** (Pandas, NumPy)
* **Scikit-learn** (Preprocessing, Feature Selection)
* **Matplotlib / Seaborn** (EDA & Visualization)
* **Jupyter Notebook** (Development)

---

## 📁 Folder Structure

```
flight-price-feature-engineering/
│
├── data/                   → Raw and cleaned datasets
├── notebooks/              → Jupyter notebooks
├── scripts/                → Python scripts for preprocessing
├── visuals/                → Plots and charts
├── README.md               → Project overview
└── requirements.txt        → Dependencies
```

## 👨‍💻 Author

**Krishna Kumar**
Connect on [LinkedIn](https://linkedin.com) | GitHub: \[your\_github\_username]

---

## 📃 License

This project is licensed under the MIT License.

---

 
