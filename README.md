# 🎬 Netflix Movie Data Analysis & Recommendation System  

This project analyzes the **Netflix dataset** and builds a **content-based recommendation system** using **Natural Language Processing (NLP)** — implemented entirely in a **Google Colab notebook**.  

It provides insights into Netflix’s catalog and recommends movies similar to a given title using **TF-IDF vectorization** and **cosine similarity**.  

---

## 📌 Description  

The notebook explores Netflix’s catalog to uncover trends such as most common genres, year-wise growth, and global distribution of content.  
It then applies **TF-IDF** on descriptions, genres, and cast information to generate vector representations and uses **cosine similarity** to recommend similar movies.  

This project demonstrates how **NLP techniques** can be applied to real-world datasets in the entertainment industry for recommendation systems.  

---

## ✨ Features  

- Exploratory Data Analysis (EDA) of Netflix dataset  
- Visualizations: Genre trends, year-wise content growth, country distribution  
- TF-IDF preprocessing on movie descriptions  
- Cosine similarity for recommendations  
- Enter a movie → get top N similar movies  

---

## 🛠 Tech Stack  

- **Google Colab** (Python 3.x)  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, nltk  

---

## ▶️ How to Run  

1. Open the notebook in **Google Colab**.  
2. Upload the dataset (`netflix_titles.csv`) when prompted.  
3. Run all cells to:  
   - Perform dataset analysis  
   - Train TF-IDF model  
   - Generate recommendations
   - Recommended Movies for 'Inception':

      Til Death Do Us Part
      Apollo 18
      Incarnate
      Black Mirror
      Transformers: Cyberverse
      Abby Sen
      Candyflip
      Altered Carbon
      Dark
      Maniac

---

## 📊 Insights  

- Netflix’s growth trend over the years  
- Top genres worldwide  
- Country-wise content distribution  
- WordCloud of movie descriptions  

---

## 🚀 Future Scope  

- Hybrid recommendation model (collaborative + content-based)  
- BERT or Sentence Transformers for semantic similarity  
- Deploy as a web app (Flask/Django + Streamlit/Gradio UI)  

---

## 📜 License  

This project is licensed under the **MIT License**.  

---

## 📂 Project Structure  
Movie-Analysis-and-Recommendation-/
├── Netflix_movie_recommendation.ipynb # Main Colab notebook
└── README.md # Documentation




