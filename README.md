# 🤖 Smart Query Routing System(Using n8n + LLM + Sentiment Analysis)
This repository contains an AI-driven automation workflow built for Innomatics Research Labs as part of my hands-on learning in real-world automation and intelligent system design. The workflow reads incoming student queries, analyzes sentiment, classifies the issue category using an LLM, and routes the query automatically to the right department.

**💡 Project Overview**
The Smart Query Routing System eliminates manual triage by combining workflow automation with AI-powered query understanding. Whenever a student submits a query, the system:
- Reads the submission
- Determines the urgency through sentiment analysis
- Classifies the type of query using an LLM
- Routes the issue to the correct department
- Sends structured email reports to the respective HOD
- All in real time — fully automated.

**⚙️ Tech Stack & Key Features**
**🔄 n8n Workflow Automation**
- End-to-end automation created in n8n
- Workflow triggered by Google Sheets Form submissions
- Modular design with Switch, IF, and Code nodes

**🤖 LLM + Sentiment Analysis**
- Sentiment Analysis Node
- Detects whether a query is Urgent, Negative, Neutral, or Positive
- Custom LLM Chain Node

**Classifies queries into 18+ departments, including:**
- Technical Doubt
- Assignments
- LMS Login
- Attendance
- Fees/Payment Issue
- Career Guidance
- Certificates
- Doubt Sessions

**📧 Automated Email Routing**
Smart logic nodes determine the correct department based on:
- Sentiment
- Classified category

**Customized Email Node sends clean, structured reports to:**
- HODs
- Coordinators
- Support teams

**⚡ Impact & Results**
- ✔️ Zero manual triage — system auto-routes all queries
- ✔️ Faster response time for urgent/negative sentiment queries
- ✔️ Improved communication between students & departments
- ✔️ Scalable & consistent classification using LLM
- ✔️ Demonstrates practical use of AI + automation + workflow design

**🚀 How It Works**
- Student submits a query through Google Form
- Response lands in Google Sheets
- n8n workflow triggers automatically
- Sentiment is analyzed ➝ urgency detected
- LLM categorizes the query
- Smart Switch/IF nodes map the category to a department
- Email report sent to the appropriate HOD

**🧠 Skills Learned & Applied**
- Workflow automation using n8n
- Advanced prompt engineering for LLM classification
- Integration of Google Workspace + AI
- Real-time system design
- Building scalable automation pipelines
- Structured email formatting and logic mapping

**📸 Screenshots**
<img width="1919" height="956" alt="Screenshot 2025-11-13 013556" src="https://github.com/user-attachments/assets/44a21e8e-6feb-454e-bcdc-7d4741ff86e3" />

