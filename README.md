# OpenAI-API-Text-Summarization

# Document Summarizer

This repository contains a Python script that utilizes OpenAI's GPT model to summarize the content of a text document. The script reads a document from a file, sends its content to the OpenAI API, and returns a concise summary of the text.

## Features

- **Read Document**: The script reads the content of a text document.
- **Summarize Document**: Uses OpenAI's GPT-3.5 model to generate a summary of the content.
- **Flexible Input**: You can specify the path to your document.
- **Customizable Settings**: You can adjust the model, token limits, and temperature for summarization.

## Requirements

To run this script, you will need:

- Python 3.6+
- OpenAI Python library
- An OpenAI API key

### Install Dependencies

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install the required dependencies:

    ```bash
    pip install openai
    ```

### Get Your OpenAI API Key

You need an OpenAI API key to use the model. You can obtain it by signing up on [OpenAI's website](https://beta.openai.com/signup/). Once you have your API key, replace the placeholder `your-api-key` with your actual API key in the script.

## Usage

1. **Place your document**: Save the text document you want to summarize in the same directory as the script, or specify the full path.

2. **Run the script**:

    ```bash
    python document_summarizer.py
    ```

   The script will read the document, summarize its content, and print the summary to the terminal.

### Example Output

```plaintext
Summarizing the document...

Summary:
Artificial Intelligence (AI) is a field of computer science focused on creating systems that can perform tasks requiring human intelligence. This includes reasoning, learning, problem-solving, perception, and language understanding. AI includes subfields like machine learning and deep learning, which enable systems to improve performance and model complex patterns. AI is used in various applications such as virtual assistants, autonomous vehicles, medical diagnostics, and robotics, with the potential to revolutionize industries like healthcare, finance, and manufacturing. However, concerns around ethics, job displacement, and privacy have sparked discussions about the responsible development and use of AI.
