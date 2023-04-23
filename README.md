# SC1005-miniproject
Fake News Detection

It is notable that fake news can be detected in large datasets of news articles by identifying patterns such as use of emotionally charged language, logical inconsistencies that are indicative of false information. Natural language processing techniques can be employed to analyse textual content. Since Machine Learning models are not foolproof, it is crucial to continuously evaluate and refine these models to reduce the number of false positives and false negatives. Seeing the negative consequences of fake news, this made us ponder which model would be the best to detect it.

These are the sections of the uploaded code:
1. Data Pre-Processing
  a) Changing the fake and real labels to 1 and 0 respectively 
  b) Checking for any null data

2. Data Processing
  a) Stemming: Reducing the word to the root form for the title data
  b) Processing the Text Data:removing punctation and stopwords (fillers)
  c) Making everything lower-case
  d) Removing unnecessary punctutations
  e) Tokenising the Text Data: reducing the data to recognisable and usable tokens
  f) Vectorising the Data using TF-IDF and Bag-of-Words (BOW) method

3. Training Data
  a) Reshape the label data
  b) Create two new datasets with vectorised TF-IDF and BoW data
  c) Split into training, validation and testing data

4. Models
  a) Logistic Regression
  b) Multinomial Naive Bayes
  c) Decision Tree Classifier

Inspired by codes from:
1. https://github.com/vibhorag101/Fake-News-Detection/blob/main/FakeNewsDetectionModel.ipynb
2. https://github.com/Shaguns26/Fake-News-Detection/blob/master/Fake%20News%20Detection%20Naive%20Bayes%20Model.ipynb
3. Dataset from: https://www.geeksforgeeks.org/passive-aggressive-classifiers/
4. https://youtu.be/nacLBdyG6jE 
5. https://scikit-learn.org/stable/ 
