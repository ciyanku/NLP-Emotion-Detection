# Emotion Detection from Text

This project predicts the emotion of a sentence using Natural Language Processing (NLP) and Machine Learning.

The goal is simple: give the model a piece of text, and it predicts the emotion behind it.

## Dataset

I used an emotion dataset where each sentence is labeled with one of the following emotions:

* Sadness
* Joy
* Love
* Anger
* Fear
* Surprise

## What I did

* Cleaned the text data
* Converted text to lowercase
* Removed punctuation, numbers, and URLs
* Removed stopwords
* Converted text into numerical features using:

  * Bag of Words
  * TF-IDF
* Trained and compared different machine learning models

## Models Used

* Logistic Regression
* SGD Classifier
* Support Vector Machine (SVM)
* DistilBERT

## Results

I compared different models and evaluated them using:

* Accuracy
* Precision
* Recall
* F1-score

Among the models I tested, **DistilBERT** gave the best performance with around **93% accuracy**.

## Project Structure

```
Emotion-Detection/
│── Emotion_Detection.ipynb
│── README.md
│── requirements.txt
```

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/emotion-detection.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook and run all the cells.

## Example

**Input**

```
I am really excited because I got my dream job.
```

**Prediction**

```
Joy
```

## Future Improvements

* Build a web application using Flask or FastAPI
* Deploy the model online
* Improve the model with larger datasets and newer transformer models

## Author

**Prashant Bisht**
