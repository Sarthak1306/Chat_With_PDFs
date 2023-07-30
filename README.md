# Chat with PDF's

## Introduction

---

Chat with PDF's is a Python application that helps you interact with pdf documents. You can upload PDF's of your liking and ask questions about the PDF's using natural language. The application will analyze the PDF content and provide you a relevent answer to your query.

## Dependencies & Installation

---

1: Clone the repository to your local machine

2: Install the following dependancies using
`
	pip install "dependency name"
	`

    - langchain
    - PyPDF2
    - python-dotenv
    - streamlit
    - openai
    - faiss-cpu
    - altair
    - tiktoken

3: Obtain an API Key from your OpenAI account and add it to '.env-example' file in the project directory and rename the file to '.env'

## Usage

---

To run the application :

1: Download all the required dependencies and add the OpenAI API Key to the .env file
2: Run the 'app.py' file using Streamlit CLI by running
`
	streamlit run app.py
	`
3: A new browser window will be opened with the running application
4: Upload your desired PDF(s) and ask questions.
