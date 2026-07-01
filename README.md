# 🇮🇳 Indian Startup Funding Analysis & Prediction

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning** on the Indian Startup Funding dataset. It analyzes funding trends, startup growth, investor activity, industry performance, and predicts startup funding amounts using a regression model.

---

## 📂 Dataset

The dataset contains information about Indian startup investments, including:

- Startup Name
- Industry Vertical
- City/Location
- Investment Type
- Investors Name
- Funding Amount (USD)
- Funding Date

---

## 🎯 Project Objectives

- Clean and preprocess startup funding data.
- Analyze yearly funding trends.
- Identify top-funded startups.
- Find the most active investors.
- Analyze funding by industry and city.
- Visualize important business insights.
- Build a machine learning regression model to predict funding amount.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio
- Kaggle API

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Data inspection
- Missing value handling
- Data cleaning
- Feature engineering
- Summary statistics
- Year-wise funding analysis
- Top industry sectors
- Top startup analysis
- City-wise funding analysis
- Investor analysis
- Investment type distribution
- Funding amount distribution
- Sector vs City heatmap

---

## 🤖 Machine Learning Model

A regression model is trained to estimate startup funding amount using features such as:

- Industry Vertical
- City/Location
- Investment Type
- Year

### Model Pipeline

- Data Preprocessing
- One-Hot Encoding
- Train-Test Split
- Regression Model
- Model Evaluation
- Feature Importance Analysis

---

## 💾 Model Saving

The trained model is saved using **Joblib** for future predictions.

Saved files include:

- Trained model (.joblib)
- Feature information
- Target transformation details

---

## 🌐 Gradio Interface

An interactive Gradio application is included to allow users to enter startup details and receive predicted funding amounts.

---

## 📈 Key Insights

- Funding trends vary significantly across years.
- Certain cities dominate startup investments.
- Technology-related sectors receive the highest funding.
- A small number of investors participate in a large share of funding rounds.
- Investment type has a noticeable influence on funding amount.

---

## 📁 Project Structure

```
IndianStartupFunding/
│
├── IndianStartup_fixed.ipynb
├── startup_funding.csv
├── startup_funding_model.joblib
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/IndianStartupFunding.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

5. Launch the Gradio application to make funding predictions.

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
gradio
kaggle
```

---

## 🚀 Future Improvements

- Improve prediction accuracy using advanced regression models.
- Deploy the application on Hugging Face Spaces or Streamlit Cloud.
- Add real-time startup funding data.
- Build a dashboard for interactive analytics.

---

## 👩‍💻 Author

**Priyanka Kambar**

---

## 📜 License

This project is intended for educational and learning purposes.
```
