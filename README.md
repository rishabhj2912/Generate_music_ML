# SMAI

## Generating music with Machine Learning

### Objective


`The objective of our project is to generate music using machine learning models. Some known models which can be applied to generate music are vanilla neural network, an LSTM RNN, and an encoder-decoder model.`

### Motivation

` To test how successful the music generation is from the neural networks, we will evaluate the prediction of the next note against the actual next note as a percentage score.`

 - **Chords** : `A chord is a grouping of two or more notes.`

- **Octave** : `In a piano, the space between two notes is expressed as an octave. Particularly, it is the space between the two notes that begin with the same letter.`


### Datasets 

`MIDI ﬁles of some piano music composers are used as dataset.`

` Some composer used are :-`

1. Chaplin 
2. Burg
3. Elise
4. Schubert
5. Pathetique
6. Mond
7. Waldstein

![alt](./Beethoven%20image.png)
![alt](./LSTM%20Model%20data.png)

### Approaches to Automatic Music Generation

1. **LSTM RNN**
```
A form of RNN (Recurrent Neural Network), Long Short Term Memory (LSTM), resolves some
situations where RNN failed. RNN networks keep data from past output in a memory for a very
little amount of time, while LSTM networks solve the long-term reliance problem of RNNs.

```
![alt](./LSTM%20RNN.png)


2. **Wavenet**

```
WaveNet is a deep-learning based generative model developed by Google DeepMind. The main
goal of the WaveNet is to generate new samples from the original distribution of data, hence the
name generative model. We will use this model as inspiration, generating a CNN based model of
our own.

```

### Result
`In conclusion, among the algorithms that we tried, the wavenet model performed the best.`