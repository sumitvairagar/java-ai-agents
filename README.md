# java-ai-agents

How AI agent frameworks in Java work **inside**: Spring AI, Embabel and A2A.

This is not a tutorial collection. Each week I take one part of a framework, follow a real call through its source code, and test what I think I learned with small experiments, including breaking it on purpose.

## How each week works
1. **Questions.** What do I want to understand about this mechanism?
2. **Source walkthrough.** Follow one real call: class → method → `file:line`, pinned to a version.
3. **Experiments.** Small code that proves or breaks what I think happens inside.
4. **Notes.** What I learned, what surprised me, what's still unclear.

## Weeks
| # | Mechanism | Folder |
|---|---|---|
| 1 | What Spring AI does between `.call()` and the model | [01-chatclient](01-chatclient) |
| 2 | The Advisor chain: order, state, and what each one changes | [02-advisors](02-advisors) |
| 3 | Tool calling and MCP: who decides, who executes, where it loops | [03-tools-mcp](03-tools-mcp) |
| 4 | RAG: from document to retrieved context in the prompt | [04-rag](04-rag) |
| 5 | Observability: which spans and metrics exist, and where they're created | [05-observability](05-observability) |
| 6 | Embabel: how GOAP plans actions on top of Spring AI | [06-embabel](06-embabel) |
| 7 | A2A: what crosses the wire between two Java agents | [07-a2a](07-a2a) |
| 8 | The whole picture | [08-wrap-up](08-wrap-up) |
