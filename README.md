# Transer
Transer extracts audio from video files, transcribes and translates the text into your desired language, and converts it back into an audio file. Seamlessly transform multimedia content with multilingual support.

## Features
* Audio Extraction: Extract audio from video files using moviepy.
* Speech-to-Text: Convert audio to text with openai-whisper.
* Text Translation: Translate the transcribed text using googletrans==4.0.0-rc1.
* Text-to-Speech: Convert the translated text back into audio with gtts.
## Libraries Used
* moviepy: A Python library for video editing, used here for audio extraction.
* openai-whisper: An automatic speech recognition (ASR) model for converting speech to text.
* googletrans==4.0.0-rc1: A Python wrapper for Google Translate API, used for translating text.
* gtts: Google Text-to-Speech, used for converting translated text back into audio.
#### Transer Does not have a UI, this repository only includes its base functionalities defined above.
