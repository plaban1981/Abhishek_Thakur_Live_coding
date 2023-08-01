# Abhishek_Thakur_Live_coding
Live coding notebooks
Problem Statement :
Use context and image based search based on the instruction provided.

Packages used :
FAISS
OPENAI
LANGCHAIN
BM25
Sentence Transformers

Workflo steps:
1. Load the image and image descriptions into Vector database which is Faiss in our case.
2. Provide a context based instruction or image to search for similar content.
3. The  content is searched in the vector store and simailr contents are provide.
