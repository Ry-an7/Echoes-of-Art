# Echoes-of-Art: Translating Audio into Art with Neural Style Transfer

## Project Overview

Echoes of Art is a creative AI project for IAT460 that transforms sound into visual art using Neural Style Transfer (NST). This project takes audio inputs (such as environmental noise, speech, music, etc.), converts them into spectrograms, and applies pre-trained deep learning models to generate unique images inspired by five famous paintings. The result is a visual representation of sound that project challenges how sound, which is traditionally viewed as an auditory sensation, can be reimagined in the visual sense.

## Features
- **Audio-to-Spectrogram Conversion**: The input audio is converted into a spectrogram, a visual representation of the sound frequencies.
- **Neural Style Transfer (NST)**: Using a pre-trained NST model, the project transforms audio spectrogram into artworks styled after famous paintings, such as Vincent van Gogh's *The Starry Night* or Hokusai *The Great Wave off Kanagawa*.
- **Multiple Style Options**: Users can choose from five classical painting to style their spectrogram after.

## Installation
## Requirements
- Python 3.x
- gradio (for the web interface)
- librosa + soundfile (for audio processing)
- matplotlib (for spectrogram visualization)
- numpy (numerical operations)
- Pillow (image handling)
- tensorflow + tensorflow-hub (style transfer model)

## Setup
1. **Clone the Repository**: To view or modify this project, clone the repository using Git:
   ```bash
   git clone https://github.com/Ry-an7/Echoes-of-Art
   cd Echoes-of-Art
   ```
2. **Install the required dependencies**: You can install all the necessary libraries by running:
    ``` bash
    pip install -r requirements.txt
    ```
    Alternatively, if you're installing manually, run:
    ``` bash
    pip install matplotlib pandas numpy librosa pillow soundfile tensorflow tensorflow_hub requests ipywidgets ipython
    ```
## Usage
1. **Record or Upload Your Audio**<br>
     You can either upload an audio file or record directly using your microphone in the provided Gradio interface.
   - **To upload an audio file:**<br>
     Click on the "Upload Audio" tab and select the file you want to use. The supported file types are audio files (e.g., .mp3, .wav).
   - **To record audio using the microphone:**<br>
     Click on the "Record Audio" tab, and press the "Record" button to record your audio.<br>
     **Note:** Make sure to **allow the browser** to access your microphone when prompted in order to record audio.
2. **Generate the Spectrogram**<br>    
    - After uploading or recording your audio, click the "Generate from Upload/Recording" button and view the spectrogram on the right.
3. **Place Your Audio File in the Provided Folder**<br>
     Upload your audio file to the `Audio/` directory, if you're running the code in Colab, make sure to adjust the path to where the file is located.
4. **Update the File Path in the Code**<br>
      To match the file you uploaded, update the following line in the code:
      ``` bash
          audio_files = glob('Desktop/Audio/Street-Sounds.mp3')
      ```
      Replace `'Street-Sounds.mp3'` with the name of the file you uploaded.
5. **Run the Code**<br>
     Now, you can run the rest of the code to process the audio and generate the corresponding spectrogram and art using Neural Style Transfer.
