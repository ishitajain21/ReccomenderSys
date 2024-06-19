
# Content-Based Music Recommender System

This project implements a content-based recommender system for Spotify music tracks using Linear Algebra techniques, specifically Singular Value Decomposition (SVD) and Principal Component Analysis (PCA). The system analyzes a dataset of 300 Spotify songs and provides personalized song recommendations based on their audio features.

## Overview

The goal of this project is to develop a recommender system that suggests similar songs to users based on the audio characteristics of the songs they enjoy. The following tasks were accomplished:

1. Preprocessed a dataset of 300 Spotify songs, consisting of 14 audio features such as danceability, energy, and tempo.
2. Applied SVD to reduce the dimensionality of the dataset from 14 columns to 10 principal components.
3. Computed the top 3 song recommendations for each song in the dataset using the reduced principal components and cosine similarity.

The dataset is sourced from [here]( https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset). 
## Installation

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo/music-recommender.git`
2. Ensure you have standard Data Science and Machine Learning libraries downloaded.
3. Run PCA.ipynb. This will create pca_data.csv, where the reduced data will be.
4. Next run SVD_Recomender.ipynb. It is reccomended to use a small subset of the data imported from (3) as SVD takes a long time to compute.
5. At the bottom of the file, the parameter id of function find_reccs is the row of the song you are trying to find reccomendations for.
6. Finally, the reccomendations are the bottom of the file. 
=
## Further Ideas
1. Implement accuracy measure for reccomender system. Perhaps benchmark against existing reccomender systems?
2. Develop UI for reccomender system

## Contributing

This project was created by Ishita Jain and Sadhvi Narayanan. Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to thank our instructors and peers for their guidance and support throughout this project.
