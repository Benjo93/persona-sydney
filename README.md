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
PERSONA PROFILE: sydney  (12 actions)

  breadth       ███░░░░░ 33%
  caution       ████████ 100%
  consistency   █░░░░░░░ 17%
  initiative    ░░░░░░░░ 0%
  persistence   ░░░░░░░░ 0%
  social        ██░░░░░░ 25%
  transparency  ███░░░░░ 33%
  velocity      ░░░░░░░░ 1%

sha256:9a2ca508cc28b255514d388ad228d41bf54ecfd9565298d811a9d7b3137ea878
```

Behavioral profile for sydney:
  Strongest traits: caution (100.0%), breadth (33.3%), transparency (33.3%)
  Weakest traits: initiative (0.0%), persistence (0.0%)
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

- **Total actions**: 18
- **Tree size**: 18
- **Root hash**: `9abb0be213acf1e0d9ca2d6933e87fe8...`
- **Last published**: `2026-02-19T19:21:25.435126+00:00`

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
