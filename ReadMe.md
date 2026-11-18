<div align="center">

# Wassim CHIKHI
### **Critical Systems & AI Engineer | Deep Learning R&D & Sovereign SecOps**
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

### `$ sysctl kernel.identity`

```bash
OPERATOR_ID="Wassim CHIKHI (vvazzim)"
LOCATION="Paris, France (CET / UTC+1)"
CURRENT_POSTURE="24/7 Production Operations at CERT VINCI (VINCI SA Holding)"
ACADEMIC_BASE="M.Sc. Research in Computer Vision & Machine Intelligence (Université Paris Cité)"
CREDENTIALS="Azure DevOps Expert (AZ-400) • ANSSI SecNumacadémie (96%) • PGP: 0xA8F90E52"
CORE_PRINCIPLE="Zero Cloud Data Egress (Privacy by Design) • Deterministic & Verifiable AI"
```

---

### 🏛️ Core Engineering Pillars

- **🧬 Computer Vision & Biomedical R&D:**  
  Gigapixel Whole Slide Image (WSI) patch classification at 0.50 µm/px achieving **AUC = 0.87** on the Camelyon benchmark (SPPR / STR-RW with DINOv2 and Vision Transformers). Deep embeddings on **100,000 H&E patches** (`NCT-CRC-HE-100K`, PyTorch ResNet50 d=2048). Dense instance segmentation (**Cellpose v4**) and kinetic trajectory tracking (**TrackPy**) on HeLa cancer cells. Multimodal **CLIP** fine-tuning on medical ROCO datasets.

- **🛡️ Sovereign SecOps, Threat Intel & IAM (CERT VINCI):**  
  Maintaining an autonomous Python triage pipeline handling **1,500 security tickets/day** with **70% automated resolution** in 24/7 production. Governed by **213 automated pytest tests** (88% coverage, 0 mypy strict errors). On-premise **Qwen2.5-3B QLoRA 4-bit** for threat extraction without cloud data leakage. Anti-quishing via **PyZbar** and **DINOv2 Siamese** brand spoofing detection. IGA Active Directory **Role Mining** with Segregation of Duties (SoD) toxic matrix audit.

- **⚙️ Distributed Data Engineering & Sovereign MLOps:**  
  Decoupled event streaming backbone via **Apache Kafka + Zookeeper** with partitioned delivery callbacks. Fine-tuned **DeBERTa-v3** transformer on FEVER benchmark achieving **F1 = 0.89**. Hardened **Kubernetes** deployments under strict RBAC policies (dedicated ServiceAccounts, least-privilege). Persistent storage on **PostgreSQL 15**.

- **💻 High-Velocity Web & Real-Time SaaS:**  
  **MAPARIS (Paris Security Pulse):** Monorepo real-time security tracking and dynamic hazard avoidance routing (Safe Routing) built with **Fastify**, **Socket.io WebSockets**, and **Leaflet**. **BABELSTORE:** Modern headless retail platform built on **Astro 5** (Google **Lighthouse 98+**, Zero-JS by default). 6 production SaaS deployed publicly.

---

### 📊 Benchmark & Inference Telemetry

| Model / Pipeline | Target Task | Parameters / Precision | VRAM / RAM | Latency (P95) | Benchmark Score |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Qwen2.5-3B-SecOps** | Threat Triage & NER | 3B (QLoRA 4-bit NF4) | 2.6 GB VRAM | 18 ms/token | 96.0% Classification Accuracy |
| **DINOv2 Siamese** | Brand Spoofing Detection | 21M (FP16) | 1.1 GB VRAM | 14 ms/image | 0.94 Precision @ Recall 0.91 |
| **Camelyon WSI Attention** | Metastasis Patch Tiling | 24M (FP32) | 4.8 GB VRAM | 120 patches/s | AUC 0.87 (Camelyon16) |
| **DeBERTa-v3-Security** | Security Payload NLI | 86M (INT8) | 850 MB RAM | 28 ms/batch | F1 0.89 (FEVER Benchmark) |
| **Cellpose HeLa Engine** | Cell Instance Tracking | 14M (FP32) | 1.8 GB VRAM | 310 ms/frame | 91.8% IoU Cell Boundary |
| **MAPARIS Socket Ingest** | Concurrent Location Fanout | Distributed Event Loop | 180 MB RAM | 8 ms response | 10k concurrent sockets/node |

---

### 🚀 Production Systems & Open Source

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
