# Bio-signals-of-smokers-non-smokers
R lab based on discovering the data of smokers' dataset and hypotheses testing 

For this project we analyze [smokers/ non - smokers data set](https://www.kaggle.com/datasets/kukuroo3/body-signal-of-smoking). It is found on the Kaggle website, containing more than 55 thousand people’s data, along with whether they smoke or not. On the Kaggle website, there is a parsed version of the original based on the National Health Insurance Service Health Checkup Information, taken from here. There are 27 categories of people’s personal info such as height, weight, age and health conditions.

The parameter smoke denotes 0 as non-smoker and 1 as smoker.

In this research we are going to discover how the specific data is distributed,its mean and mode values, analyze the dependencies of being smoker/non-smoker and health-condition.

The dataset looks in the following way:

![image](https://user-images.githubusercontent.com/92577132/210433295-44628c5c-ec1d-46cd-b393-6b1099c2e334.png)


For analysis we can use such variables as “gender”, “age”, “height”, “weight”,”hemoglobin”, “smoking” and other health parameters.
From the initial analysis of data, we saw that there are significant differences in the health of smokers and non-smokers. Also, the fraction of male smokers  is much bigger than  female’s ones. Also we noticed that the mode of the smoker’s dataset in both gender is 40 years.

From what we have seen so far, it would be reasonable to test the following hypotheses:


1)The distribution of smokers/non-smoker ratio is exponentially distributed.


2)The number of smokers, depending on people’s age is normally distributed.


3)The mean age of smokers are more equal than 40.


4)There is no significant difference in the hemoglobin mean of smokers and non-smokers.


5)There is no relation between eyesight and being smoker/non smoker.


6)There is no relation between hemoglobin and cholesterol level of  smoker/non smoker.

For testing I used hypotheses testing, especially knowledge of different methods as z-testing, t-testing, Kolmogorov-Smirnov test, correlation testing(Pearson, Kendell), linear regression.


As a result, we discovered that smoking impacts a lot people's health condition, however not so much as we expected before this research. The relation between hemoglobin level and cholesterol of smokers is stronger than in non-smoker, however relation between blood sugar level and cholesterol is the same correlated for smokers and non-smokers. It shows that smoking impact on both simultaneously : hemoglobin and cholesterol level.

Smokers' hemoglobin mean is worse than non-smokers, that shows that smoking impact people's health, however there is no relation between eyesight level and being smoker.

The distribution of smoker's age wasn't difficult to predict and our hypothesis was approved, however it was surprising that distribution of smokers/non-smokers ration is exponential.

During this research we used our theoretical knowledge on practice, almost all testing methods and linear-regression; and discovered how it works in the real testing of data. We analyze interesting data set for us, because we were curious if the impact of smoking is so crucial on this huge sample of population. In fact it doesn't make such a crucial impact, but still have harm for our health.
