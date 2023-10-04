# Voice2Summary

This repository contains Python code for audio-to-text transcription using AssemblyAI and text summarization using Transformers. It allows you to transcribe audio files and generate concise text summaries.

## Usage

1. Clone the repository to your local machine:

   ``` 
   git clone https://github.com/alimirash/Voice2Summary.git
   ```

Install the required libraries using pip:
``` 
pip install assemblyai transformers
```
Replace "YOUR_ASSEMBLYAI_API_KEY" with your AssemblyAI API key in the Python script.

Specify the URL of the audio file you want to transcribe in the FILE_URL variable.

Run the Python script:
```
python transcribe_and_summarize.py
```
The transcribed text and summary will be displayed in the console.

Feel free to customize and adapt the code to suit your specific audio transcription and summarization needs.

## Dependencies

- [AssemblyAI](https://www.assemblyai.com/): Used for audio-to-text transcription.
- [Transformers](https://huggingface.co/transformers/): Used for text summarization.


