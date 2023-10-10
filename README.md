# Book Recommendation System

This is a simple book recommendation system project that utilizes collaborative filtering to recommend books to users. It uses the [Book Recommendation Dataset](https://www.kaggle.com/arashnic/book-recommendation-dataset) from Kaggle.

## Project Overview

This project is built using Python and popular data science libraries. It provides recommendations for books based on user preferences and interactions. The system uses a Nearest Neighbors model for recommendation.

## Files in the Project Directory

- `Book recommendation system.ipynb`: Jupyter Notebook containing the code for the recommendation system.
- `app.py`: Python script for a Streamlit web application for interactively recommending books.
- `requirements.txt`: Lists the Python packages required to run the application.
- `setup.sh`: A shell script for configuring Streamlit and deploying the app.
- `Procfile`: A file for Heroku deployment configuration.

## How to Use

1. Clone the repository to your local machine.
2. Install the required Python packages listed in `requirements.txt`.
3. Run the Streamlit app using the following command:

```bash
streamlit run app.py
