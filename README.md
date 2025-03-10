# AI PDF Summarizer

## Overview
AI PDF Summarizer is a simple web-based application that extracts and summarizes text from PDF documents. It utilizes `PyMuPDF` for text extraction and `Summa` for extractive text summarization. The interface is built using `Gradio`, making it easy to use via a web-based UI.

## Features
- Extracts text from a PDF file.
- Preprocesses the extracted text by removing unwanted characters and numbers.
- Summarizes the content using extractive text summarization.
- User-friendly web interface using Gradio.
- Allows users to set a word limit for summarization.

## Installation

### Prerequisites
Ensure you have Python installed (>=3.7). Install the required dependencies:

```sh
pip install pymupdf summa gradio
```

## Usage

### Running the Application
To launch the AI PDF Summarizer, run the following command:

```sh
python app.py
```

This will start a Gradio interface where you can enter the path of your PDF file and specify the word limit for the summary.

### Using the Web Interface
1. Enter the file path of your PDF document.
2. Specify the desired word limit for the summary.
3. Click the submit button to generate the summarized text.


## Example Usage
```python
summarized_text = summarize_text("sample.pdf", max_words=300)
print(summarized_text)
```

## Contributing
Feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, reach out via GitHub or email.

