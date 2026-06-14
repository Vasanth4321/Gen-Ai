# Gen AI

This repository contains Generative AI assignments and projects developed using Python, Google Gemini, and Streamlit.

## Repository Structure

```text
Gen AI/
│
├── README.md
├── .gitignore
│
├── Reasoning_Prompts/
│   └── llm_prompts.ipynb
│
├── Blog_Assistant_Chatbot/
│   ├── app.py
│   ├── gemini_client.py
│   ├── requirements.txt
│   ├── README.md
│   └── .env.example
│
└── AI_Support_Ticket_Triager/
    ├── main.py          
    ├── model.py        
    ├── prompt.py        
    ├── parser.py        
    ├── requirements.txt 
    └── .env  
```

## Reasoning Prompts

### llm_prompts.ipynb

A Jupyter Notebook containing the implementation and experimentation for reasoning prompts like Chain-of-Thought and Tree-of-Thought.

**Technology Used:**

* Python
* Jupyter Notebook
* Generative AI concepts and workflows


## Blog Assistant Chatbot

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

## AI Support Ticket Triager

A Streamlit-based AI automation agent deployed on Hugging Face that ingests, processes, and classifies unstructured incoming customer support tickets. The application helps users:

* Validate and clean raw input ticket text streams
* Map tickets concurrently into structured classifications (Category, Priority, and Routing Queue) to reduce execution latency
* Auto-generate personalized drafts for immediate response replies
* Review complex structured backend metric outputs and schema JSON payloads

**Technology Used:**

* Python
* Streamlit
* LangChain Core & Groq (Llama 3.1 8B)
* Pydantic
* python-dotenv

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/Vasanth4321/Gen-Ai.git
cd "Gen AI"
```

### Reasoning Prompts

Open the notebook:

```bash
jupyter notebook
```

and launch:

```text
Reasoning_Prompts/llm_prompts.ipynb
```

### Blog Assistant Chatbot

Navigate to the Blog Assistant Chatbot directory and follow the instructions in its README file.


### AI Support Ticket Triager

Navigate to the AI Support Ticket Triager directory and follow the instructions in its README file.


## Notes

* API keys are stored using environment variables.
* The `.env` file is not included in version control.
* Virtual environments (`venv`) are excluded from the repository.
* Generated logs and cache files are excluded from version control.

