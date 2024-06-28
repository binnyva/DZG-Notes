---
tags:
  - permanent-notes
date: 2024-06-28 13:43:00
---

We'll get the best answer to our question in [[RAG - Retrieval Augmented Generation|RAG]] if we input the entire document collection as the context for the prompt. But this is expensive(large token size for the prompt). So to optimize this we only use the parts of the documents that is relevant to the question as the context. 

To extract these relevant parts, first we divide up the documents to smaller 'chunks' - and search for chunks  related to the question. Then we send only the found chunks as the context.

Creating vector embeddings of these chunks will let us do a semantic search against the question. But there are few decisions to be made to ensure best result - the primary one being chunk size.

You can create a single embedding for a word, a line, entire pages. So you have to decide the optimal chunk size. Too small and it can lose context, too big and it will more expensive without any advantage.

There are splitters that sets Chunk size is the number of character(not number of tokens).

But embedding models have a max token length - so make sure your chunks stay within that length(else the part after the token length will be discarded and not used in the embedding).

You can add metadata to chunks - adding even more context to help with searching.
