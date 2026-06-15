# 🎬 Movie Recommendation System

A Machine Learning-powered Movie Recommendation System that suggests movies similar to a user's selection. The application uses content-based filtering and displays movie posters fetched dynamically from TMDB.

## 🚀 Live Demo

(https://movie-recommendation-system-hoskq3pqqnqtepgpn7vbba.streamlit.app/)

## 📌 Features

* Movie recommendations based on content similarity
* Interactive web interface built with Streamlit
* Dynamic movie poster fetching using TMDB API
* Fast recommendation generation using precomputed similarity scores
* Easy-to-use and responsive UI
* Deployed for public access

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Requests
* Pickle

### APIs

* TMDB (The Movie Database) API

### Version Control & Deployment

* Git
* GitHub
* Streamlit Cloud

---

## 📊 How It Works

The recommendation engine uses a **Content-Based Filtering** approach.

### Workflow

1. Movie metadata is collected and preprocessed.
2. Important features such as:

   * Genres
   * Keywords
   * Cast
   * Crew
   * Overview
3. These features are combined into a single text representation.
4. Text data is vectorized using feature extraction techniques.
5. Cosine similarity is calculated between movies.
6. When a user selects a movie, the system finds the most similar movies based on similarity scores.
7. Recommended movie posters are fetched using the TMDB API.

---

## 📂 Project Structure

```bash
Movie-Recommendation-System/
│
├── app.py
├── Main_Code.ipynb
├── movie_list.pkl
├── similarity.pkl
├── requirements.txt
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
└── README.md
```

## ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/StarLord2006/Movie-Recommendation-System.git
```

### Navigate to Project Directory

```bash
cd Movie-Recommendation-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```bash
http://localhost:8501
```

---

## 🧠 Learning Outcomes

Through this project, I gained practical experience in:

* Machine Learning fundamentals
* Recommendation Systems
* Feature Engineering
* Data Preprocessing
* API Integration
* Streamlit Application Development
* Cloud Deployment
* Git & GitHub Workflow
* Debugging and Problem Solving

---

## 🔮 Future Improvements

* User-based collaborative filtering
* Hybrid recommendation system
* User authentication
* Movie ratings and reviews
* Search optimization
* Personalized recommendations
* Advanced UI/UX enhancements

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome.

Feel free to fork the repository and submit a pull request.

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

---

## 👨‍💻 Author

Satvik Jaiswal

GitHub: https://github.com/StarLord2006

LinkedIn: https://www.linkedin.com/in/satvik-jaiswal-650858311
