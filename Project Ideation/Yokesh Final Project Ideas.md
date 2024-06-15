# Final Project Ideas
- Identify the ingredients in a dish from a photo
  - [Link](https://towardsdatascience.com/this-ai-is-hungry-b2a8655528be)
- Visual Book Recommender
  - [Link](https://nathanrooy.github.io/posts/2023-04-12/visual-book-recommender/)
- Visual Similarities of Movie Posters
  - [Link](https://nathanrooy.github.io/posts/2019-03-24/movie-poster-tsne/)
- Physics for Birds
  - [Turing's Cake](https://www.youtube.com/watch?v=icQ_BTtNGEo) / [Virtual Pugs](https://www.youtube.com/watch?v=jM0p1JfjUq0)
- Music Genre Classification
- Sentiment Analysis on Movie Reviews
- Guess the plot from the movie poster / Genre Classification

---
<!-- Played around with GPT40 for a bit and some of the recommendations were quite solid. So I reckon we can also use that as a kick off point -->

# Project Idea 2: Music Genre Classification using Deep Learning

Team Name - TuneClassify

## Project Title
Music Genre Classification using Convolutional Neural Networks

## Project Summary
Music genre classification is an important task in music information retrieval, with applications in recommendation systems, music library organization, and more. The goal of this project is to develop a convolutional neural network (CNN) to classify music tracks into different genres based on their audio features. This project is interesting because it combines signal processing with deep learning to analyze and understand musical content.

## Approach
Our approach involves the following steps:

- Data Preparation: We will use the GTZAN dataset, which contains 1,000 music tracks from 10 genres. The audio data will be preprocessed into spectrograms for CNN input.
- Model Implementation: We will implement a CNN to classify the music genres. The model architecture will include convolutional layers for feature extraction and fully connected layers for classification.
- Training and Evaluation: We will train the model on the GTZAN dataset and evaluate its performance using metrics such as accuracy, precision, recall, and F1-score.
- Feature Engineering: We will explore various audio features, such as Mel-frequency cepstral coefficients (MFCCs) and chroma features, to improve model performance.
- Ethical Considerations: We will ensure that the dataset is used in compliance with any licensing agreements and respect the intellectual property of the music tracks.

## Resources / Related Work & Papers
The state-of-the-art for music genre classification includes various deep learning approaches. We will refer to the following resources:

- Choi, K., Fazekas, G., Sandler, M., & Cho, K. (2017). Convolutional Recurrent Neural Networks for Music Classification.
- Costa, Y. M. G., Oliveira, L. S., Silla, C. N., & Kaestner, C. A. A. (2017). An Evaluation of Convolutional Neural Networks for Music Classification Using Spectrograms.
- Humphrey, E. J., Bello, J. P., & LeCun, Y. (2012). Moving Beyond Feature Design: Deep Architectures and Automatic Feature Learning in Music Informatics.

## Datasets
We will use the GTZAN dataset for training and evaluation. This dataset includes 1,000 audio tracks categorized into 10 genres.

## Ethical Implications
We will ensure that the use of the music dataset complies with licensing terms and respect the intellectual property rights associated with the music tracks.