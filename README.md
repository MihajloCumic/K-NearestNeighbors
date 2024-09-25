# K-NearestNeighbors

This assignment focuses on applying the k-nearest neighbors (k-NN) algorithm to classify passengers based on the dataset `spaceship-titanic.csv`. The assignment is divided into three parts: splitting the dataset, experimenting with different values of `k`, and using all available features.

## Dataset
The dataset `spaceship-titanic.csv` contains information about passengers. A detailed description of the dataset and the goal of this analysis can be found in the provided link.

## Assignment Breakdown

### a) Basic k-NN with Two Features

**File:** `knn-a.ipynb`

**Task:**
- Split the dataset into training and test sets.
- Prepare the data for use in the k-NN algorithm by handling missing values (NaNs) and categorical variables.
- Apply the k-NN algorithm using only the `RoomService` and `FoodCourt` features, with `k=15`.
- The program should:
  1. Print the accuracy on the test set.
  2. Create and display a 2D plot showing the training data, where different classes are represented by different colors. The plot should also show the regions classified as belonging to each class.

### b) Finding the Best k

**File:** `knn-b.ipynb`

**Task:**
- Use the same two features (`RoomService` and `FoodCourt`), but vary the parameter `k` from 1 to 50.
- The program should:
  1. Display a plot showing the accuracy on the test set as a function of the parameter `k`.

### c) k-NN with All Features

**File:** `knn-c.py`

**Task:**
- Start with a copy of the previous file, but this time include every feature in the dataset.
- The program should:
  1. Display a similar plot to the one created in part b, showing the accuracy as a function of `k`.
  
