# newsbot-app
# Newsbot: Automated News Summarizer and QnA

This is a Streamlit application that fetches news articles from URLs, summarizes them, and answers user questions based on the article content using NLP models from Hugging Face.

## Features

- Fetch news articles from URLs.
- Summarize the article content.
- Answer questions related to the article.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/newsbot-app.git
    cd newsbot-app
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv myenv
    myenv\Scripts\activate  # On Windows
    # source myenv/bin/activate  # On macOS/Linux
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter a news article URL, fetch the article, and then summarize or ask questions about it.

## Dependencies

- `streamlit`
- `newspaper3k`
- `transformers`
- `torch`
- `lxml[html_clean]`
- `lxml_html_clean`
