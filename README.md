# Movie Recommender using Gemini Pro

## Introduction

Welcome to the Movie Recommender using Gemini Pro! This project leverages the power of Gemini Pro's language model to provide personalized movie recommendations based on user queries. The integration with Streamlit makes it user-friendly and interactive.

## How it works
The application fetches data from a CSV file, utilizing both Google's Gemini Pro (LLM) and Langchain Agents to handle user queries. The CSV agent employs a range of tools to analyze questions and produce fitting responses, with assistance from the LLM.

To enhance user interaction, the application employs Streamlit to create an intuitive graphical interface (GUI) and depends on Langchain for seamless communication with the LLM.

## Installation

To run the Movie Recommender, follow these steps:

1. Install the required dependencies by running the following command:

    ```bash
    pip install -r requirements.txt
    ```

    Additionally, obtain an OpenAI API key and add it to the `.env` file.

## Usage

Run the application by executing the `main.py` file using the Streamlit CLI. Ensure that Streamlit is installed before running the application. Use the following command in your terminal:

```bash
streamlit run main.py
