# vowelRecognition_PTBR
This repository contains a template for recognizing vowels in the Brazilian Portuguese language

1 - Make sure you have Python installed.

2 - Clone this project with the command: ''git clone git@github.com:TemistoclesZwang/vowelRecognition_PTBR.git''

3 - To run microphoneTeste.py it is necessary to install Vosk, use the command ''pip install vosk'' (or pip3). Don't forget to check Vosk dependencies.

4 - Run the microphoneTest.py script

5 - Make sure your microphone is turned on and with the proper sensitivity. Speak some vowel into the microphone and wait for the result.

Attention: the recognition of the vowel ''O'' is not very accurate, as I used few data sources to train the model.

This project was made based on this excellent repository. If you want to create your own custom template, follow it:
https://github.com/falabrasil/kaldi-br

I also learned a lot from this repository. It's great for beginners.
https://github.com/matteo-39/vosk-build-model

Also check the official documentation
Kaldi: https://kaldi-asr.org/
Vosk: https://alphacephei.com/vosk/
