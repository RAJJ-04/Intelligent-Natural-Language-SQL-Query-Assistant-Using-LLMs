# Intelligent-Natural-Language-SQL-Query-Assistant-Using-LLMs
Intelligent Natural Language SQL Query Assistant Using LLMs is a intelligent system that lets users query structured databases using plain English. Powered by advanced LLMs, it interprets user questions, generates accurate SQL, and delivers clear, data-driven answers making database analytics simple for everyone, no SQL skills required.


ntelligent Natural Language SQL Query Assistant Using LLMs
A general-purpose, AI-powered platform that allows anyone to query SQL databases using natural language, powered by large language models (LLMs). No SQL expertise required!

Table of Contents
Features

Demo Screenshot

How It Works

Installation

Configuration

Usage

Examples

Project Structure

License

Acknowledgements

Features
🔎 Query SQL databases using plain English.

🤖 Powered by LLMs like OpenAI GPT for natural language understanding and SQL generation.

📊 Supports MySQL (easily extensible to other SQL databases).

💡 Transparent: shows generated SQL and the answer.

🖥️ User-friendly Streamlit web interface.

🛠️ Modular & extendable for future improvements.

Demo Screenshot
(Add a screenshot here of your app interface, if possible)

How It Works
User submits a question in English (e.g., "Which products had the highest sales last month?").

The LLM interprets the question and generates an appropriate SQL query.

The SQL query is run on your database.

The result and the generated SQL are displayed for review and learning.

Installation
Clone the repository:

bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Install dependencies:

bash
pip install -r requirements.txt
Or manually:

bash
pip install streamlit langchain langchain-community langchain-openai mysql-connector-python
Configuration
Set up MySQL database and tables.

Obtain an OpenAI API key (or Perplexity, etc.).

Set your credentials as environment variables (recommended) or edit them in app.py:

OPENAI_API_KEY

MYSQL_URI (e.g., mysql+mysqlconnector://user:password@localhost:3306/yourdbname)

Usage
Start the app with:

bash
streamlit run app.py
Open your browser to http://localhost:8501 and enter your questions!

Examples
"How many products are in stock by brand?"

"Show total sales for May 2025."

"List top 5 customers by revenue."

"What are all discounts above 20%?"

Project Structure
text
app.py                  # Main Streamlit app
requirements.txt        # Python dependencies
README.md               # This file
(sample_data.sql)       # Optional: DB schema and sample data
