# Research Assistant LLAMA2

This project is an offline research assistant powered by LLAMA2, utilizing FAISS for efficient document retrieval and natural language processing.

## Features
- Offline research capabilities
- FAISS-based vector storage for document search
- LLAMA2 for intelligent responses
- Chainlit for interaction

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Research-assistant-LLAMA2-main
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

## File Structure
- `ingest.py` - Processes documents into FAISS
- `model.py` - Defines the ML model logic
- `a.py` - Main script to run the assistant
- `data/` - Folder for research documents
- `vectorstore/` - FAISS vector database
- `requirements.txt` - Dependencies list

## License
This project is licensed under the MIT License.

