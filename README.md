# FRIDAY - Offline Voice Assistant
![alt text](<Friday Image.png>)
This is an offline version of my previous Jarvis voice assistant. 
Friday utilizes no outside API keys and is run completely local

![alt text](<Friday Introduction.gif>)

# UPDATE
Added online functions when connected to the wifi
- Spotify functions (can play any desired song or pick a song and play it)
- Gets weather data from the National Weather Service
- Sends reminders to my phone via text messages
- Sends text messages to others

# Weather Example
Response to query "What's today's forecast?"
![alt text](<Friday Weather_Report.gif>)

# Libraries
Check the requirements.txt folder for all required libraries to install. 
Ollama is also required to be downloaded: https://ollama.com/download


# Why make Friday?

- Cost efficient - no subscriptions with external APIs
- Responses load faster than an openAI response
- More interactive experience with a local AI - more sensitive to user preference
- Can work from anywhere and without wifi
- Clean interface

# Next Steps
The following features are planned to be added to Friday for optimized functionality

- Online functionalities when hooked up to wifi: Spotify, Youtube, National Weather Service data
- AI vision from llama 3.2 for increased productivity
- Possible image generation
- Text messaging
- Alarm clock

# Instructions
1. Install Ollama on your windows machine @ https://ollama.com/download (select download for windows)
2. After installation, enter: "ollama run llama3.2" into the terminal
3. Once the model installs for the first time, enter: "ollama serve" into terminal to start a local server
4. To run the model in the terminal, enter: "ollama run llama3.2" (ctrl + d) to exit
5. Download the libraries in READM.md
6. Implement code