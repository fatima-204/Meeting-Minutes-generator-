# Meeting Minutes Generator

This repository contains a Jupyter Notebook (`Meeting_Minutes_product.ipynb`) that uses an API to convert audio files (e.g., `denver_extract.mp3`) into structured meeting minutes. The tool extracts key details such as attendees, agenda items, decisions, and action items, and formats them into a readable summary.

## Features

- **Audio to Text**: Converts audio files (e.g., `.mp3`) into text using an API.
- **Meeting Minutes Generation**: Processes the transcribed text to identify and organize key meeting details.
- **Easy to Use**: Simply upload your audio file and run the notebook to generate minutes.

## Usage

1. Upload your audio file (e.g., `denver_extract.mp3`) to the repository.
2. Open and run the `Meeting_Minutes_product.ipynb` notebook.
3. The tool will transcribe the audio and generate structured meeting minutes.

## Requirements

- Python 3.x
- API key (for the transcription service)
- Libraries: Install dependencies using `pip install -r requirements.txt`.

## Example

Input: `denver_extract.mp3`  
Output: Structured meeting minutes with attendees, agenda, decisions, and action items.
