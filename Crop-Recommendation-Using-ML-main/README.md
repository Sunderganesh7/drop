# 🌱 Crop Recommendation System using Machine Learning

## 📌 Overview

This project is a **Machine Learning-based Crop Recommendation System** that suggests the best crop to cultivate based on soil and environmental conditions.

The system takes input such as **Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall** and predicts the most suitable crop.

---

## 🚀 Features

* Predicts best crop based on input data
* User-friendly web interface
* Real-time prediction using ML model
* Input validation and error handling
* Responsive UI using Bootstrap

---

## 🛠️ Technologies Used

* **Python**
* **Flask (Backend)**
* **Scikit-learn (Machine Learning)**
* **NumPy & Pandas**
* **HTML, CSS, Bootstrap (Frontend)**
* **Pickle (Model Saving)**

---

## 📊 Input Parameters

| Parameter      | Description            |
| -------------- | ---------------------- |
| Nitrogen (N)   | Helps in leaf growth   |
| Phosphorus (P) | Root development       |
| Potassium (K)  | Plant health           |
| Temperature    | Weather condition (°C) |
| Humidity       | Moisture in air (%)    |
| pH             | Soil acidity           |
| Rainfall       | Water level (mm)       |

---

## ⚙️ How It Works

1. User enters soil and environmental values
2. Data is sent to Flask backend
3. Data is scaled using MinMaxScaler & StandardScaler
4. ML model predicts the best crop
5. Result is displayed on the webpage

---

## 📸 Screenshots

### 🔹 Input Page

<img width="1670" height="538" alt="image" src="https://github.com/user-attachments/assets/96bcfef5-52be-4ce3-8320-38a92682d8ba" />


### 🔹 Prediction Result


<img width="1580" height="268" alt="image" src="https://github.com/user-attachments/assets/44516f4d-39a1-463d-bc12-2dd9bf504088" />

---

## 📁 Project Structure

```
Crop_Recommendation/
│
├── static/
│   └── crop.png
│
├── templates/
│   └── index.html
│
├── screenshots/
│   ├── input.png
│   └── output.png
│
├── model.pkl
├── minmaxscaler.pkl
├── standscaler.pkl
├── app.py
├── train_model.py
└── README.md
```

---

## ▶️ How to Run the Project

### Step 1: Install Dependencies

```
pip install flask numpy pandas scikit-learn
```

### Step 2: Run the Application

```
python app.py
```

### Step 3: Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📌 Example

Input:

```
N = 23, P = 56, K = 78  
Temperature = 40°C  
Humidity = 200%  
pH = 7  
Rainfall = 250 mm  
```

Output:

```
Recommended Crop: Apple
```

---

## 🎯 Applications

* Helps farmers select suitable crops
* Useful in smart agriculture systems
* Reduces risk of crop failure

---

## 🚀 Future Improvements

* Add prediction confidence (%)
* Add graphs and data visualization
* Integrate real-time weather API
* Mobile app development

---

## 👨‍💻 Author

*Sunderganesh Yadavar 

---
