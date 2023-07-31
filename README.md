# **Natural Language Processing Mini Project**

This mini project focuses on Natural Language Processing (NLP) using the complaints_proceed.csv dataset. The main goal of this project is to preprocess the data and build classifiers to predict the category of the complaints. We will be using several NLP techniques and algorithms to achieve this.

## Project Structure

The project is organized into the following main parts:

### 1) Data Preprocessing:

**Handling missing values:** We use isnull() and dropna() to remove any rows with missing values.
**Stopword removal:** Stopwords are removed using a list of common stopwords from the NLTK library.
**Special character and punctuation removal:** We remove any special characters and punctuation from the complaint text.
**WordNet Lemmatization:** We apply WordNet Lemmatization to reduce words to their base or root form.

### 2) Train-Test Split:

     We split the preprocessed data into training and testing sets using the CountVectorizer method to convert the text data into numerical feature vectors.

### 3) Algorithms Used:

**Random Forest Classifier:** We use the Random Forest algorithm to build a classification model.
**Support Vector Classifier (SVC):** We also utilize the Support Vector Classifier to compare its performance with the Random Forest model.
**Decision Tree Classifier:** Another classification model, Decision Tree Classifier, is used for comparison.

### 4) Model Evaluation:

We calculate the accuracy of each classifier using appropriate evaluation metrics.
The model with the highest accuracy will be considered the best model for this dataset.

## Dependencies

The following libraries are required to run this project:
      1) pandas
      2) numpy
      3) nltk
      4) scikit-learn
Ensure you have these libraries installed before running the project.

## Results
     
     •  After running the notebook, you will find the accuracy values of the three classifiers: Random Forest, SVC, and Decision Tree. 
     •  The classifier with the highest accuracy will be considered the best model for this dataset. 
     •  The accuracy results will be displayed in the notebook after the training process.

## Conclusion

     •  This mini project demonstrates the application of NLP techniques for text data preprocessing and the implementation of various classifiers for categorizing customer complaints. 
     •  **The best-performing classifier is the Random Forest Classifier with its corresponding accuracy value.**
