🛂 SwiftVisa – AI-Based UK Visa Eligibility Screening Agent

SwiftVisa is an AI-powered web application that evaluates a user’s eligibility for different UK visa categories using official UK visa policy documents. The system combines Retrieval-Augmented Generation (RAG) with a Large Language Model (LLM) to provide accurate, policy-based eligibility decisions along with clear explanations.

🔗 Live Application:
https://swift-visa-ai-based-uk-visa-eligibility-screening-agent-4xpafm.streamlit.app/

🚀 Key Features

Multi-visa eligibility screening in a single platform

Step-by-step visa application workflow

AI-driven eligibility decision with reasons

Official UK visa policy PDF integration

Policy-grounded responses using RAG

Clean, professional Streamlit UI

🧠 Supported Visa Types

Student Visa

Graduate Visa

Skilled Worker Visa

Health & Care Visa

Visitor Visa

🛠️ Technologies Used

Python – Core application logic

Streamlit – Interactive web interface

Groq LLM (LLaMA 3.1) – AI eligibility decision engine

Vector Database (Embeddings) – Semantic search over visa rules

RAG (Retrieval-Augmented Generation) – Grounds AI decisions in policy

PyPDF2 – Extracts text from visa policy PDFs

HTML & CSS – Custom UI styling

Session State Management – Multi-step form handling

⚙️ How the System Works

User selects a visa category

User enters personal and visa-specific details

Relevant visa rules are retrieved from policy PDFs using vector search

Retrieved rules are combined with user inputs using RAG

AI evaluates eligibility based on official policies

Final decision is shown as Eligible / Not Eligible with reasons

📁 Project Structure
AIShiftVisaEligibility/
│
├── AllVisaEligibility.py        # Main Streamlit application
├── DataSets/                    # UK visa policy PDFs
│   ├── Student Visa.pdf
│   ├── Graduate Visa.pdf
│   ├── Work Visa.pdf
│   ├── Health Visa.pdf
│   └── Visitor Visa.pdf
├── assets/                      # UI assets (optional)
├── requirements.txt             # Dependencies
└── README.md

▶️ Running the Project Locally
1. Install dependencies
pip install -r requirements.txt

2. Set Groq API Key
export GROQ_API_KEY="your_api_key"


(Windows PowerShell)

$Env:GROQ_API_KEY="your_api_key"

3. Run the application
streamlit run AllVisaEligibility.py

📌 Output Example
Decision: NOT ELIGIBLE

Reasons:
- CAS not issued
- Minimum salary requirement not met
- English language requirement not satisfied

📄 License

This project is currently **not licensed**.  
All rights are reserved by the project author.

👤 Author

SwiftVisa – AI Visa Eligibility Project
Developed as an AI-driven policy-based eligibility screening system.
