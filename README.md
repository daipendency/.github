# Daipendency: Provide LLMs with context about software dependencies

Daipendency provides AI coding agents with all the information they need about any of your software dependencies, thus increasing the likelihood of getting the right code the first time around. You can [integrate it as an MCP server in your favourite coding agent](https://github.com/daipendency/daipendency-mcp) (e.g. Claude, Cursor), or [use it manually via the CLI](https://github.com/daipendency/daipendency).

This is meant as a more convenient and accurate alternative to relying on the LLM's outdated training input (when using popular dependencies), or having to instruct your agent to scrape and index the online documentation for a particular dependency (and keeping it in sync as dependencies are upgraded).

This project was inspired by [Aider's _repository map_](https://aider.chat/docs/repomap.html).
