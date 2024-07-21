Here an LLM is used to answer questions in texts, implementing the information retrieval technique called Recursive Abstractive Processing for Tree-Organized Retrieval (RAPTOR).

Reference paper: *https://arxiv.org/abs/2401.18059*

Here's what is done:
- Text from 3 textbooks have been extracted (links in textbooks.md).
- A recursive tree structure is formed out of context chunks.
- Hybrid retrieval techniques involving bm25 and dpr have been employed.
- Metadata of all nodes have been stored in a Milvus database.
- For answering questions and summarizing, Google's Gemini API has been used.
- For encoding sentences, SBert has been used.
