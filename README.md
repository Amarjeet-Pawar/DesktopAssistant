# Desktop Assistant

Siri-like desktop assistant written in Python which uses Google's speech-to-text library to process voice input.
## Installation
Install the dependencies in a virtual environment (using conda or virtualenv) to avoid any issues. Use either pip2 or pip3 for Python2 and Python3 respectively.

### Install Dependencies
For Python2:

pip2 install -r requirements.txt
<br> For Python3:

pip3 install -r requirements.txt

<br>To start the desktop assistant, run:

python desktopAssistant.py

### Supported Commands
Open reddit subreddit: Opens the subreddit in the default browser.
Open website xyz.com: Opens the specified website.
Send email/email: Follow-up questions such as recipient name and content will be asked.
Tell a joke/another joke: Says a random dad joke.
Current weather in {cityname}: Tells you the current condition and temperature.
Weather forecast in {cityname}: Tells you the condition, highest, and lowest temperature of the next two days.
What's up: Responds with a status update.