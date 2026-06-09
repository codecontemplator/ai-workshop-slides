## Fine-tuning with LoRA

Change the model's *behavior* by training on your own data.

### The problem with full fine-tuning:

- A 7B model = ~14 GB of weights
- Updating all weights requires massive GPU memory

--

## LoRA (Low-Rank Adaptation)

- Freeze the original weights
- Add tiny trainable "adapter" layers (~1-5% of parameters)
- Train only those adapters
- Result: same effect, fraction of the cost

### Use cases:

- Domain-specific language (legal, medical)
- Consistent output format
- Teaching a specific skill or style