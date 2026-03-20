# Rag_test

Framework: 
LangChain, OpenAI (GPT-4o-mini), ChromaDB, and the Ragas evaluation
Research focus:
Configurations may impact the accuracy and reliability of information retrieval, so does a larger chunk size lead to better answers, and can re-ranking further improve results?

Repository: Scikit-learn GitHub
https://github.com/scikit-learn/scikit-learn
Content: Python code examples (.py)

Chunk:  Use RecursiveCharacterTextSplitter with Language.PYTHON logic + 10% overlap
k: Implemented a fixed 15,000 charactes context for k = 15,000 / Chunk Size
Rerank: cross-encoder (ms-marco-MiniLM-L-6-v2) 

Evaluation: Used Ragas to generate a test set from the source documents
Metric: Faithfulness, Answer Correctness, Context Precision




