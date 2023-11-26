# Retrieval Augmented Generation using Google-Flan-T5-XXL on Google-Colab Free GPU
1. Used BitsandBytes to load a 4-bit quantized Google-Flan-T5-XXL model on a colab free GPU using displacement of weights between CPU and GPU
2. Loaded the fp-16 sharded version for better resource management
3. Created vector database for the query documents using HuggingFace Instruct Embeddings (Open Source) and created Inference Pipepline for Retreival Augmented Generation 
4. Finetuning for the specific task using Quantized Low-Rank Adaptation (QLoRa)
