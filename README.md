# 🎬 AI Movie Recommendation System

This project is an AI-powered movie recommendation web app built using **Streamlit**, **Python**, and **Google Colab**. It recommends movies based on user preferences including **genre**, **release year (recent/classic)**, **language**, and **mood** by leveraging NLP techniques on movie overviews.

---

## 🚀 Features

- Interactive movie recommendations based on:
  - Genre (Action, Comedy, Drama, etc.)
  - Release type (Recent or Classic)
  - Language (English, Hindi, French, etc.)
  - Mood (Happy, Thrilling, Romantic, etc.)
- Mood filtering using TF-IDF vectorization and cosine similarity on movie overviews
- Uses TMDB 5000 Movies dataset for recommendations
- Simple, clean UI powered by Streamlit
- Hosted easily via Google Colab and Ngrok tunnel

---

## 📁 Dataset

The app uses the [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). Download the dataset and upload the `tmdb_5000_movies.csv` file in Google Colab when prompted.

---

## 📒 How to Run (Google Colab)

1. Open Google Colab in your browser.
2. Upload your dataset file (`tmdb_5000_movies.csv`) when prompted.
3. Run the notebook cells to install dependencies and write the app code.
4. Add your Ngrok authtoken (replace the example token with your own from [ngrok dashboard](https://dashboard.ngrok.com/get-started/your-authtoken)).
5. Run the Streamlit app and open the generated public URL to access the web app.

---

## 🛠️ Code Overview

- `app.py` contains the Streamlit app code:
  - Loads and preprocesses the dataset
  - Creates TF-IDF vectors of movie overviews for mood matching
  - Provides a user interface for input and displays recommendations
- Ngrok is used to create a public URL for the Streamlit app running in Colab

---

## 🔧 Requirements

- Python 3.x
- Packages (auto-installed in Colab):
  - `streamlit`
  - `pyngrok`
  - `pandas`
  - `scikit-learn`

Install locally via:

```bash
pip install streamlit pyngrok pandas scikit-learn
