# Music-Composition-with-LSTM
This project is inspired by this article: [Generate music with an RNN](https://www.tensorflow.org/tutorials/audio/music_generation)

You can find the [code](https://colab.research.google.com/drive/1Cg4hS01TPFtRbYKLJ26gioNBUU5rZQYA?usp=sharing) on Google Colab.

This is a Tensorflow implementation.

## Requirements
- fluidsynth
- pretty_midi
- pandas
- tensorflow
- glob

## Our Model's Architecture

![2](https://user-images.githubusercontent.com/29801160/146526262-8a728891-cfbe-4095-bf50-9b9afe21954e.jpg)

## Metrics

### The Loss

![3](https://user-images.githubusercontent.com/29801160/146526364-065f27da-48ad-4952-bdbb-6aed3fafd0cc.jpg)

### The Perplexity

![4](https://user-images.githubusercontent.com/29801160/146526397-03c4cf44-d1b7-49e8-9b0f-585d5fc31648.jpg)

### The Histogram of 120 Generated Notes

![5](https://user-images.githubusercontent.com/29801160/146526602-d7ce425f-04c4-496a-89e0-8f0beae3acd2.jpg)

### References:
- [Generate music with an RNN](https://www.tensorflow.org/tutorials/audio/music_generation)
