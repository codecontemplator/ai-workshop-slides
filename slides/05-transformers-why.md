## The Transformer Architecture

*Deep-dive (skippable if short on time)*

### Why transformers won:

- **Before (RNNs):** process words one at a time, sequentially → slow
- **Transformers:** process all words in parallel → fast, scalable

Published in 2017: *"Attention Is All You Need"*

This parallelism is why we can train on trillions of tokens using thousands of GPUs.
