Desktop Voice Assistant using Python
Overview

This project is a Python-based Desktop Voice Assistant that can listen to user voice commands, process them using speech recognition, and respond through text-to-speech. The assistant can perform various tasks such as telling the current time and date, searching Wikipedia, playing songs on YouTube, and opening system applications like Notepad, Calculator, File Explorer, and browser.

The project demonstrates practical use of Speech Recognition, Text-to-Speech (TTS), system automation, and API integration, making it suitable for beginners and intermediate Python learners.

Features

Voice-based interaction using microphone

Text-to-speech responses

Greets the user based on time of day

Tells current time and date

Searches and summarizes results from Wikipedia

Plays songs on YouTube

Opens system applications:

Notepad

File Explorer (Downloads)

Google Chrome

Calculator

Command Prompt

Graceful exit using voice command

Technologies Used

Python 3

SpeechRecognition – for voice input

pyttsx3 – for text-to-speech output

PyAudio – for microphone access

Wikipedia API – for information retrieval

PyWhatKit – for playing YouTube videos

OS module – for system-level commands

Datetime module – for date and time operations

Project Structure
Desktop-Voice-Assistant/
│
├── desktop_assistant.ipynb   # Main Jupyter Notebook
├── README.md                 # Project documentation
└── requirements.txt          # Required Python libraries (optional)

Installation and Setup
1. Clone the Repository
git clone https://github.com/your-username/desktop-voice-assistant.git
cd desktop-voice-assistant

2. Create Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate   # For Windows

3. Install Required Libraries
pip install pyttsx3
pip install SpeechRecognition
pip install pyaudio
pip install wikipedia
pip install pywhatkit


Note:
If pyaudio installation fails on Windows, install the appropriate .whl file from:
https://www.lfd.uci.edu/~gohlke/pythonlibs/

How to Run the Project

Open Jupyter Notebook

jupyter notebook


Open desktop_assistant.ipynb

Run all cells

Speak commands clearly into the microphone

Supported Voice Commands
Command Example	Action
“What is the time”	Tells current time
“What is the date”	Tells today’s date
“Search for MS Dhoni”	Wikipedia search
“Play song name”	Plays song on YouTube
“Open notepad”	Opens Notepad
“Open downloads”	Opens Downloads folder
“Open calculator”	Opens Calculator
“Stop” / “Exit”	Closes the assistant
Sample Output
Listening...
Recognizing...
You said: search for Python
According to Wikipedia: Python is a high-level programming language...

Limitations

Requires active internet connection for Wikipedia and YouTube

Speech recognition accuracy depends on microphone quality

System commands are currently optimized for Windows OS

Future Enhancements

Add GUI using Tkinter or PyQt

Integrate chatbot responses using NLP models

Add weather and news APIs

Improve error handling and command accuracy

Learning Outcomes

Hands-on experience with speech recognition

Understanding TTS engines in Python

Real-world automation using Python

Working with third-party APIs

Author

Abhishek Sharma
Computer Science Engineering
Desktop Voice Assistant Project
