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
   * movies_dict.pkl
   * similarity.pkl

2. Get an API key from TMDB
   Replace the API key in app.py:
   ```text
   response = requests.get(
    'https://api.themoviedb.org/3/movie/{}?language=en-US&api_key=YOUR_API_KEY'.format(movie_id)
    )
   ```

3. Run the Streamlit app:

```bash
streamlit run app.py
```

## 🖥️ Usage

1. Open the Streamlit app in your browser.
2. Select a movie from the dropdown list.
3. Click Recommend.
4. View top 5 similar movies with posters side by side.
---

## 🛠️ Tech Stack

* Python → Core language
* Streamlit → Web UI for chatbot.
- Scikit-learn → Cosine similarity
+ Pandas & NumPy → Data handling
* NLTK → Text preprocessing
* TMDB API → Movie posters & metadata

---

## 📌 Requirements

See [requirements.txt](https://github.com/Mohd-Muzammil7052/Movie_Recommendation_System/blob/main/requirements.txt) for all dependencies:

```text
numpy == 1.24.3
pandas == 2.0.3
ast
nltk
streamlit
scikit-learn
gunicorn
```

---

## 🏗️ Project Structure  

```text
📦 Movie-Recommender-System
 ┣ 📜 README.md                   # Documentation
 ┣ 📜 app.py                      # Streamlit app
 ┣ 📜 movie_recommendation.ipynb  # Notebook for model building
 ┣ 📜 requirements.txt            # Dependencies
 ┣ 📜 tmdb_5000_movies.csv        # Raw dataset (movies metadata from Kaggle)
 ┣ 📜 tmdb_5000_credits.csv       # Raw dataset (cast & crew from Kaggle)
 ┣ 📜 movies_dict.pkl             # Processed movie metadata
 ┣ 📜 similarity.pkl              # Pre-computed similarity matrix

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

## 🙌 Acknowledgments  

Special thanks to the amazing open-source tools powering this project:  

- [TMDB API](https://www.themoviedb.org/)
- [Kaggle](https://www.kaggle.com/)
- [Scikit-Learn](https://scikit-learn.org/stable/)  
- [Pandas](https://pandas.pydata.org/)  
- [Numpy](https://numpy.org/)  
- [Streamlit](https://streamlit.io/)  

---

## 📧 Contact  

For queries or collaborations:  

**Mohd Muzammil**  
- [GitHub](https://github.com/Mohd-Muzammil7052)  
- [LinkedIn](https://www.linkedin.com/in/mohd-muzammil-109044290/) 
