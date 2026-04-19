# DineroMcp

DineroMcp er en MCP server til Dinero. Dette er ikke et officielt produkt fra Visma/Dinero, men et produkt udviklet og tilføjet for at hjælpe virksomheder med at bruge MCP server med Dinero.

**OBS! OBS! OBS! IKKE SUPPORTERET AF VISMA/DINERO OBS! OBS! OBS!**

## Sådan kommer du igang i Claude
I Claude tilføjer du `https://mcp.dineroai.app/mcp` som MCP server.

## Sådan kommer du igang i andre værktøjer (eksempelvis Visual Studio Code)
Lav eller rediger en `.mcp.json` fil.

Tilføj følgende:

```json
{
  "mcpServers": {
    "dinero": {
      "type": "http",
      "url": "[https://your-server-host/mcp](https://mcp.dineroai.app/mcp)"
    }
  }
}
```

## Prompting
Hvis du skal snakke med Dinero, skal du huske at referere dit organisations nummer. Du kan enten tilføje dette til din `memory.md` eller `claude.md` fil.

Eksempel på prompts:

```prompt
Find alle kontakter i organization 455490
```

# Feedback
Brug `Issues` på dette repository, så kan du give feedback.
