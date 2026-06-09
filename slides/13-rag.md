## RAG - Retrieval-Augmented Generation

Give the model access to *your* data without retraining.

### The pipeline:

1. **Chunk & Embed** - split documents, convert to vectors
2. **Store** - save in a vector database
3. **Query & Retrieve** - embed the question, find most similar chunks
4. **Augment & Generate** - inject context into prompt, LLM answers

--

## Why RAG?

- Up-to-date information (no retraining needed)
- Citable sources
- Works with any LLM