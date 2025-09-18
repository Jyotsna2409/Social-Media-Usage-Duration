# 📊 Social Media Usage Duration Prediction
This project predicts the **number of hours a user is likely to spend on social media** based on their **age** and **total likes received**.  
It was developed as part of my coursework in Machine Learning and deployed with an interactive **Streamlit UI**.

---

## 🚀 Features
- Predicts **social media usage duration** using regression models.
- Takes **age** and **total likes** as inputs.
- Preprocessing with **scaling** and cleaning steps.
- Interactive **Streamlit app** with sliders for real-time predictions.
- Model stored as `.pkl` file for reuse.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Streamlit, Requests, BeautifulSoup  
- **Deployment:** Streamlit  

---

## 📂 Repository Structure
Social-Media-Usage-Duration/
├── data/
│ └── social-media.csv # Dataset
├── models/
│ ├── best_linear_regression_model.pkl
│ └── data_scalar.pkl
├── ml_assignment.ipynb # Model training and evaluation
├── app.py # Streamlit application
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## ⚙️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Jyotsna2409/Social-Media-Usage-Duration.git
   cd Social-Media-Usage-Duration
2. Install required libraries:
pip install -r requirements.txt
3. Run the Streamlit app:
streamlit run app.py
4. Open browser at http://localhost:8501 and input age & likes to see predictions.
