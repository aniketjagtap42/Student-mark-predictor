# 🎓 Student Mark Predictor - Flask ML Web App

This is a machine learning web application that predicts **student marks** based on the number of hours studied per day. The app is built using **Flask** and utilizes a **Linear Regression model** to make real-time predictions. It’s a beginner-friendly deployment project integrating ML with web development.

![Student Mark Predictor UI](Student mark predictor input .png)

---

## 📌 Project Overview

- **Dataset:** Study Hours vs Marks dataset (`student_scores.csv`)
- **Model:** Linear Regression (`student_mark_predictor.pkl`)
- **Frameworks & Tools:** Python, Flask, scikit-learn, pandas, joblib
- **Target Variable:** `Marks (%)`
- **Input:** Study hours (range: 1 to 24)
- **Output:** Predicted marks in percentage
- **Output Logging:** Saves all user inputs & predictions to `smp_data_from_app.csv`

---

## 🧠 Features Used for Prediction

- `Number of Study Hours` (per day)

---

## 🚀 How to Run the App Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/aniketjagtap42/student-mark-predictor.git
    cd student-mark-predictor
    ```

2. (Optional) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On Mac/Linux
    ```

3. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask app:
    ```bash
    python app.py
    ```

5. Open your browser and go to:
    [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧾 Files Included

| File Name                   | Description                                      |
|----------------------------|--------------------------------------------------|
| `app.py`                   | Flask backend code                               |
| `student_mark_predictor.pkl`| Trained Linear Regression model                 |
| `templates/index.html`     | HTML frontend form                               |
| `smp_data_from_app.csv`    | Stores user predictions                         |
| `requirements.txt`         | Python packages used                            |
| `README.md`                | Project documentation                           |
| `student mark predictor input .png` | Screenshot of the web app UI       |

---

## 📷 App Preview

> Prediction UI & Result Example:
![Student Mark Predictor UI](student mark predictor input .png)

---

## 💡 Future Improvements

- Add visualizations (plot regression line, residuals, etc.)
- Enable multi-feature regression (e.g., sleep hours, revision frequency)
- Connect to a database instead of CSV logging
- Deploy the app on Render or Hugging Face Spaces

---

## 🔗 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/aniket-jagtap-27b21835b)
- [GitHub](https://github.com/aniketjagtap42)

---

## 📦 requirements.txt

```txt
Flask
pandas
numpy
scikit-learn
joblib
