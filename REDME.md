# Video to Text Transcription Script

This script extracts audio from a video file and transcribes it using two different speech recognition engines: PocketSphinx (offline) and Google Web Speech API (online).

## Features

- Extracts audio from video files.
- Transcribes audio using PocketSphinx for offline transcription.
- Transcribes audio using Google Web Speech API for online transcription.
- Handles errors and provides meaningful feedback.

## Requirements

Ensure you have the following packages installed:

- `moviepy`
- `speech_recognition`
- `pydub`
- `pocketsphinx`
- `ffmpeg` (for `moviepy` to handle audio and video files properly)

You can install these packages using `pip`:

```bash
pip install moviepy speechrecognition pydub pocketsphinx

git clone https://github.com/yourusername/videotranscription.git
cd videotranscription
pip install -r requirements.txt
python transcribe_video.py



PocketSphinx is installed correctly.
Video loaded successfully.
Audio extracted and saved to extracted_audio.wav.
Audio file loaded and recorded.
Transcription using Sphinx:  [Transcription Text]
Transcription using Google:  [Transcription Text]
Temporary audio file extracted_audio.wav deleted.
