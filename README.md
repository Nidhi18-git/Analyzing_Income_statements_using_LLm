📊Analyzing Income Statements Using Large Language Models (LLMs)
Welcome to Analyzing Income Statements Using LLMs – a project that harnesses the power of AI to automate the analysis of complex financial documents. By utilizing LLMs, this tool can extract, interpret, and summarize key financial metrics from income statements and balance sheets with precision.

🚀 Key Features
📄 Upload PDF Reports – Effortlessly upload income statements or balance sheets for AI-driven analysis.
🧠 AI-Powered Summarization – Leverages LLMs to generate concise, accurate financial summaries.
🔍 Key Metrics Extraction – Extracts essential data points such as revenue, expenses, and profit margins.
📊 Real-time Analysis – Provides instant insights after document upload and processing.
💼 Business-Driven Insights – Designed to support businesses and financial analysts with quick, reliable financial overviews.
🛠️ Installation & Setup
Follow these steps to get the project running locally:

1. Clone the Repository
bash
Copy code
git clone https://github.com/Nidhi18-git/Analyzing_Income_statements_using_LLm.git  
cd Analyzing_Income_statements_using_LLm
2. Set Up Virtual Environment (Optional but Recommended)
bash
Copy code
python -m venv venv
Activate the Virtual Environment:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate
3. Install Dependencies
bash
Copy code
pip install -r requirements.txt
🖥️ How to Use
Run the Application
bash
Copy code
streamlit run app.py
Upload Your PDF
Use the drag-and-drop feature or the upload button to select an income statement PDF.
Generate Insights
AI will analyze the PDF and summarize key financial metrics in seconds.
📁 Project Structure
bash
Copy code
Analyzing_Income_statements_using_LLm/
├── app.py                 # Main Streamlit application  
├── requirements.txt       # Project dependencies  
├── utils/  
│   ├── data_extraction.py # PDF data extraction logic  
│   └── analysis.py        # Core financial analysis methods  
├── README.md              # Project documentation  
└── assets/                # Additional resources and icons  
🧰 Technology Stack
Frontend: Streamlit – For building the interactive web interface
Backend: Python (PyPDF2, Pandas) – For PDF parsing and data processing
AI Model: OpenAI LLMs – For summarization and key insight extraction
🌐 Contributing
Contributions are welcome! Here's how you can help:

Fork this repository
Create a new branch (feature/YourFeature)
Commit your changes
Push to your branch
Open a Pull Request
📝 License
This project is licensed under the MIT License.

📧 Contact
For inquiries or collaboration opportunities, feel free to reach out

