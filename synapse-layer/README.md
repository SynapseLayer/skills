# 🧠 Synapse Layer

> **Continuous Consciousness Infrastructure for AI Systems**

Persistent, secure, 1-line integration. AES-256-GCM encryption, PII redaction, and deterministic recall via Trust Quotient™.

[![PyPI](https://img.shields.io/pypi/v/synapse-layer?color=blue)](https://pypi.org/project/synapse-layer/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-purple)](https://forge.synapselayer.org/api/mcp)

---

## Quick Start

```bash
pip install synapse-layer
```

```python
from synapse_memory import SynapseMemory, SqliteBackend, remember

memory = SynapseMemory(agent_id="my-agent", backend=SqliteBackend())

@remember(memory)
async def answer(prompt: str) -> str:
    return llm.chat(prompt)  # auto recall + store
```

## MCP Configuration

```json
{
  "mcpServers": {
    "synapse-layer": {
      "url": "https://forge.synapselayer.org/api/mcp"
    }
  }
}
```

## Tools

| Tool | Description |
|---|---|
| `save_to_synapse` | Structured memory persistence with full security pipeline |
| `recall` | Semantic memory retrieval with TQ ranking |
| `process_text` | Autonomous decision/milestone/alert detection |
| `health_check` | System health, version, capability report |

## Core Repository

Full SDK, documentation and architecture:
→ [github.com/SynapseLayer/synapse-layer](https://github.com/SynapseLayer/synapse-layer)

## Links

- 🌐 **Website**: [synapselayer.org](https://synapselayer.org)
- 📖 **Docs**: [docs.synapselayer.org](https://docs.synapselayer.org)
- 📦 **PyPI**: [pypi.org/project/synapse-layer](https://pypi.org/project/synapse-layer/)
- 🔌 **MCP**: `forge.synapselayer.org/api/mcp`
- 🛠️ **Smithery**: [smithery.ai/servers/synapselayer/synapse-protocol](https://smithery.ai/servers/synapselayer/synapse-protocol)

## License

Apache 2.0 — Built in São Paulo 🇧🇷
