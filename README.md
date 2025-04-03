# Classification with Naive Bayes

This project involves building Naive Bayes classifiers using real-world datasets to classify messages or news articles into meaningful categories. Two datasets — **SMSSpamCollection** and **German_dataset** — were explored, preprocessed, and modeled using scikit-learn tools. Developed as part of **CS154**, an introductory Python course with NLP components.

---

## 📌 Features

- Custom classification pipelines built using:
  - `CountVectorizer` and `TfidfVectorizer` for feature extraction
  - `MultinomialNB` for classification
  - `train_test_split` for model evaluation
- Dataset-specific preprocessing to handle:
  - Tab-delimited text files (SMSSpamCollection)
  - Non-standard separators and multiple label types (German_dataset)
- Customized data visualizations for multiclass text data
- Emphasis on reading documentation and understanding built-in Python libraries

---

## 🧠 Reflections

- **SMSSpamCollection**: Modeling was straightforward using the example notebook. The only challenge was handling tab-separated values, which was resolved by explicitly specifying `\t` as the separator.
- **German_dataset**: Required careful parsing. I read each line individually and split using the first semicolon due to inconsistent formatting. For visualizations, I resized figures and rotated labels to avoid x-axis text overlap when plotting 9+ categories.
- This project taught me how to adapt existing ML workflows to new datasets and troubleshoot issues with parsing, plotting, and classification accuracy.

---

## 🛠️ How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/muneebnafees/CS154_Classification-Project.git
   cd CS154_Classification-Project
   ```

2. Install dependencies (if not already installed):
   ```bash
   pip install pandas scikit-learn matplotlib
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook classification_project.ipynb
   ```

4. You’ll find two workflows inside:
   - **Spam Classifier** (SMSSpamCollection)
   - **News Topic Classifier** (German_dataset)

---

## 📊 Datasets

- **SMSSpamCollection** – Classify messages as spam or not spam
- **German_dataset** – Classify news into ~9 categories based on text type

---

## 📚 References

- [Pathlib Docs](https://docs.python.org/3/library/pathlib.html)  
- [Pandas `apply()`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.apply.html)  
- [Scikit-learn `train_test_split`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)  
- [Scikit-learn CountVectorizer](https://scikit-learn.org/1.5/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)  
- [Scikit-learn TfidfVectorizer](https://scikit-learn.org/1.5/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)  
- [Scikit-learn MultinomialNB](https://scikit-learn.org/1.5/modules/generated/sklearn.naive_bayes.MultinomialNB.html)

---

## 🪪 License

This project is licensed under the MIT License.
