#### Introduction
Welcome to the **Medical Text Cancer Type Project**🗂️!

After practicing the Netflix Genre Classification Project, I decided to apply the NLTK skills to the project related to the medical report and my previous job. This project is to **predict what kind of cancer type it is using medical reports**. There are totally 3 cancer types we want to identify:
- Thyroid cancer
- Colon cancer
- Lung cancer


#### Workflow
- Step 1: I cleaned the 17 missing data since their cancer type and text are both missing. I then converted cancer type into numeric form by using **function** and **if statement** instead of LabelEncoder to review some basic concepts of Python.

- Step 2: Now it is time to clean dirty text! The steps are
  1. covert all the characters to lowercase
  2. remove unwanted space and non-English characters
  3. tokenize the text into words
  4. create the stopword list
  5. print out the new text without stopwords
  
  You can access the clean text example here 👉 **Medical Text after cleaning.csv**


- Step 3: One new thing I added this time is this cool figure **Word Cloud**, where we can easily visualize the occurrence frequency of the words depending on their size. I would say this is the most fun thing I have added to this project :)
  
- Step 4: Again, after vectorizing the data, it is time to train the Naive Bayes classifier model and predict the outcome.


#### Result and Discussion
The accuracy is 0.8. It is better than the Netflix Genre Classification Project. The medical text is long so I think more unnecessary words can be removed!


#### Medical Text Dataset (since the file is too large) used click here 👉
https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification/data
