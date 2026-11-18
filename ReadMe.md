<div align="center">

```text
  ██╗   ██╗██╗   ██╗ █████╗ ███████╗███████╗██╗███╗   ███╗
  ██║   ██║██║   ██║██╔══██╗╚══███╔╝╚══███╔╝██║████╗ ████║
  ██║   ██║██║   ██║███████║  ███╔╝   ███╔╝ ██║██╔████╔██║
  ╚██╗ ██╔╝╚██╗ ██╔╝██╔══██║ ███╔╝   ███╔╝  ██║██║╚██╔╝██║
   ╚████╔╝  ╚████╔╝ ██║  ██║███████╗███████╗██║██║ ╚═╝ ██║
    ╚═══╝    ╚═══╝  ╚═╝  ╚═╝╚══════╝╚══════╝╚═╝╚═╝     ╚═╝
```

### **CRITICAL SYSTEMS & AI ENGINEER | DEEP LEARNING R&D & SOVEREIGN SECOPS**
*Computer Vision Research • 24/7 Security Operations • Distributed MLOps • High-Throughput SaaS*

[![CERT VINCI](https://img.shields.io/badge/CERT_VINCI-24%2F7_Production-7aa2f7?style=flat-square&logo=shield&labelColor=0d1117)](https://www.vinci.com)
[![M.Sc. Vision](https://img.shields.io/badge/M.Sc._Research-Université_Paris_Cité-bb9af7?style=flat-square&logo=academia&labelColor=0d1117)](https://u-paris.fr)
[![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-Expert_AZ--400-7dcfff?style=flat-square&logo=microsoftazure&labelColor=0d1117)](https://learn.microsoft.com/certifications/devops-engineer/)
[![ANSSI 96%](https://img.shields.io/badge/ANSSI_SecNumacadémie-96%25_Verified-9ece6a?style=flat-square&logo=gnu-privacy-guard&labelColor=0d1117)](https://secnumacademie.gouv.fr)
[![mypy strict](https://img.shields.io/badge/mypy-strict_0_errors-73daca?style=flat-square&logo=python&labelColor=0d1117)](https://github.com/vvazzim)
[![pytest](https://img.shields.io/badge/pytest-213_passed-green?style=flat-square&logo=pytest&labelColor=0d1117)](https://github.com/vvazzim)

<p align="center">
  <a href="https://chikhiwassim.netlify.app">🌐 Interactive Portfolio</a> •
  <a href="mailto:chikhimedwassim@gmail.com">📬 Email</a> •
  <a href="https://linkedin.com/in/wassim-chikhi-21477619a">💼 LinkedIn</a> •
  <a href="https://orcid.org/0009-0009-8513-6962">🔬 ORCID</a>
</p>

---

</div>

## 🧭 Profile Overview

AI & Critical Systems Engineer holding an **M.Sc. Research in Computer Vision & Machine Intelligence (Université Paris Cité)** and operating in **24/7 production at CERT VINCI (VINCI SA Holding)**.

Certified **Azure DevOps Expert (AZ-400)** and **ANSSI SecNumacadémie (96%)**, my engineering approach is centered on sovereign, deterministic architectures: deploying production-grade deep learning models and event-driven data pipelines with zero third-party cloud data leakage (Privacy by Design).

---

## 🏛️ Core Engineering Pillars

### 🧬 1. Computer Vision & Biomedical R&D
- **Computational Histopathology (WSI):** Gigapixel patch extraction at 20x magnification (0.50 µm/pixel), automated tissue segmentation, and Spatial Patch Paths Representation (SPPR / STR-RW) on the Camelyon benchmark achieving **AUC = 0.87** with Log-Sum-Exp aggregation (tau = 2.0).
- **Colorectal Cancer Classification:** Deep embeddings extraction on **100,000 H&E patches** (`NCT-CRC-HE-100K`) across 9 tissue phenotypes using PyTorch ResNet50 (2048-dim latent space) with stratified anti-leakage splitting.
- **Cellular Instance Tracking:** Dense instance segmentation via **Cellpose v4** (vector-flow representations, diameter 30px, flow 0.4) coupled with **TrackPy** (Crocker-Grier Kalman filter, memory 3 frames) for sub-pixel centroid trajectory tracking on HeLa cancer cells (`DIC-C2DH-HeLa`).
- **Multimodal Alignment & Distillation:** Contrastive fine-tuning of Vision-Language **CLIP (ViT-B/32)** on medical ROCO datasets using symmetric InfoNCE loss (CIFAR-10 Acc@1 = 89.16%, Acc@5 = 99.08%). Knowledge distillation compressing ResNet50 (23.5M params) into ResNet18 (11.1M params) with student accuracy (**93.12%**) surpassing teacher (**92.97%**).
- **Stack:** PyTorch 2.x, OpenSlide, Torchvision, Cellpose, TrackPy, OpenCV, Albumentations, Scikit-learn, CuPy.

### 🛡️ 2. Sovereign SecOps, Threat Intel & IAM Governance
- **CERT VINCI Operational Scale:** Maintaining and hardening an autonomous Python pipeline ingesting and triaging **1,500 security incident tickets/day** with **70% automated resolution** in active 24/7 production.
- **Industrial Code Quality:** Core refiner engine governed by **213 automated pytest tests** (100% passing in < 6 seconds), **88% code coverage**, and **0 mypy strict type errors**. Unidirectional 3E architecture (Extract / Extend / Enrich) across 10 domain modules.
- **Sovereign Local LLM Threat Triage:** Fine-tuned **Qwen2.5-3B via QLoRA 4-bit (NF4)** with post-hoc explainability, eliminating third-party cloud data leakage (Lin et al. 2025, Distilling Step-by-Step). Loss convergence ~0.35 on single-token classification.
- **Visual Brand Impersonation & Anti-Quishing:** Dual-stage quishing detection combining zero-network **PyZbar** QR decoding with a **DINOv2 Siamese network** for pixel-level visual brand similarity matching and Unicode confusable homoglyph normalization.
- **Enterprise IAM Governance:** Algorithmic Identity Governance & Administration (**IGA Role Mining**) engine discovering candidate Business Roles (PMR/GM) via bottom-up frequent itemset mining (S_thresh >= 0.65), detecting toxic Segregation of Duties (**SoD**) conflicts, and auditing Active Directory privilege creep.
- **Stack:** Python 3.12, QLoRA, Cortex XSOAR, DINOv2, PyZbar, Active Directory, FastAPI, pytest, mypy, Streamlit, OpenPyXL.

### ⚙️ 3. Distributed Data Engineering & Sovereign MLOps
- **Event Streaming Backbone:** Clustered **Apache Kafka + Zookeeper** handling high-throughput asynchronous event ingestion for distributed log analysis and decoupled alert dispatching (`confluent-kafka` with offset integrity callbacks).
- **NLP Fact & Threat Verification:** Fine-tuned **DeBERTa-v3** transformer model on FEVER and NLI benchmarks achieving **F1 = 0.89** on high-cardinality security incident payloads.
- **Cloud-Native Hardened Orchestration:** Production Kubernetes deployments governed by least-privilege security policies (dedicated ServiceAccounts, strict **RBAC**, NGINX Ingress).
- **Data Persistence & Indexing:** **PostgreSQL 15** running with optimized B-Tree and GIN indexes, pgvector embeddings, and automated connection pooling.
- **Stack:** Apache Kafka, Zookeeper, Kubernetes, Docker, PostgreSQL 15, DeBERTa-v3, FastAPI, Azure DevOps (AZ-400).

### 💻 4. High-Velocity Web & Real-Time SaaS
- **MAPARIS (Paris Security Pulse):** Monorepo real-time security tracking platform built with **Fastify (NodeNext)**, **Socket.io WebSockets**, **Leaflet Dark Matter**, and a custom geometric hazard-avoidance routing algorithm (Safe Routing) computing orthogonal waypoints around active risk buffers.
- **BABELSTORE:** Modern decoupled retail inventory and point-of-sale platform built on **Astro 5**, TypeScript, and Tailwind CSS, maintaining a verified Google **Lighthouse score of 98+** (Zero-JS by default).
- **Full SaaS Ecosystem:** 6 production web applications deployed publicly (including Cozyspace-DZ, DZPIECE, MACDI, Real-Estate).
- **Stack:** TypeScript, React 18, Fastify, Astro 5, Leaflet, Socket.io, Tailwind CSS, Supabase, Docker.

---

## 📊 Benchmark & Inference Telemetry

| Model / Pipeline | Target Task | Parameters / Precision | VRAM / RAM | Latency (P95) | Benchmark Score |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Qwen2.5-3B-SecOps** | Threat Triage & NER | 3B (QLoRA 4-bit NF4) | 2.6 GB VRAM | 18 ms/token | 96.0% Classification Accuracy |
| **DINOv2 Siamese** | Brand Spoofing Detection | 21M (FP16) | 1.1 GB VRAM | 14 ms/image | 0.94 Precision @ Recall 0.91 |
| **Camelyon WSI Attention** | Metastasis Patch Tiling | 24M (FP32) | 4.8 GB VRAM | 120 patches/s | AUC 0.87 (Camelyon16) |
| **DeBERTa-v3-Security** | Security Payload NLI | 86M (INT8) | 850 MB RAM | 28 ms/batch | F1 0.89 (FEVER Benchmark) |
| **Cellpose HeLa Engine** | Cell Instance Tracking | 14M (FP32) | 1.8 GB VRAM | 310 ms/frame | 91.8% IoU Cell Boundary |
| **MAPARIS Socket Ingest** | Concurrent Location Fanout | Distributed Event Loop | 180 MB RAM | 8 ms response | 10k concurrent sockets/node |

---

## 🚀 Production Systems & Repositories

| System / Repository | Architectural Archetype | Core Production Metrics | Tech Stack | Status |
| :--- | :--- | :--- | :--- | :---: |
| **[`fake-news-platform`](https://github.com/vvazzim/fake-news-platform)** | Distributed MLOps & Fact Checking | Apache Kafka, Kubernetes RBAC, F1 0.89 | Kafka, K8s, DeBERTa-v3, FastAPI | `RUNNING` |
| **[`iam-role-mining`](https://github.com/vvazzim/iam-role-mining)** | Identity Governance (IGA) & SoD Audit | 100% Green Tests, PMR/GM Role Reduction | Python, Pandas, Streamlit, OpenPyXL | `VERIFIED` |
| **[`TER_Histopathology_Classification`](https://github.com/vvazzim/TER_Histopathology_Classification)** | Gigapixel Histopathology AI | 100k patches, ResNet50 d=2048, AUC 0.87 | PyTorch, ViT, OpenSlide, Torchvision | `STABLE` |
| **[`VMI-LAB`](https://github.com/vvazzim/VMI-LAB)** | Applied Computer Vision Research Lab | HeLa Cellpose Tracking, Medical CLIP ROCO | PyTorch, Cellpose, TrackPy, CLIP | `RESEARCH` |
| **[`MAPARIS`](https://github.com/vvazzim/MAPARIS)** | Real-Time Security Map & Safe Routing | P95 < 15ms WebSocket push, Safe Routing | Fastify, Socket.io, Leaflet, React 18 | `LIVE` |
| **[`BABELSTORE`](https://github.com/vvazzim/BABELSTORE)** | Ultra-Fast Headless Retail SaaS | Lighthouse 98+, Zero-JS by default | Astro 5, TypeScript, Tailwind CSS | `PRODUCTION` |

---

<div align="center">

```text
PGP Fingerprint: E78B 4D2F 901C 84E3 F1A2  D098 B6C4 3E21 A8F9 0E52 [0xA8F90E52]
All production Git commits are cryptographically signed • Verified on GitHub
```

<sub>Engineered with deterministic rigor • Zero cloud egress on sensitive models • Production-tested under 24/7 operational conditions.</sub>

</div>
