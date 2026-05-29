## Post-training (RLHF / DPO)

How raw models become *helpful assistants*.

### Base model vs Chat model:

- **Base GPT**: completes text (might continue your question with more questions)
- **ChatGPT**: actually *answers* your question helpfully

The difference? Post-training.

### The process:

1. **SFT** - Supervised Fine-Tuning on human-written examples
2. **RLHF** - Reinforcement Learning from Human Feedback
3. **DPO** - Direct Preference Optimization (simpler alternative)

Humans rank outputs → model learns "this answer is better than that one"

> This is what makes models *safe* and *useful* - not just capable.
