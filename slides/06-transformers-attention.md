## Attention Mechanism

*Deep-dive (skippable if short on time)*

> "Which words should I focus on when predicting the next one?"

Example: *"The **bank** of the **river** was muddy"*

Attention lets the model learn that "bank" here relates to "river", not finance.

### Self-attention in brief:

1. Each token asks: "how relevant is every other token to me?"
2. Assigns attention scores (weights)
3. Combines information from the most relevant tokens
