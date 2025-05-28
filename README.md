🚀 Project Title
"Smart Voice-Controlled Media Assistant using Streamlit"

🧠 Problem Use Case
Many users desire hands-free control of media, searches, and basic tasks. Especially for accessibility needs or multitasking environments (e.g., cooking, driving, or working), a voice-activated system offers intuitive interaction. This project aims to develop a web-based voice assistant that responds to spoken commands to perform actions like playing music via YouTube and delivering spoken feedback—all in a lightweight, browser-based interface.

📝 Project Description
This project builds a browser-based voice assistant using Streamlit as the user interface framework. It listens for voice commands through a microphone, interprets them using Google’s Speech Recognition API, provides audio feedback with pyttsx3, and performs tasks such as playing songs on YouTube with pywhatkit. It also allows dynamic background customization by uploading an image.

✅ Project Responsibilities

1.Capture Voice Input from User
* Listen to spoken commands using the system’s microphone.
* Convert audio into text using Google Speech Recognition API.

2.Filter and Recognize Commands
* Check if the command contains a specific keyword (e.g., "santosh").
* Extract actionable parts of the command (e.g., "play [song name]").

3.Respond with Text-to-Speech

* Use a text-to-speech engine (pyttsx3) to give audible responses.
* Provide spoken confirmation (e.g., “Playing [song name]”).

4.Execute User Commands
* If the command includes the word “play”, search and play the corresponding YouTube video using pywhatkit.

5.Provide Visual Feedback
* Display what the user said on the Streamlit interface.
* Show success, error, or warning messages based on actions or issues.

6.Handle Errors Gracefully
* Catch exceptions such as microphone errors or recognition failures.
* Display friendly error messages using Streamlit alerts.

7.Customize Background UI
* Let users upload an image to set as the web app background.
* Encode the image in base64 and inject it into the UI with CSS.

8.Default Visual Design
* Use a fallback background image if the user does not upload one.
* Ensure the interface remains visually appealing without customization.

9.Streamlit Integration
* Run the voice assistant via a button press.
* Keep the UI interactive, responsive, and user-friendly within the Streamlit framework.

📦  Packages Used

Package                   Purpose
---------                 --------

* streamlit               Web UI and interaction handling
  
* speech_recognition	    Capturing and transcribing voice input
  
* pyttsx3	                Text-to-speech engine for responses
  
* pywhatkit	              Plays YouTube videos programmatically
  
* base64	                Encoding uploaded images for background display










