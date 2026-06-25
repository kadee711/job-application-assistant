💼 Job Application Assistant

An AI-powered job search and application assistant that helps users discover relevant job opportunities and generate personalized cover letters based on their resume, skills, and target role preferences.

Built with Streamlit, LangChain Deep Agents, OpenAI, and Tavily Search.

🚀 Features
📄 Resume Analysis
Upload resumes in PDF, DOCX, or TXT format
Extracts and analyzes resume content automatically
🔍 Intelligent Job Search
Searches the web for current job openings
Matches jobs based on:
Target job title
Preferred location
Resume skills
Additional skills provided by the user
✍️ Personalized Cover Letters
Generates tailored cover letters for each job opportunity
Highlights relevant skills and experience
Ready-to-send professional format
📥 Download Support
Download all generated cover letters as a Word document (.docx)
🌐 Real-Time Job Discovery
Uses Tavily Search to find live job postings
Provides direct application links
🛠️ Tech Stack
Frontend
Streamlit
AI & Agent Framework
LangChain
DeepAgents
OpenAI GPT Models
Search Engine
Tavily Search API
Data Processing
Pandas
PyPDF
Python Docx
Environment Management
Python Dotenv
📂 Project Structure
job-application-assistant/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
⚙️ Installation
1. Clone Repository
git clone https://github.com/yourusername/job-application-assistant.git
cd job-application-assistant
2. Install Dependencies
pip install -r requirements.txt
3. Create Environment Variables

Create a .env file in the root directory:

OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
▶️ Run the Application
streamlit run app.py

The application will open automatically in your browser.

📖 How It Works
Step 1

Upload your resume:

PDF
DOCX
TXT
Step 2

Enter:

Target Job Title
Preferred Location
Additional Skills (Optional)
Step 3

Click Run Agent

The AI agent will:

Analyze your resume
Search for matching live job opportunities
Select the best matches
Generate personalized cover letters
Provide application links
Step 4

Download generated cover letters as a .docx file.

🔑 API Keys Required
OpenAI

Get an API key from:

https://platform.openai.com/

Tavily

Get a free API key from:

https://app.tavily.com/

📸 Application Workflow
Resume Upload
      │
      ▼
Resume Analysis
      │
      ▼
AI Agent Processing
      │
      ▼
Live Job Search
      │
      ▼
Job Matching
      │
      ▼
Cover Letter Generation
      │
      ▼
Download Results

🎯 Use Cases
Freshers looking for job opportunities
Students applying for internships
Professionals seeking career transitions
AI/ML Engineers targeting specialized roles
Anyone wanting faster and smarter job applications


.env

to your .gitignore file.
