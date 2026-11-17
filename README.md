# Hi, I'm Nam (Tien Nam Nguyen) 👋

**AI Research Engineer — LLMs, Document & Speech AI · PhD in Computer Science**

I turn state-of-the-art models into useful products. 6+ years of R&D experience, from research to deployment, across **LLMs** (fine-tuning, GRPO/DPO alignment, agents, RAG), **document intelligence** (OCR, information extraction, NER/NEL) and **speech AI** (Speech-LLMs, ASR, VAD).

- 🔭 Currently building a **voice agent on Speech-LLMs** at Lumi-VN
- 📄 Published at **EMNLP, ICDAR, ICPR, LREC, IEEE Access, Scientific Reports**
- 🏆 **1st place** ICDAR 2021 competition (Task 1) · **3rd place** HIPE-OCRepair, ICDAR 2026
- 🌐 Website: [nguyennampfiev.github.io](https://nguyennampfiev.github.io)
- 📫 [namnt.pfiev@gmail.com](mailto:namnt.pfiev@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tien-nam-nguyen/)

---

## 💼 Experience

| Role | Organization | Period |
|---|---|---|
| **AI Research Engineer** | Lumi-VN · Hanoi, Vietnam | 2026 – present |
| **Research Engineer** | University of La Rochelle — Neweyes Project · France | 2025 – 2026 |
| **Research Engineer** | University of La Rochelle — ANR Chamdoc Project · France | 2024 – 2025 |
| **PhD Candidate, Computer Science** | University of La Rochelle · France | 2020 – 2023 |
| **AI Engineer** | DopikAI · Hanoi, Vietnam | 2020 – 2021 |
| **AI Engineer** | TSDV · Hanoi, Vietnam | 2019 – 2020 |

<details>
<summary><b>Details</b></summary>

**AI Research Engineer · Lumi-VN** (2026 – present)
- Designed multimodal alignment between an audio encoder and an LLM (linear projection), enabling end-to-end speech understanding for ASR and decision-making.
- Built a real-time Voice Activity Detection (VAD) pipeline for streaming.
- *Speech-LLMs, Qwen3-Omni, Whisper, WavLM, ASR, VAD*

**Research Engineer · University of La Rochelle — Neweyes** (2025 – 2026)
- Reformulated quality estimation for information extraction as a regression problem and adapted LLMs to it through fine-tuning.
- Aligned LLMs (GRPO, DPO) for named entity recognition and linking — published at EMNLP 2026, LREC 2026 and ICDAR 2026.
- *GRPO, DPO, RL, GPT-OSS, vLLM, NER, NEL*

**Research Engineer · University of La Rochelle — ANR Chamdoc** (2024 – 2025)
- Fine-tuned Grounding DINO to detect stamps and seals in manuscripts.
- Designed a hybrid loss on Swin Transformer V2 for similarity-based image retrieval.
- *VLMs, Grounding DINO, Swin Transformer, image retrieval*

**PhD Candidate · University of La Rochelle** (2020 – 2023)
- End-to-end document analysis pipeline for Cham manuscripts, from raw image to text: attention UNet enhancement, text line segmentation (docExtractor + Seam Carving), Seq2Seq/Transformer transliteration.
- Each component deployed as a microservice (Flask, Docker) in one workflow.

**AI Engineer · DopikAI** (2020 – 2021)
- End-to-end invoice information extraction with LayoutLMv2, microservices architecture with unit & integration tests.

**AI Engineer · TSDV** (2019 – 2020)
- Wake-word (voice trigger) models with HTK and Kaldi; GANs/VAEs to remove hatching patterns from documents.

</details>

## 🚀 Featured Projects

| Project | Description |
|---|---|
| [LLMOpsRAG](https://github.com/nguyennampfiev/LLMOpsRAG) | RAG document chatbot on GCP — ingestion, indexing, semantic search, CI/CD, monitoring |
| [Trend-News-Notifier](https://github.com/nguyennampfiev/Trend-News-Notifier) | Multi-agent LLM system for news search, summarization and broadcasting (AWS, Prometheus, Grafana) |
| [MCP-demo](https://github.com/nguyennampfiev/MCP-demo) | Model Context Protocol with GPT-OSS |
| [StampRetrieval](https://github.com/nguyennampfiev/StampRetrieval) | Document retrieval pipeline based on stamp information |
| [MSAED](https://github.com/nguyennampfiev/MSAED) | Multi-scale attention for document image enhancement |
| [MDPO-NEL](https://github.com/nguyennampfiev/MDPO-NEL) | Multi-negative preference learning for historical entity linking |

## 📚 Selected Publications

- **T.-N. Nguyen** et al. *Beyond Pairwise Preference: Multi-Negative Preference Learning for LLM-Centric Historical Entity Linking.* **EMNLP 2026**
- **T.-N. Nguyen** et al. *One Model, Many Guidelines: Instruction Fine-Tuning for Historical Named Entity Recognition.* **ICDAR 2026**
- **T.-N. Nguyen** et al. *Reference-free at Inference Quality Estimation of Entity Recognition and Linking over OCRed Historical Texts.* **LREC 2026**
- T.-C. Pham, **T.-N. Nguyen**, V.-D. Hoang, V.-D. Nguyen. *Enhancing Coffee Leaf Disease Classification via Active Learning and Diverse Sample Selection.* **IEEE Access** 13 (2025)
- **T.-N. Nguyen** et al. *Ambiguity-aware semi-supervised learning for leaf disease classification.* **Scientific Reports** 15 (2025)
- **T.-N. Nguyen** et al. *Text line segmentation approach combining deep learning model and traditional image processing techniques — Application to Cham manuscript.* **Multimedia Tools and Applications**, 2024
- **T.-N. Nguyen** et al. *An effective method for text line segmentation in historical document images.* **ICPR 2022**

## 🏆 Awards

- 🥉 **3rd place** — HIPE-OCRepair competition, ICDAR 2026
- 🥇 **1st place (Task 1)**, 4th (Tasks 2 & 3) — "Detect Building Blocks of the Document", ICDAR 2021
- **5th of 62 teams** — SemEval-2024 Task 8: machine-generated text detection

## 🛠️ Skills

- **LLMs & GenAI:** Fine-tuning (LoRA, PEFT), alignment (GRPO, DPO, RL), quantization, RAG, vector DBs, AI agents, LLM-as-a-judge
- **Documents & NLP:** OCR, document image analysis, information extraction (LayoutLM), NER, NEL, text classification
- **Speech:** Speech-LLMs, multimodal alignment, ASR (Whisper, WavLM), real-time VAD
- **Computer Vision:** Object detection (Grounding DINO), VLMs, fine-grained image retrieval, segmentation, GANs, VAEs
- **Frameworks:** Python, PyTorch, Hugging Face (Transformers, PEFT, TRL), vLLM, LangChain, OpenAI Agents SDK, MCP
- **MLOps & Cloud:** Docker, Kubernetes, Terraform, CI/CD, GCP, AWS, Flask, Prometheus, Grafana

## 🎓 Education

- **PhD in Computer Science and Applications** — University of La Rochelle, France (2020 – 2023)
- **Engineering Degree in Information Systems (PFIEV)** — Hanoi University of Science and Technology (2013 – 2018)

🌍 Vietnamese (native) · English (fluent) · French (intermediate)
