#### Introduction
Welcome to the **Medical & Chest x-Ray Report Classification System**🗂️!

After practicing the Netflix Genre Classification Project, I decided to apply the NLTK skills to the project related to the medical report and my previous job. This project has 2 applications. The first one is

- **Predict what kind of cancer type it is using medical reports**.

  There are totally 3 cancer types we want to identify:
  - Thyroid cancer
  - Colon cancer
  - Lung cancer

 The second one is 
 - **Predict whether this patient has abnormal lung or not using Chest X-Ray reports.**





#### Workflow
- Step 1: I cleaned the 17 missing data from Medical Text since their cancer type and text are both missing. I then converted cancer type into numeric form by using **function** and **if statement** instead of LabelEncoder to review some basic concepts of Python.

- Step 2: Now it is time to clean dirty text using **Natural Language Processing toolkit (NLTK)**! The steps are
  1. covert all the characters to lowercase
  2. remove unwanted space and non-English characters
  3. tokenize the text into words
  4. create the stopword list
  5. print out the new text without stopwords
  
  You can access the clean text example from Medical Text Data here 👉 **Medical Text after cleaning.csv**


- Step 3: One new thing I added this time is this cool figure **Word Cloud**, where we can easily visualize the occurrence frequency of the words depending on their size. I would say this is the most fun thing I have added to this project :)
  
- Step 4: Again, after vectorizing the data, it is time to train the Naive Bayes classifier model and predict the outcome.

- Step 5: Okay! Like our Netflix Genre Classification and Medical Diagnosis/Drug Treatment projects, the ultimate goal after building a project is to build something interactive! This part is to interact with users. As you can see on the last cell when I typed:

'Lung fields show non homogenous opacities in the right lower zone . Right hemidiaphragm is elevated. Both hila and vascular markings are normal. Mediastinum is central. No cardiomegaly. Both CP angles are free. Both hemidiaphragm are normal. Rib cage and spine appears normal. IMPRESSION:   Consolidation right lower zone.'

(From 👉 **Chest XRay Report.csv** row 11)

My system can predict it is an 'abnormal' lung.





#### Result and Discussion
The accuracy is > 0.85 for both data. When I entered some text, it was accurate most of the time. This model definitely has room to grow! After all, we don't want AI to make lots of mistakes when it comes to medical/clinical/healthcare applications. 


#### Medical Text Dataset (since the file is too large) used click here 👉
https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification/data
