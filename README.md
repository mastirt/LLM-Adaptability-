# LLM Adaptability

This repository contains a Streamlit-based web application that allows users to upload PDF documents and ask questions based on the content of the documents. The application uses a Large Language Model (LLM) API to provide answers.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
The LLM Adaptability app provides an interactive Q&A interface where users can upload PDF documents and ask questions related to the content of those documents. The app utilizes a pretrained Large Language Model (LLM) API to generate accurate responses.

## Features
- Upload PDF documents for text extraction.
- Ask questions based on the content of uploaded PDF documents.
- Get responses from a pretrained LLM API.
- View the history of questions and answers within the session.

## Requirements
- Python 3.10
- Streamlit
- Requests
- PyMuPDF

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/mastirt/LLM-Adaptability-.git
    cd LLM-Adaptability
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have your API key for the LLM API.
2. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
3. Open your web browser and go to `http://localhost:8501`.
4. Upload a PDF document and input your questions based on the document's content.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
