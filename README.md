
# 🚗 Driver Availability Prediction

**License:** MIT
**Tech:** Python · Flask · Machine Learning

A machine learning–powered web application built using **Flask** that predicts whether a driver is **available or not** based on location and time-related inputs.
This project is useful for **ride-sharing platforms, logistics systems, and delivery scheduling applications**.

---

## 🚀 Features

* 📍 Input pickup point, day, and time
* 🧠 Predict driver availability using a trained ML model
* 📊 Visual feedback for availability status
* 🌐 Lightweight and responsive Flask web interface

---

## 🛠 Tech Stack

| Layer    | Technology             |
| -------- | ---------------------- |
| Backend  | Python, Flask          |
| ML Model | Scikit-learn           |
| Frontend | HTML5, CSS3, Bootstrap |
| Dataset  | CSV-based              |

---

## 📂 Project Structure

```
Driver-Availability/
├── app.py              # Main Flask application
├── model.pkl           # Trained machine learning model
├── scaler.pkl          # Feature scaling object
├── templates/          # HTML templates
├── static/             # CSS and static assets
├── driver.csv          # Sample dataset
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
```

---

## 💻 How to Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Dhruthi16/Driver_Availability_Prediction.git
cd Driver_Availability_Prediction
```

---

### 2️⃣ Create & Activate a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
python app.py
```

🌐 Open your browser at:

```
http://localhost:5000
```

---

## 🧠 Machine Learning Logic

* Uses **classification techniques** (e.g., Decision Tree or Logistic Regression)
* Key input features:

  * Pickup Point
  * Day of the Week
  * Time Slot
* `model.pkl` → trained ML model
* `scaler.pkl` → standardizes input features before prediction

---

## ⚠️ Notes

* Ensure `model.pkl` and `scaler.pkl` are present in the root directory
* The model can be retrained using `driver.csv`
* Easily extendable with:

  * Geolocation APIs
  * Real-time driver availability data
  * Database integration

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project.

---
