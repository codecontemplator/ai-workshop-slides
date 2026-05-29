## Prompt Engineering

The simplest customization - shaping behavior through instructions.

### Techniques:

- **System prompts** - set persona, rules, constraints
- **Few-shot examples** - show input/output pairs
- **Chain-of-thought** - "think step by step"
- **Output formatting** - "respond in JSON"

### Example:

```
System: You are a senior code reviewer. Be concise.
        Flag security issues. Use bullet points.

User: Review this function...
```

No model changes. No infrastructure. Just better instructions.
