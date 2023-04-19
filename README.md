# EDA-Machine-Learning-Approach-For-Predicting-Titanic-Survival

In this project, I analyzed the Titanic dataset using exploratory data analysis (EDA) techniques and built a machine learning model to predict the survival of Titanic passengers with an accuracy score of 79.425%.

## Accuracy Score
Model Accuray Score on test datasets is __0.79425__ after submitting the submission to the kaggle titanic competition.

![titanic_accuracy](https://user-images.githubusercontent.com/105104702/233075834-939dd6e3-8850-4854-bb5f-c099942035de.png)

## Summary
1. Datasets contains 1309 rows and 12 columnns.
2. Datasets contains __5__ columns of __object__ type, __3__ columns of __integer__ type and __3__ columns of __float__ type.
3. Most of the __Null values__ are in the __Cabin__ column about __1014__ out of 1309, followed by __Survived__ column about __418__ and __Age__ column about __263 null values__.
4. __Fare__ and __Embarked__ column have __1__ or __2 missing values__.
5. Only __Age__, __Parch__ and __Fare__ have __positive correlation__ with target variable __Survived__.
6. __Survived__ has __2__ unique values __0__ & __1__. Most of the values are __0__ about __549__, followed by __1__ about __342__.
8. __Passenger Class__ has __3__ unique values __1, 2 & 3__. Most of the values are __3__ about __709__, followed by __1 & 2__.
9. __Gender__ has __2__ unique values __female & male__. Most of the values are __male__ about __843__, followed by __female__ about __466__.
10. __Siblings or Spouses__ has __7__ unique values __0, 1, 2, 3, 4, 5 & 8.__ Most of the values are __0__ about __891__, followed by __1 & 2__.
11. __Parents or Children__ has __8__ unique values __0, 1, 2, 3, 4, 5, 6 & 9__. Most of the values are __0__ about __1002__, followed by __1 & 2__.
12. __Port of Embarkation__ has __3__ unique values __C, Q & S__. Most of the values are __S__ about __914__, followed by __C & Q__.
13. __Most of the passengers__ fall within the __age range__ of __18 to 45__, with approximately __677__ passengers. The __age__ values in the dataset range from __2 months to 80 years__.
14. __Most of the passenger fares__ fall within the __range__ of __0 to 100__, with approximately __1308__ passengers having fares in this range. The __passenger fares__ in the dataset __range__ from __0 to 512.32__.
15. The __Five-Number Summary__ of the __Age data__ is as follows : the __minimum age__ is __0.17__, the __1st quartile__ is __21.0__, the __median__ is __28.0__, the __3rd quartile__ is __39.0__, and the __maximum age__ is __80.0__.
16. The __median__ is __close__ to the __bottom of the box__ or close to the __first quartile__ means the data is __positively skewed__ or skewed to the __right__.
17. Out of the total values, there are __552__ values that __fall__ within the __Interquartile Range (IQR)__, which is the __range__ of values between the __1st Quartile__ and the __3rd Quartile__.
18. There are __9__ values in the __age__ column that are considered __outliers__.
19. The __Five-Number Summary__ of the __Age data__ is as follows : the __minimum age__ is __0__, the __1st quartile__ is __7.9__, the __median__ is __14.45__, the __3rd quartile__ is __31.28__, and the __maximum age__ is __512.33__.
20. The __median__ is __close__ to the __bottom of the box__ or close to the __first quartile__ means the data is __positively skewed__ or skewed to the __right__.
21. Out of the total values, there are __697__ values that __fall__ within the __Interquartile Range (IQR)__, which is the __range__ of values between the __1st Quartile__ and the __3rd Quartile__.
22. There are __171__ values in the __age__ column that are considered __outliers__.
23. The __majority of the surviving__ passengers were __women__, accounting for approximately __74%__ of all __female survivors__. Only __19%__ of the __men survived__ the disaster.
24. Out of all the __male__ passengers, approximately __468 did not survive__ while only __109 survived__. In comparison, out of all the __females__, only __81 did not survive__ and a total of __233__ __females survived__.
25. __Most of the passengers__ who __did not survive__ were in __passenger class 3__, about __372__ passengers __did not survive__ and only __119__ passengers __survived__ in that __class__.
26. __Passenger class 1__ had the __highest__ number of __survivors__, with approximately __136__ passengers __surviving__ and __80__ passengers __not surviving__ in that __class__.
27. Most of the passengers who __did not survive__ had __no siblings or spouses__ onboard, comprising approximately __398__ passengers. Only __210__ passengers who __had no siblings or spouses__ onboard __survived__.
28. __Passengers__ who had __one sibling or spouse__ onboard were __survived the most__ compared to those __who did not survive__. Approximately __112__ passengers with __one sibling or spouse survived__, while __97__ passengers with __one sibling or spouse did not survive__.
29. Most of the passengers who __did not survive__ had __no parents or children__ onboard, comprising approximately __445__ passengers. Only __233__ passengers who __had no parents or children__ onboard __survived__.
30. __Passengers__ who had __one parents or children__ onboard were __survived the most__ compared to those __who did not survive__. Approximately __65__ passengers with __one sibling or spouse survived__, while __53__ passengers with __one parents or children did not survive__.
31. __Passengers__ who had __two parents or children__ onboard had an __equal__ number of __survivors__ and __non-survivors__, with approximately __40 passengers surviving__ and __40 passengers not surviving__.
32. __Most of the passengers__ who __did not survive__ were from the __S Port of Embarkation__, with approximately __427__ passengers. Only __217__ passengers __survived__ from that Port of Embarkation.
33. In the __C Port of Embarkation__, __93__ passengers __survived__ compared to about __75__ passengers who __did not survive__.
34. __Most of the passengers__ who __did not survive__ were in the __20-30__ age group, with approximately __146__ passengers, compared to only __84__ who __survived__ in that age group.
35. __86__ passengers who __did not survive__ were in the __30-40__ age group, compared to __69__ who __survived__.
36. Most of the passengers who __did not survive__ had a __passenger fare__ of __0-100__, with approximately __521__ passengers, compared to only __302__ who __survived__ in that __passenger fare group__.
37. There were __no passenger__ who had __300-400__ or __400-500__ passenger fare.


