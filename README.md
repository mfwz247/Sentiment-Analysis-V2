# Sentiment-Analysis-V2
This is Sentiment analysis as an assessment Challenge 2

kaggle : https://www.kaggle.com/code/muhammadfawzy/sentiment-analysis-v2
data that I collected from:

1 - http://saifmohammad.com/WebPages/TweetEmotionIntensity-dataviz.html
2 - https://github.com/cardiffnlp/tweeteval

Thanks to this paper

3 - https://onlinelibrary.wiley.com/doi/full/10.1002/eng2.12189

I did excel cleaning to this file as it looked like this before cleaning:


![image](https://user-images.githubusercontent.com/81578056/159089631-fbce8d57-cac2-4bbb-99d2-3a7c41b5f588.png)

to look like this : 

![image](https://user-images.githubusercontent.com/81578056/159090707-489f598a-081f-4524-9f91-297eb7eb9aa5.png)


using these functions thanks to Microsoft!

=IF(OR(C3,D3,E3,F3),C3+D3+E4+F5,0)
=IF(C2,$C$1,IF(D2,$D$1,IF(E2,$E$1,IF(F2,$F$1,"unknown"))))

![image](https://user-images.githubusercontent.com/81578056/159090576-8b81c9d4-eb68-417d-bb48-48042f471766.png)
![image](https://user-images.githubusercontent.com/81578056/159090592-a9456ab6-207e-438b-ad80-502a20050c8a.png)


Sources that helped me through this challenge: 

https://www.analyticsvidhya.com/blog/2021/06/natural-language-processing-sentiment-analysis-using-lstm/
https://www.kaggle.com/code/paoloripamonti/twitter-sentiment-analysis
https://www.coursera.org/learn/nlp-sequence-models/lecture/agZiL/gated-recurrent-unit-gru
https://github.com/RaRe-Technologies/gensim/wiki/Migrating-from-Gensim-3.x-to-4#7-methods-like-most_similar-wmdistance-doesnt_match-similarity--others-moved-to-keyedvectors
