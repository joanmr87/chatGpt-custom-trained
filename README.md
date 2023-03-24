Custom-trained AI Chatbot
=========================

This is a custom-trained AI chatbot created using the GPT-3.5-Turbo model from OpenAI. It is designed to respond to user input with coherent, relevant sentences based on the data provided in a set of documents.

Installation
------------

To run this chatbot, you will need to install the following dependencies:

-   `dotenv`
-   `gpt_index`
-   `langchain`
-   `gradio`

You can install them using the following command:

shellCopy code

`pip install dotenv gpt_index langchain gradio`

Usage
-----

1.  Clone or download this repository.
2.  Create a `.env` file in the root directory with your OpenAI API key, like this:

makefileCopy code

`OPENAI_API_KEY=your_api_key_here`

1.  Run the `app.py` script:

shellCopy code

`python app.py`

1.  Enter your text into the textbox and press Enter. The chatbot will respond with a coherent, relevant sentence based on the data provided in the `docs` directory.

Credits
-------

This chatbot was created by [your name here]. It uses the GPT-3.5-Turbo model from OpenAI and the `gpt_index` and `langchain` libraries. The `gradio` library is used to provide the user interface.

source: https://beebom.com/how-train-ai-chatbot-custom-knowledge-base-chatgpt-api/amp/