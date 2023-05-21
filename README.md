# Text to Speech Converter and PDF Reader

This is a mini-project that includes a Text to Speech Converter and a PDF Reader implemented using Python and the tkinter library for the graphical user interface. The project allows users to convert text into speech and read PDF files.

## Features

1. **Text to Speech Converter**: Converts the entered text into speech.

2. **PDF Reader**: Reads the contents of a selected PDF file.

## Dependencies

The following dependencies are required to run the project:

- tkinter: Python's standard GUI library.
- PIL (Python Imaging Library): Used for image processing and displaying images.
- gtts: Google Text-to-Speech library for converting text to speech.
- playsound: Used to play the generated speech as an audio file.
- datetime: Used to generate a timestamp for the audio file name.
- PyPDF2: Library for reading PDF files.
- pyttsx3: Library for text-to-speech conversion.

You can install these dependencies using pip:

```
pip install tkinter pillow gtts playsound PyPDF2 pyttsx3
```

## How to Use

1. Clone the repository or download the project files.

2. Make sure you have all the dependencies installed.

3. Run the `tts.py` file.

4. The application window will open, displaying the main screen with the GLBITM logo.

5. Click the "Next ->" button to go to the main menu.

6. In the main menu, you can choose between the Text to Speech Converter and the PDF Reader.

7. **Text to Speech Converter**: Enter the text you want to convert into speech, and click the "->" button. The text will be converted to speech, and the generated audio will be played.

8. **PDF Reader**: Enter the path of the PDF file you want to read, and click the "->" button. The application will extract the text from the PDF file and read it aloud.

9. Use the "Back" button to navigate back to the previous screens.
