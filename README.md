# java-ai-agents

A deep dive into how AI agents work in Java: Spring AI, Embabel and A2A.
Not a tutorial collection. Each week I read the framework's source, trace how it really works, and prove it with small experiments.

## How each week works
1. **Questions first.** What do I want to understand?
2. **Read the source.** Follow one real call through the framework, with file and line references.
3. **Experiment.** Small code that tests what I think I learned, including breaking it on purpose.
4. **Write it down.** `NOTES.md` in the week's folder: what I learned, what surprised me, what's still unclear.

## Weeks
| # | Topic | Folder |
|---|---|---|
| 1 | Spring AI `ChatClient`: how a request flows | [01-chatclient](01-chatclient) |
| 2 | Advisors: memory and safety hooks | [02-advisors](02-advisors) |
| 3 | Tool calling and MCP | [03-tools-mcp](03-tools-mcp) |
| 4 | RAG and vector stores | [04-rag](04-rag) |
| 5 | Observability: traces and metrics | [05-observability](05-observability) |
| 6 | Embabel: GOAP planning on Spring AI | [06-embabel](06-embabel) |
| 7 | A2A with Embabel and a2a-java | [07-a2a](07-a2a) |
| 8 | Putting it together | [08-wrap-up](08-wrap-up) |
