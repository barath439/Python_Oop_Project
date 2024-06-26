# Python_Oop_Project

Features
User Registration and Login:

New users can register with their name, email, and password.
Registered users can log in to access the application's features.
NLP Functionalities:

Sentiment Analysis: Analyze the sentiment of a given text.
Language Translation: Translate text to Tamil.
Language Detection: Detect the language of a given text.
Setup
Clone the Repository:

sh
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install Dependencies:
Ensure you have the google-generativeai library installed. If not, you can install it using pip:

sh
Copy code
pip install google-generativeai
Add Your API Key:
Replace "#Add your API Key" in the code with your actual API key from Google Generative AI.

Usage
Run the application:

sh
Copy code
python your_script_name.py
You will be prompted with a menu to register, log in, or exit. After logging in, you can choose between sentiment analysis, language translation, or language detection.

Code Overview
NLPModel Class
Configures the Google Generative AI model with the provided API key.
Initializes the gemini-pro model.
NLPApp Class
Inherits from NLPModel and provides the main functionality:

User Management:
__register(): Handles user registration.
__login(): Handles user login.
Menu Navigation:
__first_menu(): Displays the initial menu.
__second_menu(): Displays the secondary menu after login.
NLP Functionalities:
__sentiment_analysis(): Performs sentiment analysis on user input.
__language_translation(): Translates user input to Tamil.
__language_detection(): Detects the language of user input.
Example Usage
sh
Copy code
Hi! how would you like to proceed?

1. Not a member? Register
2. Already a member? Login
3. Do not want to do anything? Exit
Upon selecting an option, you can proceed with registration, login, or exit. After logging in, you can access various NLP functionalities.

License
This project is licensed under the MIT License.