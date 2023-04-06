# Automatic Speech Recognition

## Introduction

This Jupyter Notebook implements an end-to-end Speech-to-Text application using the Whisper Model and Gradio. The application takes an audio file as input[using the microphone, make sure to give permissions], converts the speech to text using the Whisper Model, and displays the transcribed text in the UI.

## ASR meaning

ASR stands for Automatic Speech Recognition. It is a technology that allows computers to understand human speech and convert it into text. ASR systems have numerous applications, such as voice-controlled assistants, speech-to-text transcription, and closed-captioning of audio and video content.

## Whisper Model
The Whisper Model is a state-of-the-art deep neural network model designed for Automatic Speech Recognition (ASR). It uses a hybrid architecture that combines convolutional and recurrent neural networks to achieve high accuracy on various speech recognition tasks. The model is trained on large datasets of speech recordings, and it has been shown to outperform many other ASR models on standard benchmarks.

## Gradio
Gradio is a web-based tool that allows developers to quickly create and deploy machine learning models with simple, customizable UI components. It is a great way to build an interactive and user-friendly interface for machine learning models.

## End-to-end Gradio Application for ASR
This notebook implements an end-to-end ASR application using the Whisper Model and Gradio. The application can be run locally or on Google Colab.

## How to run the application on Google Colab
### To run the application on Google Colab, follow these steps:

1. Open the ASR_with_Whisper.ipynb file in Google Colab.
2. Click on the Runtime menu and select Run all.
3. After the code execution is completed, scroll down to the last cell and click on the Gradio interface link.
4. In the interface, you can record using microphone, adjust the sampling rate and language model used by the Whisper Model, and see the transcribed text.

## How to run the application locally
### To run the application locally, follow these steps:

1. Clone the repository

``` git clone https://github.com/pratyushlohumi26/Automatic_Speech_Recognition.git ```

2. Install the required packages.

``` pip install -r requirements.txt ```

3. Run the Jupyter Notebook.

``` jupyter lab --allow-root --ip=0.0.0.0 ```

4. Open the ASR_with_Whisper.ipynb file and run the cells.

5. Go to ``` http://localhost:7860/ ``` in your web browser to interact with the Gradio interface.

6. The Gradio interface allows you to use the microphone from the computer and see the transcribed text. You can also adjust the sampling rate and language model used by the Whisper Model to experiment with different settings.

This application can be easily extended to work with live audio input, multiple audio files, and more advanced features. With Gradio, it's easy to build a simple and intuitive UI for ASR applications.

## Conclusion

This notebook implements an end-to-end ASR application using the Whisper Model and Gradio. The Whisper Model is a state-of-the-art ASR model that achieves high accuracy on various speech recognition tasks. Gradio is a powerful tool for building interactive machine learning applications. By combining these technologies, we can build a powerful and user-friendly ASR system.
