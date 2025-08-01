# Intelligent-Natural-Language-SQL-Query-Assistant-Using-LLMs
Intelligent Natural Language SQL Query Assistant Using LLMs is a intelligent system that lets users query structured databases using plain English. Powered by advanced LLMs, it interprets user questions, generates accurate SQL, and delivers clear, data-driven answers making database analytics simple for everyone, no SQL skills required.


Intelligent Natural Language SQL Query Assistant Using LLMs
A general-purpose, AI-powered platform that allows anyone to query SQL databases using natural language, powered by large language models (LLMs). No SQL expertise required!

______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Table of Contents : 

-> Features

-> Demo Screenshot

-> How It Works

-> Installation

-> Configuration

-> Usage

-> Examples

-> Project Structure

-> Acknowledgements


_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Features :

- 🔎 Query SQL databases using plain English.

- 🤖 Powered by LLMs like OpenAI GPT for natural language understanding and SQL generation.

- 📊 Supports MySQL (easily extensible to other SQL databases).

- 💡 Transparent: shows generated SQL and the answer.

- 🖥️ User-friendly Streamlit web interface.

- 🛠️ Modular & extendable for future improvements.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

How It Works : 

1. User submits a question in English (e.g., "Which products had the highest sales last month?").

2. The LLM interprets the question and generates an appropriate SQL query.

3. The SQL query is run on your database.

4. The result and the generated SQL are displayed for review and learning.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Configuration :

-> Set up your MySQL database and tables.

-> Obtain an OpenAI API key (or Perplexity, etc.).

-> Set your credentials as environment variables (recommended) or edit them in app.py:

           - OPENAI_API_KEY

           - MYSQL_URI (e.g., mysql+mysqlconnector://user:password@localhost:3306/yourdbname)

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Usage :

      - Start the app with:

bash

     - streamlit run app.py
Open your browser to http://localhost:8501 and enter your questions!

_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Examples :

"How many products are in stock by brand?"

"Show total sales for May 2025."

"List top 5 customers by revenue."

"What are all discounts above 20%?"

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

    OpenAI / Perplexity for LLM APIs

    LangChain for LLM-to-SQL integration

    Streamlit for UI
