# ICCP: Internal Context & Control Protocol
> A lightweight, schema-first standard for AI-to-AI communication and constitutional governance.

![Status](https://img.shields.io/badge/status-stable-brightgreen)
![License](https://img.shields.io/badge/license-Apache_2.0-blue)

## 🧠 Core Concepts
- `ActionRequest`: Structured intent (who, what, where, payload).
- `Decision`: Immutable verdict (status, proof, request_id).
- Topics: `iccp.action.*`, `iccp.decision.*`, `iccp.agent.*`

## 📦 Schema
- [`schema/json/`](schema/json/) — JSON Schema (v1.0)
- [`schema/protobuf/`](schema/protobuf/) — (Future)
- [`schema/rust/`](schema/rust/) — `iccp-schema` crate (re-exported from `axiom-core`)

## 🚀 Adopt ICCP
- [Axiom Core](https://github.com/axiom-org/axiom-core) — Reference impl (Rust + Python)
- [Go SDK](https://github.com/axiom-org/iccp-go) — (Coming soon)

---
Licensed under Apache 2.0. ICCP is a community standard — *not* owned by any company.
