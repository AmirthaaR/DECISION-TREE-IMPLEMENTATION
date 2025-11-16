# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AMIRTHAA R

*INTERN ID*: CT04DR1837

*DOMAIN*: Machine Learning

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION ABOUT MY PROJECT 

The objective of Task 1 is to build, train, and visualize a Decision Tree Classification model using the scikit-learn library. A decision tree is a supervised machine learning algorithm that works by splitting data into branches based on conditions, ultimately forming a tree-like structure that helps in predicting outputs. For this task, the Iris dataset was selected due to its simplicity, balanced classes, and suitability for classification problems. The Iris dataset contains 150 samples of flowers categorized into three species—Setosa, Versicolor, and Virginica—based on four numerical features: sepal length, sepal width, petal length, and petal width. These features make the dataset well-suited for learning and interpreting decision boundaries.

The workflow begins with importing the required Python libraries such as NumPy, Pandas, Matplotlib, and scikit-learn components. The dataset is loaded using load_iris() and explored to understand its structure. A DataFrame is created for an organized view of the features and target labels. The data is then split into training and testing subsets using an 80-20 ratio, ensuring that the model is trained effectively while still being tested on unseen data.

A Decision Tree Classifier is built using scikit-learn’s DecisionTreeClassifier. Parameters such as criterion="gini" and max_depth=3 are chosen to prevent overfitting and ensure a simpler model. The model is trained on the training data and predictions are generated for the test data. Evaluation is conducted using metrics such as accuracy, precision, recall, and F1-score, which together provide insight into the model’s performance. Typically, the trained decision tree achieves an accuracy between 95–100% on the Iris dataset, making it highly reliable.

One of the key deliverables of the task is the visualization of the decision tree. Using plot_tree(), a graphical representation of the tree structure is created, showing how the model splits at various feature thresholds. Each node includes information about the feature used for splitting, the gini impurity, sample count, class distribution, and predicted class. This makes the decision tree interpretable and allows us to easily follow the logic behind the classification decisions.

In conclusion, Task 1 effectively demonstrates the full machine learning pipeline: data loading, preprocessing, model training, evaluation, and visualization. Decision trees offer a transparent and interpretable approach to classification, and this task provides a strong foundation for understanding how machine learning models make decisions using structured data.

# OUTPUT
