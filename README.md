# 🌲 Fire Weather Index (FWI) Web App Predictor 🌲

This web application predicts the **Fire Weather Index (FWI)** for Algerian forest fires using various regression models, including:

- 🔍 **Ridge Regression**
- 🧮 **Lasso Regression**
- 📈 **Linear Regression**
- 🌀 **ElasticNet**

After comparison and cross-validation, **Ridge Regression** was selected as the optimal model due to its superior accuracy.

---

### 📊 Dataset Overview

- **Regions:** Bejaia (northeast) & Sidi Bel-abbes (northwest)
- **Period:** June to September 2012
- **Attributes:** Weather-related data like temperature, humidity, wind speed, rain, and FWI system components

---

### ⚙️ Technologies Used

- **Programming Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Pickle, Warnings
- **Web Framework:** Flask 🖥️
- **Frontend:** HTML, CSS 🎨

---

### 🧹 Data Cleaning & Preprocessing

- Addressed missing values, data type conversions, and removed unnecessary features.
- Cleaned categorical values and saved the cleaned data as a CSV file.

---

### 🔍 Exploratory Data Analysis (EDA)

- Analyzed fire distribution across months and regions.
- **Key Insight:** August had the highest number of fires in both regions.
- **Tools:** Box plots, count plots, and correlation matrices.

---

### 🔧 Feature Engineering & Model Development

- Conducted feature selection based on correlation to identify important variables.
- Addressed multicollinearity by dropping highly correlated columns.
- Standardized features using **StandardScaler**.
- Compared Ridge, Lasso, Linear Regression, and ElasticNet models. Ridge Regression was chosen for its superior performance.

---

### 📈 Model Evaluation

- Evaluated model performance using **Mean Absolute Error (MAE)** and **R2 Score**.
- **Ridge Regression** provided promising results and insights for FWI prediction.

---

### 🖥️ Web App Usage

To run the web application locally, follow these steps:

---

### 1️⃣ Clone the GitHub Repository

```bash
git clone https://github.com/MihirKT/Pregrad_August_Project.git
```

---

2️⃣ Install Python
If you don’t have Python installed, download it from the official website:
🔗 Download [Python](https://www.python.org/downloads/)

---

3️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
```
---
4️⃣ Activate the Virtual Environment (Optional but Recommended)
For Windows:
```bash
venv\Scripts\activate
```
For macOS and Linux:
```bash
source venv/bin/activate
```
---

5️⃣ Install Required Packages
Navigate to the root folder of your cloned repository and run the following command:
```bash
pip install -r requirements.txt
```
---

6️⃣ Run the Flask Application
Run the Flask app using:
```bash
python application.py
```
---

7️⃣ Access the Application
Once the application is running, open your browser and go to:
```
🌍 http://localhost:5000
```

