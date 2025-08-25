# 🏥 Medical Cost Prediction using Insurance Dataset

This project analyzes the **Medical Cost Personal Insurance Dataset** from Kaggle and builds machine learning models to predict individual medical charges based on demographic and lifestyle features.

---

## 📂 Dataset
- **Source:** Kaggle - [Medical Cost Personal Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
- **Features:**
  - `age`: Age of the individual  
  - `sex`: Gender (male/female)  
  - `bmi`: Body Mass Index (numeric)  
  - `children`: Number of children/dependents  
  - `smoker`: Smoking status (yes/no)  
  - `region`: Residential area (northeast, northwest, southeast, southwest)  
  - `charges`: Individual medical costs billed by health insurance  

---

## 🔍 Project Workflow
1. **Data Exploration (EDA)**  
   - Summary statistics  
   - Distribution plots & histograms  
   - Correlation heatmaps  

2. **Data Preprocessing**  
   - Handling categorical features with encoding  
   - Feature scaling  
   - Checking missing values  

3. **Modeling**  
   - Linear Regression  
   - Decision Trees / Random Forest  
   - Gradient Boosting / LightGBM  
   - Model evaluation (RMSE, R² score)  

4. **Insights & Visualization**  
   - Effect of smoking on charges  
   - Relationship between BMI and medical cost  
   - Regional differences  

---

## 📊 Results
- Smoking is the **most significant factor** affecting medical charges.  
- Higher BMI is correlated with increased insurance costs.  
- Ensemble models such as **Random Forest & LightGBM** outperform simple linear regression.  

---

## 🚀 Tech Stack
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn, LightGBM** – Machine Learning  

---

## 📌 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Medical-Cost-Prediction.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook medical-cost-personal.ipynb
