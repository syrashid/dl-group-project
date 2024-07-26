## Team Name
Poster Toasters

## Project Title
Breaking Down the Movie Poster

## Project Summary
The current landscape of movie posters is saturated with similar looking posters and predictable layouts. This homogeneity leads to a form of decision fatigue when it comes to choosing a film. This project aims to dissect this phenomenon of repetitiveness by identifying commonly used features and patterns. By determining common designs and patterns, deep learning could be a tool to help generate novel poster features through breaking the current designs which in turn may appeal to movie goers. The shift wouldn't just be aesthetically pleasing, it could also be used as a marketing tool, and spark customers to select a movie based solely, or in part, on the poster design.

## What You Will Do (Approach)
The inital phase of our project will involve scraping large datasets of movie posters from the internet and performing appropriate preprocessing (removing duplicates, low quality, irrelevant images, etc). Using existing pre-trained architectures such as InceptionV3 and utilizing transfer learning from ImageNet key feature vectors can be extracted from the layers which can then be used to cluster the existing data, t-SNE may be applied to first reduce the dimensionality of the data for a visual inspection. With clusters in hand our experimentation can take a few interesting directions. Clusters can then be utilized to identify key patterns or features and determine how well they align to key attributes such as genre, year, ratings, etc. If time permits it'd be interesting to see if transformations of existing posters could be performed that would change our categorization or adversarial training could be introduced to determine how robust our model is to perturbations.

## Resources / Related Work & Papers
1. "EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks" by Tan and Le (2019) – A guide to efficient neural network architectures.
2. "Visualizing Data using t-SNE" by Maaten and Hinton (2008) – A foundational paper on t-SNE for dimensionality reduction.
3. "Deep Learning for Image Recognition" by Szegedy et al. (2016) – InceptionV3 architecture details.
4. "Movie Poster Analysis" by Nathan Rooy (2019) – Inspiration for this project.
5. "Density-Based Spatial Clustering of Applications with Noise (DBSCAN)" by Ester et al. (1996) – Clustering methodology.

## Datasets
We will use publicly available movie poster datasets such as those from IMDB or TMDB. These datasets contain a vast collection of posters that will be used for our analysis:
1. IMDB Dataset: [Link](https://developer.imdb.com/non-commercial-datasets/)
2. Kaggle Dataset: [Link](https://www.kaggle.com/datasets/rezaunderfit/48k-imdb-movies-with-posters)


## Team Members
- Vijayaragunathan, Yokesh Babu
- Vaidya, Omkar K
- Rashid, Syfuddin M

## Backup Dataset
1. Pre Labelled Movie Poster Dataset: [Link](https://www.cs.ccu.edu.tw/~wtchu/projects/MoviePoster/index.html)

