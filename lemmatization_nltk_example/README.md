# 📘 Lemmatization with NLTK's WordNetLemmatizer

This notebook explains how to use **WordNetLemmatizer** from the NLTK library to reduce words to their **dictionary base form**.

---

## 📌 What is Lemmatization?

**Lemmatization** is the process of converting a word to its **base or dictionary form** (called the *lemma*).

Examples:
- `"products"` → `"product"`
- `"produces"` → `"produce"`
- `"was"` → `"be"`

It’s smarter than stemming because it understands **grammar and context**.

---

## 🔍 Lemmatizer vs Stemmer

| Feature         | Lemmatizer                      | Stemmer                  |
|-----------------|----------------------------------|--------------------------|
| Accuracy        | High (uses dictionary)          | Lower (rule-based)       |
| Meaningful Words| Yes                              | Often not real words     |
| Needs POS Tag   | Yes (optional, improves results) | No                       |
| Slower          | Yes                              | Faster                   |

---

## 🔧 Why Use Lemmatization?

- Improves accuracy in NLP tasks
- Helps in search engines, chatbots, text classification
- Keeps words meaningful and readable

---

## 💡 Example Sentence

> "The products produced by the process today are far better than what it produces generally."

### Expected Output:
> "The product produced by the process today are far better than what it produce generally."

---

