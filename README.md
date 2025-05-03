
# 📰 Fake News Detection System using Python & Machine Learning

Detecting fake news is a major challenge in the era of social media. This project leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to build an effective Fake News Classifier.

---

## 🚀 Project Overview

This project demonstrates how to build a **Fake News Detection System** using the **TfidfVectorizer** and a **PassiveAggressiveClassifier**, based on the tutorial from [Simplilearn](https://www.simplilearn.com/tutorials/machine-learning-tutorial/how-to-create-a-fake-news-detection-system).

---

## 📊 Dataset

We use the popular dataset: `news.csv`, which contains labeled news articles with the following fields:

- `title`: Title of the news article
- `text`: Full content of the news article
- `label`: Ground truth (FAKE or REAL)

📁 **Example Rows:**

| Title                                   | Text                                    | Label |
|----------------------------------------|-----------------------------------------|-------|
| Donald Trump Sends Out Embarrassing... | Donald Trump just couldn’t shake ...    | FAKE  |
| Watch The Exact Moment Paul Ryan...    | House Speaker Paul Ryan’s approval ... | REAL  |

---

## 🧰 Technologies Used

- 🐍 Python 3.x
- 🧠 Scikit-learn
- 📊 Pandas
- 🧼 TfidfVectorizer (NLP)
- ⚙️ PassiveAggressiveClassifier

---

## 🔧 How It Works

1. **Load Data**: Read the CSV and inspect the data.
2. **Data Preprocessing**: Clean and prepare text using `TfidfVectorizer`.
3. **Model Training**: Use `PassiveAggressiveClassifier` to learn from the data.
4. **Model Evaluation**: Check accuracy, precision, and confusion matrix.
5. **Predict**: Classify new/unseen news as REAL or FAKE.

---

## 📈 Sample Output

```bash
Accuracy: 0.93
Confusion Matrix:
[[586   52]
 [ 47 587]]
```

This indicates that the model correctly classifies fake and real news with ~93% accuracy.

---

## 📦 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
```

2. Install dependencies:

```bash
pip install pandas scikit-learn
```

3. Run the script:

```bash
python fake_news.py
```

---

## 📌 Key Takeaways

- This project demonstrates the power of NLP in real-world applications.
- Passive Aggressive Classifier is ideal for large-scale text classification.
- Simple preprocessing (TF-IDF) can yield strong results in classification tasks.

---

## 💡 Future Improvements

- Add web-based UI for live testing.
- Explore deep learning models like LSTM for better accuracy.
- Implement multilingual fake news detection.

---

## 🙌 Acknowledgments

- Based on the tutorial by **Simplilearn**:  
  👉 [How to Create a Fake News Detection System](https://www.simplilearn.com/tutorials/machine-learning-tutorial/how-to-create-a-fake-news-detection-system)

---

## 📬 Contact

Feel free to reach out for suggestions or improvements.

**Author**: [Your Name]  
**Email**: your.email@example.com  
**GitHub**: [@yourusername](https://github.com/yourusername)

---

⭐ If you found this project helpful, feel free to give it a star!
