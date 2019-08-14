# DeepSpeech Fastai

DeepSpeech Fastai is an attempt to implement [DeepSpeech](http://arxiv.org/abs/1412.5567) using the [Fastai_Audio Library](https://github.com/mogwai/fastai_audio). 

The data used for this project is [Mozilla's Common Voice](https://voice.mozilla.org/en/datasets) and contains 780 hours of validated Speech to Text in English. 

To start, download Common Voice and extract Common Voice to the data directory.  

The other thing that is required for this is to create a symbolic link (`ln -s`) that links the audio folder from Fastai_Audio into the fastai core library.  

This is all that should be required to begin working with this notebook!