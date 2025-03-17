# Echoes-of-Art: Translating Audio into Art with Neural Style Transfer

## Project Overview

Echoes of Art is a creative project for IAT460 that transforms sound into visual art using Neural Style Transfer (NST). This project takes audio inputs (such as environmental noise, speech, music, etc.), converts them into spectrograms, and applies pre-trained deep learning models to generate unique images inspired by five famous paintings. The result is a visual representation of sound that project challenges how sound, which is traditionally viewed as an auditory sensation, can be reimagined in the visual sense.

## Features
- **Audio-to-Spectrogram Conversion**: The input audio is converted into a spectrogram, a visual representation of the sound frequencies.
- **Neural Style Transfer (NST)**: Using a selection of pre-trained NST models, the project merges the spectrogram with famous artistic styles, such as Impressionism, Cubism, and Abstract Expressionism.
- **Multiple Style Options**: Users can choose from several classical painting styles to apply to their spectrograms.

## Installation
## Requirements
- Python 3.x
- Pandas
- Numpy
- TensorFlow
- TensorFlow_hub
- PyTorch
- librosa (for audio processing)
- matplotlib (for visualization)
- Pillow
- Soundfile
- Requests
- Ipython

## Setup
1. **Clone the Repository**: To view or modify this project, clone the repository using Git:
   ```bash
   git clone https://github.com/Ry-an7/Echoes-of-Art
   ```
2. **Navigate to the Folder**: Once cloned, navigate to the project directory:
    ``` bash
    cd Ry-an7.github.io
    ```
3. **Install the required dependencies**: You can install all the necessary libraries by running:
    ``` bash
    pip install -r requirements.txt
    ```
Alternatively, if you're installing manually, run:
    ``` bash
    pip install matplotlib pandas numpy librosa pillow soundfile tensorflow tensorflow_hub requests ipython
    ```

## Acknowledgments
- **TensorFlow** and **PyTorch** for their powerful machine learning frameworks.
- **librosa** for audio processing and spectrogram generation.
- Pre-trained models for Neural Style Transfer.