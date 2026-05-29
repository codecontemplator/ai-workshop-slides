## Tool Use & MCP

Let the LLM *do* things, not just talk about them.

### Function/Tool calling:

The LLM decides when to invoke an external tool:

- Calculator, database query, API call, web search
- The model outputs a structured tool call, your code executes it

### MCP (Model Context Protocol):

An open protocol for connecting LLMs to tools and data sources.

- Standardized way to expose tools
- Works with Claude Desktop, OpenCode, and others
- Example: file system access, GitHub, databases

> The LLM becomes an *orchestrator*, not just a text generator.
