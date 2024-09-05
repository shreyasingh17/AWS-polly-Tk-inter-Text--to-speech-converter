# T2S-Con Amazon Polly

T2S-Con Amazon Polly is a simple GUI-based text-to-speech application built with Python's `tkinter` for the user interface and `boto3` to interact with Amazon Polly for text-to-speech conversion. Users can input text, and the app will convert it to speech using Amazon Polly's neural voice synthesis and save it as an MP3 file.

## Features

- **Text Input**: Users can enter text via the `tkinter` GUI.
- **Text-to-Speech**: Converts the input text to speech using Amazon Polly.
- **MP3 Output**: The synthesized speech is saved as an MP3 file.
- **Play Audio**: Automatically plays the audio after synthesis (Windows only).

## Requirements

- Python 3.x
- `boto3` (Amazon Web Services SDK for Python)
- AWS Account with access to Amazon Polly
- `tkinter` (comes pre-installed with most Python distributions)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/T2S-Con-Amazon-Polly.git
2. Navigate to the project directory:
    ```bash
   cd T2S-Con-Amazon-Polly
3. Install the required dependencies:
    ```bash
    pip install boto3
4. Set up AWS credentials:

   Create an AWS user with access to Amazon Polly via the IAM console.
   Ensure you have the correct profile set up, e.g., demo_user.
   Configure your AWS credentials by running:
   ```bash
   aws configure
## Usage
Run the Python script:

 ```bash
python t2s_con_amazon_polly.py

->In the GUI window, enter the text you want to convert to speech.

->Click the ReadIt button. The application will generate speech using Amazon Polly and save it as an MP3 file.

->If you're on Windows, the MP3 file will automatically play after synthesis.
   
   

