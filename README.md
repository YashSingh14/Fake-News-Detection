# Fake-News-Detection

# Tools Used:
 Python : The primary programming language used for data analysis and modeling.

 Pandas : For data manipulation and preprocessing.

 NumPy : For numerical operations on datasets.

 Scikit-learn : For implementing machine learning models such as Linear Regression,
Decision Trees, Gradient Boosting Regressor, etc.

 TfidfVectorizer : For converting textual data into numerical features using Term Frequency-
Inverse Document Frequency (TF-IDF)

 PassiveAggressiveClassifier : For real-time data processing and applications where the
dataset is too large to be loaded into memory all at once.

 Jupyter Notebook : As the development environment for coding and documentation.


# Working Procedure:
 Loading of Data
Works begin with the loading of a news article dataset, and it enters the design as a Pandas
DataFrame for manipulation and analysis.

 Label Extraction
REAL or FAKE labels are attached to each article corresponding to those contained in the
DataFrame. These are used as the labels for supervised learning where the model has been
trained on real articles and fake articles.

 Data Splitting
The data are divided into training and test sets; 80% is used for training the data and 20% for
testing. Such random assignments are meant to reduce bias and allow testing for proper
model performance.

 Text Vectorization
TfidfVectorizer is used for converting text data into some numeric form that the machine can
learn. The conversion applies to training data with vocabulary regardless of frequent stop
words that may introduce noise.

 Model Training
Accordingly, a Passive Aggressive Classifier is created and trained with vectorized training
data and their corresponding labels. The methodology can handle huge volumes of data and
can be deployed in real-time applications depending on the latency allowed.

 Making Predictions
The model can now be used to make predictions on the test set on which it has been trained.
It’s predictions are made out of sample by the model.

 Evaluation:
Its overall accuracy was evaluated using the accuracy_score function. A confusion matrix is
also developed to learn more about true positives, true negatives, false positives, and false
negatives.


# Learning Outcomes:
 Developed proficiency with TfidfVectorizer for data preprocessing and text vectorization.

 Developed proficiency with the machine learning algorithms found in the scikit-learn library.

 Studied evaluation metrics such as accuracy and confusion matrices. enhanced ability to
manage, sort, and process textual data in order to classify it.

 Acknowledged the value and application of classifiers in everyday life, especially when it
comes to addressing the issue of identifying misleading information.
