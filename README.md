Interview Trainer Agent (RAG + IBM Granite)

An AI-powered interview preparation assistant built using Retrieval-Augmented Generation (RAG).

Features

* Generates role-specific interview questions
* Provides model answers and preparation tips
* Supports technical and behavioral interviews
* Uses FAISS for knowledge retrieval
* Powered by IBM Granite (or Hugging Face fallback)

 Tech Stack

* Python
* LangChain
* FAISS
* Sentence Transformers
* IBM Granite
* Transformers
  
 Usage

```python
interview_trainer(
    "Yamini",
    "Entry-Level",
    "Software Engineer",
    "Give me 5 likely interview questions and model answers."
)
```

 Project Structure: 

```text
interview-trainer-agent/
│── README.md
│── interview_trainer_agent.py
│── requirements.txt
└── data/
```

 Future Improvements:

* Resume upload support
* Interactive mock interviews
* More job-role datasets
* Interview scoring system

License:

MIT License
