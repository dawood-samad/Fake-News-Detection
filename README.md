# Fake-News-Detection
Detect fake and real news using NLP and machine learning (TF-IDF + SVM)
# 📰 Fake News Detection with Machine Learning

This project detects whether a news article is **real** or **fake** using **Natural Language Processing (NLP)** and **Machine Learning**.

Built with:
- Python (Google Colab)
- TF-IDF Vectorization
- Logistic Regression, Random Forest, and SVM
- Gradio for live demo

---

## 📂 Dataset

- **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- Contains `Fake.csv` and `True.csv`

---

## 🧠 Models Compared

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ✅ 94% |
| Random Forest       | ✅ 95% |
| SVM (Best)          | ✅ 96% |

---

## 🔍 Sample Gradio App

![https://f17a79041569097141.gradio.live/]
![image](https://github.com/user-attachments/assets/cfd621d5-3a81-4cd4-aecf-9be6445d9acb)



Get "Fake" or "Real" in seconds!

🚀 How It Works
Text cleaning (stopwords, lemmatization)

TF-IDF vectorization

SVM classifier

Gradio interface

📊 Example Output

📁 Files
FakeNewsDetector.ipynb: Main code

README.md: You're here

gradio_demo.png: UI preview 

📌 Future Improvements
Use deep learning (LSTM, BERT)

Deploy on Hugging Face Spaces or Streamlit Cloud

Add multilingual support

🙋‍♂️ Author
Dawood Samad – https://www.linkedin.com/in/dawood-samad-986215366/ | https://github.com/dawood-samad


### Try it out! 🚀

```python
interface.launch(share=True)
