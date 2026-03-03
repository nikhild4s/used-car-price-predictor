# used-car-price-predictor
Machine Learning project to predict used car prices using Random Forest Regression

## 🚗 Used Car Price Prediction  

A Machine Learning project that predicts used car prices based on features like brand, year, kilometers driven, fuel type, transmission, engine details, and more.

---

## 📁 Project Structure  

PROJECTAI.ipynb
│── Main ML notebook (EDA, preprocessing, training, evaluation)

app.py
│── Streamlit web application for real time prediction

car_details_v4_1.csv
│── Dataset containing 2059 used car listings

---

## 🧠 Models Implemented  

| Model                        | R² Score |
|------------------------------|----------|
| Random Forest Regression     | 0.818    |
| Polynomial Regression        | 0.810    |
| Decision Tree Regression     | 0.799    |
| Multiple Linear Regression   | 0.713    |
| Simple Linear Regression     | 0.001    |
| Support Vector Regression    | -0.116   |

---

## ✅ Best Performing Model  

**Random Forest Regression** achieved the highest performance.

R² Score = **0.818**

This means the model explains approximately **81.8 percent** of the variance in car prices.

---

## ⚙️ Tech Stack  

- Python  
- Pandas  
- NumPy  
- Scikit learn  
- Matplotlib  
- Seaborn  
- Streamlit  

---

## 🚀 How to Run the Project  

### 1️⃣ Install Dependencies  

```bash
pip install pandas numpy scikit-learn matplotlib seaborn streamlit
```

### 2️⃣ Run the Notebook  

Open `PROJECTAI.ipynb` in Jupyter Notebook.

### 3️⃣ Run the Web Application  

```bash
streamlit run app.py
```

---

## 📊 Dataset Description  

The dataset contains **2059 used car listings** with features such as:

- Make  
- Model  
- Year  
- Kilometer Driven  
- Fuel Type  
- Transmission  
- Engine  
- Max Power  
- Max Torque  
- Location  
- Owner Type  
- And other relevant attributes  

---

## 📈 Key Highlights  

- Performed Exploratory Data Analysis  
- Applied Feature Engineering  
- Compared Multiple Regression Models  
- Evaluated using R² score  
- Deployed using Streamlit  

---

## 👨‍💻 Author  

**Nikhil Swarup Das (2401020189)**  
AI Project
