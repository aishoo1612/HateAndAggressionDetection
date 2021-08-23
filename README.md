**A Comprehensive Study of Hate and Aggression Detection on Social Media**



With the rise of social media&#39;s availability, people have been using such platforms to express themselves. While, these allow people to communicate throughout the world without much censoring, hate and aggression has also been increasing. Since, they are fine-grained sentiments, thus they end up passing the elementary sentiment detection algorithms easily, making social media a toxic place. Due to the social media guidelines and policies, several of such comments and/or posts are often taken down, thus making the collection of data even scarce. This research involves a comprehensive of study of low resource algorithms such as regression, to high resource algorithms as BERT and other Deep learning approaches such as force-feed, label smoothing, transfer learning, alongside with a newer approach of introducing PonderNet, which adapts its computational learning in a probabilistic approach depending upon the data provided, which makes its result more humane.

  **Disclaimer –** 

The article contains material that many will find offensive or hateful; however this cannot be avoided owing to the nature of the work.

  **Keywords –** 

_Hate speech detection · Social media texts · Machine learning · Text classification_

  **Datasets used -**

Due to online platform guidelines, comments and/or posts which have crossed the community guidelines often get taken down which makes the collection of such data even scarce. For the purpose of this study, 2 benchmark datasets have been considered i.e.

1. HateXplain dataset –

2. SemEval 2019 Task 5 dataset-

This dataset contains 2 sets of such offensive tweets in English and Spanish language. The text is binary categorized for 3 different kinds i.e. hateful, targeted and aggressive, with 0 representing not and 1 accounting for the positive. This dataset has 4469 tweets for training in spanish and 2805 tweets for training in english language.

3. TRAC dataset-

This dataset contains comments from facebook in english and hindi languages for aggression detection and has 3 different levels of aggression i.e. NAG, CAG and OAG. This dataset contains 12000 elements for english language and 12000 elements for training in hindi language.

**Models used -**

The following models of classification shall be used for the study&#39;s purposes :

- Low Resource Models

1. Logistic Regression
2. K-NN
3. SVM
4. Random Forests

- Boosted Algorithms

1. ADABOOST

- Deep learning algorithms-

1. CNN-GRU
2. BERT
3. mBERT

- Transfer Learning model

1. MUSE + CNN\_GRU
2. Translation +BERT
3. LASER + LR

- PonderNet

 **Outputs Received :** 

_For Low Resource Models :_

_For agr\_en\_train model:_

| **Technique type** | **Model Name** | **Precision** | **Recall** | **Support** | **F1-Score** | **Accuracy** |
| --- | --- | --- | --- | --- | --- | --- |
| --- | _Random Forests_ | _0.51_ | _0.52_ | _3000_ | _0.51_ | _0.52_ |
| Low Resource | _KNN_ | _0.49_ | _0.48_ | _3000_ | _0.46_ | _0.48_ |
| Models | _ **SVM** _ | _ **0.54** _ | _ **0.53** _ | _ **3000** _ | _ **0.50** _ | _ **0.53** _ |
| --- | _ **Multinomial Naive Bayes** _ | _ **0.54** _ | _ **0.53** _ | _ **3000** _ | _ **0.50** _ | _ **0.53** _ |
| Transfer Learning | _Machine Translation - Seq2Seq_ | _0.41_ | _0.41_ | _2400_ | _0.40_ | _---_ |

![](RackMultipart20210817-4-c1mmhw_html_cc5587ac2b36ca7d.png)


