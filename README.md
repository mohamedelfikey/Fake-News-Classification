# Fake News Classification

This project focuses on building a **Fake News Classification System** to identify whether a news headline is real or fake. The dataset includes the news title and corresponding label, where:
- **0**: Fake news
- **1**: Real news

---

## Project Overview
Fake news detection is critical in today's information-driven world to ensure the credibility of information. This project leverages machine learning and deep learning techniques to classify news headlines. The performance of different methods was evaluated based on training and testing accuracy.

---

## Technologies Used
- **Python**: Programming language
- **Libraries**: 
  - Scikit-learn
  - TensorFlow/Keras
  - Gensim
  - NumPy
  - Pandas
  - Matplotlib / Seaborn (for visualization)
- **Jupyter Notebook / Colab**: For development and experimentation

---

## Dataset
The dataset contains two columns:
- **Title**: The headline or title of the news
- **Label**: Binary values indicating if the news is fake (0) or real (1)

---

## Models Implemented
The following methods were implemented for fake news classification, with their respective training and testing accuracy:

### 1. Bag of Words (BOW)
- **Train Accuracy**: 94%
- **Test Accuracy**: 89%

### 2. Word Embedding Methods
1. **End-to-End Embedding**:
   - **Train Accuracy**: 95%
   - **Test Accuracy**: 90%

2. **Gensim Word2Vec**:
   - **Train Accuracy**: 90%
   - **Test Accuracy**: 87%

### 3. Recurrent Neural Networks (RNN)
1. **Simple RNN**:
   - **Train Accuracy**: 92%
   - **Test Accuracy**: 89%

2. **LSTM**:
   - **Train Accuracy**: 95%
   - **Test Accuracy**: 90%

---

## Key Findings
1. **End-to-End Embedding** and **LSTM** models achieved the highest accuracy for both training and testing, demonstrating superior performance.
2. Bag of Words (BOW) also showed promising results for a simpler, traditional approach.
3. The performance of models trained on Word2Vec embeddings was slightly lower but still effective.

---

## Results
This project demonstrates that using advanced methods like **End-to-End Embedding** and **LSTM** can yield high accuracy for fake news detection. However, simpler models like **BOW** can still be effective depending on the requirements.

---

## Future Improvements
- Testing the models on a more diverse dataset.
- Building a web-based or mobile interface for real-time fake news detection.
- Exploring transformer-based models like BERT for better context understanding.

---


## Author
- **Mohamed Ahmed** - [LinkedIn](https://www.linkedin.com/in/mohamed-elfikey/) | [GitHub](https://github.com/mohamedelfikey)
- 
