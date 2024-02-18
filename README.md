Chatbot with Python
This Python script implements a simple conversational chatbot that interacts with users based on pre-defined responses stored in a CSV file. The bot can engage in conversation, respond to greetings, answer questions, and bid farewell to users.

Features
Utilizes the pandas library to read conversation data from a CSV file.
Implements difflib's SequenceMatcher to find the best matching response to user input.
Provides error handling for unrecognized user input.
Limits users to asking up to three questions before prompting whether to continue.
Includes responses for greetings and farewells.
Usage
Ensure you have Python installed on your system.
Install the required libraries using pip install pandas.
Prepare your conversation data in a CSV file with columns "question" and "answer".
Run the script using python chatbot.py.
Interact with the chatbot by entering text in the console.
File Structure
chatbot.py: The main Python script containing the chatbot implementation.
Conversation.csv: Sample conversation data stored in a CSV file.
