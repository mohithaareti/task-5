# task-5
# Tree-Based Models for Classification (Heart Disease Dataset)

## Objective
Learn and apply **tree-based machine learning models** for classification using Scikit-learn and Graphviz.

---

## Steps

### 1. Decision Tree Classifier & Visualization
- We train a `DecisionTreeClassifier` using the heart dataset.
- The model predicts whether a person has heart disease.
- Visualization is done with **Graphviz** to see how the tree makes decisions.



---

### 2. Overfitting & Depth Control
- A tree without restrictions can **overfit** (memorize training data).
- We control this by limiting `max_depth`.
- Smaller depth → simpler tree → less overfitting.

**Example:**  
`max_depth=3` often improves generalization.

---

### 3. Random Forest
- A **Random Forest** is an ensemble of decision trees.
- Each tree sees different parts of the data → more robust & accurate.
- We compare its accuracy to the single Decision Tree.

---

### 4. Feature Importances
- Random Forests give a score for each feature’s importance.
- Higher score = more influence in decision-making.
- A bar plot (`feature_importances.png`) helps visualize this.

---

### 5. Cross-Validation
- Instead of a single train/test split, **cross-validation** splits the data multiple times to get more reliable accuracy.
- We compare Decision Tree vs Random Forest with 5-fold CV.
