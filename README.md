# HybridRAG: Overview of Hybrid Retrieval Methodologies in RAG

This paper delves into hybrid retrieval architectures and mechanisms within the domain of Retrieval Augmented Generation. 

## Abstract: 
Retrieval-Augmented Generation (RAG) is a prominent and effective method of elevating the quality and relevance of generated content by integrating Large Language Models (LLMs) with a private text corpus or knowledge base for contextualized and fact based responses.  However, as document size and dataset dimensionality and density scale up, the ability to maintain the accuracy and factual consistency of a standard RAG model becomes continuously more challenging. Hybrid RAG models represent a promising advancement in alleviating this issue by integrating diverse data processing capabilities within a unified framework. This study provides a survey of prevalent algorithms used for vector and semantic search, discusses various fusion architectures for merging results, and analyzes their respective performance on gold standard Q&A (question-answering) datasets such as SQuAD and Google's NQ (Natural Questions) Dataset. This study aims to offer insights into past developments in Hybrid RAG methodologies and potential advancements of Hybrid RAG models, setting the stage for future research in integrated generative AI systems.

## RAG Architecture:
![RAG_Architecture-1](https://github.com/user-attachments/assets/27a107bc-e1f7-4905-9735-9732df699e12)

## Hybrid RAG Architecture
![Hybrid_Retrieval_Architecture](https://github.com/user-attachments/assets/c20a9fa0-b4f3-45d7-a9b0-56be4ffb122e)


## Models:
**Sentence Transformer: **
**QA Pipeline: **

## Dataset

## Evaluation Scores

| **Metrics**  | **Base** | **Hybrid** |
|--------------|----------|------------|
| Accuracy     | 60%      | 64%        |
| F1 Score     | 0.38     | 0.42       |
| Precision    | 0.41     | 0.42       |
| Recall       | 0.38     | 0.47       |
| ROUGE-L      | 0.66     | 0.71       |



