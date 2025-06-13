# 🕵️‍♂️ Social Media Fake Profile Detection

This is a Flask-based web application that uses a trained XGBoost model to detect fake social media profiles based on user input data.

---

## 📁 Project Structure

Social-media/
│
├── app.py                  # Main Flask application  
├── model.pkl               # Trained XGBoost model  
├── req.txt                 # Python dependencies  
├── /venv/                  # Virtual environment (optional)  
└── /templates/             # HTML templates (index.html etc.)  
    └── index.html

---

## ⚙️ Setup Instructions

1. Clone the repository and move into the folder:
    ```bash
    git clone <repo_url>
    cd Social-media
    ```

2. Install `virtualenv` (if not installed):
    ```bash
    pip install virtualenv
    ```

3. Create a virtual environment:
    ```bash
    virtualenv -p python3 venv
    ```

4. Activate the virtual environment (Windows):
    ```bash
    .\venv\Scripts\activate
    ```

5. Install required packages:
    ```bash
    pip install -r req.txt
    ```

---

## ▶️ How to Run the App

1. Activate your virtual environment:
    ```bash
    .\venv\Scripts\activate
    ```

2. Start the Flask app:
    ```bash
    python app.py
    ```

3. Open the server link shown in the terminal:
    ```
    http://127.0.0.1:5000/
    ```

⚠️ **Do not open `index.html` directly in browser. Use the Flask server.**

---

## 🛠 Tech Stack

- Python  
- Flask  
- Jinja2  
- HTML/CSS  
- XGBoost  
- Pandas  

---

## 👨‍💻 Author

**Neeraj Verma**

---

## 📄 License

This project is licensed under the **MIT License**.
