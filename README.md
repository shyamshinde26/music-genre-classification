### Project Overview

 This dataset is previously in the audio format .au. I have extracted the features from audio files and taken the mean of each feature. Using these I classified the data in various Music genres. These are the features extracted from the .au files.
Feature	                                        Description
chroma_stft  	                  Frequency of sound
spectral_centroid	           Keys which represents the note
spectral_bandwidth	         Bandwidth of the sound
rolloff	                           Measures the shape of the signal
zero-crossing rate	   Represents that where the waveform crosses zero
mfcc	                           short term power of the spectrum 


### Learnings from the project

 After completing this project, I have a better understanding of working on any audio data. In this project, I applied the following concepts.

Train-test split
Ensemble models
Logistic Regression
StandardScaler
visualisations


### Approach taken to solve the problem

 Here I am using various classification algorithms and checking which algorithm has the best accuracy score. To improve the performance of the model I have applied ensemble methods bagging and voting classifier.


