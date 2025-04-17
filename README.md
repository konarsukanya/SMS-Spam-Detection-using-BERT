# SMS-Spam-Detection-using-BERT


This project builds a **binary text classification model** using **BERT** to detect **spam messages** in SMS data. It leverages TensorFlow, TensorFlow Hub, and Google Colab for training and evaluation.

---

## 📁 Dataset

We use the **SMS Spam Collection Dataset** (available in `spam.csv`) which contains labeled SMS messages as:

- `ham` (not spam)
- `spam` (unwanted promotional messages)

---

## 📦 Dependencies

Install required libraries:

```bash
pip install tensorflow tensorflow_hub tensorflow_text pandas scikit-learn seaborn matplotlib
