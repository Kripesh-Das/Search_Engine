# LangChain - Chat with Search
# Link to the model deployed on streamlit - https://kripeshsearchengine.streamlit.app/ 

This repository contains a Streamlit application that integrates with LangChain to create a chatbot capable of searching the web using various tools like Arxiv, Wikipedia, and DuckDuckGo.

## Features

- **Interactive Chatbot**: Engage with a chatbot that can search the web and provide information.
- **Streamlit Integration**: Uses `StreamlitCallbackHandler` to display the thoughts and actions of the agent in real-time.
- **Multiple Search Tools**: Integrates Arxiv, Wikipedia, and DuckDuckGo for comprehensive search capabilities.

## Installation

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    - Create a `.env` file in the root directory of the project.
    - Add your Groq API Key to the `.env` file:
      ```env
      GROQ_API_KEY=your_groq_api_key
      ```
## File Structure
- **app.py**: Main application file.
- **requirements.txt**: List of dependencies.
- **toolsagents.ipynb**: Jupyter notebook for additional tools and agents.
- **venv/**: Virtual environment directory.
