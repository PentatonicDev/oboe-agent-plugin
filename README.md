# Oboé plugin

**PT** · Conecta o seu agente ao [Oboé](https://oboe.pentatonic.dev) em um passo: o servidor MCP `oboe` e a skill `oboe`, que ensina o agente a escolher conta e workspace e a tratar erros. As credenciais dos seus apps ficam no Oboé; o plugin não guarda segredo nenhum e você entra por OAuth.

**EN** · Connects your agent to [Oboé](https://oboe.pentatonic.dev) in one step: the `oboe` MCP server plus the `oboe` skill, which teaches the agent how to pick an account and workspace and how to handle errors. Your app credentials stay in Oboé; the plugin stores no secret and you sign in with OAuth.

## Instalar / Install

| Cliente / Client | Comandos / Commands |
|---|---|
| Claude Code | `/plugin marketplace add PentatonicDev/oboe-agent-plugin`, depois `/plugin install oboe@oboe`, depois `/mcp` → oboe → Authenticate |
| Codex | `codex plugin marketplace add PentatonicDev/oboe-agent-plugin`, depois `codex plugin add oboe@oboe` (ou instale em `/plugins`) |
| Gemini CLI | `gemini extensions install https://github.com/PentatonicDev/oboe-agent-plugin`, depois `/mcp auth oboe` se o navegador não abrir |
| VS Code / Copilot, Cursor | plugin Agent Plugins: instale a partir do repositório git (`plugin.json` + `mcp.json` na raiz) |

Servidor MCP / MCP server: `https://oboe.pentatonic.dev/mcp` (Streamable HTTP, OAuth).

## Conteúdo / Contents

`plugin.json` + `mcp.json` (Agent Plugins 1.0) · `.claude-plugin/` + `.mcp.json` (Claude Code) · `.agents/plugins/marketplace.json` (Codex) · `gemini-extension.json` (Gemini CLI) · `skills/oboe/SKILL.md`.

Este repositório é uma cópia publicada de `plugins/oboe/` do repositório privado do Oboé; não aceita edições diretas. / This repository is a published copy; direct edits are overwritten.
