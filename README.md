# DECISION-TREE-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: P.SANSKRITHI KRISHNA

INTERN ID: CT04DR1831

DOMAIN: Machine Learning

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION ABOUT MY PROJECT

This project is a part of my CODTECH  and focuses on implementing a Decision Tree Classification Model using Python and Scikit-learn. The main goal of this project is to understand how decision trees work, train a classification model on a chosen dataset, visualize the resulting decision structure, and evaluate the model’s performance. I selected the Iris dataset, a classic and widely used dataset for classification tasks, because it is clean, simple, and ideal for demonstrating machine learning concepts.

A Decision Tree is a supervised machine learning algorithm that splits data into branches based on conditions. It creates a tree-like structure where each internal node represents a decision based on a feature, each branch represents an outcome, and each leaf node represents a final class prediction. This transparency makes Decision Trees popular, as we can easily interpret how the model arrives at a decision.

The project begins by loading the Iris dataset using Scikit-learn. This dataset contains 150 samples of iris flowers categorized into three species: Setosa, Versicolor, and Virginica. Each sample has four features—sepal length, sepal width, petal length, and petal width. After loading the data, I split it into training and testing sets, typically following a 70–30 ratio. The training set is used to build the model, while the testing set helps evaluate its performance on unseen data.

Next, I created a Decision Tree classifier using the DecisionTreeClassifier() function. Training the model involves passing the training features and labels to the .fit() method. Once trained, I used the .predict() and .score() functions to test the model’s accuracy on the test dataset. The model usually achieves an accuracy between 90% to 95% for the Iris dataset, which indicates that the Decision Tree is effective at distinguishing between different species of iris flowers.

One of the most important parts of this task is visualizing the Decision Tree. Using Scikit-learn’s plot_tree() function, I generated a complete visual representation of the decision-making process. The visualization clearly shows how the model splits the data based on feature thresholds. For example, the tree might first check whether the petal length is less than a certain value, which helps separate Setosa from other species. Each subsequent split further refines the prediction. The final tree diagram helps understand how the model uses specific features to classify each flower.

The project successfully demonstrates the end-to-end workflow of a machine learning model: data loading, preprocessing, model building, training, testing, visualization, and analysis. Through this project, I gained practical experience with Decision Tree algorithms and learned how interpretable machine learning models work internally. The output includes the accuracy score and a detailed tree visualization, both confirming that the model performs well. Overall, this project helped build a strong foundation in machine learning and enhanced my ability to implement classification techniques using Python and Scikit-learn.

 #OUTPUT
 
 <img width="1182" height="790" alt="Image" src="https://github.com/user-attachments/assets/54045494-3711-48f0-95a7-e870dc2aa13c" />
