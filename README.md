# GPT4V-notebook
chat with gpt-4-vision-preview in the notebook


This project provides a simple chat interface that allows users to interact with OpenAI's GPT-4 Vision model. It includes functionality to send messages, upload images, and receive responses from the AI. The conversation can be cleared or downloaded as a HTML file.

## Features

- Send text messages to GPT-4 Vision model.
- Upload images to be included in the conversation.
- Adjust the AI's response creativity with a temperature slider.
- Clear the conversation history.
- Download the conversation history in HTML format.
- Save and use an OpenAI API key for authentication.

## Requirements

To run this project, you will need:

- An OpenAI API key with access to the GPT-4 Vision model.
- Python environment with the following packages installed:
  - `ipywidgets`
  - `IPython`
  - `requests`
  - `base64`
  - `json`

## Setup

1. Clone this repository or copy the code into a Python file.
2. Ensure you have the required packages installed in your Python environment.
3. Run the code in a Jupyter Notebook or JupyterLab environment to interact with the widgets.

## Usage

1. Enter your OpenAI API key in the provided text box and click "Save API Key".
2. Type your message in the 'Message' text area.
3. Optionally, upload an image to send along with your message.
4. Click "Send Message" to send your message to the GPT-4 Vision model.
5. The conversation will be displayed in the interface.
6. Use the "Clear Conversation" button to reset the conversation history.
7. Use the "Download Conversation" button to save the conversation to your device.
8. Adjust the "Temperature" slider to control the randomness of the AI's responses.

## Notes

- The `send_message` function handles the sending of messages and images, as well as the reception of AI responses.
- The `clear_conversation` function resets the conversation history.
- The `download_conversation` function allows you to download the conversation history as a HTML file.
- The `save_api_key` function saves the API key entered by the user for subsequent requests.

## Disclaimer

This code is for demonstration purposes and is not production-ready. Ensure you handle your API keys securely and adhere to OpenAI's usage policies.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more information.
