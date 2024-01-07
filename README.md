# Sarcasm-Detection-Application


The Sarcasm Detection Application is a Python-based tool designed to identify and analyze sarcasm within textual content such as headlines and tweets. Leveraging advanced Natural Language Processing (NLP) techniques and Machine Learning algorithms, this application enables users to understand the nuanced sentiment behind text by determining whether it carries a sarcastic tone.

Key Features:
Cutting-edge Analysis: Utilizes TextBlob and SentiWordNet libraries to perform sentiment analysis, enabling the identification of sarcastic expressions through polarity analysis.
Machine Learning Models: Employs Support Vector Machine (SVM) classifiers trained on distinct feature sets—proposed features and reduced N-gram features obtained via Principal Component Analysis (PCA)—enhancing accuracy in sarcasm detection.
User-Friendly Interface: Offers an intuitive PyQt5-based interface, allowing users to input text for instant sarcasm detection and real-time feedback.
How It Works:
Upon receiving input text, the application processes it by analyzing sentiment polarity at both sentence and word levels. Through the evaluation of individual word sentiment scores and sentence-level sentiments, it employs a comprehensive approach to accurately detect sarcasm.

Usage:
Setup: Requires Python 3.x and installation of necessary libraries (textblob, nltk, scikit-learn, PyQt5).
Running the Application: Users can input tweets or text within the provided interface, initiating the sarcasm detection process with ease and obtaining immediate detection results.
Dataset & Metrics:
Utilizing a preloaded dataset of headlines (stored in Sarcasm_Headlines_Dataset.json), the application assesses its accuracy, precision, recall, and F1 score metrics based on a subset of the dataset. This transparent evaluation ensures reliability and performance validation of the trained models.

The Sarcasm Detection Application is an invaluable tool for those seeking to decipher subtle sentiment nuances within text, offering a robust platform for discerning sarcasm and understanding the deeper sentiments conveyed in textual data.


