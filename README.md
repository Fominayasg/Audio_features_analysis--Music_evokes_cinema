# Music evokes cinema(audio features analysis)
#### *Can we use ML to predict what music make us feel??*

![portada](/img/guitars-gb190c7313_1920.jpeg)

This project has been developed in the context of Ironhack's data analysis bootcamp, and selected for the Hackshow event organized by Ironhack.

## Context

Movie soundtracks are one of the most important cinematographic resources to induce the viewers to an specific emotion and feel more involved in the movie. The rhythm, the percussion, the tensions marked by different groups of chords and many other resources that are used in musical composition, inevitably lead us to perceive different sensations.

But in the end, music is just an audio wave that physically stimulates our ears, which send a signal to the brain where it is interpreted. 

The process is not very different when we use a computer, the same wave with its intrinsic characteristics can be transformed into data. The question is, can we figure out the emotion that a song conveys (regardless of the lyrics) by analyzing the physical characteristics of the wave?

## Project objectives

The main goal of this project is to **clasify** different instrumental pieces onto 5 cinematographic genres.


## Repository structure

The repository is constructed in such a way that the complete process can be followed using the numbered notebooks in the main folder:

1. Data analysis: Transformation and resampling of the data. Feature extraction and feature transformation.
1. Model training: Neural network building and evaluation.
1. Final model: Final model training using the settings that gave the best performance.Exporting model to a file.
1. Cinema genre prediction: Demonstration of the model performance with new audio tracks.


# Data

All the data has been included on the .gitignore due to size restrictions in github.



## Technology Stack

- [Pandas](https://pandas.pydata.org/docs/)
- [Librosa](https://librosa.org/doc/latest/index.html) *(Audio analysis)*
- [Tensorflow & Keras](https://www.tensorflow.org/)
- [Numpy](https://numpy.org/)
- [Scipy](https://www.scipy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Sklearn](https://scikit-learn.org/)