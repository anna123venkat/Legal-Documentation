# Offline Research Assistant

This project is an offline research assistant powered by LLAMA2, utilizing FAISS for efficient document retrieval and natural language processing.

## Features
- Offline research capabilities
- FAISS-based vector storage for document search
- LLAMA2 for intelligent responses
- Chainlit for interaction

## Installation

1. Clone the repository:
   ```bash
   git https://github.com/anna123venkat/Offline-Research-Assistant.git
   cd Offline-Research-Assistant
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables in `.env` (if required).

## Usage

### Ingest Data
To process documents and store embeddings:
```bash
python ingest.py
```

### Run the Assistant
To start the research assistant:
```bash
python a.py
```

## Project Structure
```
.project_root/
│── .chainlit/
│   ├── config.toml
│
├── data/
│   ├── 71763-gale-encyclopedia-of-...
│
├── docs/
│   ├── flowchart.png
│
├── src/
│   ├── .chainlit/
│   ├── __pycache__/
│   ├── a.py
│   ├── ingest.py
│   ├── model.py
│
├── vectorstore/db_faiss/
│   ├── index.faiss
│   ├── index.pkl
│
├── .env
├── .gitattributes
├── README.md
├── requirements.txt
```

## References
- [FAISS - Facebook AI Similarity Search](https://faiss.ai/)
- [LLAMA2 - Meta AI](https://ai.meta.com/llama/)
- [Chainlit - Interactive LLM UI](https://github.com/Chainlit/chainlit)

## Contributors

- **[Prasanna Venkatesh S](https://github.com/anna123venkat)**
- **[Naboth Demitrius](https://github.com/demi2k-sudo)**
- **[Dinesh Kumar](https://github.com/sudoDinesh)**

