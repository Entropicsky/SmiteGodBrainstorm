# AutoFinetune

Simple python app to demonstrate using a JSON file to define a chain of prompts to use to create a Word document with the results of the prompts. The example is constructed to create a word document for a SMITE god brainstorming session.

## Features

- Prompts user for God, Pantheon, Class, Ability Type, Damage Type, and other info
- Loops through prompts contained in the document_structure.json file
- Writes results of prompts into a word document for download

## Installation

### Prerequisites

- Python 3.7 or later
- An OpenAI API key

### Steps

1. Clone the repository:

2. Change to the project directory:

3. Install the required packages:

npm install

npm install openai

npm install python-docx

4. Create a .env file in the project root directory and add your OpenAI API key OR just add your API key to loop_prompts.py
echo "OPENAI_API_KEY=your_api_key_here" > .env

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

