# 🩺 Diabetes Prediction Web App  

A **Flask-based web application** that predicts whether a person is **Diabetic or Non-Diabetic** based on health parameters.  
The model is trained on the **PIMA Diabetes Dataset** and deployed with a simple HTML frontend.  

---

## 📑 Table of Contents  

- [📖 Introduction](#-introduction)  
- [✨ Features](#-features)  
- [📂 Dataset](#-dataset)  
- [🚀 Installation](#-installation)  
- [⚙️ Setup](#️-setup)  
- [🖥️ Usage](#️-usage)  
- [🛠️ Tech Stack](#-tech-stack)  
- [📌 Requirements](#-requirements)  
- [🏗️ Project Structure](#️-project-structure)  
- [📄 License](#-license)  
- [🤝 Contributing](#-contributing)  
- [📧 Contact](#-contact)  

---

## 📖 Introduction  

Diabetes is one of the most common chronic diseases worldwide.  
This project uses **machine learning models (Logistic Regression, Naive Bayes, SVM, Decision Tree)** to predict diabetes based on medical attributes.  

A trained model is integrated into a **Flask web app**, where users can input their health details and get predictions in real time.  

---

## ✨ Features  

- 🧪 **Predict Diabetes** → Input health parameters and check if the person is diabetic.  
- 📊 **Multiple ML Models** → Logistic Regression, Naive Bayes, SVM, Decision Tree were tested.  
- 🌐 **Web Interface** → HTML templates for input and results.  
- 🔧 **Scalable Flask App** → Easily deployable to cloud platforms.  

---

## 📂 Dataset  

- Dataset: `Dataset/diabetes.csv`  
- Contains medical attributes like:  
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
  - Outcome (0 = Non-Diabetic, 1 = Diabetic)  

---

## 🚀 Installation  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/<your-username>/Diabetes-Prediction-WebApp.git
cd Diabetes-Prediction-WebApp
pip install -r requirements.txt
```

## ⚙️ Setup

1. Place the following files in the project root:
   * modelforprediction.pkl
   * standardScaler.pkl

2. Run the Flask app:
   ```text
   python application.py
   ```

## 🖥️ Usage

1. Open the app in your browser at http://127.0.0.1:5000/
2. Navigate to:
   * / → Home page
   * /predictdata → Enter health parameters for prediction 
3. The app will display:
   * Diabetic
   * Non-Diabetic
---

## 🛠️ Tech Stack

* Python → Core language
* Flask → Backend web framework
- Scikit-learn → Machine learning models
+ Pandas & NumPy → Data handling
* Seaborn → Data visualization (exploration phase)
* HTML/CSS → Frontend templates

---

## 📌 Requirements

See [requirements.txt](https://github.com/Mohd-Muzammil7052/Diabetes_Prediction_Ml/blob/main/requirements.txt) for all dependencies:

```text
pandas
numpy
scikit-learn
seaborn
Flask
```

---

## 🏗️ Project Structure  

```text
📦 Diabetes-Prediction-WebApp
 ┣ 📂 Dataset
 ┃ ┗ 📜 diabetes.csv
 ┣ 📂 Model
 ┃ ┣ 📜 modelforprediction.pkl
 ┃ ┗ 📜 standardScaler.pkl
 ┣ 📂 Notebook
 ┃ ┣ 📜 logistic_regression.ipynb
 ┃ ┗ 📜 naive_bayes_svm_decision_tree.ipynb
 ┣ 📂 templates
 ┃ ┣ 📜 home.html
 ┃ ┣ 📜 index.html
 ┃ ┗ 📜 single_prediction.html
 ┣ 📜 application.py
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

## 📄 License  

This project is licensed under the [MIT License](https://opensource.org/license/mit).  
Feel free to use, modify, and distribute it as needed.

---

## 🤝 Contributing  

Contributions are welcome! 🎉  
If you’d like to improve this project:  

1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request  

---

## 📧 Contact  

For queries or collaborations:  

**Mohd Muzammil**  
- [GitHub](https://github.com/Mohd-Muzammil7052)  
- [LinkedIn](https://www.linkedin.com/in/mohd-muzammil-109044290/) 
