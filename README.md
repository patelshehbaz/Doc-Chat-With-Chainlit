# Document-Chat-With-Chainlit

Doc-Chat-With-Chainlit is designed to enable users to interact with documents via a chatbot interface. The project utilizes Langchain and Chainlit to process and respond to user queries based on the content of the documents.

Teckstack

- Langchain
- OpenAI
- ChromaDB

Ensure you have the following installed:

- Python 3.10 or higher
- Virtualenv

### Steps

1. Clone the repository:

   ```
   git clone https://github.com/patelshehbaz/Doc-Chat-With-Chainlit.git
   ```

2. Create and activate a virtual environment:

   ```
   conda create -p venv python=3.10 -y
   conda activate venv
   ```

3. Install the dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up environment variables by creating a `.env` file in the root directory and adding your configuration details:

   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

Run the Chainlit application:

```
chainlit run app.py
```
