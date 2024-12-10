Chatbot using Llama3 (Streamlit + Ollama)

This is a simple Streamlit web app that integrates Llama3 via the langchain_ollama library to generate AI-based responses. Users can input a prompt, and the app will generate and display a response from the Llama3 model.
Prerequisites

Before running the app, ensure you have the following installed:

    Python 3.x
    Streamlit: For building the web app.
    langchain-ollama: For integrating with the Ollama API.
    Ollama: Ensure the Llama3 model is accessible on your system or from a remote server.

1. Install Required Libraries

To get started, clone this repository and install the dependencies:

pip install streamlit langchain_ollama

2. Setup Ollama

Make sure you have Ollama installed and running on your system. Follow the official Ollama setup guide for instructions.
3. Run the App

After the installation, navigate to the folder where you saved the project and run:

streamlit run app.py

This will launch the web app in your browser.
How It Works

    Streamlit Interface:
        The app provides a text area for users to input a prompt.
        When the "Generate" button is clicked, the app calls the Llama3 model to generate a response.

    Llama3 (via Ollama):
        The OllamaLLM class from langchain_ollama is used to connect with the Llama3 model and generate the AI response.

    Model:
        The model used here is llama3, which you can replace with any other Llama model available on Ollama.

Example Use

When you input a prompt like:

"Tell me a joke."

The app will display a response from the Llama3 model, something like:

"Why don’t skeletons fight each other? They don’t have the guts!"
Contributing

Feel free to fork this repository, submit issues, and send pull requests. Contributions are always welcome!
License

This project is licensed under the MIT License.
