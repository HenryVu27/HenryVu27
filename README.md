# Henry Vu

ML engineer [@eXRealityAI](https://exreality.ai/) and CS grad student [@UTDallas](https://www.utdallas.edu/).
Previously researched online algorithms and multi-armed bandits [@Amii](https://www.amii.ca/). BSc Honors [@UAlberta](https://www.ualberta.ca/).

[henryvu.io](https://henryvu.io) · [blog](https://www.henryvu.blog/)

## now

- Lead engineer on Smart DVI at eXRealityAI, an AI vehicle-inspection app for Meta Quest 3. I own its AI layer, from photo grading to the agents that run on the headset.
- Ultrasound segmentation for an NIH-funded project at ThorMed.

## research

- **[simulacrum](https://github.com/HenryVu27/simulacrum)**: which concepts does the world force on any mind, and which does a body add? Trains 14 minds that share one learning rule and one 2D physics world (JAX) but differ in senses and body: human-like, dog-like, blind, smell-only, echolocating, a yoked passive observer. Probes what each knows about object permanence, number, cause and space, then breaks the world's physics on purpose to split each concept into what the mind contributes and what the world forces. Preregistered, with an independent audit of what holds.
- **[pianolens](https://github.com/HenryVu27/pianolens)**: scoring piano performances on correctness, control, shaping and interpretation against expert performances. Audited so far: expert ratings reduce to 3 to 5 factors, and interpretable MIDI features match a MuQ audio model on unseen works.
- **[human](https://github.com/HenryVu27/human)**: why AI-written prose still reads as AI. Local writers (OLMo-2-13B with QLoRA, trained on pre-ChatGPT essayists) tested against Pangram as a held-out judge, with selection rules committed before every scan.

## computer vision

- **[Domain-Aligned Pretraining for Ultrasound Bladder Segmentation](https://github.com/HenryVu27/thormed)**: U-Net encoders pretrained on thyroid and breast ultrasound, supervised and with SimSiam, reach 96% Dice on bladder segmentation. At 4-bit weights they keep 75 to 93% Dice while ImageNet-initialized encoders fall to 11 to 71%. [Paper](https://github.com/HenryVu27/thormed/blob/main/Thormed_ISBI_New.pdf)
- **[polyps](https://github.com/HenryVu27/polyps)**: U-Net and Attention U-Net on Kvasir-SEG and BUSI.
- **[samus-masks](https://github.com/HenryVu27/samus-masks)**: bladder segmentation masks from the SAMUS ultrasound foundation model, with a refinement step.

## LLM and agent systems

- **[compass](https://github.com/HenryVu27/compass)**: parent-facing ADHD coaching chatbot. LangGraph ReAct agent behind input/output guardrail gates, hybrid Qdrant dense+sparse retrieval with RRF and a local ONNX cross-encoder reranker, multi-tier memory, and an offline eval package with golden sets and LLM judges. FastAPI + React.
- **[datdai](https://github.com/HenryVu27/datdai)**: Vietnamese land-law RAG assistant on Cloud Run. Models the amendment graph between statutes so retrieval resolves which decree amends which, verifies every legal citation against retrieved text, and replays live production traces through an LLM judge for scoring.
- **[inference](https://github.com/HenryVu27/inference)**: LLM inference engine built from scratch for Qwen2.5-7B on an RTX 5080. In progress.
- **[suspect](https://github.com/HenryVu27/suspect)**: clinical record analysis. LangGraph supervisor routing detection agents over hybrid FAISS + SQLite FTS retrieval.
- **[voicebridge](https://github.com/HenryVu27/voicebridge)**: real-time Vietnamese/Russian speech translation over WebSockets. Deepgram STT, DeepL, Google TTS.
- **[frontier](https://github.com/HenryVu27/frontier)**: study notes and an MDX textbook on pretraining, post-training, distributed training, and evaluation.

## other research

- **[zuco](https://github.com/HenryVu27/zuco)**: CNN + Transformer conformer on the ZuCo EEG and eye-tracking dataset.
- **[sarcasm](https://github.com/HenryVu27/sarcasm)**: engineered scikit-learn features against a fine-tuned DistilRoBERTa on Reddit comments.
- **[bandits](https://github.com/HenryVu27/bandits)**: Exp3, Exp4, Thompson sampling, with seminar slides from Amii.
- **[setcover](https://github.com/HenryVu27/setcover)**: survey of approximation algorithms and PTAS for unit disks in the plane.

## markets

- **[alpha](https://github.com/HenryVu27/alpha)**: geopolitical event-driven swing trading signals. Redis Streams layers, backtesting, WhatsApp alerts.
- **[greek](https://github.com/HenryVu27/greek)**: study guide on market microstructure and options dealer flows. Next.js MDX site with KaTeX.
- **[tcgnosis](https://github.com/HenryVu27/tcgnosis)**: One Piece card game catalog built from Bandai's card lists plus tournament prize printings, the base for price tracking.

## products and tools

- **[GardenXR](https://www.meta.com/experiences/gardenxr/24200709416226235/)**: mixed-reality plant care assistant, live on the Meta Quest Store.
- **[homeiq](https://github.com/HenryVu27/homeiq)**: home-buying readiness and city comparison calculator. Next.js 16, Supabase, Stripe.
- **[MLInterviewPractice](https://github.com/HenryVu27/MLInterviewPractice)**: 131 ML interview problems with an in-browser Pyodide editor.
- **[TFT-Rolling-Calculator](https://github.com/HenryVu27/TFT-Rolling-Calculator)**: Markov chain rolling odds calculator, seven languages.
- **[btsim](https://github.com/HenryVu27/btsim)**: interactive concert ticket queue simulator.

## links

[henryvu.io](https://henryvu.io) · [blog](https://www.henryvu.blog/) · [linkedin](https://www.linkedin.com/in/henry-vu27/) · [x](https://x.com/HenryVu27)
