# AI Web Scraper

A Streamlit-based web application that combines Selenium web scraping with AI-powered content parsing using Ollama's llama3.1 model. This tool allows users to scrape websites and extract specific information using natural language instructions.

## Features
- Scrape dynamic web content using Selenium and ChromeDriver
- Clean and process HTML content with BeautifulSoup
- AI-powered parsing of scraped content using LangChain and Ollama
- User-friendly Streamlit interface for input and results

## Setup Instructions
1. **Clone the repository**
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download ChromeDriver** (if not included) and place it in the project directory
4. **Run the app:**
   ```bash
   streamlit run main.py
   ```

## Usage
1. Enter the website URL in the input box
2. Click "Scrape site" to fetch and clean the website content
3. Enter a description of the information you want to extract (e.g., "all email addresses")
4. Click "Parse Content" to let the AI extract the relevant data

## Technologies Used
- Python
- Streamlit
- Selenium WebDriver
- BeautifulSoup
- LangChain
- Ollama (llama3.1)

## Note
- Ensure you have the correct version of ChromeDriver for your Chrome browser
- The AI model requires Ollama to be installed and running 