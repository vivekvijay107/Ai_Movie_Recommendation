# 🎬 AI Movie Recommendation System

This is a simple AI-powered movie recommendation system built using Python and Google Colab. It allows users to receive movie suggestions based on their preferences like **genre**, **release year**, **language**, and **mood**.

---

## 🚀 Features

- Interactive movie recommendation based on:
  - Genre (Action, Comedy, Drama, etc.)
  - Preference for recent or classic movies
  - Preferred language (e.g., English, Hindi, French)
  - Optional mood input (Happy, Sad, Thrilling, etc.)
- Works with the **TMDB 5000 Movies Dataset**
- Built entirely using **Python** and **Pandas**
- Runs smoothly in **Google Colab**

---

## 📁 Dataset

This project uses the **TMDB 5000 Movie Dataset**, which you can download from:

🔗 [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Place the file `tmdb_5000_movies.csv` in your working directory or upload it in Colab.

---

## 📒 How to Run the Project (Google Colab)

1. Open [Google Colab](https://colab.research.google.com)
2. Upload the notebook file (`ai_movie.ipynb`)
3. Upload the dataset `tmdb_5000_movies.csv` when prompted
4. Run the notebook cells
5. Answer the questions in the console to get your movie recommendations!

---

## 🧠 Example Questions Asked

```text
What genre do you like? (e.g., Action, Comedy, Drama)
Do you prefer 'recent' or 'classic' movies?
Preferred language? (e.g., en, hi, fr)
What's your mood? (optional)
## 📦 Requirements

This project runs directly in Google Colab (no installation needed there), but if you're running locally, install the following packages:

- `pandas==2.2.2` – for data manipulation
- `numpy==1.26.4` – for numerical operations
- `scikit-learn==1.4.2` – (optional) for future machine learning enhancements
- `streamlit==1.35.0` – (optional) to build a web UI
- `ipykernel==6.29.4` – for Jupyter Notebook compatibility

### 📥 Install all at once:
```bash
pip install pandas numpy scikit-learn streamlit ipykernel
