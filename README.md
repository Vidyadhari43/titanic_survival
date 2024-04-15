# Titanic Survival
<p>We will be using different <b> machine learning algorithms </b> to predict the survival of a person. </p>

<p>Pre-processing the data before applying machine learning algorithms is an important step that can help improve the performance of our model. Some additional details about common pre-processing techniques include:</p>

<p><b> Handling missing values:</b> NULL or missing values in your dataset can cause problems when training machine learning models, as many algorithms are unable to handle NULL values. There are several approaches you can take to deal with missing values, such as dropping rows or columns with missing values, imputing missing values with the mean or median of the feature, or predicting missing values using a separate model. Which approach you choose will depend on the specific characteristics of your dataset and the goals of your analysis.</p>

<p><b>Feature selection:</b> Identifying the most relevant features in your dataset and selecting a subset to use in your model can help reduce the complexity of the model and improve its performance. There are several approaches you can take to select features, such as using statistical tests to identify the most important features, using domain knowledge to identify relevant features, or using machine learning algorithms that have built-in feature selection methods.</p>

<p><b>Feature engineering:</b> Creating new features from existing features in your dataset can help capture additional information or trends in the data that might not be apparent in the raw features. This can be done through techniques such as combining or transforming existing features, or using domain knowledge to create features based on your understanding of the problem.
After Preprocessing the data, we can move on to splitting it into a training set and a test set. This is an important step because it allows us to evaluate the performance of your model on unseen data, which is a more realistic representation of how the model will perform in practice.</p>

<p><b>Scaling: </b>After splitting the data, it is often a good idea to perform feature scaling. This is a technique that adjusts the values of numeric features so that they have a common scale. This is important because many machine learning algorithms assume that the features are in the same scale, and failing to perform feature scaling can lead to poor model performance.</p>

<p>Once the data is ready, we can then apply a variety of machine learning algorithms to it and compare their performance. There are many different algorithms to choose from, and the specific algorithm that works best will depend on the nature of the data and the prediction task. Some common algorithms for the Titanic Survival Problem include:</p>
<p><ol>
    <li>Logistic Regression</li>
    <li>Decision Trees</li>
    <li>Random Forests</li>
    <li>Support Vector Machines (SVM)</li>
    <li>K-Nearest Neighbors</li>
</ol> </p>

<p>After training and evaluating each algorithm, we can then compare their performance to see which one provides the most accurate predictions. To do this, we can use metrics like accuracy. These metrics will give you an idea of how well the model is able to correctly predict the survival of passengers. </p>

<p>After Evaluating, we observed that SVM (support vector machine) showed the maximum accuracy</p>
