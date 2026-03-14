# 💰 Salary Prediction Using Machine Learning

A **Machine Learning project** that predicts employee salaries based on features such as experience, education, and other relevant attributes.  
The model analyzes historical salary data and learns patterns to estimate salary for new inputs.

This project demonstrates the **complete machine learning workflow**, including data preprocessing, model training, evaluation, and prediction.

---

# 📌 Project Overview

Salary prediction is a common regression problem in machine learning.  
This project applies multiple ML algorithms to predict salary values based on given input features.

The workflow includes:

- Data preprocessing and cleaning
- Feature analysis
- Model training
- Model evaluation
- Salary prediction using trained models

---

# 🧠 Machine Learning Models Used

The following algorithms were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Among these models, **Random Forest achieved the best performance with the highest accuracy**.

---

# ⚙️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📁 Project Structure

```
salary-prediction-ml
│
├── dataset
│   └── salary_data.csv
│
├── notebooks
│   └── salary_prediction.ipynb
│
├── models
│   └── trained_model.pkl
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Dataset

The dataset contains information about employees and their corresponding salaries.

Example features:

| Feature | Description |
|------|-------------|
| Experience | Years of work experience |
| Education Level | Qualification level |
| Job Role | Type of job |
| Location | Job location |
| Salary | Target variable |

---

# 🔄 Machine Learning Pipeline

The project follows these steps:

### 1️⃣ Data Collection
The dataset is loaded using **Pandas**.

### 2️⃣ Data Preprocessing
- Handling missing values
- Feature encoding
- Data normalization

### 3️⃣ Feature Selection
Important features are selected to improve prediction performance.

### 4️⃣ Model Training
Multiple regression models are trained using **Scikit-learn**.

### 5️⃣ Model Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 6️⃣ Prediction

The trained model predicts salary values for new data inputs.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/salary-prediction-ml.git
```

Navigate to the project folder

```bash
cd salary-prediction-ml
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Launch the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```
salary_prediction.ipynb
```

Run all cells to train the model and generate predictions.

---

# 📈 Results

The Random Forest model achieved the **highest prediction accuracy** compared to other models.

Example evaluation metrics:

- MAE: Low error rate
- MSE: Minimal prediction variance
- R² Score: High prediction reliability

---

# 🔮 Future Improvements

Possible enhancements include:

- Deploying the model as a **web application**
- Adding **more features to the dataset**
- Implementing **deep learning regression models**
- Creating an **interactive dashboard**

---

# 👩‍💻 Author

**Thumma Manojna Reddy**

AI / ML Enthusiast  
B.Tech CSE (AI & ML)

🔗 GitHub  
https://github.com/thummamanojnareddy  

🔗 LinkedIn  
https://www.linkedin.com/in/manojna-reddy-thumma-536b9730b/

---

⭐ If you found this project helpful, consider **starring the repository**!
