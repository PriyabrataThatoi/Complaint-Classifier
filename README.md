# COMPLAINT CLASSIFIER USING NLP (LDA & TF-IDF)

Problem: While filing a complaint, customers are asked to choose the complaint category or theme. However, customers are unaware of business terms so they often choose the wrong category. This was a major issue for us with more than 20% of complaints being misclassified and routed incorrectly. This led to long wait times and incomplete resolution of customer complaints.


Solution: We leveraged topic algorithms such as TF-IDF and LDA to reclassify customer complaints based on the exact language used in the complaint. As seen in the chart below, there are several differences between original (customer-led) and new (NLP-recommended) themes. Especially, NLP-themes identified ‘Late Fees’ as the main reason (17%) for customer complaints, which was considerably higher than the previous estimate.


![Text Classification](https://user-images.githubusercontent.com/54467567/87732510-cc99b700-c792-11ea-9d2d-12e660869cd4.png)


- Kaggle: https://www.kaggle.com/dhorvay/consumer-complaint-classifier-lda-topic-modeling
- Reference : https://towardsdatascience.com/https-medium-com-vishalmorde-humanizing-customer-complaints-using-nlp-algorithms-64a820cef373
