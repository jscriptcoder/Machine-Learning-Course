# Week 9

## Anomaly Detection
Hello all! I hope everyone has been enjoying the course and learning a lot! This week, we will be covering anomaly detection which is widely used in fraud detection (e.g. ‘has this credit card been stolen?’). Given a large number of data points, we may sometimes want to figure out which ones vary significantly from the average. For example, in manufacturing, we may want to detect defects or anomalies. We show how a dataset can be modeled using a Gaussian distribution, and how the model can be used for anomaly detection.

We will also be covering recommender systems, which are used by companies like Amazon, Netflix and Apple to recommend products to their users. Recommender systems look at patterns of activities between different users and different products to produce these recommendations. In these lessons, we introduce recommender algorithms such as the collaborative filtering algorithm and low-rank matrix factorization.

As always, if you get stuck on the quiz and programming assignment, you should post on the Discussions to ask for help. (And if you finish early, I hope you'll go there to help your fellow classmates as well.)

### Density Estimation
- [x] [Problem Motivation](https://www.youtube.com/watch?v=086OcT-5DYI&index=88&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)
- [x] [Gaussian Distribution](https://www.youtube.com/watch?v=mh6rAYA0e7Q&index=89&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)
- [x] [Algorithm](https://www.youtube.com/watch?v=g2YBWQnqOpw&index=90&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)

### Building an Anomaly Detection System
- [x] [Developing and Evaluating an Anomaly Detection System](https://www.youtube.com/watch?v=8DfXJUDjx64&index=91&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)
- [x] [Anomaly Detection vs. Supervised Learning](https://www.youtube.com/watch?v=lCipWj-Cets&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=92)
- [x] [Choosing What Features to Use](https://www.youtube.com/watch?v=ZKaOfJIjMRg&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=93)

### Multivariate Gaussian Distribution (Optional)
- [x] [Multivariate Gaussian Distribution](https://www.youtube.com/watch?v=JjB58InuTqM&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=94)
- [x] [Anomaly Detection using the Multivariate Gaussian Distribution](https://www.youtube.com/watch?v=YRS-IB3vCow&index=95&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)

**Review**
- [Lecture Slides](lecture15.pdf)

**Quiz**
- [x] Anomaly Detection

## Recommender Systems
When you buy a product online, most websites automatically recommend other products that you may like. Recommender systems look at patterns of activities between different users and different products to produce these recommendations. In this module, we introduce recommender algorithms such as the collaborative filtering algorithm and low-rank matrix factorization.

### Predicting Movie Ratings
- [x] [Problem Formulation](https://www.youtube.com/watch?v=giIXNoiqO_U&index=96&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)
- [x] [Content Based Recommendations](https://www.youtube.com/watch?v=9siFuMMHNIA&index=97&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)

### Collaborative Filtering
- [x] [Collaborative Filtering](https://www.youtube.com/watch?v=9AP-DgFBNP4&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=98)
- [x] [Collaborative Filtering Algorithm](https://www.youtube.com/watch?v=YW2b8La2ICo&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=99)

### Low Rank Matrix Factorization
- [x] [Vectorization: Low Rank Matrix Factorization](https://www.youtube.com/watch?v=5R1xOJOFRzs&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=100)
- [x] [Implementational Detail: Mean Normalization](https://www.youtube.com/watch?v=Am9fhp2Q91o&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=101)

**Review**
- [Lecture Slides](lecture16.pdf)

**Quiz**
- [x] Recommender Systems

**Programming Assignment**
- [x] [Anomaly Detection and Recommender Systems](ex8)
