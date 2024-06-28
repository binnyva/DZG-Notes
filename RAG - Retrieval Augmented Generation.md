---
tags:
  - permanent-notes
  - llm
  - rag
date: 2024-06-24 22:57:00
---

If you want to use LLMs with your own data, you can do it using RAG. You'll have to create a RAG Pipeline...

## Steps in RAG Pipeline

![[RAG Pipeline.excalidraw]]

#### Extract data from the documents

This can be easier for text/markdown documents. But more complex for PDF, scanned documents, images, etc.

#### [[Chunking in RAG]]

Split the documents in smaller chunks according to some metric. This can be character length, paragraphs, semantics, etc.

#### Create Embeddings

Convert each chunk into an vector - these are called embeddings. 

#### Store Embeddings in a [[Vector Database]]

#### User Query

When a query is made, an embedding of the query is matched against the vector DB and the top resulting chunks are returned.

#### Prompt Generation

The system will make a prompt with both the query and the top chunks. Something along the lines of...

```
Using this context...
[Chunks return in the vector db search]

Answer this question...
[User Query]
```

#### LLM Response

We then send the entire prompt to an LLM - and fetch the response. Depending on the chuck size and number of chunks that we include in the prompt, this can be big. Some optimization will be required to keep the token size low.

## Advanced Usage

You can have multiple pipelines in play - for different use cases or even different types of questions. Just have a router to execute the right pipeline when you get the question.

If RAG is fitting your use case, the next option you have is fine-tuning the model for your use case.
