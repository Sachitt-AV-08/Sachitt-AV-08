<div align="center">

# A V Sachitt

**Building local-first AI that refuses to guess.**

```
> whoami
A. V. Sachitt  |  17  |  Pre-college
IIITDM Chennai (Smart Manufacturing) + IIT Madras (Data Science)
```

<img src="./pixel-me.gif" width="620" alt="Pixelated reveal of the author">

[![Website](https://img.shields.io/badge/Website-codaos.qzz.io-000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://codaos.qzz.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sachitt-a-v-604224414/)
[![Email](https://img.shields.io/badge/Email-sachittav@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sachittav@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-@sachitt_av-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sachitt_av)
[![M8ven](https://img.shields.io/badge/M8ven-Verified%20Publisher-7c3aed?style=for-the-badge)](https://m8ven.ai/mcp/sachitt-av-08/orvima)
[![Visitors](https://komarev.com/ghpvc/?username=Sachitt-AV-08&color=58a6ff&style=flat-square&label=Profile+Views)](https://github.com/Sachitt-AV-08)

</div>

---

## The stack I'm putting most effort into

An agent that can act on your machine should not be able to act on *anything*.
These three are built so that each one can stop the next.

```
  goal ──▶ errands ──── is there a checked recipe for this?
                │              no ─▶ refuse
                │              yes
                ▼
          sentinel ─────── is this action reversible?
                │              no ─▶ ask a human
                │              yes
                ▼
           orvima ──────── act on your real browser,
                            in a viewport you can pause
```

| | |
|---|---|
| **[orvima](https://github.com/Sachitt-AV-08/orvima)** | MCP server. Any agent gets `browse_*` tools on **your own** Chrome, Edge or Brave - your logins, your machine, your live viewport. 22 tools, 470 tests, MIT. |
| **[sentinel](https://github.com/Sachitt-AV-08/sentinel)** | Calibrated local classifier. Decides which actions run unattended, which need a human, and which are refused. Fails closed, including when it is broken. |
| **[errands](https://github.com/Sachitt-AV-08/errands)** | Recipe-based goals. A goal matches a checked recipe or it is refused. Every step gated, every step verified. No generative planning. |

---

## Featured work

<table>
<tr>
<td width="50%">

### [graphify](https://github.com/Sachitt-AV-08/graphify)
**74,084 lines** &nbsp;|&nbsp; Python

Codebase knowledge graph. Tree-sitter extraction across 36+ languages, an MCP server, and integrations for 20+ AI assistants. The largest thing here, by a wide margin.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/graphify)</sub>

</td>
<td width="50%">

### karna
**56,113 lines** &nbsp;|&nbsp; Python

Neural core with trained weights and a BPE tokenizer. 229 Python modules. Private - ask for access.

<sub>private &middot; ask for access</sub>


</td>
</tr>
<tr>
<td width="50%">

### [orvima](https://github.com/Sachitt-AV-08/orvima)
**14,504 lines** &nbsp;|&nbsp; Python

MCP server giving any AI agent eyes and hands on <b>your own</b> Chrome, Edge or Brave. 22 tools, a live viewport you can pause, and 470 tests.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/orvima)</sub>

</td>
<td width="50%">

### [AUDIT](https://github.com/Sachitt-AV-08/AUDIT)
**13,247 lines** &nbsp;|&nbsp; TypeScript

One shell, many worlds. TypeScript toolkit for running autonomous digital-intelligence environments.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/AUDIT)</sub>


</td>
</tr>
<tr>
<td width="50%">

### [vijay-voice-assistant](https://github.com/Sachitt-AV-08/vijay-voice-assistant)
**6,310 lines** &nbsp;|&nbsp; Python

Modular desktop voice assistant. 30+ capabilities with wake-word detection, running fully local.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/vijay-voice-assistant)</sub>

</td>
<td width="50%">

### [parley](https://github.com/Sachitt-AV-08/parley)
**4,436 lines** &nbsp;|&nbsp; Python

Drives your <b>already-installed</b> WhatsApp Desktop locally. No cloud, no QR, no second browser profile.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/parley)</sub>


</td>
</tr>
<tr>
<td width="50%">

### [rotation-scan-3d](https://github.com/Sachitt-AV-08/rotation-scan-3d)
**3,928 lines** &nbsp;|&nbsp; Python

3D body scanning from a phone rotation video. Pure geometry, zero neural networks, runs on a laptop CPU.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/rotation-scan-3d)</sub>

</td>
<td width="50%">

### [coda-forge-3d](https://github.com/Sachitt-AV-08/coda-forge-3d)
**3,070 lines** &nbsp;|&nbsp; Python

18-stage photorealistic human reconstruction from phone video. COLMAP, Gaussian splatting, geometric fallback.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/coda-forge-3d)</sub>


</td>
</tr>
<tr>
<td width="50%">

### [bhaasm-transformer](https://github.com/Sachitt-AV-08/bhaasm-transformer)
**2,535 lines** &nbsp;|&nbsp; Python

From-scratch decoder-only transformer. RoPE, grouped-query attention, SwiGLU, optional MoE.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/bhaasm-transformer)</sub>

</td>
<td width="50%">

### [deception-engine](https://github.com/Sachitt-AV-08/deception-engine)
**2,076 lines** &nbsp;|&nbsp; Python

Defensive honeypots and canary tokens for adversary misdirection. MITRE ATT&amp;CK mapped.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/deception-engine)</sub>


</td>
</tr>
<tr>
<td width="50%">

### [coda-security-primitives](https://github.com/Sachitt-AV-08/coda-security-primitives)
**1,866 lines** &nbsp;|&nbsp; Python

AES-256-GCM, Argon2, PBKDF2, MFA and tamper-evident audit chains. No dependencies.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/coda-security-primitives)</sub>

</td>
<td width="50%">

### [genesis-media-engine](https://github.com/Sachitt-AV-08/genesis-media-engine)
**1,714 lines** &nbsp;|&nbsp; Python

Declarative DSL for rendering video, audio and images through FFmpeg.

<sub>MIT &middot; [source](https://github.com/Sachitt-AV-08/genesis-media-engine)</sub>


</td>
</tr>
<tr>
<td width="50%">

### claro-studio
**14,718 lines** &nbsp;|&nbsp; TypeScript

AI-native IDE for a small reversible UI language, with live visual editing. Private.

<sub>private &middot; ask for access</sub>


</td>
</tr>
</table>

---

## The rest of the 44 repositories

**Large systems**

| Project | Lines | What it does |
|---|---:|---|
| **[graphify](https://github.com/Sachitt-AV-08/graphify)** | 74,084 lines | Codebase knowledge graph tool ΓÇö 36+ languages, 9+ LLM backends, MCP server, 20+ AI assistant integrations. |
| **[priva](https://github.com/Sachitt-AV-08/priva)** | 23,150 lines | . |
| **[orvima](https://github.com/Sachitt-AV-08/orvima)** | 14,504 lines | Why should Claude be the only one with a browser? Orvima gives any MCP-capable AI (Claude, Cursor, Copilot, your own agent) eyes and hands on your own Chrome or Edge ΓÇö your logins, your machine, your watch. |
| **[AUDIT](https://github.com/Sachitt-AV-08/AUDIT)** | 13,247 lines | AUDIT ΓÇö Autonomous Universal Digital Intelligence Toolkit. |
| **[vijay-voice-assistant](https://github.com/Sachitt-AV-08/vijay-voice-assistant)** | 6,310 lines | Modular desktop voice assistant with 30+ capabilities, wake word detection, and real-time processing. |
| **[parley](https://github.com/Sachitt-AV-08/parley)** | 4,436 lines | Drive your already-installed WhatsApp Desktop locally: read, send, reply, react & schedule ΓÇö no cloud, no QR, no new browser tab. |
| **[rotation-scan-3d](https://github.com/Sachitt-AV-08/rotation-scan-3d)** | 3,928 lines | No-GPU 3D scanning from phone rotation videos ΓÇö pure geometry, no neural networks, no cloud. |
| **[errands](https://github.com/Sachitt-AV-08/errands)** | 3,790 lines | Recipe-based goals: a goal matches a checked recipe or it is refused. |

**COSMIC ecosystem** - composable pieces, each usable on its own

| Project | Purpose |
|---|---|
| **[Cosmic-Core](https://github.com/Sachitt-AV-08/Cosmic-Core)** | The shell the other pieces plug into |
| **[Cosmic-Explore](https://github.com/Sachitt-AV-08/Cosmic-Explore)** | Graph-powered file explorer |
| **[Cosmic-Atlas](https://github.com/Sachitt-AV-08/Cosmic-Atlas)** | 3D codebase knowledge graph |
| **[Cosmic-Debug](https://github.com/Sachitt-AV-08/Cosmic-Debug)** | Visual debugger, traces through time |
| **[Cosmic-Flow](https://github.com/Sachitt-AV-08/Cosmic-Flow)** | Drag-and-drop pipeline builder |
| **[Cosmic-Voice](https://github.com/Sachitt-AV-08/Cosmic-Voice)** | Local speech in, speech out |
| **[Cosmic-Vision](https://github.com/Sachitt-AV-08/Cosmic-Vision)** | Gesture recognition and hand tracking |
| **[Cosmic-Canvas](https://github.com/Sachitt-AV-08/Cosmic-Canvas)** | Sketch to 3D |
| **[Cosmic-Shield](https://github.com/Sachitt-AV-08/Cosmic-Shield)** | Supply chain security for your deps |
| **[Cosmic-Connect](https://github.com/Sachitt-AV-08/Cosmic-Connect)** | Local service registry |

**Small tools** - the ones that get used daily

| Project | What it does |
|---|---|
| **[servehere](https://github.com/Sachitt-AV-08/servehere)** | File server with a QR code &nbsp;·&nbsp; 113 lines |
| **[patchwork](https://github.com/Sachitt-AV-08/patchwork)** | One CLI to set, get and diff YAML/JSON/TOML &nbsp;·&nbsp; 264 lines |
| **[envcheck](https://github.com/Sachitt-AV-08/envcheck)** | Scans code and .env for missing keys &nbsp;·&nbsp; 182 lines |
| **[pixelflow](https://github.com/Sachitt-AV-08/pixelflow)** | Terminal image toolbox &nbsp;·&nbsp; 204 lines |
| **[picgrid](https://github.com/Sachitt-AV-08/picgrid)** | Lays out N images in a labelled grid &nbsp;·&nbsp; docs &amp; design |
| **[imagediff](https://github.com/Sachitt-AV-08/imagediff)** | Before/after slider for model output &nbsp;·&nbsp; docs &amp; design |
| **[modelview](https://github.com/Sachitt-AV-08/modelview)** | Drag-and-drop GLB/OBJ/STL viewer &nbsp;·&nbsp; docs &amp; design |
| **[neural](https://github.com/Sachitt-AV-08/neural)** | One CLI for local and cloud LLMs &nbsp;·&nbsp; 243 lines |

<details>
<summary><b>All 40 public repositories</b></summary>

| Repository | Lines | Description |
|---|---:|---|
| [graphify](https://github.com/Sachitt-AV-08/graphify) | 74,084 lines | Codebase knowledge graph tool ΓÇö 36+ languages, 9+ LLM backends, MCP server, 20+ AI assistant integrations |
| [priva](https://github.com/Sachitt-AV-08/priva) | 23,150 lines |  |
| [orvima](https://github.com/Sachitt-AV-08/orvima) | 14,504 lines | Why should Claude be the only one with a browser? Orvima gives any MCP-capable AI (Claude, Cursor, Copilot, your own agent) eyes and hands on your own Chrome or Edge ΓÇö your logins, your machine, your watch. Self-hosted, local-first, MIT. MCP-native browse_* tools + live viewport. |
| [AUDIT](https://github.com/Sachitt-AV-08/AUDIT) | 13,247 lines | AUDIT ΓÇö Autonomous Universal Digital Intelligence Toolkit. One Shell, Many Worlds. File import, editing, analysis, TODOs, key phrases, 19 integrated tools. Electron + React + TypeScript. |
| [vijay-voice-assistant](https://github.com/Sachitt-AV-08/vijay-voice-assistant) | 6,310 lines | Modular desktop voice assistant with 30+ capabilities, wake word detection, and real-time processing |
| [parley](https://github.com/Sachitt-AV-08/parley) | 4,436 lines | Drive your already-installed WhatsApp Desktop locally: read, send, reply, react & schedule ΓÇö no cloud, no QR, no new browser tab. Local-first CDP automation for Windows/macOS/Linux. |
| [rotation-scan-3d](https://github.com/Sachitt-AV-08/rotation-scan-3d) | 3,928 lines | No-GPU 3D scanning from phone rotation videos ΓÇö pure geometry, no neural networks, no cloud |
| [errands](https://github.com/Sachitt-AV-08/errands) | 3,790 lines | Recipe-based goals: a goal matches a checked recipe or it is refused. Every step gated and verified, no generative planning. |
| [agent-bootstrap](https://github.com/Sachitt-AV-08/agent-bootstrap) | 3,586 lines | One command turns any machine into a 10/10 AI agent environment: 163 role-scoped agents, fleet orchestration, plan-to-PR pipeline. Free-tier, local-first. |
| [sentinel](https://github.com/Sachitt-AV-08/sentinel) | 3,432 lines | Calibrated local action classifier: decides which browser actions run unattended, which need a human, and which are refused. |
| [coda-forge-3d](https://github.com/Sachitt-AV-08/coda-forge-3d) | 3,070 lines | 18-stage photorealistic 3D human reconstruction pipeline with CPU geometric reconstruction and Gaussian splatting |
| [Cosmic-Core](https://github.com/Sachitt-AV-08/Cosmic-Core) | 2,855 lines | Local AI operating system ΓÇö the life force of your COSMIC device |
| [bhaasm-transformer](https://github.com/Sachitt-AV-08/bhaasm-transformer) | 2,535 lines | From-scratch decoder-only transformer with RoPE, GQA, SwiGLU, and optional MoE ΓÇö 2.2B parameters |
| [Cosmic-Vision](https://github.com/Sachitt-AV-08/Cosmic-Vision) | 2,411 lines | Gesture recognition engine ΓÇö sees what you mean before you touch |
| [coda-financial-agent](https://github.com/Sachitt-AV-08/coda-financial-agent) | 2,385 lines | AGNI/VEDA trading agent with paper trading, backtesting, LSTM prediction, and sector analysis |
| [apkscope](https://github.com/Sachitt-AV-08/apkscope) | 2,152 lines | MCP server to view and drive a running Android app as text, for agents without image input |
| [deception-engine](https://github.com/Sachitt-AV-08/deception-engine) | 2,076 lines | Defensive honeypot/deception framework for adversary misdirection and threat intelligence |
| [Cosmic-Voice](https://github.com/Sachitt-AV-08/Cosmic-Voice) | 1,881 lines | Voice pipeline ΓÇö local-first speech, no cloud, no API keys, just your voice |
| [coda-security-primitives](https://github.com/Sachitt-AV-08/coda-security-primitives) | 1,866 lines | Production-ready encryption, password hashing, and key derivation for Python applications |
| [genesis-media-engine](https://github.com/Sachitt-AV-08/genesis-media-engine) | 1,714 lines | DSL-driven media rendering engine for video, audio, and image generation |
| [Cosmic-Debug](https://github.com/Sachitt-AV-08/Cosmic-Debug) | 1,321 lines | Visual code debugger ΓÇö traces through time, finds the bug |
| [Cosmic-Explore](https://github.com/Sachitt-AV-08/Cosmic-Explore) | 1,266 lines | Visual Architecture Yielding Understanding ΓÇö graph-powered file explorer that flies through code |
| [Cosmic-Shield](https://github.com/Sachitt-AV-08/Cosmic-Shield) | 1,145 lines | Supply chain security platform ΓÇö the armor for your dependencies |
| [Cosmic-Connect](https://github.com/Sachitt-AV-08/Cosmic-Connect) | 982 lines | Local service registry ΓÇö the energy center of your COSMIC device |
| [Cosmic-Atlas](https://github.com/Sachitt-AV-08/Cosmic-Atlas) | 928 lines | Interactive 3D codebase knowledge graph ΓÇö navigate code like star constellations |
| [Cosmic-Flow](https://github.com/Sachitt-AV-08/Cosmic-Flow) | 892 lines | Visual pipeline builder ΓÇö threads of execution, drag-and-drop |
| [Cosmic-Canvas](https://github.com/Sachitt-AV-08/Cosmic-Canvas) | 669 lines | AI sketch-to-3D ΓÇö gives form to your ideas |
| [nebula-fs](https://github.com/Sachitt-AV-08/nebula-fs) | 554 lines | Force-directed file explorer -- navigate your filesystem as nodes and edges, not folders and lists |
| [patchwork](https://github.com/Sachitt-AV-08/patchwork) | 264 lines | Config file patcher ΓÇö set/get/diff across YAML, JSON, TOML from one CLI |
| [neural](https://github.com/Sachitt-AV-08/neural) | 243 lines | Unified CLI for local + cloud LLMs ΓÇö BHAASM, Ollama, NIM in one command |
| [pixelflow](https://github.com/Sachitt-AV-08/pixelflow) | 204 lines | Terminal image toolbox ΓÇö ASCII preview, frame extraction, thumbnails, format conversion |
| [envcheck](https://github.com/Sachitt-AV-08/envcheck) | 182 lines | Environment variable validator ΓÇö scan code + .env, report missing keys before runtime |
| [servehere](https://github.com/Sachitt-AV-08/servehere) | 113 lines | Instant file server with QR code ΓÇö share files over LAN in one command |
| [.github](https://github.com/Sachitt-AV-08/.github) | docs &amp; design | Profile README |
| [COSMIC](https://github.com/Sachitt-AV-08/COSMIC) | docs &amp; design | Connected Operating System for Multimodal Intelligent Computing ΓÇö the COSMIC ecosystem |
| [imagediff](https://github.com/Sachitt-AV-08/imagediff) | docs &amp; design | Visual before/after image comparison ΓÇö slider overlay for model output evaluation |
| [JARVIS-by-A.V.SACHITT](https://github.com/Sachitt-AV-08/JARVIS-by-A.V.SACHITT) | docs &amp; design |  |
| [modelview](https://github.com/Sachitt-AV-08/modelview) | docs &amp; design | Drag-and-drop 3D model viewer ΓÇö GLB, OBJ, STL in the browser with Three.js |
| [picgrid](https://github.com/Sachitt-AV-08/picgrid) | docs &amp; design | Image grid comparator ΓÇö lay out N images in a labeled grid for A/B comparison |
| [Sachitt-AV-08](https://github.com/Sachitt-AV-08/Sachitt-AV-08) | docs &amp; design | GitHub Profile README |

</details>

---

## By the numbers

Every figure below was measured by cloning each repository and counting the
source. Vendored, generated and minified trees were excluded.

```
  253,229     lines of code   (all 44 repos, public and private)
  182,175     lines in public repositories
  71,054     lines in private repositories
       44      repositories
       40      public
        4      private
        1      developer
```

| Language | Share |
|---|---:|
| Python | 71.3% |
| TypeScript | 14.6% |
| HTML | 11.3% |
| CSS | 1.3% |
| PowerShell | 1.2% |
| Shell | 0.2% |

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/HTML-e34c26?style=flat-square&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS-563d7c?style=flat-square&logo=css3&logoColor=white" alt="CSS">
<img src="https://img.shields.io/badge/PowerShell-012456?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">
<img src="https://img.shields.io/badge/Shell-4eaa25?style=flat-square&logo=gnubash&logoColor=white" alt="Shell">
<img src="https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">

---

## Principles

1. **Local-first.** Your hardware, your data, your logins. No key, no subscription, no telemetry.
2. **Refuse rather than guess.** Unknown is treated as irreversible.
3. **Count, don't claim.** Every number in this file was measured from the source.
4. **Verify the layer that reads.** A passing suite proves nothing; a mutated one that should fail proves something.

---

## Beyond the code

Table tennis, cricket, football, badminton, chess. City- and district-level
rankings in Free Fire and Rocket League. I read, write and speak **Sanskrit** -
seven years of it - alongside English, Hindi, Telugu, Tamil, Kannada, Bengali
and Spanish.

Building an AI ecosystem and playing competitive esports turn out to need the
same two things: staying calm under pressure, and thinking ten moves ahead.

### Current focus

```
> cat /etc/coda/current
+-- orvima: real-browser agent safety, shipped to PyPI
+-- AGNI/VEDA dual-agent training
+-- IEEE paper: Rotation-Scan + AGNI/VEDA
+-- 3D dataset training (Colab T4 + Kaggle P100)
```

---

<div align="center">

Built by <a href="https://github.com/Sachitt-AV-08">A V Sachitt</a> &nbsp;·&nbsp;
[Website](https://codaos.qzz.io) &nbsp;·&nbsp;
[LinkedIn](https://linkedin.com/in/sachitt-a-v-604224414/)

*If something here is useful to you, an issue or a star genuinely helps. If you
want to fund the work, [open an issue](https://github.com/Sachitt-AV-08/orvima/issues/new)
and say so - sponsorships are being set up.*

</div>
