# 🚗 RoadGuard AI – Road Accident Risk Prediction

RoadGuard AI is a machine learning project that predicts potential road accident risk based on weather conditions, road conditions, and traffic levels. It uses a **Decision Tree Classifier** to classify risk as Low, Medium, or High through an interactive web dashboard.

## ✨ Features

* 🚦 **Accident Risk Prediction** – Predicts Low, Medium, or High risk.
* 🌦️ **Weather Analysis** – Considers different weather conditions.
* 🛣️ **Road Condition Analysis** – Evaluates dry, wet, and slippery roads.
* 🚘 **Traffic Analysis** – Considers low, medium, and high traffic levels.
* 🌳 **Decision Tree Classifier** – Uses a machine learning classification model.
* 📊 **Confusion Matrix** – Displays model evaluation results.
* 📈 **Classification Report** – Shows precision, recall, F1-score, and support.
* 💻 **Interactive Dashboard** – Provides a simple interface to explore predictions.

## 🛠️ Technologies Used

* Python
* Flask
* Pandas
* Scikit-learn
* HTML
* CSS
* JavaScript
* Machine Learning

## 📂 Project Structure

```text
RoadGuard-AI/
├── app.py
├── accident_data.csv
├── requirements.txt
├── templates/
│   └── index.html
└── static/
    ├── style.css
    └── script.js
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/RoadGuard-AI.git
```

### 2. Navigate to the project folder

```bash
cd RoadGuard-AI
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Open in your browser

Visit:

```text
http://127.0.0.1:5000
```

## 🧠 How It Works

1. The user selects weather, road, and traffic conditions.
2. The application sends the selected conditions to the machine learning model.
3. The Decision Tree Classifier predicts the corresponding risk category.
4. The dashboard displays the prediction and model evaluation information.

## 📊 Model Evaluation

The project uses a confusion matrix, classification report, and accuracy score to evaluate the model on test data.

Evaluation results depend on the dataset and the training/test split.

## 🎯 Project Objective

The objective is to explore how machine learning can analyze road and traffic conditions to estimate accident risk and support road-safety awareness.

## 🔮 Future Improvements

* Use larger, real-world road accident datasets.
* Include additional factors such as vehicle speed and time of day.
* Improve model performance through comparison with other algorithms.
* Deploy the application online.
* Integrate real-time traffic and weather data.

## ⚠️ Disclaimer

This project is an educational machine learning prototype. Its predictions are not a verified measure of real-world accident probability and should not be used as the sole basis for road-safety decisions.

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)

---

⭐ If you find this project interesting, consider giving the repository a star!
