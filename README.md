
# RAG-Chatbot-with-PDF-Upload-and-Chat-History

This project is a Streamlit application that allows users to upload PDF files and ask questions about their content. The application leverages the Langchain framework, Gemma 2, Groq API, and a history-aware retriever to maintain chat history and provide contextually accurate answers.

You can check the live project [here](https://rag-chatbot-with-pdf-upload-and-chat-history.streamlit.app/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- Python 3.10 or higher
- [Streamlit](https://streamlit.io/)
- [Langchain](https://github.com/hwchase17/langchain)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [pypdf](https://pypi.org/project/pypdf/)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/devesht21/RAG-Chatbot-with-PDF-Upload-and-Chat-History
   cd RAG-Chatbot-with-PDF-Upload-and-Chat-History

2. Create a virtual environment:

    ```bash
    conda create -p venv python==3.10.0 -y
    conda activate venv

3. Install the required packages:

    ```bash
    pip install -r requirements.txt

4. Set up your environment variables by creating a .env file in the root directory and adding your Hugging Face and Groq API keys:

    ```bash
    HF_TOKEN=your_huggingface_api_key

5. Run the Streamlit application:

    ```bash
    streamlit run app.py


## Usage

1. Open your web browser and navigate to http://localhost:8501.
2. Enter your Groq API Key and wait
3. Enter your session id and upload PDF you want to question about.
4. Enter your question.
5. The application will display the response generated by the Gemma 2 model based on the context of the loaded pdf

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.



