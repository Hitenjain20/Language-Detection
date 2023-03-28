# Language-Detection #
----

This is a language detection project that uses the Logistic Regression algorithm to classify the language of input text. It is built using Python and requires the following modules to be installed:


* `numpy`
* `regex`
* `sklearn`
* `pandas`


## Installation ##

To install the necessary modules, run the following command:
 
* `pip install numpy` 
* `pip install regex` 
* `pip install sklearn` 
* `pip install pandas`


## Usage ##

To use the language detection model, you can run the app.py file using the following command:

`streamlit run app.py`

This will launch a web application where you can enter text and get the predicted language. The web application is built using the Streamlit library.


## Training ##

The language detection model is trained using the Logistic Regression algorithm. The training data is a corpus of text in multiple languages. The text is preprocessed to remove stop words, special characters, and digits, and then converted into numerical features using the Term Frequency-Inverse Document Frequency (TF-IDF) method. The resulting feature vectors are used to train the Logistic Regression model to classify the language of input text.
