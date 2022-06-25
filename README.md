# Twitter-Sentiment-Polarity-Analysis
This project was done as part of the course CS F469 (Information Retrieval) in the Second Semester of AY 21-22 under the guidance of Prof. Poonam Goyal, BITS Pilani.

## Brief Description
We implemented a Naive Bayes Sentiment Classifier for Short-form text messages (Tweets), to classify them into binary (mutually exclusive) categories: Positive or Negative.

## Description

- Preprocessing
-  Training (Multinomial, Bernoulli) + Dataset
-  
<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/5031f72d5cc1560be4edc5947e48a8733c06bda9/Assets/Sentiment%20140%20Dataset.png"><br>
<!-- <em><b>Sentiment140 Dataset, from Kaggle</b></em> -->

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/5031f72d5cc1560be4edc5947e48a8733c06bda9/Assets/3D%20Embedding%20TSNE.png">
<!-- <em><b>TSNE Visualization in 3D Space</b></em> -->

Results

## Installation and Use

A prediction tool was built using the aforementioned Naive Bayes Classifier. It takes a user tweet as input and then predicts the tweet to have either Positive sentiment, or negative sentiment. The simple python GUI also offers choice of Naive Bayes model (Multinomial or Bernoulli), and whether the user wants to apply feature selection (Chi-Square feature selection or None at all). Some sample results are shown below:

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/cf1829c9a60dac7fe07baebb32fae004e26d4d07/Assets/Positive%20Tweet.png" width = "512"><br>
<em><b>Positive Tweet</b></em>
<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/cf1829c9a60dac7fe07baebb32fae004e26d4d07/Assets/Negative%20Tweet.png" width = "512"><br>
<em><b>Negative Tweet</b></em>
## References
- <em>N. Yadav, O. Kudale, S. Gupta, A. Rao and A. Shitole, "Twitter Sentiment Analysis Using Machine Learning For Product Evaluation," 2020 International Conference on Inventive Computation Technologies (ICICT), 2020, pp. 181-185</em> ([Paper Link](https://ieeexplore.ieee.org/document/9112381))
- Please refer to the Project Report for a more detailed analysis and explanation of the code. ([Project Report Link](https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/5031f72d5cc1560be4edc5947e48a8733c06bda9/Twitter%20Sentiment%20Analysis%20using%20Naive%20Bayes.pdf))
