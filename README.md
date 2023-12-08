# Retrieval Augmented Generation using Google-Flan-T5-XXL on Google-Colab Free GPU
1. Loaded and split the pdf documents into 1000-sized queryable chunks using HuggingFace Instructor Embeddings
2. Created vector database using ChromaDb to run similarity-search queries on the embeddings for Question-Answering
3. Quantized the Google-Flan-T5-XXL model into 4-bits using BitsandBytes and loaded into a Langchain pipeline
4. Utilized the model to match prompt queries with relevant document sections, generating accurate responses
