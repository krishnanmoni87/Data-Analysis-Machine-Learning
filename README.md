# Data-Analysis-Machine-Learning
This is a data analysis project on the Indian Liver Patient Dataset

The aim of this project was to predict the presence of liver disease in a set of 117 samples (mix of males and females) after training the model with 468 samples. As this was 
a second attempt at this dataset to improve prediction accuracy, it can be safely stated that this aim was achieved successfully. I was able to bring out a prediction accuracy 
of 74.36% from a previous best of 57%. So, there is an ~ 23% improvement in prediction accuracy between the current and last attempt. So, this means there is still scope for 
enhancement. Maybe it is because of the way I cleaned my data or selected the features of my data, or how I split the training and testing data (80-20 ratio), or even the choice
of algorithms. All these could be reasons. 

However, looking at it from a real-world perspective, nothing is good short of a 100%, especially when it comes to disease prediction. 74.36% prediction accuracy by SVM algorithm 
was the best I could achieve this time, which is not a great achievement as far as a patient is concerned. This means that there is still an ~ 25% chance (1 out 4) that the 
algorithm will make the wrong prediction of disease being present in a patient, when it is not. This can be very dangerous and can cause panic amongst families and patient 
themselves. This happened to one of my friends, where in a hospital he was predicted with liver disease. He then went to two other hospitals to take a second opinion and reconfirm
this. He was surprisingly found to be free of disease. So, we want to avoid this situation. I personally would not want something like this to happen to me if I were in this
situation. However, the success of an algorithm depends on various factors surrounding the dataset.


To answer the initially stated questions, as mentioned earlier, Support Vector Machine had the best prediction accuracy of 74.36%, followed by Decision Tree and Random Forest with
71.79%. Surprisingly, these three algorithms had nearly 100% accuracy at training level, but then dipped to the 70s during testing phase. It was also interesting to observe how 
the split of the testing data resulted in different Precision, Accuracy and F1-scores in each of the algorithms. Attempts to further improve accuracy by removing and adjusting 
features in the dataset failed as this only decreased the accuracy. GNB had the worst performance at 52.99%, which was expected as this algorithm was relevant only for
regression-based algorithms. 

The second question that was asked was about the features that determine the presence of the disease. Yes, there are a group of features that may determine the presence of disease
as shown by the correlation chart and pair plots. These were “Direct Bilirubin” and “Total Bilirubin”; “Aspartate Aminotransferase” & “Alamine Aminotransferase”; “Total Proteins” 
and “Albumin”; and “Albumin and Globulin Ration” and “Albumin”. While there is no solid proof that a combination of these features will determine if a person has liver disease, 
and it would be incorrect to assume so. However, it would be correct to say and assume that one or more combinations of these features are surely an indication of liver disease. 

Further improvement to this study to enhance prediction accuracy could be that the dataset needs to be updated and should include more rows of data for analysis. Different splits
of training and testing data sets can be tried. There are many other Machine Learning algorithms, which can be implemented on the model. Different features can also be chosen for 
analysis.  
