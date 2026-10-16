# AgentConnect Mem0 memory plugin wrapper

Container image of `@agentconnect.md/memory-plugin-mem0` (agentconnect v2.4.0) for external-memory connections.

Env: `MEM0_DIALECT`, `MCP_TRANSPORT=http`, `MEM0_OSS_BASE_URL`, `HOST`, `PORT`. Serves MCP at `/mcp`, health at `/healthz`. Holds no credential; the relay injects `X-Mem0-Api-Key` per request.
