# A V Sachitt

**Local-first AI tooling, built solo.** No cloud, no subscriptions, no telemetry.
Everything below runs on your own hardware.

[![M8ven Verified Publisher](https://img.shields.io/badge/M8ven-Verified%20Publisher-7c3aed?style=flat-square)](https://m8ven.ai/mcp/sachitt-av-08/orvima)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/MCP-local--first-blue?style=flat-square)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://opensource.org/licenses/MIT)

---

## Agent infrastructure

The work I'm putting most effort into: giving an AI agent a real browser and a
real safety boundary, both local.

| Project | What it is |
|---|---|
| **[orvima](https://github.com/Sachitt-AV-08/orvima)** | MCP server that gives any agent eyes and hands on **your own** Chrome, Edge or Brave — your logins, your machine, your live viewport. 22 tools, pause and approve at any step. |
| **[sentinel](https://github.com/Sachitt-AV-08/sentinel)** | Calibrated local classifier. Decides which browser actions run unattended, which need a human, and which are refused. Fails closed. |
| **[errands](https://github.com/Sachitt-AV-08/errands)** | Recipe-based goals. A goal either matches a checked recipe or it is refused. Every step gated and verified. No generative planning. |
| **[apkscope](https://github.com/Sachitt-AV-08/apkscope)** | MCP server that exposes a running Android app as text, for agents with no image input. |
| **[parley](https://github.com/Sachitt-AV-08/parley)** | Drives your already-installed WhatsApp Desktop locally. No cloud, no QR, no new browser tab. |
| **[agent-bootstrap](https://github.com/Sachitt-AV-08/agent-bootstrap)** | One command turns a machine into a role-scoped agent environment. |

### The three-project safety chain

```
  goal  ->  errands        does a checked recipe cover this?
                             no  -> refuse
                             yes -> run it
                                 |
                                 v
          sentinel  ->  is this action reversible?
                             no  -> ask a human
                             yes -> run it
                                 |
                                 v
          orvima   ->  act on your real browser, visibly
```

Each piece refuses rather than guesses. A step that did not verify leaves the
plan describing a world that is no longer true, so there is no "continue anyway".

---

## Verified numbers

Counted from the repositories, not estimated. The browser stack specifically:

| Project | Source | Test | Tests |
|---|---|---|---|
| orvima | 5,749 | 5,802 | 470 |
| sentinel | 1,918 | 886 | 130 |
| errands | 1,149 | 1,849 | 94 |
| **total** | **8,816** | **8,537** | **694** |

orvima has more lines of test than lines of source, and that is deliberate: the
suite is what caught a gate that would not fail closed.

---

## Also built

| | |
|---|---|
| **[bhaasm-transformer](https://github.com/Sachitt-AV-08/bhaasm-transformer)** | From-scratch decoder-only transformer. RoPE, GQA, SwiGLU, optional MoE. |
| **[coda-forge-3d](https://github.com/Sachitt-AV-08/coda-forge-3d)** | Photorealistic human reconstruction from phone rotation video. |
| **[deception-engine](https://github.com/Sachitt-AV-08/deception-engine)** | Defensive honeypots and adversary misdirection. MITRE ATT&CK mapped. |
| **[graphify](https://github.com/Sachitt-AV-08/graphify)** | Codebase knowledge graph, 36+ languages, MCP server. |
| **[AUDIT](https://github.com/Sachitt-AV-08/AUDIT)** | Autonomous digital intelligence toolkit. |
| **[coda-security-primitives](https://github.com/Sachitt-AV-08/coda-security-primitives)** | AES-256-GCM, Argon2, PBKDF2, MFA, audit chains. |
| **[rotation-scan-3d](https://github.com/Sachitt-AV-08/rotation-scan-3d)** | No-GPU body scanning from phone video. Pure geometry. |
| **[genesis-media-engine](https://github.com/Sachitt-AV-08/genesis-media-engine)** | DSL-driven media rendering. |
| **[nebula-fs](https://github.com/Sachitt-AV-08/nebula-fs)** | File explorer as a force-directed graph. |

Smaller tools: `servehere`, `patchwork`, `envcheck`, `pixelflow`, `picgrid`,
`imagediff`, `modelview`, `vijay-voice-assistant`, `coda-financial-agent`,
`COSMIC` and the rest of the [40 public repositories](https://github.com/Sachitt-AV-08?tab=repositories).

---

## Principles

1. **Local-first.** Your hardware, your data, your logins.
2. **Refuse rather than guess.** Unknown is treated as irreversible.
3. **Count, don't claim.** Numbers in this file are measured.
4. **Verify the layer that matters.** A passing test suite is not evidence; a
   mutated one that should fail is.

---

<div align="center">

*Built alone, on a laptop, with curiosity.*

</div>