# -DECISION-TREE-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: ANISETTY GNANA SAI

INTERN ID: CT04DN782

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

##DESCRIPTION: 
During my four-week internship at CodTech IT Solutions in the Machine Learning domain, I worked on a project titled "Decision Tree Implementation". The main objective of this project was to build a desktop-based application with a graphical user interface (GUI) that allows users to load a dataset, train a decision tree classifier, visualize the tree, and make predictions.

The application was developed using Python. It uses the tkinter library for GUI, pandas for data handling, scikit-learn for the machine learning model, and matplotlib for visualizing the decision tree. The workflow was implemented in the following structured way:

1. Loading CSV File
The first task was to allow users to load any CSV dataset. I implemented a file dialog for users to browse and upload their dataset. After loading, the app reads the file using pandas.read_csv() and displays the column names for further selection.

2. Selecting Target Column
Once the data is loaded, the user can select the target column (the output variable) from a dropdown. This column is used as the label for classification during model training.

3. Adjusting Test Size
A slider was added to adjust the test size (from 0.1 to 0.5) for splitting the dataset into training and testing sets using train_test_split from scikit-learn.

4. Training the Model
The user can click a button to train the model. The features (independent variables) and target (dependent variable) are separated. If the dataset contains categorical features, they are converted into numerical format using one-hot encoding. Then, a DecisionTreeClassifier is trained on the data. After training, predictions are made on the test set, and metrics such as accuracy and a classification report (precision, recall, F1-score) are displayed.

5. Tree Visualization
The trained decision tree is visualized using plot_tree() from scikit-learn. A plot window opens to show the tree structure, with split criteria, feature names, and class labels clearly visible. This helps the user understand the decision-making process of the model.

6. Exporting Tree as Image
The user can export the visualized tree as a PNG image. This functionality is useful for reports or documentation. The image is saved using matplotlib.pyplot.savefig().

7. Prediction on New Input
A form is generated dynamically based on the input features used during training. The user can enter values for a new record, and on clicking "Predict," the model predicts the class label for that record and displays the result in a message box.

8. Displaying Accuracy and Output
The application displays the model's accuracy in percentage format after training. A Text widget is used to show the full classification report for detailed performance evaluation

#OUTPUT:
![Image](https://github.com/user-attachments/assets/49ff55ec-7b82-4258-afd2-ecb354a4f6ad)
![Image](https://github.com/user-attachments/assets/1509092f-07ce-4719-8a43-3c45cc29b325)
