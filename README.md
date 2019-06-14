# UCI_sentiment_analysis

Sentiment analysis using custom word embeddings and LSTM on the UCI review dataset.

The dataset consists of reviews posted from three websites- Amazon, imdb and yelp

We then implement LSTM based network to achieve the followign accuracies:

<table>
<tr>
<td>Training accuracy</td>
<td>100%</td>
</tr>
<tr>
<td>Testing accuracy</td>
<td>80%</td>
</tr>
</table>

Clearly our model has overfitted and the performance can be further improved by using:
1. Batch normalization layers
2. Pre-trained word embeddings like GLoVe, Fasttext etc.

Feel free to contribute your versions with better accuracies!
