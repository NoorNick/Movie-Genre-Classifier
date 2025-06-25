# 🎬 SimpleKNN Movie Genre Classifier 

A simple **K-Nearest Neighbors (KNN)** classifier implemented from scratch in Jupyter Notebook using NumPy and Counter to predict movie genres based on their action and romance scores.

---

## 🚀 Features

- Implements KNN algorithm with customizable `k` neighbors
- Classifies movies as **Action** or **Romance** based on input features
- Visualizes training and test points with Matplotlib 📊
- Easy to extend and modify for other classification tasks

---

## 🛠️ How to Use

1. Clone this repository:
 ```bash
  git clone https://github.com/your-username/simple-knn-movie-genre-classifier.git
 cd simple-knn-movie-genre-classifier
 ```
2. Run the Python script:

```
python knn_movie_classifier.py
```

3. See genre predictions for new movies printed in the console and a plot visualizing the data!

## 📊 Example Output

```
Predicted genre: Romance
Movie 1 (Action: 6, Romance: 2) → Predicted genre: Action
Movie 2 (Action: 2, Romance: 9) → Predicted genre: Romance
Movie 3 (Action: 5, Romance: 5) → Predicted genre: Romance
Movie 4 (Action: 7, Romance: 1) → Predicted genre: Action
Movie 5 (Action: 1, Romance: 10) → Predicted genre: Romance
Movie 6 (Action: 3, Romance: 7) → Predicted genre: Romance
Movie 7 (Action: 8, Romance: 3) → Predicted genre: Action
Movie 8 (Action: 4, Romance: 6) → Predicted genre: Romance
Movie 9 (Action: 6, Romance: 5) → Predicted genre: Action
Movie 10 (Action: 2, Romance: 6) → Predicted genre: Romance

```
## 📈 Visualization
The script generates a scatter plot showing:
- Training points colored by genre
- New movies marked with black crosses (x)

Happy coding and movie classifying! 🎉🍿



