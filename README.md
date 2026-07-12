# 🎬 Movie Recommendation System

A Movie Recommendation System built using **Python**, **Machine Learning**, and **Streamlit** that recommends movies similar to a selected movie using **Content-Based Filtering**.

## 🚀 Features

* Search and select a movie from the dataset.
* Get top movie recommendations instantly.
* Content-based recommendation using movie metadata.
* Interactive and user-friendly interface.
* Fast recommendation generation using precomputed similarity scores.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle
* TMDB Dataset

## 📂 Project Structure

```
Movie-Recommendation/
│── app.py
│── movies.pkl
│── similarity.pkl
│── requirements.txt
│── README.md
│── notebooks/
│── data/
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/jayc525/Movie-Recommendation.git
cd Movie-Recommendation
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

Activate the environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

## 📖 How It Works

1. Load the movie dataset.
2. Preprocess movie metadata.
3. Convert movie information into feature vectors.
4. Compute cosine similarity between movies.
5. Recommend the most similar movies based on the selected title.

## 📊 Dataset

This project uses the **TMDB Movie Dataset**, containing movie metadata such as:

* Movie Title
* Genres
* Overview
* Keywords
* Cast
* Crew

## 📸 Screenshots

Add screenshots of the application here.

Example:

```
screenshots/home.png
screenshots/result.png
```

## 🌟 Future Improvements

* Add movie posters using the TMDB API.
* Search autocomplete.
* Filter recommendations by genre, language, and release year.
* User authentication.
* Personalized recommendations based on user preferences.
* Deploy the application using Streamlit Community Cloud or Render.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

## 📄 License

This project is intended for educational and learning purposes.

## 👨‍💻 Author

**Jai Chakkarwar**

GitHub: https://github.com/jayc525
