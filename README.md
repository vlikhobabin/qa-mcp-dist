# qa-mcp distribution

Public delivery channel for **qa-mcp** (native 1C TestClient QA — Windows model‑B, thin cross‑machine).

## What ships here
Each tagged release attaches the Windows host‑side assets the deploy needs:
- `qa-mcp-host-agent.exe` (+ `.sha256`) — the host display/input agent
- `install-windows-host-agent.ps1`, `bootstrap.ps1`, `windows-agent-runbook.md`, `README.md`

## Run it
The protected MCP image is published to **GHCR**:

```
docker pull ghcr.io/vlikhobabin/qa-mcp-thin:latest
```

Then follow `windows-agent-runbook.md` (or `bootstrap.ps1`) from the latest Release.
