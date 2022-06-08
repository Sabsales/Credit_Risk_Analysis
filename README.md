# Credit_Risk_Analysis
////Purpose:

The purpose of this analysis is to determine which methods were best to identify loans that may turn out to be high risk. The methods that were used in evaluation included different models such as Logistical Regression, SMOTTEN, Random Forest Classifier, and Easy Ensemble Classifier.

////Analysis:
Among predicted high risk loans, the precision was only 0.01 which means that approximately 99% of those predicted to be high risk were actually low risk.

![Image1](https://user-images.githubusercontent.com/96558665/172510142-4b2baf53-a8a0-4e93-94ea-90e4f8c6315d.png)

Which means that many potential loan applicants were misclassified and labeled wrong by the algorithm.

![Image2](https://user-images.githubusercontent.com/96558665/172510092-00bb80db-7b3b-4dfc-9ad7-88d59d3fb2af.png)

The confusion matrix depicted above also shows the same problem with misclassification. The 7914 loans are predicted to be high risk when they are in actuality, low risk. This misclassification skews the data results and returns a flawed assessment.

![Image3](https://user-images.githubusercontent.com/96558665/172510213-535b21ef-2aae-494d-89f6-ad01a6965401.png)

The accuracy shown in this result above is sub optimal for the purpose of determining if loan applicants are high or low risk.

![Image4](https://user-images.githubusercontent.com/96558665/172510250-91233246-f3fb-4a24-9831-8d4c6fe83e01.png)

The Easy Ensemble Classifier however had an accuracy of 93 percent. Showing that this model was able to predict with a higher accuracy of which loan applicants were high or low risk.

![Image5](https://user-images.githubusercontent.com/96558665/172510265-30acb015-2f2d-4803-b14c-722cda6f9db6.png)

Here, the Random Forest Classifier shows a result of improvement for determining the risk assessment of loan applicants however the misclassification of loan applicants is still prevalent with this model. I would suggest for determining the risk of loan applicants, to use Easy Ensemble Classifier as the chosen model.

////Summary:

In these data sets the high risk loans were very rare so the data was highly imbalanced. Because of this imbalance methods using Logistical Regression and SMOTTEN were not reliable in predicting loan risk status. You don’t want to use this because potential loan applicants could be turned away in error. On the other hand, after I used Beautiful Random Forest Classifier and Easy Ensemble Classifier to compensate for the imbalanced data and that led to reasonably accurate prediction. It would be reasonable to use Easy Ensemble Classifier for one tool for identifying potentially high risk loan applicants. Even with 93% however, some loan applicants would still be misclassified. So when reviewing applicants, one should still consider other information. 
