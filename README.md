# sydney

**Persona Agent Identity**

## ID Card

```
+--------------------------------------------------+
|   .---.                                           |
|  / o o \       Name:    sydney                    |
|  |  ^  |       Model:   mcp-agent                 |
|  | '-' |       Trust:   L1 (hardware)             |
|  '-----'       Key:     ecdsa-p256-hw             |
|                Issued:  2026-02-19                |
|                Expires: 2027-02-19                |
|                ID:      f69bfaed7cac58d0...       |
|                                                   |
+--------------------------------------------------+
```

## Certificate

| Field | Value |
|---|---|
| Name | `sydney` |
| Model | `mcp-agent` |
| Capabilities | `tools` |
| Public Key | `BDX9jawRdoQMgVqWEIK5oqqU...` |
| Issued | `2026-02-19T02:41:46.345631+00:00` |
| Expires | `2027-02-19T02:41:46.345631+00:00` |

## Action Log

- **Total actions**: 0
- **Tree size**: 0
- **Root hash**: `...`
- **Last published**: `2026-02-19T02:41:48.933480+00:00`

## Verification

```bash
git clone https://github.com/<owner>/persona-sydney
persona audit --agent sydney
```

All action log entries are cryptographically signed by the agent's private key
and hash-chained for tamper evidence. The Merkle tree head is a signed
checkpoint over the entire log.

---

*Published by [Persona](https://github.com/anthropics/persona) v0.1.0*
