# Amazon-music-review-sentiment-and-topic-analysis

This notebook contains a two-part analysis of a dataset of Amazon CD and Vinyl reviews: a topic analysis and sentiment analysis. Roughly 100,000 reviews are randomly sampled from the original dataset, which contains about 1.1 million records. The reviews were then classified as positive or negative based on the value of the rating (1-2 stars is rated as "negative" and 4-5 stars is rated as "positive." Neutral 3-star reviews were excluded). After various pre-processing and vectorization steps are applied to the text of the reviews, the topic analysis is performed using Latent Dirichlet Allocation. The sentiment analysis is performed using a variety of classification methods.