# GPU Cloud Cost & Value Calculator ⚡

[![Live Web Tool](https://img.shields.io/badge/Live_Tool-345.ai%2Fcalc-00f2fe?style=for-the-badge&logo=google-chrome&logoColor=white)](https://345.ai/calc.html)
[![AI Directory Hub](https://img.shields.io/badge/Hub-345.ai-7c3aed?style=for-the-badge)](https://345.ai/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Zero_Deps-100%25_Vanilla_JS-orange?style=for-the-badge)](index.html)

An open-source, interactive web calculator and benchmark index comparing on-demand cloud GPU prices (RunPod vs. AWS vs. Hyperscalers) for AI inference and fine-tuning workloads (FLUX.1, SDXL, LLaMA 3, Qwen 2.5).

Built with zero external dependencies, 100% Vanilla HTML/CSS/JavaScript, and sub-0.5s load times.

---

## 🚀 Live Demo

- **English (Global)**: [https://345.ai/calc.html](https://345.ai/calc.html)
- **简体中文**: [https://345.ai/calc-cn.html](https://345.ai/calc-cn.html)
- **日本語 (Japan)**: [https://345.ai/calc-jp.html](https://345.ai/calc-jp.html)
- **한국어 (Korea)**: [https://345.ai/calc-kr.html](https://345.ai/calc-kr.html)
- **العربية (Arabic)**: [https://345.ai/calc-ar.html](https://345.ai/calc-ar.html)

---

## 📊 2026 Cloud GPU Benchmark Index

| Workload / Model | Recommended GPU | RunPod Rate | AWS Equivalent | Estimated Savings |
| :--- | :--- | :--- | :--- | :--- |
| **FLUX.1 / SDXL Image Gen** | `RTX 4090 (24GB)` | **$0.69 / hr** | $1.21 / hr (g5.2xl) | **43% Cheaper** |
| **LLaMA 3 8B LoRA Fine-Tuning** | `A100 SXM (80GB)` | **$1.89 / hr** | $4.09 / hr (p4de) | **54% Cheaper** |
| **High-Throughput LLM Inference** | `NVIDIA L4 (24GB)` | **$0.35 / hr** | $0.97 / hr (g6.2xl) | **64% Cheaper** |

---

## ✨ Key Features

1. **Task-Based GPU Matching**: Select whether you are running image diffusion, fine-tuning an 8B LLM, or deploying high-speed inference.
2. **Dynamic Monthly Cost Curve**: Interactive daily runtime slider (1 to 24 hours/day) that computes projected monthly cloud bills.
3. **Honest "Buy vs. Rent" Breakeven Analysis**: Unlike typical affiliate calculators, this tool actively warns users when running 24/7 that purchasing a physical workstation (e.g. RTX 4090 @ $1,600) breaks even in ~3 months compared to continuous cloud rental.
4. **Zero Ads & Pure Utility**: Non-commercial, direct official links, no affiliate query tracking parameters.
5. **Ultra-Lightweight & Embeddable**: Can be embedded into any dashboard or documentation page via an `<iframe>` or standalone script.

---

## 💻 Quick Start (Run Locally)

No Node.js, npm, or build tools required.

```bash
# Clone the repository
git clone git@github.com:wethinkincode/gpu-cost-calculator.git

# Navigate into the project
cd gpu-cost-calculator

# Open in browser directly
open index.html
```

---

## 📁 Repository Structure

```text
gpu-cost-calculator/
├── index.html       # English calculator (Standalone)
├── cn.html          # Simplified Chinese (简体中文)
├── jp.html          # Japanese (日本語)
├── kr.html          # Korean (한국어)
├── ar.html          # Arabic (العربية - RTL layout)
├── LICENSE          # MIT License
└── README.md        # Documentation & Benchmark Index
```

---

## 🌐 Powered by

Developed as part of the open AI tool initiatives at **[345.ai](https://345.ai/)** — Curated AI & Web3 Tools Directory.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
