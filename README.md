# Legolas Desktop Assistant
##### Legolas is a Python-based voice assistant designed to perform a variety of desktop tasks using voice commands. It leverages speech recognition, text-to-speech, and multiple external APIs to provide real-time information and control over your system. Whether you need to fetch the latest weather, play music, search Wikipedia, or even control system applications, Legolas is here to help.

- **"Speech Recognition"**: Uses the Google Speech Recognition API (via the SpeechRecognition library) to convert spoken commands into text.
- **"Text-to-Speech"**: Utilizes Pyttsx3 for offline speech synthesis, providing immediate audio feedback.
- **Weather Updates"**: Retrieves current weather details (temperature, condition, humidity, wind speed) for a specified city using the OpenWeatherMap API.
- **"Music Control"**:
-**"Play Music"**: Plays all MP3 files from a designated music directory.
- **"Stop Music"**: Attempts to stop music playback by closing the active media player window.
- **"News Headlines"**: Fetches top headlines from TechCrunch using NewsAPI.
- **"Wikipedia Search"**: Retrieves concise information on a queried topic from Wikipedia.
- **"Web & Application Controls"**: Opens websites (e.g., YouTube, Google, Facebook, StackOverflow) and system applications (Notepad, Adobe Acrobat, Command Prompt, Calculator) directly via voice commands.
- **"Timer & System Commands"**:
- **"Set Timer"**: Sets a timer (with minutes or seconds as the unit) and alerts the user when time is up.
- **"System Controls"**: Allows for shutting down, restarting, or putting the system to sleep.

  #Legolas In Action 

1> Playing Music

![Screenshot 2025-03-12 140733](https://github.com/user-attachments/assets/6af69588-3e35-4c83-89b3-8b98492da457)

2> Searching Information through Web-browser

![Screenshot 2025-03-11 200402](https://github.com/user-attachments/assets/ae3eaf1d-7cd7-4383-bf61-510346e621fa)

3> Fetching Weather Updates using API :

![Screenshot 2025-03-11 195900](https://github.com/user-attachments/assets/1397044b-9cb0-4e6d-ac12-90ab6c6b2768)

4> Performing System Opeartions.

![Screenshot 2025-03-11 195435](https://github.com/user-attachments/assets/2f836f17-7969-4286-b57f-5c75b7b011de)


## Installation
#### Clone the Repository:
```git clone https://github.com/yourusername/legolas-desktop-assistant.git```
```cd legolas-desktop-assistant```

#### Set Up a Virtual Environment (Optional but Recommended):
```python -m venv venv```
```source venv/bin/activate   # On Windows: venv\Scripts\activate```

#### Install Dependencies: Install the required Python packages:
```pip install pyttsx3 SpeechRecognition wikipedia pywhatkit pyjokes requests pyautogui opencv-python```
You may also need to install additional packages (such as those for handling emails) if not already available.

#### Usage
Run the Assistant: Start the assistant by executing:
```python Legolas_VA.py```

#### Interact via Voice Commands:
Greeting: Legolas will greet you based on the current time.
Example Commands:
- **"Open notepad"** – Launches Notepad.
- **"Play music"** – Plays all MP3 files from your music folder.

- **"Stop music"** – Stops the media player.
- **"Give weather"** – Prompts for a city name and provides weather details.
- **"What is ..."** – Searches and summarizes information from Wikipedia.
- **"Open YouTube"** – Asks for a search query and opens YouTube results.
- **"Set timer"** – Sets a countdown based on user input.
- **"Exit Command"**: Saying "ok thanks" will gracefully exit the application.
