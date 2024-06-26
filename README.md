###### Python_Oop_Project

## NLP Application:

This project is a simple NLP (Natural Language Processing) application built using the google.generativeai library. It allows users to perform sentiment analysis, translation, and detection. The application includes a user registration and login system to manage access.


## Features
1.User Registration and Login:
New users can register with their name, email, and password.
Registered users can log in to access the application's features.

2.NLP Functionalities:
Sentiment Analysis: Analyze the sentiment of a given text.
Language Translation:Translate text to Tamil.
Language Detection: Detect the language of a given text.

## Setup
1.Clone the Repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2.Install Dependencies:
Ensure you have the google-generativeai library installed. If not, you can install it using pip:
pip install google-generativeai

3.Add Your API Key:
Replace "#Add your API Key" in the code with your actual API key from Google Generative AI.

## Usage
Run the application:
python your_script_name.py
You will be prompted with a menu to register, log in, or exit. After logging in, you can choose between sentiment analysis, language translation, or language detection.

## Code Overview
1.NLPModel Class
Configures the Google Generative AI model with the provided API key.
Initializes the gemini-pro model.

## NLPApp Class
Inherits from NLPModel and provides the main functionality:

1.User Management:
__register(): Handles user registration.
__login(): Handles user login.
2.Menu Navigation:
__first_menu(): Displays the initial menu.
__second_menu(): Displays the secondary menu after login.
3.NLP Functionalities:
__sentiment_analysis(): Performs sentiment analysis on user input.
__language_translation(): Translates user input to Tamil.
__language_detection(): Detects the language of user input.

## Example Usage
Hi! how would you like to proceed?

1. Not a member? Register
2. Already a member? Login
3. Do not want to do anything? Exit

1. Not a member? Register
2. Already a member? Login
3. Do not want to do anything? Exit
Upon selecting an option, you can proceed with registration, login, or exit. After logging in, you can access various NLP functionalities.

License
This project is licensed under the MIT License.
