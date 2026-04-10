# Synapse Layer — Zero-Knowledge Persistent Memory for AI Agents

This PR adds the **Synapse Layer** skill to the inference.sh skills directory.

## 🧠 What is Synapse Layer?

Synapse Layer is the first **zero-knowledge persistent memory layer** for AI agents. It enables agents to:
- Remember user preferences across sessions
- Transfer context between models (Claude → GPT → Gemini)
- Store encrypted memories with AES-256-GCM
- Recall past conversations semantically
- Resolve conflicting information automatically

## 🔑 Key Features

- **Zero-Knowledge Context™** — AES-256-GCM encryption before data leaves client
- **Neural Handover™** — HMAC-signed context transfer between models
- **Consensus Engine™** — Trust Quotient formula resolves contradictions
- **Semantic Recall** — pgvector HNSW for intelligent memory retrieval
- **MCP-Native** — Works with any MCP-compatible agent
- **LGPD/GDPR Compliant** — Soft-delete, audit trails, user control

## 📦 Installation

```bash
npm install -g synapse-layer
synapse remember "User prefers TypeScript" --user user_123
```

## 🔗 Links

- **npm:** https://www.npmjs.com/package/synapse-layer
- **Smithery.ai:** https://smithery.ai/servers/synapselayer/essencial
- **Website:** https://synapselayer.org
- **GitHub:** https://github.com/SynapseLayer/essencial

## 🎯 Why this matters

AI agents currently have amnesia. Every conversation starts from zero. Synapse Layer fixes this by providing persistent, encrypted, cross-model memory.

Built in São Paulo 🇧🇷 by Ismael Marchi.

---

## 📋 Files Added

- `synapse-layer/skill.yaml` — Skill manifest with 6 commands and 12 keywords
- `synapse-layer/README.md` — Complete documentation

## ✅ Checklist

- [x] skill.yaml follows the standard format
- [x] README.md includes installation and usage instructions
- [x] All 6 commands documented (remember, recall, handover, import, status, forget)
- [x] npm package published and tested
- [x] MCP server operational
- [x] Zero-knowledge encryption validated
