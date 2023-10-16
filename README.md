# Book Recommendation System

This is a simple book recommendation system project that utilizes collaborative filtering to recommend books to users. It uses the [Book Recommendation Dataset](https://www.kaggle.com/arashnic/book-recommendation-dataset) from Kaggle.

**Deployed Link**: [https://book-recommendation-system02.streamlit.app/](https://book-recommendation-system02.streamlit.app/)

# Table of Contents

1. [Project Overview](#project-overview)
2. [How to Use](#how-to-use)
3. [Dependencies](#dependencies)
4. [Dataset](#dataset)
5. [Acknowledgments](#acknowledgments)
6. [Author](#author)

## Project Overview

This project is built using Python and popular data science libraries. It provides recommendations for books based on user preferences and interactions. The system uses a Nearest Neighbors model for recommendation.

## Project Files

- `Book recommendation system.ipynb`: Jupyter Notebook containing the code for the recommendation system.
- `app.py`: Python script for a Streamlit web application for interactively recommending books.
- `requirements.txt`: Lists the Python packages required to run the application.
- `setup.sh`: A shell script for configuring Streamlit and deploying the app.
- `final_model.sav`: A file containing the trained recommendation model.
- `final_rating.csv`: A CSV file containing preprocessed book ratings data.
- `dataset/dataset_links.txt`: A text file containing the link to the Book Recommendation Dataset.

## How to Use

1. Clone the repository to your local machine.
   
   ```bash
   git clone https://github.com/pmohanta2/book-recommendation-system.git
   cd book-recommendation-system
   ```
2. Install the required Python packages listed in `requirements.txt`.

   ```bash
   pip install -r requirements.txt
   ```
  
3. Run the Streamlit app using the following command:

   ```bash
   streamlit run app.py
   ```

## Dependencies

* [![Python][python]][Python-url]
* [![Pandas][pandas]][Pandas-url]
* [![NumPy][numpy]][NumPy-url]
* [![SciPy][scipy]][SciPy-url]
* [![Scikit-learn][scikit-learn]][Scikit-learn-url]
* [![Streamlit][Streamlit.io]][Streamlit-url]



## Dataset

The project uses the [Book Recommendation Dataset](https://www.kaggle.com/arashnic/book-recommendation-dataset) available on Kaggle. You can download the dataset from the provided link.

## Acknowledgments

This project is for educational purposes and is based on the collaborative filtering concept for book recommendations.

## Author

Prabin

Feel free to explore and modify the code to suit your needs. Enjoy recommending and discovering new books!





<!-- MARKDOWN LINKS & IMAGES -->
[python]:https://img.shields.io/badge/Python-blue?logo=python&logoColor=yellow
[Python-url]:https://www.python.org/
[pandas]:https://img.shields.io/badge/Pandas-green?logo=pandas&logoColor=black
[Pandas-url]:https://pandas.pydata.org/
[numpy]: https://img.shields.io/badge/NumPy-violet?logo=numpy&logoColor=black
[NumPy-url]:https://numpy.org/
[scipy]:https://img.shields.io/badge/SciPy-lavender?logo=scipy&logoColor=black
[SciPy-url]:https://www.scipy.org/
[scikit-learn]:https://img.shields.io/badge/Scikit--learn-cyan?logo=scikitlearn&logoColor=black
[Scikit-learn-url]:https://scikit-learn.org/stable/index.html
[Streamlit.io]:https://img.shields.io/badge/Streamlit-DD0031?logo=streamlit&logoColor=black
[Streamlit-url]:https://streamlit.io/
