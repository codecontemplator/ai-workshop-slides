## RAG - Retrieval-Augmented Generation

Give the model access to *your* data without retraining.

### The pipeline:

1. **Chunk** - split documents into pieces
2. **Embed** - convert chunks to vectors (numbers)
3. **Store** - save in a vector database
4. **Query** - embed the user's question
5. **Retrieve** - find most similar chunks
6. **Augment** - inject retrieved text into the prompt
7. **Generate** - LLM answers using the context

--

## Why RAG?

- Up-to-date information (no retraining needed)
- Citable sources
- Works with any LLM