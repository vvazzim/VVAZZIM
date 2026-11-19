<div align="center">

```text
  ██╗   ██╗██╗   ██╗ █████╗ ███████╗███████╗██╗███╗   ███╗
  ██║   ██║██║   ██║██╔══██╗╚══███╔╝╚══███╔╝██║████╗ ████║
  ██║   ██║██║   ██║███████║  ███╔╝   ███╔╝ ██║██╔████╔██║
  ╚██╗ ██╔╝╚██╗ ██╔╝██╔══██║ ███╔╝   ███╔╝  ██║██║╚██╔╝██║
   ╚████╔╝  ╚████╔╝ ██║  ██║███████╗███████╗██║██║ ╚═╝ ██║
    ╚═══╝    ╚═══╝  ╚═╝  ╚═╝╚══════╝╚══════╝╚═╝╚═╝     ╚═╝
```

### **AI & COMPUTER VISION ENGINEER | DEEP LEARNING R&D & APPLIED SYSTEMS**
*Computer Vision Research • Cyber AI & Automation • Distributed MLOps • Scalable SaaS*

[![M.Sc. Vision](https://img.shields.io/badge/M.Sc._Research-Université_Paris_Cité-bb9af7?style=flat-square&logo=academia&labelColor=0d1117)](https://u-paris.fr) [![ANSSI 96%](https://img.shields.io/badge/ANSSI_SecNumacadémie-96%25_Verified-9ece6a?style=flat-square&logo=gnu-privacy-guard&labelColor=0d1117)](https://secnumacademie.gouv.fr) [![Outstanding Award](https://img.shields.io/badge/Outstanding_Award-Higher_Institute_of_Sciences-f7768e?style=flat-square&logo=academia&labelColor=0d1117)](https://chikhiwassim.netlify.app)

<p align="center">
  <a href="https://chikhiwassim.netlify.app">🌐 Interactive Portfolio</a> •
  <a href="mailto:chikhimedwassim@gmail.com">📬 Email</a> •
  <a href="https://linkedin.com/in/wassim-chikhi-21477619a">💼 LinkedIn</a> •
  <a href="https://orcid.org/0009-0009-8513-6962">🔬 ORCID</a>
</p>

---

</div>

## 🧭 Profile Overview

AI & Computer Vision Engineer holding an **M.Sc. Research in Computer Vision & Machine Intelligence (Université Paris Cité)** and recipient of the **Outstanding Contribution Award** from the **Higher Institute of Sciences** for academic excellence, technical mentorship, and institutional prestige.

Experienced in designing production automation pipelines and AI detection tooling at **Direction Cybersécurité Groupe VINCI (CyberForge)**. Accredited by **ANSSI SecNumacadémie (96%)** with practical expertise in **Cloud & DevOps (Azure AZ-900, Docker, CI/CD)**. My engineering approach centers on deterministic systems: deploying robust deep learning models, event-driven data pipelines, and privacy-preserving local AI.

---

## 🏛️ Core Engineering Pillars

### 🧬 1. Computer Vision & Biomedical R&D
- **Computational Histopathology (WSI):** Gigapixel patch extraction at 20x magnification (0.50 µm/pixel), automated tissue segmentation, and Spatial Patch Paths Representation (SPPR / STR-RW) on the Camelyon benchmark achieving **AUC = 0.87** with Log-Sum-Exp aggregation (tau = 2.0).
- **Colorectal Cancer Classification:** Deep embeddings extraction on **100,000 H&E patches** (`NCT-CRC-HE-100K`) across 9 tissue phenotypes using PyTorch ResNet50 (2048-dim latent space) with stratified anti-leakage splitting.
- **Cellular Instance Tracking:** Dense instance segmentation via **Cellpose v4** (vector-flow representations, diameter 30px, flow 0.4) coupled with **TrackPy** (Crocker-Grier Kalman filter, memory 3 frames) for sub-pixel centroid trajectory tracking on HeLa cancer cells (`DIC-C2DH-HeLa`).
- **Multimodal Alignment & Distillation:** Contrastive fine-tuning of Vision-Language **CLIP (ViT-B/32)** on medical ROCO datasets using symmetric InfoNCE loss (CIFAR-10 Acc@1 = 89.16%, Acc@5 = 99.08%). Knowledge distillation compressing ResNet50 (23.5M params) into ResNet18 (11.1M params) with student accuracy (**93.12%**) surpassing teacher (**92.97%**).
- **Stack:** PyTorch 2.x, OpenSlide, Torchvision, Cellpose, TrackPy, OpenCV, Albumentations, Scikit-learn, CuPy.

### 🛡️ 2. Cyber AI, Threat Intelligence & Automation (VINCI CyberForge)
- **CyberForge Automation Scale (VINCI):** Modernized and automated phishing signal processing within Cortex XSOAR and CERTWeb, delivering a modular Python library across 10 analysis modules, 15 new detection routines, 13 system upgrades, and 213 automated tests (88% code coverage) deployed to live production.
- **Industrial Reliability:** Core refiner engine validated by 213 automated tests (88% code coverage). Unidirectional 3E architecture (Extract / Extend / Enrich) across 10 domain modules.
- **Local LLM Threat Triage:** Fine-tuned **Qwen2.5-3B via QLoRA 4-bit (NF4)** with post-hoc explainability for local incident classification, ensuring zero sensitive data leaves the enterprise environment (Lin et al. 2025, Distilling Step-by-Step). Loss convergence ~0.35 on single-token classification.
- **Visual Brand Impersonation & Anti-Quishing:** Dual-stage quishing detection combining zero-network **PyZbar** QR decoding with a **DINOv2 Siamese network** for pixel-level visual brand similarity matching and Unicode confusable homoglyph normalization.
- **Enterprise IAM Governance:** Algorithmic Identity Governance & Administration (**IGA Role Mining**) engine discovering candidate Business Roles (PMR/GM) via bottom-up frequent itemset mining (S_thresh >= 0.65), detecting toxic Segregation of Duties (**SoD**) conflicts, and auditing Active Directory privilege creep.
- **Stack:** Python 3.12, QLoRA, Cortex XSOAR, DINOv2, PyZbar, Active Directory, FastAPI, pytest, Streamlit, OpenPyXL.

### ⚙️ 3. Distributed Data Engineering & Production MLOps
- **Event Streaming Backbone:** Clustered **Apache Kafka + Zookeeper** handling high-throughput asynchronous event ingestion for distributed log analysis and decoupled alert dispatching (`confluent-kafka` with offset integrity callbacks).
- **NLP Fact & Threat Verification:** Fine-tuned **DeBERTa-v3** transformer model on FEVER and NLI benchmarks achieving **F1 = 0.89** on high-cardinality security incident payloads.
- **Cloud-Native Hardened Orchestration:** Production Kubernetes deployments governed by least-privilege security policies (dedicated ServiceAccounts, strict **RBAC**, NGINX Ingress).
- **Data Persistence & Indexing:** **PostgreSQL 15** running with optimized B-Tree and GIN indexes, pgvector embeddings, and automated connection pooling.
- **Stack:** Apache Kafka, Zookeeper, Kubernetes, Docker, PostgreSQL 15, DeBERTa-v3, FastAPI, Azure, CI/CD.

### 💻 4. High-Velocity Web & Real-Time SaaS
- **MAPARIS (Paris Safety Map):** Interactive real-time public safety and hazard-monitoring map for Paris pedestrians and commuters, featuring live incident alerts, WebSocket updates, and smart detour routing around reported risk areas.
- **DZPIECES:** Automotive spare parts marketplace and search catalog helping vehicle owners quickly find and source verified replacement parts.
- **BABELSTORE & CozySpace:** High-velocity headless retail storefront (Lighthouse 98+) and modern real-estate property discovery interface.
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

<sub>Engineered with deterministic rigor • Validated by rigorous testing • Bridging academic research and production engineering.</sub>

</div>
