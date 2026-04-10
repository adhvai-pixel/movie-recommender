🎬 Movie Recommender

A simple and efficient Movie Recommendation System built using Machine Learning that suggests similar movies based on user input.

📌 Project Overview

This project recommends movies by analyzing features such as genres, keywords, cast, and crew. It uses content-based filtering to find similarities between movies and suggest relevant ones.

🚀 Features

🔍 Enter a movie name

🎯 Get top 5 similar movie recommendations

⚡ Fast and lightweight system

🧠 Built using machine learning concepts

🛠️ Tech Stack

Language: Python 🐍

Libraries:

Pandas

NumPy

Scikit-learn

📂 Project Structure
movie-recommender/
│── main.py            # Main application file
│── preprocess.py      # Data preprocessing and vectorization
│── recommend.py       # Recommendation logic
│── requirements.txt   # Dependencies
│── movies.csv         # Dataset
│── README.md          # Documentation
![WhatsApp Image 2026-03-13 at 3 37 26 AM](https://github.com/user-attachments/assets/bd78d40e-85d0-4b12-8a6f-1f90cc85e652)

⚙️ How It Works

Load and clean the movie dataset

Combine important features (genres, keywords, cast, crew)

Convert text data into vectors using CountVectorizer

Compute similarity using cosine similarity

Recommend top 5 similar movies

🧠 Algorithm Used

Content-Based Filtering

Cosine Similarity

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the project
python main.py
📈 Future Improvements

🎥 Add movie posters using API

🌐 Build a web interface using Streamlit

🤖 Improve recommendations using advanced ML models

👨‍💻 Author

Adhvai
Aspiring Data Scientist 🚀
