# SMS Spam Detection

A Machine Learning project that classifies SMS messages as **Spam** or **Not Spam (Ham)**.

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to detect whether an SMS message is spam.

The model is trained using the **SMS Spam Collection Dataset** and text preprocessing techniques such as:

* Lowercase conversion
* Tokenization
* Stopword removal
* Stemming
* Text vectorization

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Google Colab
* Machine Learning
* Natural Language Processing (NLP)

---

## Dataset

The project uses the **SMS Spam Collection Dataset**, which contains SMS messages labeled as:

* `ham` – Normal message
* `spam` – Spam message

---

## Project Workflow

```text
SMS Dataset
     ↓
Data Cleaning
     ↓
Text Preprocessing
     ↓
Tokenization
     ↓
Stopword Removal
     ↓
Stemming
     ↓
Text Vectorization
     ↓
Machine Learning Model
     ↓
Spam / Ham Prediction
```

## Example

**Input:**

```text
Congratulations! You have won a free prize. Click now!
```

**Prediction:**

```text
Spam
```

---

## Google Colab

You can view the complete implementation in Google Colab:

[Open Google Colab Notebook](https://colab.research.google.com/drive/11PpEtgkQHtMZUDWhRQbpxZBmrwjlqcGR?usp=sharing)

---

## Future Use

The trained model can be integrated into a real-world application using **Flask** and deployed as a web API.
