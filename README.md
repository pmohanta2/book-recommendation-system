# Book Recommendation System

This is a simple book recommendation system project that utilizes collaborative filtering to recommend books to users. It uses the [Book Recommendation Dataset](https://www.kaggle.com/arashnic/book-recommendation-dataset) from Kaggle.

**Deployed Link**: [https://book-recommendation-system02.streamlit.app/](https://book-recommendation-system02.streamlit.app/)

## Project Overview

This project is built using Python and popular data science libraries. It provides recommendations for books based on user preferences and interactions. The system uses a Nearest Neighbors model for recommendation.

## Project Files

- `Book recommendation system.ipynb`: Jupyter Notebook containing the code for the recommendation system.
- `app.py`: Python script for a Streamlit web application for interactively recommending books.
- `requirements.txt`: Lists the Python packages required to run the application.
- `setup.sh`: A shell script for configuring Streamlit and deploying the app.
- `Procfile`: A file for Heroku deployment configuration.
- `final_model.sav`: A file containing the trained recommendation model.
- `final_rating.csv`: A CSV file containing preprocessed book ratings data.
- `dataset/dataset_links.txt`: A text file containing the link to the Book Recommendation Dataset.

## How to Use

1. Clone the repository to your local machine.
2. Install the required Python packages listed in `requirements.txt`.
3. Run the Streamlit app using the following command:

```bash
streamlit run app.py
'''

## Dependencies

Python
Pandas
NumPy
SciPy
Scikit-learn
Streamlit

## Dataset

The project uses the [Book Recommendation Dataset](https://www.kaggle.com/arashnic/book-recommendation-dataset) available on Kaggle. You can download the dataset from the provided link.

## Acknowledgments

This project is for educational purposes and is based on the collaborative filtering concept for book recommendations.

## Author

Prabin

Feel free to explore and modify the code to suit your needs. Enjoy recommending and discovering new books!
