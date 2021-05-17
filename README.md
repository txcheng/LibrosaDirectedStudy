# LibrosaDirectedStudy

Hi! This was a small project conducted to explore some Librosa library functions as well as study modelling using TensorFlow.

Here are the steps for setup:
1. Install Python 3.X
2. Install Jupyter, Tensorflow, Sklearn, Librosa, matplotlib.pyplot and ffmpeg
    - On a Mac, you can use a combination of brew and pip to install these libraries
    - On a Windows machine, you can use pip and chocolatey
3. Download the fma_small dataset from here: https://github.com/mdeff/fma
4. Unzip the fma_small.zip folder in the repository
5. Start with Librosa exploration, then proceed to Dataset exploration, then finish with Model Exploration notebook.

The goal of the model is to take in audio as a time series and generate a unique fingerprint. This fingerprint could be used in future work to quickly identify the name of the song - just like Shazam.