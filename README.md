Here is the dataset from [kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Hello everyone,

I used the "creditcardfraud" data set in this notebook. I have developed a model that decides whether the transaction is fraud or a legit transaction using the Logistic Regression model, which is the Binary Classification methods.

While reviewing our data set, I realized that the data set belonged to a bank from past competitions and that the data was standardized and shared with us.

On EDA step I saw that there was no missing (NAN) data in our data. And it helped to me for less work. Later, when I looked at the distribution of dependent variables in the data set, I realize that the data was biased.

During the modeling phase, first eliminated this bias with the Under-sampling method (there are many other different models, I have added them below(+ Plus)). Then, I divided our data into dependent and independent variables and divided it as a test-train set. Finally, I created our model and moved on to the evaluation phase.

During the evaluation phase, I tried to use all evaluation metrics used in Classification models and tried to be as descriptive as I could.

Please keep in mind that I am still learning, so if you spot any incorrect explanations or anything, please let me know. Enjoy your journey, as well.

Thank you for reading this far.
