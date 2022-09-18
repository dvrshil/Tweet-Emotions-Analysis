
My code is available in this directory in the COVID Emotions.ipynb file. The Python notebook can be run using Jupyter Notebook from Anaconda or Google Colab or some similar software.

------------------------------------

Dataset description:

My data consists of three files:

1. Corona_NLP_train.csv: original training dataset

2. Corona_NLP_test.csv: original test dataset

3. trainedEmotions.csv: This file contains emotions for each tweet that was returned by OpenAI. I included this file as obtaining the emotions again would be a redundant task and it will take a few hours to be processed completely if obtained using the OpenAI API. I have included the code for how to use the API in my code.

------------------------------------

Libraries set up for running the code:

- Popular libraries I have used: pandas, numpy, matplotlib, scikitlearn/sklearn, tensorflow, re

- Some other libraries I used (likely needed to be installed on your end): gensim, nltk, pyLDAvis, wordcloud, pprint

- All of the libraries can be installed by running the following command in the Terminal on a mac or a windows device: (don't include the brackets, use the library name given above, if not mentioned otherwise)

	pip install <library_name>

- The pyLDAvis library name is case sensitive for setting it up.

- The pprint library needs to be set up using the command "pip install pprintpp"