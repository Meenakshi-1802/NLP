# 🔤 Stemming Words using NLTK's PorterStemmer

This notebook explains how to use the **PorterStemmer** from the **NLTK** library to reduce words to their base or root form, a common step in **Natural Language Processing (NLP)**.

---

## 📌 What is Stemming?

**Stemming** is the process of removing prefixes or suffixes from words to reduce them to their **root form**.

For example:
- "playing" → "play"
- "studies" → "studi"
- "running" → "run"

Stemming helps in simplifying text for tasks like:
- Text classification
- Search engines
- Chatbots
- Machine learning models

---

## 🧠 What is PorterStemmer?

The **PorterStemmer** is one of the most widely used stemming algorithms in NLP.  
It applies a series of rules to remove common English suffixes.

It’s known for being:
- **Simple**
- **Fast**
- **Good for English text**

---

## 📚 How Does It Work?

Let’s say you have this sentence:
"Before eating, it would be nice to sanitize your hands with a sanitizer."

Using **PorterStemmer**, the sentence becomes:

As you can see:
- "eating" → "eat"
- "sanitize" → "sanit"
- "sanitizer" → "sanit"
- "hands" → "hand"

It trims off parts of words but keeps the **core meaning**.

---

## ✅ Why Use PorterStemmer?

| Benefit                       | Description                                     |
|------------------------------|-------------------------------------------------|
| 🔄 Reduces word forms        | Helps in treating "run", "running", "runs" the same |
| 🧹 Simplifies text           | Great for preprocessing before ML models        |
| ⚡ Fast and lightweight       | Works well even on large text datasets          |
| 📘 Easy to implement         | Comes built-in with NLTK                        |

---





