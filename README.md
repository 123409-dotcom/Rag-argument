# RAG-argument 
rag-research-assistant/
│
├── data/
│   ├── papers/
│   └── processed/
│
├── notebooks/
│   ├── 01_document_processing.ipynb
│   ├── 02_embeddings.ipynb
│   └── 03_retrieval.ipynb
│
├── src/
│   ├── ingestion/
│   ├── embeddings/
│   ├── retrieval/
│   ├── generation/
│   └── evaluation/
│
├── app/
│   └── streamlit_app.py
│
├── tests/
│
├── .env.example
├── .gitignore
├── requirements.txt
├── README.md
└── main.py

### 1.DATA
= PAPER add some pdf files in your code so that the pymupdf can be able to read through to your notes that will be provided by the pdf according to the requirements of the user. 
## 2.NOTEBOOKS
1.document_processing this is where you feed the model the pdf files of different issues so that it can load and read through the files and also process the file by removing the error from the files before giving outn results
2.embeddings this is where byt the models is train to show the differences and the similaritie between the files of the pdf that has been given.
3.retrieval this is the final data that enable the model to choose the best and efficient answer that it can give the user after loading from the data that it has been given.

