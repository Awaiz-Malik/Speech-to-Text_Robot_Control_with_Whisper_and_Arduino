# Voice-Controlled Robot Project

## Overview
This project implements a voice-controlled robot using Python and Arduino. The robot responds to voice commands, performs various actions, and can be controlled through a physical body connected via serial communication.

## Features
- Voice recognition using the `whisper` library.
- Text-to-speech using `pyttsx3` for natural interaction.
- Integration with Arduino Nano for physical movement control.
- Actions include playing YouTube videos, Google searches, opening URLs, and more.

## Prerequisites
- Python 3.x
- Arduino IDE
- Libraries: `speech_recognition`, `pyttsx3`, `datetime`, `webbrowser`, `serial`, `pywhatkit`, `whisper`

## Getting Started
1. Connect the Arduino Nano board to the computer.
2. Upload the provided Arduino sketch to the board.
3. Run the Python script to initiate voice control.

## Usage
1. Pronounce the wake-up word (default: 'robo') to activate the robot.
2. Issue commands such as:
   - "play [video]"
   - "search [query]"
   - "get info [topic]"
   - "open [URL]"
   - "hi" or "hello" for a greeting, "bye" for farewell, etc.

## Arduino Commands
- 'h': Wave hand and greet.
- 'p': Perform a double punch.
- 'u': Raise both hands.
- 'l': Move head left.
- 'U': Execute a right upper-cut.
- 's': Perform a smashing action.

## Customization
- You can customize wake-up word, commands, and actions as needed.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Thanks to [whisper](https://pypi.org/project/whisper/) for providing speech-to-text capabilities.

Feel free to contribute or report issues!
