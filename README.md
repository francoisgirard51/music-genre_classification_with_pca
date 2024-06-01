# A Machine Learning Project Predicting Music Styles through Dimensionality Reduction
## Case Description
### Objective

In the era of digital streaming, there’s an increasing need to categorize and recommend music based on genres. By analyzing various musical features extracted from tracks, we can delve deeper into their defining patterns. In this music genre classification project, you’ll work with a dataset containing various musical features extracted from tracks across different styles.

Please note that while this music genre classification dataset is extensive, it is incomplete. A significant portion of the records lacks specific genre information. Your primary task is to predict the genres of these unlabeled tracks.

To accomplish this, you’ll employ Principal Component Analysis (PCA) to reduce the dimensionality of the dataset. By transforming the abundant features into principal components, you’ll streamline the data, making it more manageable and revealing patterns that are not immediately obvious in the raw data. The principal components you’ve derived will form the foundation for the next step in the project—employing a supervised machine learning algorithm, with a focus on the well-known logistic regression technique.
Why Principal Component Analysis (PCA)?

Music tracks are complex entities with numerous inherent features. Some of these features might be correlated. For instance, specific rhythm patterns might be prevalent in rock and blues. In this machine learning project, PCA can assist in reducing redundancy by transforming correlated musical features into a set of linearly uncorrelated variables or principal components. Reducing dimensionality can drastically improve the performance of classification algorithms by eliminating noise.

The features in the music genre classification dataset are designed to be intuitive and accessible, allowing you to focus on the core concepts of PCA and machine learning without the need for specialized audio knowledge.

Prepare to dive deep into the layers of musical data and discover the patterns that help outline the musical genres.
Project Requirements

You'll need Python 3 or a newer version and can choose any IDE (Jupyter Notebook, Spyder, PyCharm, Visual Studio, etc.). The file provided with the solution for this music genre classification project is a Jupyter Notebook.

You’ll also need to have the following Python libraries installed:

    pandas
    NumPy
    matplotlib
    scipy
    scikit-learn
    seaborn

Project Files

The music data for the Music Genre Classification project can be found in the music_dataset_mod.csv file, and the data legend is provided in the Music Data Legend.xlsx. To get started, you can download the Music Genre Classification with PCA - Project.ipynb notebook, open it in Jupyter Notebook, and run the first cell to import the required libraries.
Steps to Follow

    Loading & Reading Data Files
        Load the dataset and create a copy for exploratory data analysis (EDA).
        Identify and handle missing values in the dataset.

    Data Exploration & Visualization
        Examine the unique genres present in the dataset.
        Visualize the distribution of genres to understand the balance of the dataset.

    Correlation Analysis
        Conduct a correlation analysis to understand the relationships between different features and their influence on music genres.

    Dimensionality Reduction with PCA
        Apply PCA to reduce the dimensionality of the dataset.
        Determine the number of principal components necessary to capture at least 80% of the data's variance.
        Visualize the explained variance by the components to decide on the optimal number of principal components.

    Model Training and Evaluation
        Train and evaluate a Logistic Regression classifier using both the PCA-transformed data and the original features.
        Compare the performance of the models based on accuracy and classification reports.

    Genre Prediction and Integration
        Leverage the more effective model to predict unknown genres in the dataset.
        Apply these predictions to fill in the missing genre information in your original DataFrame, completing the dataset.

Conclusion

This project demonstrated the use of PCA for dimensionality reduction and logistic regression for genre classification. By reducing the dataset to its principal components, we improved the efficiency of our classification model and gained insights into the underlying patterns of musical genres.

Feel free to clone the repository, explore the notebook, and experiment with different techniques to enhance the model’s performance.
How to Contribute

If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Any contributions, whether they be improvements to the model, code optimization, or additional features, are welcome.
Contact
