# Sarcasm-Detection-Application

The Sarcasm Detection Application is a Python-based tool designed to identify and analyze sarcasm within textual content such as headlines and tweets. Leveraging advanced NLP techniques and Machine Learning algorithms, it determines whether text carries a sarcastic tone.

# Key Features:
- Cutting-edge Analysis: Utilizes TextBlob and SentiWordNet libraries for sentiment analysis to identify sarcastic expressions through polarity analysis.
- Machine Learning Models: Employs SVM classifiers trained on proposed features and reduced N-gram features obtained via PCA for enhanced accuracy.
- User-Friendly Interface: Offers an intuitive PyQt5-based interface for instant sarcasm detection and real-time feedback.

# How It Works:
Processes input text by analyzing sentiment polarity at sentence and word levels to accurately detect sarcasm.

# Usage:
Setup: Requires Python 3.x and installation of necessary libraries (textblob, nltk, scikit-learn, PyQt5).
Running the Application: Users input tweets or text within the provided interface, initiating the sarcasm detection process with immediate results.

# Dataset & Metrics:
Utilizes a preloaded dataset of headlines (Sarcasm_Headlines_Dataset.json) to assess accuracy, precision, recall, and F1 score metrics, ensuring model reliability and performance validation.

The Sarcasm Detection Application is a valuable tool for deciphering subtle sentiment nuances within text, allowing users to discern sarcasm and comprehend deeper sentiments conveyed in textual data.


