# LinkedIn Post Generator using LangChain and LLaMA

## Overview
This project is a LinkedIn Post Generator that leverages the power of *LangChain* and *LLaMA* to generate engaging LinkedIn posts. It uses *ChromaDB* as a vector database and *Streamlit* for the UI. The project enables users to create effective, AI-generated LinkedIn posts for various purposes, such as personal branding, marketing, and networking.

## Features
- Generates LinkedIn posts using *LLaMA* and *LangChain*.
- Stores and retrieves relevant data using *ChromaDB*.
- Provides a user-friendly interface via *Streamlit*.
- Supports environment variable management with *dotenv*.
- Utilizes web scraping tools like *BeautifulSoup4* for additional data gathering.

## Installation
To run this project locally, ensure you have Python installed and run the following commands:

bash
pip install langchain
pip install -qU langchain-groq
pip install chromadb
pip install streamlit
pip install dotenv
pip install -qU langchain_community beautifulsoup4


## Usage
1. Clone this repository:
   bash
   git clone <repository_url>
   cd linkedin-post-generator
   
2. Install dependencies:
   bash
   pip install -r requirements.txt
   
3. Run the Streamlit application:
   bash
   streamlit run main.py
   
4. Use the web interface to generate LinkedIn posts based on your input criteria.

## Technologies Used
- *LangChain*: Framework for building applications with LLMs.
- *LLaMA*: Language model for generating posts.
- *ChromaDB*: Vector database for semantic search.
- *Streamlit*: Interactive UI framework.
- *dotenv*: Environment variable management.
- *BeautifulSoup4*: Web scraping for relevant data.

## Contribution
Feel free to contribute to this project by submitting pull requests or reporting issues.

---
Made with ❤ using LangChain and LLaMA.
