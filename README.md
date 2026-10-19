# Hi, I'm Yuting Liu (@Yyitan) 👋

MS student in computer science. My research so far has centered on **Compositional Zero-Shot Learning (CZSL)** with vision-language models, plus multimodal applications (diffusion feedback, explainable sentiment analysis).

## 🔬 My first-year research, in one thread

**Build trustworthy baselines → probe them rigorously → improve on them.**

- 🧪 **Systematic reproductions** — Troika (CVPR 2024), CAILA (WACV 2024), PLID (ECCV 2024), plus unofficial reimplementations of methods that never released code (FlowComposer, H2EM, EVA)
- 🔍 **Preregistered explorations** — six go/no-go studies where the gate was written *before* reading the numbers; honest negative results included
- 🚀 **Method development** — a family of improvements on CAMS (arXiv:2511.16378): diffusion feedback, generative residual flows, causal disentanglement, MoE adapters, conditional disentanglement...

## 📌 Selected repositories

| Repo | What it is |
|------|------------|
| [CAMS-ADR](https://github.com/Yyitan/CAMS-ADR) | Generative residual-flow exploration on CAMS (MERF / nested primitive transport / reverse flow), with real experiment logs |
| [CoDA-CZSL](https://github.com/Yyitan/CoDA-CZSL) | Conditional disentanglement + feasibility-aware augmentation (OCAD / MID / FACA) |
| [VRDIFF](https://github.com/Yyitan/VRDIFF) | Frozen Stable Diffusion 1.5 as a training-time feedback module for CAMS |
| [EVA2](https://github.com/Yyitan/EVA2) · [EVA3](https://github.com/Yyitan/EVA3) | Unofficial implementations of **EVA** (ICLR 2026, no official code) on the CAMS / Troika frameworks |
| [CAMS-Diff](https://github.com/Yyitan/CAMS-Diff) | A negative-result study: frozen SD 2.1 feedback on CAMS, with systematic failure diagnosis |
| [sparse-patch-troika](https://github.com/Yyitan/sparse-patch-troika) | Patch-level local evidence on Troika under preregistered protocols |
| [czsl-reproductions](https://github.com/Yyitan/czsl-reproductions) | Reproduction notes, protocols & licenses for the CZSL baseline zoo |
| [czsl-explorations](https://github.com/Yyitan/czsl-explorations) | Six preregistered exploratory studies — negative results included |
| [multimodal-emotion-analysis](https://github.com/Yyitan/multimodal-emotion-analysis) | End-to-end multimodal sentiment analysis: word-level alignment, missing-modality robustness, Shapley-based explainability |

## 🛠️ Toolbox

**Python · PyTorch · CLIP/OpenCLIP · diffusers (Stable Diffusion) · Wav2Vec2 · BERT · MediaPipe · librosa · pytest · Linux GPU clusters**

## 📑 How I run experiments

- Preregister go/no-go gates before reading numbers; double-seed disambiguation for borderline effects
- Bias-swept AUC integration + closed/open-world HM as the standard CZSL protocol
- Respect upstream licensing: increment + patch format when a baseline has no license

## 🔎 Open to

Research / ML engineering internships. Feel free to open an issue in any of my repos to reach me.
