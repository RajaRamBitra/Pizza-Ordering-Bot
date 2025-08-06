# Pizza Ordering Chatbot

This project is a conversational chatbot that acts as an automated assistant for a pizza restaurant. It's built using Python, the Groq API for natural language processing, and the Panel library for the user interface.

## Features

* **Conversational Ordering:** Guides users through the process of placing an order in a friendly, conversational manner.
* **Menu Awareness:** The bot is provided with a menu and can help users with selections, including sizes and toppings.
* **Order Summarization:** Can generate a detailed summary of the order with an itemized price list.
* **Pickup or Delivery:** Asks the user for their preferred delivery method and can request an address if needed.
* **Error Handling:** It can even offer a small discount if it makes a mistake during the ordering process.

## Technologies Used

* **Python:** The core programming language for the project.
* **Groq:** Provides the powerful language model that drives the chatbot's conversational abilities.
* **Panel:** A Python library used to create the interactive chat interface.
* **Jupyter Notebook:** The development environment where the code is written and executed.

## How to Use

### 1. Installation

First, you'll need to install the necessary Python libraries. You can do this by running the following command in your terminal:

```bash
pip install groq panel
```

### 2. Get a Groq API Key

To use the chatbot, you need a free API key from Groq.

1. Go to https://console.groq.com/keys
2. Sign up for a free account
3. Create a new API key and copy it

### 3. Configure the API Key

Open the `Pizza_Ordering_Bot.ipynb` file and find the following section:

```python
# IMPORTANT: Paste your Groq API key here.
# Get a free key from https://console.groq.com/keys

API_KEY = ""
```

Paste your copied Groq API key into the empty quotes.

### 4. Running the Chatbot

Once you've installed the libraries and added your API key, you can run the chatbot by executing the cells in the Jupyter Notebook in order.

The notebook is divided into the following sections:

* **Setup and Initialization:** Installs and imports the necessary libraries.
* **Core Functions:** Contains the main function for communicating with the Groq API.
* **Chatbot Configuration and UI:** This is where the chatbot's personality is defined and the interactive chat interface is created.
* **Summarize the Final Order:** Includes the code to generate a summary of the conversation.
* **Clear Conversation History (Optional):** Provides a way to reset the chatbot's memory and start a new order.

To start a new order at any time, simply rerun the cell in section 5 to clear the bot's memory.

## Requirements

* Python 3.7+
* Groq API key (free)
* Jupyter Notebook or JupyterLab
