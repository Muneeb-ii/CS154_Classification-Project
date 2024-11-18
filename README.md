[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/0C7hcwxP)
# Project 6 Classification

## Name

_Muneeb Azfar Nafees_

## Introspection

### Modeling Datasets:
1. **SMSSpamCollection** was pretty easy to model using the example model. The only difficult part was resolving the error while splitting the text, as we had to specify an extra parameter separator as tab (\t).
2. In the **German_dataset**, I faced issues while separating the data and making plots.
    - For this dataset, each separator I used threw an error, so I used a different technique. I read the file line by line and separated each line using the first semicolon, as the data was organized in the form Type;News.
    - As there were around nine types, I had to fix the plots of each graph to ensure there was no text overlap on the x-axis. I increased the size of the figure and rotated the text 45 degrees to ensure there was no overlap.

## Dataset
1. SMSSpamCollection
2. German_dataset

## Resources
1. https://docs.python.org/3/library/pathlib.html
2. https://pandas.pydata.org/docs/reference/series.html
3. https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
4. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.apply.html
5. https://scikit-learn.org/1.5/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
6. https://scikit-learn.org/1.5/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html
7. https://scikit-learn.org/1.5/modules/generated/sklearn.naive_bayes.MultinomialNB.html


### *DO NOT EDIT BELOW THIS LINE*
---

## Goal

The goals of this project are:

* Using built-in and core Python libraries to develop a classification model for an unseen dataset
* Understand the steps for a machine learning task
* Learn to read documentation to understand what each object and method does and other helpful methods available.

## Description

In this project, you are provided with a Jupyter Notebook that contains code to train a Naive Bayes classifier to predict the sentiment of IMDB review dataset. Your goal is to use this notebook as an example and create a similar notebook to train a classifier on a similar dataset, but **not the IMDB dataset**. These dataset files are provided in the dataset folder.

In this project there are two primary tasks:

1. Create a Jupyter notebook that performs all the steps described in the example notebook on a different dataset.
2. Understand the libraries, classes, and methods being used by reading the documentation and answer the prompt questions.

It should be fairly easy to duplicate the example notebook and train a ML model on a different dataset, however, without understanding what is happening you won't be able to use it on a different problem. Answer each question in as much detail as possible. 


## Rubric

**1. Version Control Practice** - **10 points**

- **Commit Numbers and Sizes**: *5 points*
  - The commits are made at regular intervals and of coherent pieces 
- **Commit Messages**: *5 points*
  - Easy to follow along the commit history

**3. ML Steps ** - **40 points**

- Steps 1 - 4 are implemented.
- The accuracy is higher than 50%
- The model is trained on both Bag of Words and TF IDF features

**4. Question Answers ** - **50 points**

- All questions are answered
- Each question is answered in detail

**Total Points: 100**

## Tips On How To Excel


* Start early!
* Ask for help when stuck. Remember the 30 minute rule? No? Look into the syllabus.
* Break down the problem into smaller tasks and try to implement them in Jupyter Notebook. Once implemented in the notebook successfully, transfer it into `.py` file.
* Run the `.py` file to make sure the new addition did not break any changes.
* After implementing each small task, commit changes.
* Review the notebooks from classes available on GitHub if you cannot remember syntax for anything.
* Run your code multiple times and vary the inputs to ensure it works as intended. 

## Feedback


