# 📚 Recommendo - Smart Book Recommender System

Welcome to **Recommendo**! A Machine Learning-based web application that suggests your next favorite read. Whether you're a fan of thrillers, romance, or sci-fi, our system finds the "twin" of the book you love using Collaborative Filtering.

## 🚀 Features
* **Top 50 Books:** Explore the most popular books based on user ratings and votes.
* **Smart Search:** Enter a book title and get 4-5 highly similar recommendations instantly.
* **Modern UI:** A sleek, dark-themed interface built for book lovers.
* **Fast Backend:** Powered by Flask and optimized with NumPy.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Custom Glassmorphism UI), Jinja2 Templates.
* **Backend:** Python, Flask.
* **Machine Learning:** Pandas, NumPy, Scikit-learn (Collaborative Filtering).
* **Data Source:** Amazon Book Reviews Dataset (Kaggle).

## 📂 Project Structure
```text
├── app.py                # Main Flask Application
├── templates/            # HTML Files (index.html, recommend.html)
├── static/               # CSS and Images
├── models/               # Pickled files (popular.pkl, pt.pkl, etc.)
└── requirements.txt      # List of dependencies
```

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KrishSabharwal-byte/Book-recommendation-System.git
   cd Book-recommendation-System
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the App:**
   ```bash
   python app.py
   ```
   Open `http://127.0.0.1:5000` in your browser. 🌐

## 🧠 How It Works
The system uses **Collaborative Filtering**. We calculate the **Cosine Similarity** between users' ratings. If users who liked "The Da Vinci Code" also liked "Angels & Demons", the system will recommend the latter to you.



## 🤝 Contributing
Contributions are welcome! If you have ideas to improve the UI or the recommendation logic, feel free to fork the repo and create a pull request.

## 📧 Contact
**Krish Sabharwal** [GitHub Profile](https://github.com/KrishSabharwal-byte)

---
