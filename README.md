### Financial Data Extraction Tool Using OpenAI API

This tool is a streamlit based app that uses openai api to extract key financial measures such as company name, stock symbol, revenue, net income etc. from a news article. The news article is typically an article about company's finance reporting.

### Installation

```bash
pip install -r requirements.txt
```

### Setup

1. You need to create an account on openai website. You will get initial $5 free credits which is more than enough for this project.

2. Once you get an API key from your account, create a `.env` file in the project root directory:

```bash
cp .env.example .env
```

3. Edit the `.env` file and add your OpenAI API key:

```
OPENAI_API_KEY=your_api_key_here
```

### Running the Application

```bash
streamlit run main.py
```

**Note**: Never commit your `.env` file or API keys to version control. The `.env` file is already included in `.gitignore`.
