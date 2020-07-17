# Telemarketing Campaign
 Artificial Intelligence, Machine Learning Project using Rapid-Miner and Weka Softwar.

## Project Overview 
The increasing number of marketing campaigns over time cause reducing their effects on the public. So, to increase marketing campaign efficiency we build this project to get a dataset that acts as factors that affect the success of a campaign and predicting whether the campaign will be successful or not.
The objective is to build a KNN classifier that predicts whether a client will subscribe a term deposit. If the classifier has high accuracy, then banks can arrange a better management to improve their efficiency their profits.

This project aims to build a prediction about who will subscribe a term deposit based on dataset using K-Nearest Neighbor operator, and applied this algorithm on the dataset for 10,000 clients, 1 special attribute and 20 attributes using both Rapid Miner and Weka. Also, this algorithm will be applied again with two validation options (split & cross validation).

## Installation 

This project requires **Rapid-Miner** and **Weka**.
To download theses programs :
- [Rapid-Miner](https://my.rapidminer.com/nexus/account/index.html#downloads)
- [Weka](http://www.cs.waikato.ac.nz/ml/weka/downloading.html)
## K-Nearest Neighbor Method
We used k-nearest method as a classifier operator that generates a k-Nearest Neighbor model from the input dataset then classified the new value to binary classification (Yes, No) based on a similarity measure (distance functions) and classified by a majority vote of its neighbors. We chose this method because it helps in predicate the results of the target attribute, which the attribute can be classified as binary response.

## Bank Telemarketing Dataset
Bank telemarketing dataset contain 10,000 datasets that related with direct marketing which based on phone call. The goal of classification these data is to predict whether campaign will be successful to a certain client according on the dataset attributes.

## Results
The main findings of the code can be found at the post available [here](https://medium.com/@algethamishahad/telemarketing-campaign-280e253ea8c5?sk=5707e576a9194ece2f94f68d54d68cb3)

## Conclusion
[![image.png](https://i.postimg.cc/MHW9JWNq/image.png)](https://postimg.cc/1njGpZyj)
As the previous result, we approved a difference between each program (rapid miner & weka) in predicate the target. Since in Spilt validation, the accuracy values are better a little in weka than rapid miner, unless the rapid miner is better than weka in evaluate the precision and recall values. Also in Cross validation, we noticed that weka still better than rapid miner in evaluate the accuracy and in the precision; but still weak in calculating the recall value.

As a conclusion, we noticed that cross validation using weka program is better for telemarketing campaign success because its produce a high accuracy and precision results. After Applying the model to test/predicate new data with client information.

[![image.png](https://i.postimg.cc/26xxws6J/image.png)](https://postimg.cc/LYnf40jB)

we get the same result as we expected (prediction = yes): means client will subscribe a term deposit. Since the prediction is affected by data as factors; we can see the client performed 2-contacts during the campaign, last contacts were before 10 days and the outcome of the previous marketing campaign was success for this client. these are some of the factors helps in predicate the results.

## References

- [Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- [Who Will Subscribe A Term Deposit?](http://www.columbia.edu/~jc4133/ADA-Project.pdf) 
- [Evaluating Classifiers: Confusion Matrix for Multiple Classes](https://www.youtube.com/watch?v=FAr2GmWNbT0&list=PLea0WJq13cnCZZ3sXVEZ2OE5CLeZUlCmm&index=4) 
- [What is Classification?](https://www.youtube.com/watch?v=SAUIDEhGC8w&index=2&list=PLea0WJq13cnCS4LLMeUuZmTxqsqlhwUoe) 
- [Confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix) 
