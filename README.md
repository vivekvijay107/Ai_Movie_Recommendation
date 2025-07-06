AI Movie Recommender Web App
============================

An AI-powered movie recommendation system built with Streamlit and Google Colab. It recommends movies based on:

- 🎞️ Genre
- 🗣️ Language
- 🕰️ Year preference (Recent or Classic)
- 😄 Mood (e.g., happy, romantic, thrilling)

It uses TF-IDF and cosine similarity on movie overviews to suggest the most relevant films.

----------------------------------------

How to Use in Google Colab
---------------------------

1. Install required packages:
   !pip install streamlit pyngrok --quiet

2. Upload the dataset:
   from google.colab import files  
   files.upload()  # Upload tmdb_5000_movies.csv

3. Save the app code:
   %%writefile app.py  
   # (Paste your Streamlit app code here)

4. Add your ngrok token:
   !ngrok config add-authtoken YOUR_AUTHTOKEN

5. Run the app:
   from pyngrok import ngrok  
   !streamlit run app.py &>/content/log.txt &  
   public_url = ngrok.connect("http://localhost:8501")  
   print(public_url)

----------------------------------------

Requirements
------------

- pandas  
- scikit-learn  
- streamlit  
- pyngrok

Install locally with:
pip install pandas scikit-learn streamlit pyngrok

----------------------------------------

Author
------

Vivek Vijay  
GitHub: https://github.com/vivekvijay107
