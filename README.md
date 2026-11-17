# Hi, I'm Nam (Tien Nam Nguyen) 👋

**AI Research Engineer — LLMs, Document & Speech AI · PhD in Computer Science**

I turn state-of-the-art models into useful products. 6+ years of R&D experience, from research to deployment, across **LLMs** (fine-tuning, GRPO/DPO alignment, agents, RAG), **document intelligence** (OCR, information extraction, NER/NEL) and **speech AI** (Speech-LLMs, ASR, VAD).

- 🔭 Currently at Lumi-VN building **full-duplex Speech-LLMs**, **target-speaker ASR** and **speaker diarization**
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
| **AI Engineer** | TSDV · Hanoi, Vietnam | Aug 2018 – Dec 2019 |

<details open>
<summary><b>Details</b></summary>

### AI Research Engineer · Lumi-VN (2026 – present)
*Voice agents built on Speech-LLMs*
- **Full-duplex dialogue:** developing a spoken dialogue model that listens and speaks at the same time, handling natural turn-taking, interruptions and backchannels.
- **Speech-LLM architecture:** connected audio encoders (Qwen3-Omni, NVIDIA Nemotron) to frozen LLM decoders through projection layers (linear / MLP) and learned soft-prompt tokens, trained in stages: alignment warm-up → ASR → spoken QA.
- **Target-speaker ASR:** conditioning the model on a target speaker to transcribe only their speech in overlapping, noisy and far-field multi-speaker audio, with dedicated data augmentation.
- **Speaker diarization:** joint transcription and diarization ("who spoke when") with timestamps for long-form multi-speaker conversations.
- **Real-time streaming:** Voice Activity Detection (VAD) and end-of-turn detection for low-latency voice interaction.
- **Efficient training & evaluation:** 4-bit (NF4) quantized training of 30B-scale decoders on a single GPU, serving, and benchmarking on VoiceBench.
- *Speech-LLMs · full-duplex · target-speaker ASR · diarization · Qwen3-Omni · Nemotron · Whisper · WavLM · VAD*

### Research Engineer · University of La Rochelle — Neweyes (2025 – 2026)
*LLMs for information extraction from historical documents*
- **Entity linking (EMNLP 2026):** LLM generates normalized entity names to retrieve Wikidata candidates, then an LLM selector picks the right one — trained with multi-negative preference learning (MDPO), beyond pairwise DPO. Code: [MDPO-NEL](https://github.com/nguyennampfiev/MDPO-NEL)
- **NER (ICDAR 2026):** instruction fine-tuning so a single model follows many annotation guidelines.
- **Quality estimation (LREC 2026):** NER/NEL quality estimation over OCRed text as regression, reference-free at inference.
- GRPO / DPO alignment; efficient inference with vLLM and GPT-OSS (MXFP4). 3rd place at HIPE-OCRepair, ICDAR 2026.
- *GRPO · DPO · RL · GPT-OSS · vLLM · NER · NEL*

### Research Engineer · University of La Rochelle — ANR Chamdoc (2024 – 2025)
*Stamp-based retrieval of historical documents*
- **Detection:** fine-tuned Grounding DINO to locate stamps and seals in manuscripts.
- **Retrieval:** hybrid loss (triplet loss with custom hard-sample miner) on Swin Transformer V2, then k-NN search. Code: [StampRetrieval](https://github.com/nguyennampfiev/StampRetrieval)
- Benchmarked fine-grained baselines (DCL); shipped a Streamlit / Gradio demo with Docker.
- *Grounding DINO · Swin Transformer · metric learning · image retrieval*

### PhD Candidate · University of La Rochelle (2020 – 2023)
*End-to-end analysis of Cham manuscripts, from raw image to text*
- **Enhancement:** Pix2Pix GAN with multi-scale attention ([MSAED](https://github.com/nguyennampfiev/MSAED), ICDAR 2021).
- **Text line segmentation:** fine-tuned docExtractor + Seam Carving with an extra cost function (ICPR 2022, MTAP 2024).
- **Transliteration:** two-stage Seq2Seq (Cham → Latin) followed by a Transformer corrector.
- Each component deployed as a Flask/Docker microservice in one workflow. 1st place (Task 1), ICDAR 2021 competition.

### AI Engineer · DopikAI (2020 – 2021)
*Invoice information extraction*
- Orientation-correction pre-processing for scanned / photographed invoices.
- Key-field extraction (invoice number, date, total…) with LayoutLMv2, robust to varied templates.
- Delivered as a micro AI service in the full pipeline, with unit and integration tests.

### AI Engineer · TSDV (Aug 2018 – Dec 2019)
*Speech recognition & generative models*
- Wake-word (voice trigger) models for Russian, Spanish and French, combining HTK and Kaldi.
- Per-language acoustic and language model tuning.
- GANs / VAEs to remove hatching patterns from documents.

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
- **Speech:** Speech-LLMs, full-duplex dialogue, multimodal alignment, ASR (Whisper, WavLM), target-speaker ASR, speaker diarization, real-time VAD
- **Computer Vision:** Object detection (Grounding DINO), VLMs, fine-grained image retrieval, segmentation, GANs, VAEs
- **Frameworks:** Python, PyTorch, Hugging Face (Transformers, PEFT, TRL), vLLM, LangChain, OpenAI Agents SDK, MCP
- **MLOps & Cloud:** Docker, Kubernetes, Terraform, CI/CD, GCP, AWS, Flask, Prometheus, Grafana

## 🎓 Education

- **PhD in Computer Science and Applications** — University of La Rochelle, France (2020 – 2023)
- **Engineering Degree in Information Systems (PFIEV)** — Hanoi University of Science and Technology (2013 – 2018)

🌍 Vietnamese (native) · English (fluent) · French (intermediate)
