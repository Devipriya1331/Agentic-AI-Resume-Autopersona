# Agentic AI – Resume Autopersona

**Agentic AI – Resume Autopersona** is an AI-powered chatbot that represents a user online by answering questions about their career, skills, and experience. It uses information extracted from a LinkedIn PDF and a summary file to provide accurate responses. The system can also record user details and unknown questions, generate professional resumes, and interact via a user-friendly Gradio interface.



## Features

- AI-based career and skill representation  
- Automatic resume generation using user data  
- Records unknown questions for review  
- Records user emails and notes via Pushover notifications  
- PDF data extraction for LinkedIn profiles  
- Interactive chatbot interface with Gradio  



## Tech Stack

- Python  
- Gradio  
- PyPDF  
- OpenAI Gemini API  
- Pushover API for notifications  
- dotenv for secure API key management  



## Installation

## 1. Clone the repository:
```bash
git clone https://github.com/your-username/agentic-ai-resume-autopersona.git
cd agentic-ai-resume-autopersona
```

## 2.Install required packages:
```
pip install -r requirements.txt
```
## 3.Create a .env file in the project root and add:
```
GEMINI_API_KEY=your_gemini_api_key
PUSHOVER_TOKEN=your_pushover_token
PUSHOVER_USER=your_pushover_user
```
## 4.Place your Resume PDF in the ``` me/ ``` folder and add a summary in ```me/summary.txt```.
### Chatbot Interface

![Chatbot Screenshot](Downloads/resumechatbot1.png)
## How It Works

- User asks a question in the chatbot interface.

- The system retrieves information from the LinkedIn PDF and summary.

- The Gemini AI model generates a relevant response.

- If the system doesn’t know the answer, it records the question for review.

- User emails or other details are optionally recorded using the Pushover notifications system.



## Author

 Devipriya P
