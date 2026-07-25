<div align="center">

```
 ██████╗  █████╗ ██████╗  █████╗ ████████╗ ██████╗  ██████╗ ██╗   ██╗███████╗
 ██╔══██╗██╔══██╗██╔══██╗██╔══██╗╚══██╔══╝██╔═══██╗██╔═══██╗██║   ██║██╔════╝
 ██║  ██║███████║██║  ██║███████║   ██║   ██║   ██║██║   ██║██║   ██║███████╗
 ██║  ██║██╔══██║██║  ██║██╔══██║   ██║   ██║   ██║██║   ██║██║   ██║╚════██║
 ██████╔╝██║  ██║██████╔╝██║  ██║   ██║   ╚██████╔╝╚██████╔╝╚██████╔╝███████║
 ╚═════╝ ╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝
```

### Connected Operating System for Multimodal Intelligent Computing

**296,000+ lines of real code. 25+ components. 5 languages. All local. No cloud.**

[![GitHub](https://img.shields.io/badge/-Sachitt--AV--08-181717?style=flat-square&logo=github)](https://github.com/Sachitt-AV-08)
[![COSMIC](https://img.shields.io/badge/COSMIC-Ecosystem-7c3aed?style=flat-square)](https://github.com/Sachitt-AV-08/COSMIC)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)

</div>

---

## What I Built

**CODA** is a local-first AI operating system. No API keys, no subscriptions, no telemetry.
Everything runs on your hardware. I built it alone.

```
         +-----------+
         |   HUMAN   |
         +-----+-----+
               |
    +----------+----------+
    |          |          |
    v          v          v
+--------+ +--------+ +--------+
| CODA   | | KARNA  | | CODA   |
| OS     | | (2.2B) | | Forge  |
| 5 UIs  | | Voice  | | 3D     |
+---+----+ +---+----+ +---+----+
    |          |          |
    +-----+----+----+-----+
          |         |
          v         v
    +-----------+ +-----------+
    |  BHAASM   | |  Cloud    |
    |  Brain    | |  GPU      |
    |  43K loc  | |  Training |
    +-----------+ +-----------+
```

---

## Pinned Projects

<table>
<tr>
<td width="50%">

### [BHAASM Transformer](https://github.com/Sachitt-AV-08/bhaasm-transformer)
**43,768 lines** | Python

From-scratch 2.2B decoder-only transformer.
RoPE + GQA + SwiGLU + MoE (8 experts).
LoRA fine-tuning, debate engine, generation refinement.

[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)]()
[![MoE](https://img.shields.io/badge/MoE-8%20experts-orange)]()

</td>
<td width="50%">

### [CODA Forge 3D](https://github.com/Sachitt-AV-08/coda-forge-3d)
**32,800 lines** | Python

17-stage photorealistic 3D human reconstruction.
Phone rotation video -> textured, watertight mesh.
COLMAP + ECON + PIFuHD + Gaussian Splatting.

[![3D](https://img.shields.io/badge/3D-Reconstruction-blue)]()
[![GPU](https://img.shields.io/badge/GPU-Optional-brightgreen)]()

</td>
</tr>
<tr>
<td>

### [Rotation-Scan 3D](https://github.com/Sachitt-AV-08/rotation-scan-3d)
**~3,000 lines** | Python

No-GPU 3D body scanning. CPU-only, zero neural networks.
Silhouette widths at 360 angles -> ellipse fit -> mesh.
Works on any laptop.

[![CPU](https://img.shields.io/badge/CPU-Only-green)]()
[![No GPU](https://img.shields.io/badge/No%20NN-blue)]()

</td>
<td>

### [Deception Engine](https://github.com/Sachitt-AV-08/deception-engine)
**1,785 lines** | Python

Active defense through deception.
Fake services, canary tokens, honeypots.
MITRE ATT&CK mapped. 12 techniques.

[![Security](https://img.shields.io/badge/Security-Red)]()
[![MITRE](https://img.shields.io/badge/ATT%26CK-12%20techniques-yellow)]()

</td>
</tr>
<tr>
<td>

### [Genesis Media Engine](https://github.com/Sachitt-AV-08/genesis-media-engine)
**1,204 lines** | Python

Declarative DSL for video generation.
Write scenes in text, render with FFmpeg.
Plugin-based, sandboxed rendering.

[![Video](https://img.shields.io/badge/Video-Gen-orange)]()
[![FFmpeg](https://img.shields.io/badge/FFmpeg-purple)]()

</td>
<td>

### [Security Primitives](https://github.com/Sachitt-AV-08/coda-security-primitives)
**~800 lines** | Python

AES-256-GCM, Argon2, PBKDF2, MFA.
Tamper-evident audit chains.
Production-ready. No dependencies.

[![Crypto](https://img.shields.io/badge/AES--256-GCM-green)]()
[![MFA](https://img.shields.io/badge/3--Factor-MFA-red)]()

</td>
</tr>
</table>

---

## Tech Stack

| Domain | Tools |
|--------|-------|
| **AI/ML** | PyTorch, HuggingFace, LoRA, MoE, BPE Tokenizer |
| **3D** | COLMAP, ECON, PIFuHD, Gaussian Splatting, TripoSR |
| **Generation** | Stable Diffusion XL, AnimateDiff, I2V, NIM FLUX |
| **Voice** | Silero VAD, faster-whisper, edge-tts, MediaPipe |
| **Web** | FastAPI, Next.js 16, React 19, TailwindCSS |
| **Desktop** | PySide6, Electron 28, Flutter/Dart |
| **Security** | AES-256-GCM, PBKDF2, MFA, Audit Chain |
| **Cloud** | Kaggle T4, Modal T4, Colab T4, Lightning T4 |

---

## COSMIC Ecosystem

10 composable projects forming a virtual device:

| Project | Purpose |
|---------|---------|
| **Cosmic Explore** | 3D codebase intelligence |
| **Cosmic Voice** | Local voice pipeline (STT + TTS) |
| **Cosmic Vision** | Gesture recognition + hand tracking |
| **Cosmic Canvas** | Sketch-to-3D generation |
| **Cosmic Core** | AI operating system shell |
| **Cosmic Flow** | Visual pipeline builder |
| **Cosmic Atlas** | 3D code navigation |
| **Cosmic Debug** | Visual debugger |
| **Cosmic Connect** | Service registry + discovery |
| **Cosmic Shield** | Supply chain security |

---

## By The Numbers

```
  296,000+    lines of code
      30      public repositories
      25+     working components
       5      programming languages
       4      cloud GPU tiers
       3      UI frameworks
       1      developer
```

---

## Design Principles

1. **Local-first** -- No cloud. Your hardware, your data.
2. **Composable** -- Each piece works standalone.
3. **Agent-driven** -- AGNI creates, VEDA validates, VIJAY interacts.
4. **Self-improving** -- TRISHUL loop: generate, evaluate, improve.
5. **Multi-accelerator** -- CPU + GPU + iGPU + NPU.

---

<div align="center">

*Built with curiosity and a laptop. No team. No funding. Just code.*

</div>
