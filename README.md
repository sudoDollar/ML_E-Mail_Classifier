# ML based E-Mail Classifier
EL-GY-9133 Machine Learning for Cyber-Security: E-mail Spam Filtering

![Static Badge](https://img.shields.io/badge/Language-Python-blue)

Dataset: [Ling-Spam by Ion Androutsopoulos](http://www.aueb.gr/users/ion/data/lingspam_public.tar.gz)

1. Feature Selection: Information Gain
2. Naive Bayes based Spam Email Classifier
3. SVM Based Spam Email Classifier

|Model                                      |#Features|Spam Precision     |Spam Recall         |Test Accuracy    |Latency             |
|-------------------------------------------|---------|-------------------|--------------------|-----------------|--------------------|
|Bernoulli NB with binary features          |10       |0.7096774193548387 |0.4489795918367347  |87.62886597938144|0.008576155         |
|Bernoulli NB with binary features          |100      |0.8541666666666666 |0.8367346938775511  |94.84536082474226|0.071364641         |
|Bernoulli NB with binary features          |1000     |0.9565217391304348 |0.8979591836734694  |97.59450171821305|0.6290507316589355  |
|Multinomial NB with binary features        |10       |1                  |0.061224489795918366|84.19243986254295|0.00288105          |
|Multinomial NB with binary features        |100      |0.8888888888888888 |0.4897959183673469  |90.37800687285224|0.023763895         |
|Multinomial NB with binary features        |1000     |1                  |0.5918367346938775  |93.12714776632302|0.5207004547119141  |
|Multinomial NB with Term Frequency features|10       |0.38461538461538464|0.20408163265306123 |81.09965635738831|0.002846718         |
|Multinomial NB with Term Frequency features|100      |0.85               |0.6938775510204082  |92.78350515463917|0.023176908493041992|
|Multinomial NB with Term Frequency features|1000     |0.7333333333333333 |0.22448979591836735 |85.56701030927834|0.24455142          |
|SVM with Term Frequency features           |ALL      |0.886792453        |0.959183673         |97.25085911      |0.326929569         |



