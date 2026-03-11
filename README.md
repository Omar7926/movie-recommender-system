# 🎬 Movie Recommender System

📌 Description

This project is a content-based Movie Recommender System that suggests similar movies based on user input.
The data is preprocessed and cleaned using NLP techniques, and machine learning similarity methods are applied to generate recommendations.
The model is built in Jupyter Notebook and deployed as an interactive web app using Streamlit.

🚀 Demo

Enter a movie name and get top recommended similar movies instantly.

✨ Features

- Data cleaning and preprocessing using NLP
- Text vectorization and similarity calculation
- Content-based movie recommendation
- Interactive web interface using Streamlit
- Fast movie suggestions with precomputed similarity matrix

🛠 Tech Stack

- Python
- Jupyter Notebook
- Numpy
- Pandas
- Scikit-learn
- NLTK
- Pickle
- Streamlit

⚙️ Installation & Setup
1️⃣ Clone the repository

git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the Streamlit app

streamlit run app.py

📂 Project Structure

movie-recommender-system/

│── data/

│── notebooks/

│    └── movie_recommender.ipynb

│── app.py

│── movies.pkl

│── similarity.pkl

│── requirements.txt

│── README.md

🧠 How It Works

- Movie dataset is cleaned and preprocessed.

- Important text features (overview, genres, keywords, cast) are combined.

- NLP techniques (tokenization, stemming) are applied using NLTK.

- Text is converted into vectors using CountVectorizer.

- Cosine similarity is calculated between movies.

- Streamlit UI allows users to search a movie and get recommendations.

 🌐 Local Demo
Run the app locally and open:

http://localhost:8501

📊 Results

- Accurate similarity-based movie recommendations

- Fast prediction using precomputed similarity matrix

- Smooth and interactive Streamlit web interface
