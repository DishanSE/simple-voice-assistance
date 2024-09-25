# Simple Voice Assistant

This is a Python-based Voice Assistant that can perform simple tasks such as greeting the user, telling the current time and date, performing web searches, and playing videos on YouTube based on voice commands.

## Features
- Responds to basic greetings like "hello" or "hi"
- Tells the current time and date
- Performs web searches based on user queries
- Plays a specified music video on YouTube
- Simple text-to-speech (TTS) and speech recognition using `pyttsx3` and `speech_recognition`
- Uses `pywhatkit` to play YouTube videos directly

## How It Works
1. The assistant listens to your voice commands using your system’s microphone.
2. It recognizes the commands and performs the following tasks:
   - **Greeting**: Responds when you say "hello" or "hi."
   - **Tell the Time/Date**: You can ask for the current time or date.
   - **Search the Web**: You can perform a Google search by saying "search [query]."
   - **Play YouTube Videos**: You can say "play [video name] on YouTube," and the assistant will search and play the video on YouTube.
   - **Exit**: You can stop the assistant by saying "exit" or "stop."

## Prerequisites
Make sure you have the following libraries installed in your Python environment:

```bash
pip install speechrecognition pyttsx3 pywhatkit pyaudio
```

### Required Libraries:
1. `speech_recognition`: For recognizing voice input from the user.
2. `pyttsx3`: For text-to-speech conversion.
3. `pywhatkit`: For playing YouTube videos directly.
4. `pyaudio`: For accessing the microphone for voice input.

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/voice-assistant.git
   ```

2. Install the required Python libraries:
   ```bash
   pip install speechrecognition pyttsx3 pywhatkit pyaudio
   ```

3. Run the `voice_assistant.py` file:
   ```bash
   python voice_assistant.py
   ```

4. Speak to the assistant using the following commands:
   - "Hello" or "Hi"
   - "What is the time?"
   - "What is the date?"
   - "Search [query]" for a web search
   - "Play [video name] on YouTube"
   - "Exit" to stop the assistant

## Project Structure

```
.
├── voice_assistant.py   # Main Python file for the voice assistant
├── README.md            # This README file
```

### Example Usage

1. **Greeting**: 
   - User: "Hello"
   - Assistant: "Hello! How can I assist you today?"

2. **Tell Time/Date**: 
   - User: "What is the time?"
   - Assistant: "The time is 10:30 AM."

3. **Play YouTube Video**: 
   - User: "Play Shape of You on YouTube."
   - Assistant: "Playing Shape of You on YouTube."

4. **Exit**: 
   - User: "Exit."
   - Assistant: "Goodbye, Have a nice day!"

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
