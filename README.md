# nlp-disaster
https://www.kaggle.com/c/nlp-getting-started/overview
The above link is the link for dataset in kaggle
NLP is the subset of Data-science and which allows us to deal with text data . NLP has several applications like in sentiment analysis
as social is very powerful nowadays it become very important to analyse the text data and not only this there are several applications 
of NLP as well
In this dataset i have used SVM model to predict the output and for creating this model i have used many techniques like

1)First of all i have analysed the data using EDA like i have checked first the class imbalance which was almost balanced(almost)

2)Then i was analyzing the lenghts in each tweets i found that non disastorous tweets having of more length than the disastorous tweets on an average

3)Then i calculated the percentage of disastorous tweets is less as compared to non-disastorous ones

4)Then i used NLP techniques to preprocess the data such as tokenizing then i removed stopwords then i removed special characters and applied stemming 
lemitization

5)After that i have splitted the train.csv data into X_train,X_test,Y_train,Y_test to create and train our model , i used countvectorizer to used the make the sparse
array and after loading my SVM model i trained my model and predicted on the test.csv data and i have attached the predictions data to the sample_submission.csv
data to submit in kaggle 
