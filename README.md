# Classification Challenge
>
>## Module 13 home work assignment
>
***The Data***
> The code is analyzing data collected from an email filtering system for the customers of an Internet Service Provider. The data hasinformation
> about emails, including but not limited to make, address, character frequency, length, Capital letters etc. that are considered attributes of the > email address. The resut of the classification is contained in the variable called 'spam' where a 0 indicated no spam and 1 indicates Spam email.
> The data contains 4601 entries with no null values detected
> All fields are numeric so no transformation is needed
> 'Spam' variable is skewed higher to ***no spam(2788 entries)*** vs ***Spam (1813 entries)*** 

***Files***
> the file is called ***spam-detector.ipynb***
> The code shows the development of a  supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of > > its customers' inboxes.
>* Two classification models  were created o fit the provided data:
>* The inital prediction made was that Random classifer will do a better job of classifying Spam as it is a smaller dataset but with many attributes.
>* Logistic regression is an alternatve mode this is compared with which model is more accurate at detecting spam
 
***Model Comparison***
> Comparison is done by calculating the Accoracy score of each model
>
> Both models seem to be highly predictive but the ***Random classifier seems to be more predictive*** with an ***accuracy score of 0.95*** compared to the logistic regression accuracy score of 0.93. the high scores also may indicate overfitting and further analysis needs to be done on variable selection to evaluate resuts
