# Relata DB

**Frontier Sovereign Intelligence Database**  
*A [ZySec.AI](https://github.com/ZySec-AI) product — Your AI. Your Data. Your Terms.*

---

Relata DB is a governed temporal knowledge database where **policy, provenance, and bi-temporal history are in the query path** — not bolted on top.

Built for intelligence, security, and compliance workloads that cannot compromise on auditability, data sovereignty, or query correctness.

```sql
SELECT * FROM Threat AS OF '2026-01-01' WITH PROVENANCE
```

## What makes it different

- **Bi-temporal** — every row carries valid-time and system-time; query any point in history
- **Governed** — Cedar-inspired ABAC, cell masking, and PURPOSE-tagged queries in the execution path
- **Multi-modal** — relational, graph, vector, full-text, and identity in one store
- **Protocol-compatible** — speaks Postgres wire, Bolt, S3, Redis, MongoDB, ClickHouse, Arrow Flight, gRPC, MCP
- **Self-hosted** — runs on your infrastructure, air-gapped if needed; no cloud dependency

## Products

| Repo | Description |
|------|-------------|
| [RelataDB](https://github.com/relatadb/RelataDB) | Core database — Rust, AGPL-3.0 |
| [sdk-typescript](https://github.com/relatadb/sdk-typescript) | TypeScript / Node.js SDK |
| [sdk-python](https://github.com/relatadb/sdk-python) | Python SDK |
| [sdk-go](https://github.com/relatadb/sdk-go) | Go SDK |
| [console](https://github.com/relatadb/console) | Web ops console |
| [portal](https://github.com/relatadb/portal) | Marketing site — [relatadb.dev](https://relatadb.dev) |

## Get started

```bash
curl -sSL https://relatadb.dev/install.sh | bash
relata serve
```

👉 [Documentation](https://relatadb.dev) · [Releases](https://github.com/relatadb/RelataDB/releases) · [ZySec.AI](https://github.com/ZySec-AI)

---

*Sovereign Intelligence. Verifiable. Secure. Yours.* 🔒
