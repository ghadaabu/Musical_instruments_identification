# Musical_instruments_identification

Project by: 
Elias Assaf & Ghada Abu Elzalaf

## Introduction:

In the field of music information retrieval (MIR), recognizing the musical instruments played within an audio clip is crucial. It enables music search by specific instruments, computes the similarity between compositions and helps recognize musical genres. <br>
In our project we propose 3 different neural network architectures to solve the task, each with it's own properties, CNN's that extract high level features of the input, RNN's that consider temporal properties of the input, and finally using attention models so we can set the model to focus on specific parts of the input, they are trained with single instrument audio clips and tested with polyphonic music with several instruments. <br>
The data is given in a .wav format which are uncompressed waveforms of the signal that come in 2 channels (stereo), in the project we will explore different transformations to apply on the data such as the stft and mel-spectrogram, to get the best possible output results.

## Data set

IRMAS dataset which includes musical audio files with metadata files that describe the prominent instrument in each
recording.

https://www.upf.edu/web/mtg/irmas

