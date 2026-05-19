# 👋 AI / ML Engineer

> Ingénieur IA orienté **produit**. Je conçois, fine-tune et **livre** des
> systèmes d'IA jusqu'à l'application finie — du modèle à l'App Store.

*Identité volontairement privée. CV nominatif disponible sur demande directe.*

---

### 🧰 Stack globale

| Catégorie | Technologies |
|---|---|
| **Langages** | Python · TypeScript · JavaScript · MQL4 |
| **ML / DL** | PyTorch · Transformers · Reinforcement Learning (TFT, Dreamer) · STT / TTS / voice cloning · NMT |
| **Mobile** | React Native · Expo · iOS on-device (ANE / CoreML / MLKit) |
| **LLM / Agents** | Anthropic API · OpenAI API · RAG (LlamaIndex, ChromaDB) · orchestration multi-agents |
| **Infra** | Vast.ai GPU (RTX 5090 / H100 / RTX PRO 6000) · Docker · CUDA · FastAPI · GitHub Actions (CI iOS) · cloudflared |

> Chaque projet ci-dessous indique **sa propre stack** — les choix techniques diffèrent selon les contraintes (embarqué, temps réel, entraînement GPU…).

---

## 🗣️ Speech & Voice AI

### 🚀 Just One Tap — App de traduction vocale (iOS · live App Store)

Pipeline IA **embarqué** : reconnaissance vocale → traduction → synthèse vocale.
24 langues, exécution **100 % on-device** (zéro surchauffe), 4 modes
(Solo / Duo / Caméra / Texte).

| | | | | |
|:-:|:-:|:-:|:-:|:-:|
| ![Voice](images/justonetap_1_voice.jpg) | ![Conversation](images/justonetap_2_conversation.jpg) | ![Camera](images/justonetap_3_camera.jpg) | ![Text](images/justonetap_4_text.jpg) | ![Why](images/justonetap_5_why.jpg) |

> **Stack ·** `TypeScript` · `React Native` · `Expo` · `iOS Speech (STT on-device)` · `MLKit Translate (ANE)` · `Apple TTS` · `OCR caméra` · `GitHub Actions (CI iOS)` · `EAS OTA`

---

### 🗣️ Moteur voix multilingue

TTS / clonage vocal **23 langues**, streaming temps réel, VAD robuste au bruit
ambiant, endpoint de synthèse à faible latence.

> **Stack ·** `Python` · `PyTorch` · `FastAPI` · `faster-whisper (STT)` · `Chatterbox Multilingual / Piper (TTS)` · `m2m100 (NMT)` · `streaming + VAD` · `cloudflared`

---

### 🎚️ Fine-tune TTS français

Fine-tuning d'un modèle TTS sur dataset **~100h** : préparation données,
phonémisation, entraînement LoRA multi-GPU cloud, pipeline reproductible.

> **Stack ·** `Python` · `PyTorch` · `Kokoro-82M / StyleTTS2` · `LoRA` · `espeak-ng (phonémisation)` · `Vast.ai multi-GPU (RTX 5090 / H100)` · `DDP`

---

## 🧠 LLM · RAG · Agents

### 🔎 RAG bancaire sécurisé — assistant conformité

RAG sur documents de conformité (**AML / RGPD / guide interne**) : recherche
vectorielle, génération **encadrée par garde-fous d'entrée/sortie**
(anti-injection, blocklist, contrôle de la réponse), citations des sources, API.

![Banking RAG dashboard](images/rag_console.png)

> **Stack ·** `Python` · `FastAPI` · `LlamaIndex` · `ChromaDB` · `embeddings MiniLM` · `Claude (Anthropic)` · `guardrails I/O` · `Docker` · `GitHub Actions (CI)` · `pytest`

---

### 🤖 FRAPZ — Système multi-agents IA

Console d'orchestration **multi-agents** : 9 agents spécialisés répartis sur un
workflow en 3 phases (Discovery → Activation → Production), avec portes de
décision Go/No-Go, suivi tokens/coût et synthèse agrégée.

![FRAPZ multi-agent console](images/frapz_console.png)

> **Stack ·** `JavaScript` · `Alpine.js` · `Tailwind CSS` · `Anthropic API` · `OpenAI API` · `orchestration multi-agents` · `Telegram Bot API`

---

## 📈 Reinforcement Learning

### RL Trading Engine — ensemble multi-agents à grande échelle

Pipeline de **reinforcement learning population-based** : 800 agents (TFT +
Dreamer) entraînés par tournois évolutifs isolés, puis ensemble des 20
meilleurs en vote majoritaire. Inférence **live CPU < 50 ms/décision**.
Entraînement GPU cloud dockerisé et reproductible.

![RL Trading Engine architecture](images/rl_trading_engine_v2.png)

> **Stack ·** `Python` · `PyTorch` · `Temporal Fusion Transformer` · `Dreamer (world-model RL)` · `algorithmes évolutionnaires` · `CUDA` · `Docker` · `Vast.ai 4× RTX PRO 6000` · `pont live MQL4`

---

## 🎬 Creative & Automation

### Generative Video Studio — pipeline vidéo automatisé

**Agent d'orchestration** qui pilote l'**API Seedance** : génération automatique
de plusieurs **branches / variantes par scène** (multi-seed, retry & suivi de
coût), assemblage du **montage Remotion** synchronisé, post-traitement
(upscale) et export multi-format. Couplé à une **création visuelle / direction
artistique** maison.

![Generative Video Studio dashboard](images/video_studio.png)

> **Stack ·** `Python` · `API Seedance (I2V / T2V)` · `agent d'orchestration` · `Remotion` · `TypeScript` · `FFmpeg` · `upscaling`
>
> **Création ·** `Photoshop` · `design / direction artistique` · `création web (HTML / CSS / JS)`

---

## 🧠 Domaines de compétence

`LLM fine-tuning` · `Speech AI (STT / TTS / voice cloning)` · `On-device & mobile AI`
`Model quantization & optimization` · `Neural Machine Translation` · `RAG & guardrails`
`Multi-agent systems` · `Reinforcement Learning` · `GPU cloud training`

<sub>🎬 Loisir : clip musical animé généré par IA — <code>modèles de diffusion</code> · <code>Remotion</code>.</sub>

---

## 📫 Contact

Échanges via recruteur — **contact direct uniquement** (pas de réseaux sociaux par choix).
