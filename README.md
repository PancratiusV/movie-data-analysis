# 🎬 Movie Data Analysis — Mini Project 1

An exploratory data analysis (EDA) project investigating what makes a movie successful using a TMDB movie dataset.

## 📋 Questions Explored

1. What makes a movie popular?
2. Does having a higher budget lead to higher revenue?
3. Does having a higher budget lead to higher ratings?
4. Does popularity equal higher ratings?
5. Do newer movies outperform older movies?
6. Are movies getting longer over time?

## 📁 Project Structure

```
MiniProject1/
├── MiniProject1.ipynb       # Main analysis notebook
├── movie_data_clean.csv     # Cleaned movie dataset
├── movie_with_detail.csv    # Movie dataset with additional details
├── Questions.txt            # Research questions
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Common data science libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

### Installation

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Notebook

```bash
jupyter notebook MiniProject1.ipynb
```

## 🔑 API Key Setup

This project uses the [TMDB API](https://www.themoviedb.org/documentation/api) for fetching movie data.

1. Sign up at [themoviedb.org](https://www.themoviedb.org/) and get a free API token.
2. Create a file named `access_token.txt` in the project root.
3. Paste your TMDB API Read Access Token into that file.

> ⚠️ **Never commit `access_token.txt` to version control.** It is listed in `.gitignore`.

## 📊 Dataset

The datasets used in this project were sourced from TMDB (The Movie Database) and contain information about movies including budget, revenue, ratings, popularity, runtime, and release dates.
