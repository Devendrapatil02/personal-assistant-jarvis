
# Personal Assistant-JARVIS

The provided Python script is a basic implementation of a voice-controlled virtual assistant called "Jarvis." It uses various libraries to perform tasks like speech recognition, text-to-speech conversion, web browsing, and sending emails.


## Installation

Before running the program, make sure you have the required Python packages installed. Open your terminal or command prompt and run the following commands:

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia

```
Ensure that you have also installed the required dependencies for pyaudio. You may need to install additional libraries or executables depending on your operating system. Refer to the PyAudio installation guide for more details.


## SetUp
This script uses a custom voice located at 'D:\my stuff\custom_voice.wav'. Make sure that the file path is your own selected, and the file exists. If you don't have a custom voice, you can use the default voice by initializing 'pyttsx3' with 'pyttsx3.init()' instead of 'pyttsx3.init('sapi5')'.

Replace Email Credentials:
In the sendEmail function, replace 'youremail@gmail.com' and 'your-password' with your actual Gmail email address and its password. Be cautious about storing passwords in code; it's generally better to use more secure methods like environment variables.
## Running Tests

To run tests, run the following command

```bash
 python jarvis.py
```
The program will start, and you'll see the "Listening..." message. Speak a command, and Jarvis will respond accordingly.

