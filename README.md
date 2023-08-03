# Audio_translation
This code implements a speech-to-text and text-to-speech pipeline for translating English audio to Hindi audio. The pipeline consists of the following steps:

1. Preprocess the audio using Librosa.
2. Perform speech-to-text recognition using Wav2Vec2.
3. Translate the text to Hindi using Google Translate.
4. Generate Hindi audio using gTTS.
5. Convert the Hindi audio to MP3 using FFmpeg.


# Audio Processing with librosa

This repository contains code snippets and examples for audio processing using the `librosa` library in Python. The `librosa` library is widely used for analyzing, manipulating, and visualizing audio data.

## Features

- Loading and playing audio files
- Displaying waveforms and spectrograms
- Extracting mel spectrograms
- Converting power spectrograms to decibels (dB)

Instructions
To run the code, you will need to install the following Python packages:

librosa
soundfile
gtts
pydub
pyworld
torch
transformers
googletrans

## Installation

1. Clone the repository:
git clone https://github.com/Sana1228/Audio_translation.git

Install the required dependencies:
pip install -r requirements.txt


3. Run the code snippets in Jupyter Notebook, google collab or Python IDE.

## Usage

This repository provides code examples for various audio processing tasks using the `librosa` library. You can use these examples as a starting point for your own audio analysis projects. Modify and extend the code according to your requirements.

## Code Organization

- `audio_processing.ipynb`: Jupyter Notebook containing code snippets and examples.
- `requirements.txt`: List of Python dependencies required for running the code.

## Resources

- [librosa Documentation](https://librosa.org/doc/main/index.html): Official documentation for the librosa library.
- [librosa GitHub Repository](https://github.com/librosa/librosa): Source code and issues for the librosa library.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to use and contribute to this repository. If you encounter any issues or have suggestions for improvements, please create an issue or submit a pull request.

Author: Sana Simran

