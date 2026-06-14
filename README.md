# Gen AI

This repository contains Generative AI assignments and projects developed using Python, Google Gemini, and Streamlit.

## Repository Structure

```text
Gen AI/
│
├── README.md
├── .gitignore
│
├── reasoning_prompts/
│   └── llm_prompts.ipynb
│
├── Blog Assistant Chatbot/
│   ├── app.py
│   ├── gemini_client.py
│   ├── requirements.txt
│   ├── README.md
│   └── .env.example
│
└── AI Support Ticket Triager/
    ├── main.py          
    ├── model.py        
    ├── prompt.py        
    ├── parser.py        
    ├── requirements.txt 
    └── .env  
```

## Reasoning Prompts

### llm_prompts.ipynb

A Jupyter Notebook containing the implementation and experimentation for Task 1.

**Technology Used:**

* Python
* Jupyter Notebook
* Generative AI concepts and workflows

---

## Blog Assistant Chatbot

### Blog Assistant Chatbot

A Streamlit-based chatbot powered by Google's Gemini AI that helps users:

* Generate blog ideas
* Create blog outlines
* Improve existing content
* Generate SEO-friendly content
* Download generated responses as Markdown files
* Download complete conversation history

**Technology Used:**

* Python
* Streamlit
* Google Gemini API
* python-dotenv

Refer to the Blog Assistant Chatbot README for detailed setup and usage instructions.

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Vasanth4321/Gen-Ai-Tasks.git
cd "Gen AI"
```

### Reasoning Prompts

Open the notebook:

```bash
jupyter notebook
```

and launch:

```text
reasoning_prompts/llm_prompts.ipynb
```

### Blog Assistant Chatbot/

Navigate to the Blog Assistant Chatbot directory and follow the instructions in its README file.

---

### AI Support Ticket Triager

Navigate to the AI Support Ticket Triager directory and follow the instructions in its README file.

---

## Notes

* API keys are stored using environment variables.
* The `.env` file is not included in version control.
* Virtual environments (`venv`) are excluded from the repository.
* Generated logs and cache files are excluded from version control.

---
## Author

Vasanth Neeli
