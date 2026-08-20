# Instalação detalhada

SEMA PA: Lista de Desmatamento Ilegal do Pará (LDI) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sema_pa_ldi`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sema_pa_ldi` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sema_pa_ldi` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sema_pa_ldi` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sema_pa_ldi` (ou `servers.sema_pa_ldi` no VS Code) do config do cliente e reinicie.
