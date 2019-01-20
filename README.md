# Movie-Rating-Prediction-Using-Naive-Bayes
## Quick Summary
In this project, the ultimate aim is to build a Naive Bayes classifier to classify movie reviews into two distinct categories: "Fresh" or "Rotten". As usual, exploratory data analysis is first executed to gain a better understanding of the data available. To assess the accuracy of the model, several performance metrics, ranging from log-likelihood to classification accuracy, were used. 

## Conclusion
USing merely the Naive Bayes classifier, a simple which makes many erroneous assumptions about the nature of the dataset, we were still able to obtian a cross-validation classification rating of about 77.1%. To investigate further, we also determined which words best determine if a review is "Fresh" or "Rotten". For example, the top 5 words which predict "Fresh" well are: "masterpiece", "delight", "touching", "superb" and "remarkable". 

It is important to note that the classifier assumes that each work affects the "Freshness" probability independent of other words, which is clearly untrue. In many cases, the meaning of a review is formed by _a group of words_, and not the meaning of any particular word alone. For instance, "awfully" has a negative connotation when taken on its own, but when used in the phrase "awfully good", it can give an entirely different meaning. 
