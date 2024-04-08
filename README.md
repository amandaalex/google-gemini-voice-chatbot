# Voice Assistant Utilizing Google Gemini

This repository houses an advanced voice assistant developed using Google's cutting-edge Gemini Pro AI model and Python. It is designed to interface seamlessly with the Google Gemini Pro API, enabling it to process any user request. Upon receiving a request, the system generates a textual response, which is then converted into spoken audio, providing an interactive voice-based user experience.

## Prerequisites

Before proceeding with the deployment of this voice assistant on your local machine, it is essential to ensure that the necessary dependencies are installed. These dependencies include various packages critical for the operation of the voice assistant, such as libraries for AI communication, speech recognition, text-to-speech conversion, and audio handling.

Execute the following commands in your terminal to install the required packages:

```console
pip install -q -U google-generativeai
pip install speechrecognition openai pyttsx3 pyaudio pygame
```

For users operating on Python version 3.12 or later, the installation of the "setuptools" package is also required. This can be done using the command below:

```console
pip install setuptools
```

Please ensure that all installations are complete before attempting to run the voice assistant on your system.
