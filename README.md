# 🏠 House Price Prediction ML App

__This project is a simple machine learning-powered web application that predicts house prices based on user input. The application is built using Python, trained using scikit-learn, and deployed with Flask.__
## 📁 Project Structure

```harshyadav152-price-prediction-ml-app/
├── app.py                        # Flask minimal web app
├── House_Price_Prediction.ipynb  # Notebook for data analysis and model training
├── house_price_prediction.pkl    # Trained machine learning model
├── requirements.txt              # Python dependencies
└── templates/
    └── index.html                # HTML template for the web UI
```

---

## 🚀 Features

1. Web interface to input housing parameters

2. Predicts house prices using a trained ML model

3. Easy-to-run Flask app

4. Includes Jupyter notebook for training and exploration
---

## 📦 Installation

1. Clone the repository

``` bash
git clone https://github.com/HarshYadav152/Price-prediction-ML-app.git
cd Price-prediction-ML-app
```
2. Create and activate a virtual environment (optional but recommended)

``` python
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install dependencies

```python
pip install -r requirements.txt
```

---

## 🧠 Model Training (optional)

The model is already trained and saved as house_price_prediction.pkl. However, if you wish to retrain it:

### Open and run the Jupyter notebook:
```bash
jupyter notebook House_Price_Prediction.ipynb
```

---

# 🌐 Running the Web App

- After installing dependencies, simply run:

```python
python app.py
```
- Then, open your browser and go to:

- `http://localhost:5000/`

- Enter the required housing details, and the app will display the predicted price.
---

## 🛠 Built With

- [Python](https://python.org)

- [Flask](https://flask.palletsprojects.com/en/stable/)

- [scikit-learn](https://scikit-learn.org/stable/)

- [Pandas](http://pandas.pydata.org/)

- [Jupyter Notebook](https://jupyter.org/)
---

📌 Example Use
## Check now [here](https://price-ml-app.onrender.com)
- As it is hosted on `render.com` so wait or 2 to 5 minutes for restart app.
- Fill details it ask. 
- After clicking Predict, the app will output a predicted house price in currency (₹/$ based on the dataset used).

---

## ✅ Requirements

See requirements.txt for full package list. Key ones include:

- Flask
- scikit-learn
- pandas
- numpy
---
## Support
[By a star](https://github.com/HarshYadav152/Price-prediction-ML-app)
# 👤 Author

__Harsh Yadav__
- [🔗 GitHub Profile](https://github.com/HarshYadav152)
- [🔗 Linkedin Profile](https://linkedin.com/in/HarshYadav152)
