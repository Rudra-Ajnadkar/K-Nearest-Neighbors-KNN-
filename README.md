# K-Nearest-Neighbors-KNN-

### Objective :
Use KNN to classify iris flower species based on petal/sepal features.

### Dataset:
- Iris dataset with 3 classes: Setosa, Versicolor, Virginica
- 4 numeric features scaled with StandardScaler

### Steps:
- Train/test split (80/20)
- Feature scaling
- KNN trained using `K=3` and compared across K values
- Accuracy plotted for K = 1 to 20
- Decision boundaries visualized in 2D

### Results:
- Best Accuracy: 100% with K=6
- Confusion matrix shows perfect classification for most K values

### What I Learned:
- Instance-based learning uses entire training data at inference
- Distance metric (Euclidean) is sensitive to feature scale
- K is a hyperparameter — low K can overfit, high K can underfit
