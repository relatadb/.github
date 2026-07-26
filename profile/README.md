# Relata DB

**Frontier Sovereign Intelligence Database**  
*A [ZySec.AI](https://github.com/ZySec-AI) product — Your AI. Your Data. Your Terms.*

---

<p align="center">
  <img src="https://raw.githubusercontent.com/relatadb/.github/main/profile/relatadb-concept.svg" alt="Relata DB — connect any dataset, query any moment" width="860"/>
</p>

---

Governed temporal knowledge database where **policy, provenance, and bi-temporal history are in the query path** — not bolted on top. Built for intelligence, security, and compliance workloads that cannot compromise on auditability or data sovereignty.

## Get started in seconds

```bash
# Run with Docker
docker run -p 9090:9090 ghcr.io/relatadb/relatadb:latest

# Pick your SDK
pip install relata-sdk                        # Python
npm install @zysec-ai/relata-sdk              # TypeScript
go get github.com/relatadb/sdk-go             # Go
```

## What makes it different

- **Bi-temporal** — every row carries valid-time and system-time; query any point in history
- **Governed** — Cedar-inspired ABAC, cell masking, and PURPOSE-tagged queries in the execution path
- **Multi-modal** — relational, graph, vector, full-text, and identity in one store
- **Protocol-compatible** — Postgres wire, Bolt, S3, Redis, MongoDB, ClickHouse, Arrow Flight, MCP
- **Self-hosted** — runs on your infrastructure, air-gapped if needed; no cloud dependency

## SDKs

| Repo | Language | Package |
|------|----------|---------|
| [sdk-typescript](https://github.com/relatadb/sdk-typescript) | TypeScript / Node.js | `npm install @zysec-ai/relata-sdk` |
| [sdk-python](https://github.com/relatadb/sdk-python) | Python | `pip install relata-sdk` |
| [sdk-go](https://github.com/relatadb/sdk-go) | Go | `go get github.com/relatadb/sdk-go` |

---

👉 [Documentation](https://relatadb.dev) · [Releases](https://github.com/relatadb/RelataDB/releases) · [ZySec.AI](https://github.com/ZySec-AI)

*Sovereign Intelligence. Verifiable. Secure. Yours.* 🔒
