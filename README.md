# AI_webscrapper
AI Web Scraper with Streamlit, Selenium, and Llama 3.2

## Solution Approach
### 1. Problem Statement
The goal of this project is to build a streamlined system that: <br />
Automatically extracts website content through scraping. <br />
Cleans and processes the extracted data. <br />
Performs AI-driven tasks based on user instructions. <br />

### 2. System Architecture
The solution is designed as a modular, full-stack application with the following components: <br />
<b>Frontend</b>: A user-friendly interface built using Streamlit, allowing users to input target URLs and describe operations to perform on the data. <br />
<b>Backend</b>: Python-based logic for: <br />
Automating browsing with Selenium and ChromeDriver. <br />
Extracting and processing website content. <br />
Sending instructions and data to Llama 3.2 for processing. <br />
<b>AI Model</b>: Llama 3.2 from Ollama, a large language model that processes user-defined tasks on the scraped content. <br />

### System Workflow <br />

<b>User Input</b>: The user provides a URL and a description of the operation (e.g., "Summarize this page"). <br />
<b>Scraping</b>: Selenium automates web browsing, extracts content from the specified URL, and preprocesses it (cleaning and chunking). <br />
<b>Processing</b>: The cleaned data, along with the user-defined instructions, is sent to Llama 3.2 for processing. <br />
<b>Output</b>: The results are displayed on the Streamlit interface.  <br />


## How to run the project 
Prerequisites
Ensure you have the following installed:

<b>Python 3.9+ </b> <br />
<b>Google Chrome and ChromeDriver (compatible with your Chrome version) </b>  <br />
<b>Streamlit</b>: pip install streamlit <br />
<b>Selenium</b>: pip install selenium <br />
<b>Ollama (for Llama 3.2)</b>: Follow installation instructions at Ollama's website.<br />
</b>Additional dependencies</b>: Install from the provided requirements.txt. <br />
<b>Steps to Run </b>  <br />
<b>Clone the repository</b>: <br />
git clone https://github.com/your-repository-name.git
cd your-repository-name
<br />
<b>Install dependencies </b>:
pip install -r requirements.txt
<br />
<b>Run the Streamlit app </b>:
streamlit run app.py
<br />
Open the local Streamlit interface in your browser, typically at:
http://localhost:8501
<br />
Input the target URL and operation description to start scraping and processing.


