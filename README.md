# Chat App with LLM3, Langchain, and Streamlit


## Overview

This project is a **Chat Application** built using **LLM3**, **Langchain**, and **Streamlit**. The app enables users to interact with an advanced language model in real-time, leveraging Langchain for structured conversation flows and state management.

## Features

- **Real-time Chat**: Interact with an advanced large language model powered by LLM3.
- **Structured Conversation**: Manage and organize conversations using **Langchain** to enhance context retention and flow.
- **User-Friendly Interface**: Simple and interactive UI powered by **Streamlit**.
- **Customizable Parameters**: Adjust the model's behavior, such as response length and creativity, to tailor interactions.

## Technologies Used

- **LLM3**: A powerful large language model that generates responses for the chat.
- **Langchain**: A framework used to manage and structure conversations, chain multiple tasks, and manage model states.
- **Streamlit**: A Python library for building interactive web apps with minimal code.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Steps

### Step 1: Install Ollama (LLM3)

1. **Install Ollama**:
   Ollama is required to interact with models like Llama2.

   - For **macOS**:
     ```bash
     brew install ollama
     ```

2. **Download Llama2 Model**:
   Use Ollama to download the **Llama2** model (or any model you prefer):

   ```bash
   ollama pull llama2
   ollama pull  qwen2.5:1.5b
   ollama pull mistral-small

   ```

3. **install langchain_ollamal and streamlit**:

   ```bash
   pip install langchain_ollamal
   pip install streamlit

   ```

4. **Python function**:
   Write a python code to intialization and take user prompt and select model we want to chat.


https://github.com/user-attachments/assets/a5674ded-a854-4771-9091-cfdfdcf84919


5.** Run the Application**:


