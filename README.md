# Sentiment Analysis

This project helps in identifying whether a particular movie review is positive or negative depending on the training set present which is used to train our classifier.

### Prerequisite:
* Prior knowledge of Supervised Learning Methods.
* Basics of python and how to use external libraries.
* Basics of NLP

### Installation required
* Numpy
* Pandas
* Matplotlib
* ScikitLearn

**For Windows Powershell**
```
python -m pip install numpy
```

or if you have **Anaconda** installed
```
conda install numpy
```

in **Unix*8 you can directly use pip install

## Theory 

***Processing the text*** <br/>
Simple words can't be processed directly as computer doesn't understand them. So, they have to be parsed and converted into meaningful format which is easily understood by our computer. <br/> 
For doing what is mentioned above follow the steps below: <br/>
**Step 1:** Tokenize them into smaller segments(mostly words). <br/>
**Step 2:** Remove stopwords(words that occur very oftenly like a,the,of,and etc.). <br/>
**Step 3:** Make bag of frequency matrix which keep count of all the different words occuring in a text. <br/>
**Step 4:** *(Optional)* Perform tf-idf vectorization on the matrix formed. <br/>

***Classifying the text*** <br/>
In this problem movie reviews were tagged with the sentiment beforehand. Thus, we can use them to train our classifier according to the classification rules.<br/>

***Analysing the text***<br/>




## Results Explained ##
We used Bayesian Statistics and performed Gaussian and Multimonial methods on our text data. <br/>



***Gaussian Naive Bayes***
![alt text](https://github.com/RoronaRohit/sentiment-analysis/blob/master/gaussian_ROC_curve.png)

ROC score= 0.6418341932040562


**Confusion Matrix** | Predicted negative | Predicted positive
-------------------- | ------------------ | ------------------
Actual negative      |       421          |      216
Actual positive      |       296          |      476


***Multimonial Naive Bayes***
![alt text](https://github.com/RoronaRohit/sentiment-analysis/blob/master/multimonial_ROC_curve.png)

ROC score =0.734385715685314(Area under curve)


**Confusion Matrix** | Predicted negative | Predicted positive
-------------------- | ------------------ | ------------------
Actual negative      |       381          |      48
Actual positive      |       327          |      644








