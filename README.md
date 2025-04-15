# Rasa Chatbot Project

This repository contains a Rasa-based chatbot project. Follow the instructions below to set up and run the chatbot.

## Prerequisites

- **Python 3.9.13** (Required for Rasa installation)
- **Git**

## Installation

## Clone the repository:

**git clone https://github.com/DroidalAdmin/ai_chatbots.git](https://github.com/ajithpav/braincenter.git**
**cd ai_chatbots**

Create and activate a virtual environment:
### On Windows
**python -m venv venv**

**venv\Scripts\activate**

### On macOS and Linux
**python3 -m venv venv**

**source venv/bin/activate**

### Install Rasa and other dependencies:
**pip install rasa**

**pip install -r requirements.txt**


### Training the Model
To train the Rasa model, run:
**rasa train**
Running the Chatbot

### Start the Rasa Action Server (in a new terminal window):
**rasa run actions**

### Start the Rasa API Server (in another new terminal window):
**rasa run --enable-api --cors "*" --debug**

The "--debug" is optional is used to monitor the debug log in terminal


Integration with UI
To integrate with a user interface:

Configure your credentials in credentials.yml.
Ensure your UI is set up to communicate with the Rasa API endpoints.

Debugging
To test and debug your Rasa model:

Use the Rasa Shell:
**rasa shell --debug**

Here ,the "--debug" is optional is used to  monitor the debug log in terminal

Check the debug logs when running the API server.

Additional Information

For more detailed information about Rasa, visit the official Rasa documentation.
If you encounter any issues, please check the Rasa Community Forum or open an issue in this repository.

Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
