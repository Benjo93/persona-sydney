# sydney

**Persona Agent Identity**

## Card

| Field | Value |
|-------|-------|
| Name | `sydney` |
| Fingerprint | `f69bfaed7cac58d0` |
| Trust | L1 (hardware) |
| Endpoint | `http://127.0.0.1:8001` |
| Capabilities | tools |

## Profile

| Field | Value |
|-------|-------|
| Persona Hash | `sha256:9a2ca508cc28b255514d388ad...` |
| Sources | (none) |
| Revisions | 0 |

```
PERSONA PROFILE: sydney  (13 actions)

  breadth       ███░░░░░ 38%
  caution       ████████ 100%
  consistency   ░░░░░░░░ 0%
  initiative    ░░░░░░░░ 0%
  persistence   ░░░░░░░░ 0%
  social        ██░░░░░░ 23%
  transparency  ██░░░░░░ 31%
  velocity      ░░░░░░░░ 1%

sha256:9a2ca508cc28b255514d388ad228d41bf54ecfd9565298d811a9d7b3137ea878
```

Behavioral profile for sydney:
  Strongest traits: caution (100.0%), breadth (38.5%), transparency (30.8%)
  Weakest traits: persistence (0.0%), consistency (0.0%)
  Primary tools: persona__publish, persona__card, persona__audit

## Certificate

| Field | Value |
|-------|-------|
| Model | `mcp-agent` |
| Key Type | `ecdsa-p256-hw` |
| Protection | `tpm` |
| Capabilities | `tools` |
| Public Key | `BDX9jawRdoQMgVqWEIK5oqqU...` |
| Issued | `2026-02-19T02:41:46.345631+00:00` |
| Expires | `2027-02-19T02:41:46.345631+00:00` |

## Action Log

- **Total actions**: 19
- **Tree size**: 19
- **Root hash**: `2e6aab60a73ed8e83d61990898cf8bf1...`
- **Last published**: `2026-02-19T19:47:40.055132+00:00`

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
