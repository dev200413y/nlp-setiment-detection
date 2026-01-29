# 🎭 NLP Sentiment Detection

A Natural Language Processing (NLP) project for detecting emotions/sentiments from text using Machine Learning.

## 📌 Features
- Text preprocessing (lowercase, punctuation removal, stopwords removal)
- Emotion classification from text data
- Uses Bag of Words (BoW) & TF-IDF vectorization
- Naive Bayes classifier for prediction

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Dataset
- Custom training dataset with text and emotion labels
- Emotions: sadness, anger, love, surprise, fear, joy

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/dev200413y/nlp-setiment-detection.git
```
2. Install dependencies
```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn
```
3. Open `finalproject.ipynb` in Jupyter Notebook
4. Run all cells

## 📈 Model
- **Algorithm:** Multinomial Naive Bayes Classifier
- **Feature Extraction:** CountVectorizer (Bag of Words)
- **Train-Test Split:** 80-20

## 📁 Project Structure
```
├── finalproject.ipynb   # Main notebook with code
├── train.txt            # Training dataset
└── README.md            # Project documentation
```

## 👨‍💻 Author
- GitHub: [@dev200413y](https://github.com/dev200413y)
