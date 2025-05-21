  # 🎬 Movie Recommendation & Rating Classification

This project implements a **content-based movie recommendation system** using **cosine similarity** and a **KNN classifier** to predict movie ratings. It uses categorical movie attributes like **genre** and **lead studio**, with weighted importance, and evaluates classification performance using standard metrics.
This project implements two types of content-based recommender systems using movie data:

## 📌 Tasks

### ✅ Task 1: Movie Recommendation Using Cosine Similarity

- One-hot encodes categorical features (`Genre`, `Lead Studio`)
- Applies weights to emphasize genre over studio
- Computes cosine similarity between movies
- Recommends movies with the most similar genre/studio profiles

### ✅ Task 2: Rating Classification Using KNN

- Uses features from the dataset to predict the `rating_J` category
- Splits training data into 80% training and 20% validation (3 random runs)
- Tests a range of `k` values to find the best KNN model
- Evaluates on unseen test data with:
  - Accuracy
  - Precision, Recall, F1 Score
  - Confusion matrix
  - Classification report


## 🔍 Features Used

- **Genre** (weighted ×2)
- **Lead Studio** (weighted ×1)


## 📁 Project Structure
- `notebooks/`: Jupyter notebooks for both tasks
- `data/`: All input and split datasets
- `results/`: Evaluation outputs and plots
- `report/`: Final PDF report and presentation slides

## 📊 Libraries Used
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 🧠 Authors
- Ananya Mehta 
- Jaanvi Das – rating_J
- Henil Shah – rating_H

## 🗂️ Dataset Source
- Provided by course instructor (modified for lab tasks)
