# Sales Assistant: Automated Company Brochure Generator

The **Sales Assistant** is a tool designed to help sales professionals efficiently prepare for client meetings by generating concise, data-driven company brochures. Using publicly available information from company websites, this assistant extracts relevant content and structures it into an easy-to-read format, saving time and enhancing productivity.

---

## **Features**
- **Web Scraping**: Automatically fetches and processes content from a company's website.
- **Link Filtering**: Identifies and prioritizes relevant pages such as "About Us" or "Careers."
- **AI-Powered Summarization**: Creates a concise company brochure in Markdown format using OpenAI's GPT-4 model.

---

## **Installation**

### **Prerequisites**
1. Python 3.8 or higher.
2. A valid OpenAI API key.

### **Steps**

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/sales-assistant.git
   cd sales-assistant

2. Create a virtual environment and activate it:
    ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # source venv/bin/activate  # On macOS/Linux

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Create a .env file in the root directory with your OpenAI API key:
   ```bash
   OPENAI_API_KEY=sk-proj-<your-api-key>

5. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook

6. Open the notebook sales_assistant.ipynb and follow the instructions.

---

## **Usage**

1. Run the Jupyter Notebook.
2. Provide the company name and website URL when prompted.
3. The assistant will:
   - Scrape the website.
   - Extract relevant links and content.
   - Generate a company brochure in Markdown format.

---

## **Dependencies**
- beautifulsoup4==4.12.3: For HTML parsing.
- ipython==8.30.0: To render Markdown outputs in Jupyter.
- openai==1.55.3: For AI-powered text generation.
- python-dotenv==1.0.1: To load environment variables.
- requests==2.32.3: For web scraping.

Install all dependencies using:
   ```bash
    pip install -r requirement.txt
   ```

---

## **Acknowledgements**
This project uses:
- OpenAI's GPT-4 for language generation.
- BeautifulSoup for web scraping.
- Python ecosystem libraries for seamless data handling.