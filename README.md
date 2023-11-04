# AI Chatbot with Speech Recognition and Text-to-Speech Integration

This GitHub repository contains a Python script that combines OpenAI's GPT-3.5 Turbo model with speech recognition and text-to-speech capabilities to create an interactive chatbot that can understand and generate spoken responses.

## Features

- **OpenAI GPT-3.5 Turbo**: The script leverages the power of GPT-3.5 Turbo, an advanced language model, to provide intelligent responses to user queries.

- **Speech Recognition**: It includes speech recognition using the SpeechRecognition library to capture and convert spoken user input into text.

- **Text-to-Speech**: The chatbot can convert its responses into speech using the gTTS (Google Text-to-Speech) library and play the generated audio using the simpleaudio library.

- **Trigger Function**: The script incorporates a trigger function that activates the chatbot when a predefined trigger word is spoken. This makes it easy to control the interaction with the chatbot.

## How to Use

1. Clone this repository to your local environment.

2. Replace the placeholder OpenAI API key with your actual API key in the \`api_key\` variable.

3. Create a character sheet for the chatbot and save it as \"charactersheet.txt\" in the same directory. This character sheet can contain context or information you want the chatbot to have during the conversation.

4. Ensure you have the necessary Python libraries installed. You can use \`pip\` to install them:

```bash
pip install openai speech_recognition gtts simpleaudio
```

5. Customize the trigger word (variable \`triggerword\`) to your preference, which activates the chatbot.

6. Run the script, and the chatbot will wait for the trigger word. Once triggered, you can start speaking to the chatbot, and it will respond with text and spoken responses.

## Usage Examples

You can use this script to create interactive chatbots for various applications, such as virtual assistants, customer support, or interactive storytelling.

**Note**: Ensure you comply with OpenAI's usage policies and guidelines when using their API for chatbots.

For more information on OpenAI GPT-3.5 Turbo and the Python libraries used in this script, refer to the respective documentation and guidelines.

Enjoy interacting with your AI chatbot!"


You will maybe run into some errors this maybe will help:
openai: You can install it using pip.
```bash
pip install openai
```
speech_recognition: Install it using pip.
```bash
pip install SpeechRecognition
```
gtts (Google Text-to-Speech): You can install it with pip.
```bash
pip install gTTS
```
pydub: Install it with pip.
```bash
pip install pydub
```
simpleaudio: You can install it using pip.
```bash
pip install simpleaudio
```

