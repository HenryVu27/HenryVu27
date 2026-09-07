# Henry Vu

Founding ML engineer [@eXRealityAI](https://exreality.ai/) and CS grad student [@UTDallas](https://www.utdallas.edu/).
Previously researched online algorithms and multi-armed bandits [@Amii](https://www.amii.ca/). BSc Honors [@UAlberta](https://www.ualberta.ca/).

[henryvu.io](https://henryvu.io) · [blog](https://www.henryvu.blog/)

## now

- LLM agents, retrieval systems, and edge AI at eXRealityAI.
- Ultrasound segmentation for an NIH-funded project at ThorMed.

## LLM and agent systems

- **[ADHDAgent](https://github.com/HenryVu27/ADHDAgent)**: parent-facing ADHD coaching chatbot. LangGraph ReAct agent behind input/output guardrail gates, hybrid Qdrant dense+sparse retrieval with RRF and a local ONNX cross-encoder reranker, multi-tier memory, and an offline eval package with golden sets and LLM judges. FastAPI + React.
- **[DatDai](https://github.com/HenryVu27/DatDai)**: Vietnamese land-law RAG assistant on Cloud Run. Models the amendment graph between statutes so retrieval resolves which decree amends which, verifies every legal citation against retrieved text, and replays live production traces through an LLM judge for scoring.
- **[Suspect-Detection](https://github.com/HenryVu27/Suspect-Detection)**: clinical record analysis. LangGraph supervisor routing detection agents over hybrid FAISS + SQLite FTS retrieval.
- **[VoiceBridge](https://github.com/HenryVu27/voice-agent)**: real-time Vietnamese/Russian speech translation over WebSockets. Deepgram STT, DeepL, Google TTS.
- **[InferenceEngineering](https://github.com/HenryVu27/InferenceEngineering)**: LLM inference engine built from scratch for Qwen2.5-7B on an RTX 5080. In progress.
- **[frontierllm](https://github.com/HenryVu27/frontierllm)**: study notes and an MDX textbook on pretraining, post-training, distributed training, and evaluation.

## ML research

- **[Domain-Aligned Pretraining for Ultrasound Bladder Segmentation](https://github.com/HenryVu27/ISBI2026)**: SimSiam SSL and supervised US30K pretraining, plus 4-bit quantization for edge deployment. In-domain pretraining holds up substantially better than ImageNet initialization under quantization.
- **[Polyps-Segmentation](https://github.com/HenryVu27/Polyps-Segmentation)**: U-Net and Attention U-Net on Kvasir-SEG and BUSI.
- **[EEG-Multimodal-Decoding](https://github.com/HenryVu27/EEG-Multimodal-Decoding)**: CNN + Transformer conformer on the ZuCo EEG and eye-tracking dataset.
- **[PoliticalSarcasm](https://github.com/HenryVu27/PoliticalSarcasm)**: engineered scikit-learn features against a fine-tuned DistilRoBERTa on Reddit comments.
- **[Multi-armed Bandits and Online Learning](https://github.com/HenryVu27/Multi-armed-Bandits-and-Online-Learning)**: Exp3, Exp4, Thompson sampling, with seminar slides from Amii.
- **[Geometric-Set-Cover](https://github.com/HenryVu27/Geometric-Set-Cover)**: survey of approximation algorithms and PTAS for unit disks in the plane.

## products and tools

- **[GardenXR](https://www.meta.com/experiences/gardenxr/24200709416226235/)**: mixed-reality plant care assistant, live on the Meta Quest Store.
- **[HomeIQ](https://github.com/HenryVu27/HomeIQ)**: home-buying readiness and city comparison calculator. Next.js 16, Supabase, Stripe.
- **[MLInterviewPractice](https://github.com/HenryVu27/MLInterviewPractice)**: 131 ML interview problems with an in-browser Pyodide editor.
- **[TFT-Rolling-Calculator](https://github.com/HenryVu27/TFT-Rolling-Calculator)**: Markov chain rolling odds calculator, seven languages.
- **[BTSIM](https://github.com/HenryVu27/BTSIM)**: interactive concert ticket queue simulator.

## links

[henryvu.io](https://henryvu.io) · [blog](https://www.henryvu.blog/) · [linkedin](https://www.linkedin.com/in/henry-vu27/) · [x](https://x.com/HenryVu27)
