![Image](https://mehtalkculous.com/assets/images/projects/recommendation-banner.jpg)

## Recommendation System
This project aims to build a decently-accurate deep learning model, trained for recommending movies to customers. The project thus attempts to perform exploratory data analysis and build neural networks based on collaborative filtering and content-based filtering which are well-suited for the context. The study objective is to explore different techniques, examine the outcomes, and draw some conclusions.

The dataset, published on Kaggle, features over 20 Million ratings and free-text tagging activities from MovieLens. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995, and March 31, 2015. Users were selected at random for inclusion. All selected users had rated at least 20 movies. I believe this will ensure that the model is not biased.

### Results
```
--------------------------------------------------------
|            Model                       | HitRatio@10 |
|----------------------------------------|-------------|
| 3-layer model(without regularization)  |    0.524    |
|----------------------------------------|-------------|
| 3-layer model(with regularization)     |    0.57     |
|----------------------------------------|-------------|
| 4-layer model(without regularization)  |    0.59     |
--------------------------------------------------------
```

Overview: [Google Slides](https://docs.google.com/presentation/d/1W4Nlr6mGUWtmGRDXmf1XP5Wo8z4Zy3KsuhpVaxQmEoY/edit?usp=sharing)