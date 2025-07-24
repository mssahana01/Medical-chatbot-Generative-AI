# Medical-chatbot-Generative-AI
This project is an AI-powered medical chatbot that allows users to ask questions from a medical encyclopedia and receive intelligent, context-aware answers.

## 🔧 Tech Stack
- **Python** for backend logic
- **Pinecone** for vector similarity search
- **OpenAI API** for generating natural language responses
- **Flask** for web integration
- **Medical Encyclopedia** as the knowledge base (processed and chunked)


## 📌 Features
- Upload and process medical text data
- Chunk and embed content using Pinecone
- Semantic search to retrieve relevant context
- Conversational answers powered by OpenAI
- Simple and responsive Flask-based web app


## How to run?
### STEPS:


Clone the repository

```bash
   project repo: https://github.com/mssahana01/Medical-chatbot-Generative-AI.git
```

### step 1 - Create a conda environment after opening the repository
```bash
   conda create -n medibot python=3.12 -y
```

```bash
   conda activate medibot
```

### step 2 - Install the requirements
```bash
   pip install -r requirements.txt
```

```ini
PINECONE_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
OPENAI_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
```


```bash
# Run the following command to store embeddings to pinecone
python store_index.py
```

```bash
#Finally run the following command
python app.py
```



