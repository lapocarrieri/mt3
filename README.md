# MT3: Project of Neural Network for Sapienza based on Multi-Task Multitrack Music Transcription

MT3 is a multi-instrument automatic music transcription model that uses the [T5X framework](https://github.com/google-research/t5x).



## Transcribe your own audio
The project is composed by two parts: “Music Transcription with Transformers” (https://colab.research.google.com/drive/1FIN5JHnhsLPHg6AKSu9nDPWMGdxQc5Rw#scrollTo=ibSG_uu0QXgc) and “Filtering to solo piano music” (https://colab.research.google.com/drive/1CttbvcTIONMEKc77vIV2kXa8OHGDMXhZ#scrollTo=W7B3FmBaqkGu).
The second one is used to create a colab notebook that can transform in MIDI file also songs with other instruments. This file download in the PC every possible song from the web, in particular it supports youtube. Then the downloaded mp3 file can be used to be tested in “Music Transcription with Transformers in order to get the MIDI transcription.

## Project

We don't touch the code but we simply add comments and reshape the colab notebook.
Is there the possibility to train the model but since it is a transformer, 
trying we found that it took more powerful computers and a lot of time
