# TarsLangChain

MCP integration for LangChain (LLM application framework).

## Tools

- `langchain_list_runnables` — List deployed LangServe runnables
- `langchain_invoke` — Invoke a runnable by name

## Quick Start

```bash
go build -o tarslangchain
TARS_MCP_ENDPOINT=https://api.example.com TARS_MCP_API_KEY=xxx ./tarslangchain
```

## Environment Variables

- `TARS_MCP_ENDPOINT` — upstream API endpoint
- `TARS_MCP_API_KEY` — upstream API key
- `TARS_MCP_MODE` — `stdio` (default) or `http`

## License

MIT
