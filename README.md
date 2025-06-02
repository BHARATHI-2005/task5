Task 5: Decision Trees and Random Forests

Objective
This task focuses on implementing **Decision Tree** and **Random Forest** classifiers using the `heart.csv` dataset. The goal is to understand how tree-based models work, visualize them, control overfitting, evaluate performance, and interpret feature importance.

Dataset

Dataset Used:Heart Disease Dataset  

Target Variable: 
- `0` = No heart disease  
- `1` = Presence of heart disease

Tools & Libraries Used
- Python 3.x
- pandas
- numpy
- matplotlib & seaborn
- scikit-learn
- graphviz / sklearn.tree.plot_tree

Steps Performed
 1. Data Loading & Exploration
- Loaded the dataset using pandas
- Checked for missing values and data types
- Plotted target distribution

2. Preprocessing
- Split features (X) and target (y)
- Used `train_test_split` to split into training and test sets

3. Decision Tree Classifier
- Trained a Decision Tree Classifier using `scikit-learn`
- Visualized the tree using `plot_tree`
- Evaluated accuracy and classification report
- Controlled tree depth (`max_depth`) to analyze overfitting

4. Random Forest Classifier
- Trained a Random Forest Classifier
- Compared its performance to the decision tree
- Evaluated using accuracy and classification report
- Visualized **feature importance**

5. Cross-Validation
- Applied 5-fold cross-validation
- Reported average accuracy

Results

| Model             | Accuracy |
|------------------|----------|
| Decision Tree     | ~Initial Accuracy |
| Pruned Tree (Depth=4) | ~Improved Generalization |
| Random Forest     | ~Highest Accuracy |

 Key Learnings

- Decision Trees are interpretable but prone to overfitting.
- Controlling depth helps mitigate overfitting.
- Random Forests perform better due to bagging and ensemble effect.
- Feature importance helps interpret which features influence the predictions most.
