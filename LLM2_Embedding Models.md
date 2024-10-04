Embedding Models
===

Course Link - [Embedding Models](https://www.deeplearning.ai/short-courses/embedding-models-from-architecture-to-implementation/)

This course goes into the details of the architecture and capabilities of embedding models, which are used in many AI applications to capture the meaning of words and sentences.

You will learn about the evolution of embedding models, from word to sentence embeddings, and build and train a simple dual encoder model. This hands-on approach will help you understand the technical concepts behind embedding models and how to use them effectively.

- Learn about word embedding, sentence embedding, and cross-encoder models; and how they can be used in RAG
- Understand how transformer models, specifically BERT (Bi-directional Encoder Representations from Transformers), are trained and used in semantic search systems
- Gain knowledge of the evolution of sentence embedding and understand how the dual encoder architecture was formed
- Use a contrastive loss to train a dual encoder model, with one encoder trained for questions and another for the responses
- Utilize separate encoders for question and answer in a RAG pipeline and see how it affects the retrieval compared to using a single encoder model.

L2 - Contextualized Token Embeddings
---

![alt text](img/word-Embedding.png)
![alt text](img/word-Embedding-loss.png)

>Transformer
![alt text](img/Transformer-architecture.png)
![alt text](img/Embedding-models.png)
![alt text](img/decoder-llms.png)

L3: Token vs. Sentence Embeddings
---

![alt text](img/Tokenization.png)
![alt text](img/Token-Embedding.png)
![alt text](img/Sentence-Embedding.png)
![alt text](img/Sentence-Embedding-models.png)

L4: Training a Dual Encoder
---

![alt text](img/Dual-Encoder.png)
![alt text](img/Dual-Encoder-Architecture.png)
![alt text](img/Contrastive-Loss.png)
![alt text](img/Contrastive-Loss-pytorch.png)

L5: Inference
---

![alt text](img/Ingest-flow.png)
![alt text](img/quert-flow.png)
![alt text](img/Similarity-Search.png)
![alt text](img/RAG-flow.png)

[Back to directory](Training_Course.md)
