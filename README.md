# Desktop-Voice-Assistant

Have you ever questioned how cool it might be to have your personal assistant? Imagine how less complicated it might be doing Wikipedia searches with out establishing net browsers, and acting many different each day duties like gambling song with the assist of a unmarried voice command, establishing exclusive browsers in only a voice command. This venture is straightforward computing device voice assistant constructed with python named as “Jarvis Desktop Voice Assistant”. This venture is completely finished and mistakess free. It turned into compiled in VS Code Editor.
  
🔸 Let's be honest, it is now no longer as shrewd as withinside the movie, however it may do a whole lot of cool matters and automate your each day duties you do in your private computers/laptops.

Here’s a list of features and main points about the voice assistant program you’ve shared:

Features:

Text-to-Speech (TTS) Capability:
Uses pyttsx3 to convert text responses into speech.

Voice Command Recognition:
Employs speech_recognition to listen to and interpret user commands through the microphone.

Current Time and Date:
Provides current time and date when prompted by the user.

Greeting and Time-Based Wishes:
Greets the user with a customized message based on the time of day (morning, afternoon, evening).

Wikipedia Search:
Allows users to search for information on Wikipedia and reads out the summary of the results.

Web Browsing:
Opens specified websites (e.g., YouTube, Google, Stack Overflow) in the default web browser using webbrowser.

Music Playback:
Plays a random song from a specified directory on the user’s system.

Browser Opening:
Opens Google Chrome or performs a search in Chrome using a command.

Memory Feature:
Can remember a piece of information provided by the user and retrieve it upon request.

Screenshot Functionality:
Takes a screenshot of the current screen (though the saving path is not specified in the code).

Main Points:
Initialization: Initializes pyttsx3 for text-to-speech functionality and sets up a basic framework for interaction.

Command Handling: The program listens for specific keywords in the user’s command to execute corresponding functions.

Error Handling: Includes basic error handling for voice recognition and web searching tasks.

Loop Structure: Runs in an infinite loop (while True) to continuously listen for commands and act on them.

Function Definitions: Functions are defined for time, date, greeting, screenshot, and command execution to modularize the code.

External Libraries: Utilizes external libraries such as pyttsx3, speech_recognition, wikipedia, and pyautogui for various functionalities.

File Operations: Reads from and writes to a text file to store and retrieve user-provided information.

Web and Local Resource Access: Opens web pages and local applications (e.g., media player) based on user commands.

User Feedback: Provides spoken and printed feedback to the user about the actions being performed or errors encountered.
