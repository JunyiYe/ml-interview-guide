Here are some machine learning models and their complexities:

### Decision Trees
- **Training Complexity**: Decision trees can be trained relatively quickly, especially for small to medium-sized datasets. The complexity is generally <code>O(n \log n)</code>, where <code>n</code> is the number of training samples.
- **Evaluation Complexity**: The evaluation complexity is <code>O(\log n)</code>, as it involves traversing the tree from the root to a leaf node.
- **Example**: Decision trees are often used in classification tasks, such as predicting whether a customer will buy a product based on their demographic information.

### Support Vector Machines (SVM)
- **Training Complexity**: The training complexity of SVMs can be quite high, especially for large datasets, as it involves solving a quadratic optimization problem. The complexity is generally <code>O(n^2)</code> to <code>O(n^3)</code>, where <code>n</code> is the number of training samples.
- **Evaluation Complexity**: The evaluation complexity is <code>O(k)</code>, where <code>k</code> is the number of support vectors.
- **Example**: SVMs are used for tasks like image classification and text categorization.

### K-Nearest Neighbors (KNN)
- **Training Complexity**: KNN has a very low training complexity, as it essentially involves storing the training data. The complexity is <code>O(1)</code>.
- **Evaluation Complexity**: The evaluation complexity is <code>O(n)</code>, where <code>n</code> is the number of training samples, as it involves calculating the distance between the query point and all training points.
- **Example**: KNN is used in recommendation systems and anomaly detection.

### Random Forests
- **Training Complexity**: Random forests, which are ensembles of decision trees, have a training complexity of <code>O(m \cdot n \log n)</code>, where <code>m</code> is the number of trees and <code>n</code> is the number of training samples.
- **Evaluation Complexity**: The evaluation complexity is <code>O(m \cdot \log n)</code>, as it involves evaluating each tree in the forest.
- **Example**: Random forests are used in various applications, including fraud detection and medical diagnosis.

### Gradient Boosting Machines (GBM)
- **Training Complexity**: GBMs have a training complexity of <code>O(m \cdot n \log n)</code>, where <code>m</code> is the number of boosting iterations and <code>n</code> is the number of training samples.
- **Evaluation Complexity**: The evaluation complexity is <code>O(m \cdot \log n)</code>, similar to random forests.
- **Example**: GBMs are used in tasks like ranking in search engines and predicting customer churn.

These examples illustrate the diversity of machine learning models and their varying complexities in terms of training and evaluation. Each model has its strengths and weaknesses, making them suitable for different types of tasks and datasets.
