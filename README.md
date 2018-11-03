# DNN Speech Recognizer
A deep neural network that functions as part of an end-to-end automatic speech recognition pipeline

This project builds deep neural network that functions as part of an end-to-end automatic speech recognition pipeline.

This has been achieved in 3 broad steps

1. Pre-processing to convert raw audio to one of two feature representations that are commonly used for automatic speech recognition.
2. An acoustic model that accepts audio features as input and returns a probability distribution over all potential transcriptions.
3. A pipeline that takes the output from the acoustic model and returns a predicted transcription.

## Models
Following models have been tried, each with varying degrees of success
1. RNN
2. RNN + TimeDistributed Dense
3. CNN + RNN + TimeDistributed Dense
4. Deeper RNN + TimeDistributed Dense
5. Bidirectional RNN + TimeDistributed Dense
6. CNN + Deep Bidirectional RNN + TimeDistributed Dense

