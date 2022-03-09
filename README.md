# Welcome to the DQW Audio app repository! 🎶

This repo contains the DQW Audio streamlit app code, however, the streamlit apps have been split into 5 for maintenance purposes:

- [Main Streamlit app 📊](https://share.streamlit.io/soft-nougat/dqw-ivves/app.py)
- [Tabular Data Section 🏗️](https://share.streamlit.io/soft-nougat/dqw-ivves_structured/main/app.py)
- [Audio Data Section 🎶](https://share.streamlit.io/soft-nougat/dqw-ivves_audio/main/app.py)
- [Text Data Section 📚](https://share.streamlit.io/soft-nougat/dqw-ivves_text/main/app.py)
- [Image Data Section 🖼️](https://share.streamlit.io/soft-nougat/dqw-ivves_images/main/app.py)

The packages used in the application are in the table below.

| App section                |     Description    |     Visualisation    |     Selection    |     Package             |
|----------------------------|--------------------|----------------------|------------------|-------------------------|
|     Audio                  |          x         |           x          |                  |     [dtw](https://github.com/pierre-rouanet/dtw)                 |
|     Audio                  |                    |                      |         x        |     [audiomentations](https://github.com/iver56/audiomentations)     |
|     Audio                  |          x         |           x          |                  |     [AudioAnalyser](https://github.com/QED0711/audio_analyzer)       |
| 

## Unstructured data - audio

Key points addressed:
- Provide EDA of audio files
- Augment audio files to showcase methods of increasing robustness of the audio dataset
- Provide methods of comparison of two files

To complete the key points, the following subsections are created:
- One file EDA with librosa
- One file augmentation with audiomentations
- Two file comparison with DTW
- Two file comparsion with audio_compare method

## How to run locally

1.	Installation process:

    Create virtual environment and activate it - https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
    
    Clone or download files from this repo
    
    Run pip install -r requirements.txt
    
    Run streamlit app.py to launch app

2.	Software dependencies:

    In requirements.txt

3.	Latest releases

    Use app.py