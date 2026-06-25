# 💼 Job Application Assistant

An AI-powered job search and application assistant that helps users discover relevant job opportunities and generate personalized cover letters based on their resume, skills, and target role preferences.

Built with **Streamlit**, **LangChain Deep Agents**, **OpenAI**, and **Tavily Search**.

---

## 🚀 Features

### 📄 Resume Analysis
- Upload resumes in PDF, DOCX, or TXT format
- Automatically extracts and analyzes resume content

### 🔍 Intelligent Job Search
- Finds real-time job opportunities based on:
  - Target job title
  - Preferred location
  - Resume skills
  - Additional skills provided by the user

### ✍️ Personalized Cover Letters
- Generates tailored cover letters for each job opportunity
- Highlights relevant skills and experience
- Professional and ready-to-send format

### 📥 Download Support
- Download all generated cover letters as a DOCX file

### 🌐 Real-Time Job Discovery
- Uses Tavily Search API to find current job openings
- Provides direct application links

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### AI & Agent Framework
- LangChain
- DeepAgents
- OpenAI GPT Models

### Search Engine
- Tavily Search API

### Data Processing
- Pandas
- PyPDF
- Python-Docx

### Environment Management
- Python Dotenv

---

## 📂 Project Structure

```text
job-application-assistant/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/job-application-assistant.git
cd job-application-assistant
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Create a .env File

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Running the Application

```bash
streamlit run app.py
```

The application will automatically open in your browser.

---

## 📖 How It Works

### Step 1
Upload your resume:
- PDF
- DOCX
- TXT

### Step 2
Enter:
- Target Job Title
- Preferred Location
- Additional Skills (Optional)

### Step 3
Click **Run Agent**

The AI agent will:

1. Analyze your resume
2. Search for matching job opportunities
3. Select the best job matches
4. Generate personalized cover letters
5. Provide direct application links

### Step 4
Download all generated cover letters as a DOCX file.

---

## 🔑 API Keys Required

### OpenAI API Key

Get your API key from:

https://platform.openai.com/

### Tavily API Key

Get your API key from:

https://app.tavily.com/

---

## 🔄 Application Workflow

```text
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
```

---

## 🎯 Use Cases

- Freshers looking for jobs
- Students applying for internships
- Professionals seeking career transitions
- AI/ML Engineers targeting specialized roles
- Job seekers wanting faster applications

---

## 🔒 Security Note

Never upload your `.env` file to GitHub.

Add the following to `.gitignore`:

```gitignore
.env
```

---

