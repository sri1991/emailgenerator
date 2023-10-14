# Email Generator

This is a web app that can generate emails based on the user's input. The app uses Streamlit and LangChain to create a user interface and a language model. The app allows the user to enter the email topic, sender name, recipient name, and writing style, and then generates an email text by using the language model.

## Requirements

To run this app, you need to have the following:

- Python 3.7 or higher
- Streamlit 1.2.0 or higher
- LangChain 0.1.0 or higher
- CogView Transformers 0.0.1 or higher
- A local file called `models/llama-2-7b-chat.ggmlv3.q8_0.bin`, which is a quantized version of the Llama-2-7B-Chat model.

## Installation

To install the required libraries, you can use the following command:

```bash
pip install streamlit langchain ctransformers```

## To download the model file, you can use the following command:
