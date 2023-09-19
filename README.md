# -LaMini-text-summerisation-

Document Summarization App using Language Models with Streamlit

This application is designed to allow users to upload PDF files and receive a summarized version of the content using a language model. It leverages the power of the T5 transformer model from the transformers library and Streamlit for the web interface.
Features:

    PDF file uploading.
    Deep learning-powered text summarization.
    Display both original and summarized content side by side.
    Easy to use web-based interface.

Installation:

Clone the repository:

bash

git clone <repository-url>
cd <repository-directory>

Install the required dependencies:

pip install -r requirements.txt

Usage:

Run the Streamlit app:

arduino

streamlit run <filename>.py

Visit the provided local URL in your browser, upload a PDF file, and click "Summarize".
Technical Details:

This app utilizes the following key libraries and tools:

    streamlit for creating the web-based interface.
    transformers for leveraging the T5 model for text summarization.
    Custom modules such as langchain for text and document processing.

License:

MIT License
Contributing:

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Acknowledgements:

    The Hugging Face team for the transformers library.
    The Streamlit community for the fantastic web framework.
    AI anytime for great llm tutorials 
