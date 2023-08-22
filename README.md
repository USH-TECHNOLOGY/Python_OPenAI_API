# Python_OpenAI_API
This Repo contains the python application we have developed for parsing through PDFs. The demo for this was originally done in May of 2023.

This project allows the user to upload a PDF document and ask relevant questions about its content. Langchain, open ai api model, and Facebook Ai Similarity Search library are used to process the text within the PDF and ultimately provide answers to the questions pertaining to the document.

## Installation:

### 1. Clone the Repo Or open with VSCode.
`git clone <repository_url>`

`cd <your_directory>`


### 2. Create a Virtual Environment
`python -m venv venv_name`


### 3. Install Required Dependencies
`pip install -r requirements.txt`


### 4. Add OpenAI API key to the .env file

- Create or edit the `.env` file in your project root and set `OPENAI_API_KEY=your_api_key_here`.

### 5. Run application
`streamlit run yourfilename.py`

Make sure to replace <repository_url> with the actual URL of your repository and <your_directory> with the actual directory name you wish to use. Similarly, replace venv_name with the desired name for your virtual environment if you don't want to use the default venv name.

