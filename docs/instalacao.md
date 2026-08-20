# Instalação detalhada

Conselho Regional de Enfermagem SP: Cadastro é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_coren_sp_cadastro`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_coren_sp_cadastro` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_coren_sp_cadastro` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_coren_sp_cadastro` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.coren_sp_cadastro` (ou `servers.coren_sp_cadastro` no VS Code) do config do cliente e reinicie.
