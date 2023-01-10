# Music genre prediction

Analysis & Model creation by Nazanin(Naz) Faghih Mirzaei

The dataset for this project was obtained from kaggle : 
https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre


The work is structured into several parts:
* Description of the dataset, Goal of the project and the Questions we are trying to answer
* Preprocessing of the dataset
* Vizualization of the dataset after cleaning
* Creation, Fine-tuning metaparameters and result of 3 different models


## Summary of dataseet

This dataset consists of 18 columns. The target attribute for us is the music genre, there are 17 other attributes that describes properties of each song. 

Goal : We will use machine leearning techniques to predict the geenre of a song based on other attributes exist in the dataset. 


### Some of the important Columns

* *instance_id*: id of the track

* *artist_name*: name of the artist

* *track_name*: name of the track

* *popularity*: how popular a song is on a scale of 0 (least popular) to 100(most popular).

* *acousticness*: how acoustic a song is on a scale of 0 (low confidence) to 1.0(high confidence).

* *danceability*: how suitable a song is for dancing on a scale of 0 (least danceable) to 1.0(most danceable).

* *duration_ms*: track length (milliseconds)

* *energy*: how intense and active a song is on a scale of 0 (low) to 1.0(high).

* *instrumentalness*: how vocal a song is on a scale of 0 (low) to 1.0(high).

* *key*: the key the track is in. If the key was not detected, the value is -1


* *liveness*: On a scale of 0 to 1 how likely it is that there is audience in the song. (0.8 or higher it is a live recording)

* *loudness*: How loud it is (in DB)

* *mode*: Whether the song is Major(1) or Minor(0).

* *tempo*: estimated tempo of a track in beats per minute (BPM). 

