## Team Name
PosterVision (Temporary Name)

## Project Title
Visual Similarities of Movie Posters (Temporary Title)

## Project Summary
The current landscape of movie posters is saturated with similar looking posters and predictable layouts. This homogeneity leads to a form of decision fatigue when it comes to choosing a film. This project aims to dissect this phenomenon of repetitiveness by identifying overused features and patterns. By filtering out predictive designs, deep learning could be a tool to identify novel poster features which may appeal to movie goers. The shift wouldn't just be aesthetically pleasing, it could also be used as a marketing tool, and spark customers to select a movie based solely, or in part, on the poster design. 

## What You Will Do (Approach)
We will start by scraping a large dataset of movie posters from the internet, removing duplicates and irrelevant images. Using a pre-trained InceptionV3 model, we will extract feature vectors for each poster. These vectors will be reduced using t-SNE to visualize the high-dimensional data in a 2D space. We will then apply DBSCAN to cluster the posters based on visual similarity. To proceed further than our inspiration, we'll then implement further classifications and predictions on the clustered data such as Genre, Year, Ratings, etc. Our implementation will include preprocessing, feature extraction, dimensionality reduction, clustering, and visualization, ensuring thorough analysis and optimization at each step.

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
