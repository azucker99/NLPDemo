# NLPDemo
Presents an introduction to Natural Language Processing (NLP) through an interactive notebook format.

## Text Classification
Text classification is a fundamental task in NLP where texts are categorized into organized groups. With the abundance of unstructured text produced daily, being able to extract insights rapidly from text represents can prove quite beneficial. Text classification is ubiquitous in our lives, innovations like email spam filters and language detection capabilities all rely on text classification.

This notebook uses the open-source NLP library [spaCy](https://spacy.io/) to train a **binary classifier** to predict whether a particular job posting is fake or not. This dataset was collected from [kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction). `spaCy` is run as a pipeline consisting of components, which are machine learning models. The component trained in this experiment is the `textcat` component. 

## Installation
We will be using [Google Colab](https://colab.research.google.com/) to run the code found in the demo notebook. It provides a notebook interface to run Python code and only requires a Google account. It handles the creation of a virtual environment as well as runs the code on Google's cloud servers. 

1. In Google Colab, go to File -> Open Notebook, and select GitHub.  Enter this repository to open the notebook: https://github.com/azucker99/NLPDemo.git

2. Select the azucker99/NLPDemo repository

3. Select the appropriate branch (main, or dev during the development branch)

4. Open nlp_demo.ipynb

5. Run this command in the first cell: `!git clone https://github.com/azucker99/NLPDemo.git` - during the development branch, run `!git clone -b dev https://github.com/azucker99/NLPDemo.git`

6. Click the folder icon on the left of the screen, and now you should see entire repo available for use


## Challenges
Here are a couple of questions and challenges about where to go after completing the demo:

1. How can we improve our current classification model? 

2. Identify key features (e.g., entities, words, phrases) of job descriptions that belong to the fraudulent class

2. Perform Exploratory Data Analysis (EDA) to find interesting insights (e.g., most frequent words, what departments have the most fraudulent advertisements, etc.)

3. Create a classification model using all the features to predict fraudulent jobs (e.g, using logisitic regression, random forest, etc.)
