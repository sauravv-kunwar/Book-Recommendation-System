# 📚 NOVELNEST - AI Book Recommendation System
- Smart book discovery powered by machine learning algorithms. Find your next favorite read instantly.

# ✨ Features
- 🎯 AI-Powered Recommendations - Get personalized suggestions

- 📊 Top 50 Trending Books - Curated collection with rankings

- 🎨 Modern UI - Beautiful, responsive design

- ⚡ Fast & Accurate - Real-time recommendations

- 🔄 Interactive Experience - Smooth animations & transitions



## Live Demo

Deployed Application:
https://book-recommendation-system-2-webw.onrender.com


## Project Structure

```
Book-Recommendation-System
│
├── app.py
├── requirements.txt
├── Procfile
│
├── templates
│   ├── index.html
│   └── recommend.html
│
├── books.pkl
├── popular.pkl
├── pt.pkl
├── similarity_scores.pkl
│
├── Ratings.csv
├── Users.csv
└── README.md
```

## Technologies Used

* Python
* Flask
* Pandas
* NumPy
* HTML / CSS
* Pickle (for model storage)

## How It Works

1. The dataset is processed to create a **pivot table of users and books**.
2. A **similarity matrix** is generated using cosine similarity.
3. When a user enters a book name, the system finds similar books from the matrix.
4. Recommended books are displayed on the web interface.

## Installation (Run Locally)

Clone the repository:

```
git clone https://github.com/your-username/Book-Recommendation-System.git
```

Move into the project folder:

```
cd Book-Recommendation-System
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the Flask application:

```
python app.py
```

Open your browser and go to:

```
http://127.0.0.1:5000
```

## Dataset

The project uses book rating data containing:

* Users
* Books
* Ratings

These datasets are used to generate book recommendations based on similarity.

## Future Improvements

* Add search autocomplete for book names
* Improve UI design
* Add user accounts and personalized recommendations
* Use a database instead of CSV files

## Author

Saurav Kunwar

## License

This project is for educational and learning purposes.
