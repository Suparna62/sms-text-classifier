# ✉️ SMS Text Classifier with Neural Networks

This project classifies SMS messages as **ham** or **spam** using a neural network built with TensorFlow.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bSVbl0wUFBvo-L8HJhwdQU6HoFXdKBwc?usp=sharing)

---

## 📚 Dataset
SMS Spam Collection dataset, pre-split into train and test.

---

## 🔍 How It Works

- Preprocess and tokenize the messages
- Use an embedding layer + dense layers
- Outputs probability + label (`spam` if > 0.5 else `ham`)

---

## 🧠 `predict_message()` Output

```python
predict_message("Free entry in 2 a weekly prize draw...")
# Output: [0.98, 'spam']
