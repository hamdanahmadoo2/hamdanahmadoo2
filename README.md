## ◈ What I Actually Do

<table>
<tr>
<td width="50%" valign="top">

### 🧠 Text-Based AI (LLMs)
**Models I work with deeply:**
> `BERT` · `BART` · `T5` · `GPT` · `LLaMA` · `DeepSeek`

- **Fine-Tuning** — LoRA, QLoRA, PEFT on HuggingFace models for domain-specific accuracy
- **RAG Systems** — Hybrid search, re-ranking, multi-query, agentic retrieval — full pipeline
- **Chatbots & Copilots** — Context-aware, memory-enabled, tool-using conversational AI
- **Built Transformer from Scratch** — Self-attention, positional encoding, encoder-decoder — zero pre-trained weights, pure
- PyTorch math

</td>
<td width="50%" valign="top">

### 🖼️ Image-Based AI (Vision Models)
**Models I work with deeply:**
> `GAN` · `cGAN` · `ESRGAN` · `Pix2Pix` · `Stable Diffusion`

- **GANs & Conditional GANs** — Image synthesis, style control, conditional generation
- **ESRGAN** — Super-resolution, restoring low-quality images to high fidelity
- **Pix2Pix** — Image-to-image translation, domain transformation
- **Diffusion Models** — Stable Diffusion pipelines, ControlNet, custom LoRA training for image generation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AI Agents & Automation
**What I build beyond chatbots:**
- **ReAct Agents** — Autonomous reasoning + action loops
- **Multi-Agent Pipelines** — Specialized agents collaborating via LangGraph
- **Tool-Using Systems** — APIs, databases, web search, code execution
- **Memory Architectures** — Short-term, long-term, vectorstore-backed memory
- **Business Automation** — Customer service, reporting, content generation — hands-free

</td>
<td width="50%" valign="top">

### 🌐 Full Stack Web (AI-Native)
**How I ship it to the world:**
- **Next.js 14 + MERN** — Modern, scalable, production-ready web apps
- **AI-Integrated Platforms** — Real-time streaming AI responses in web UIs
- **Unique Frontend Design** — No templates. Custom visual identity every time
- **API Architecture** — Clean REST/GraphQL backends purpose-built for AI workflows
- **Cloud Deployment** — Vercel, AWS, GCP — optimized for AI workloads

</td>
</tr>
</table>

---
## ◈ Deep Expertise — Expanded

<details>
<summary><b>🔬 LLM Fine-Tuning — What I actually do under the hood</b></summary>
<br/>

| Technique | Where I Apply It |
|---|---|
| **LoRA** | Parameter-efficient adapter training on BERT, GPT, LLaMA |
| **QLoRA** | 4-bit quantized fine-tuning for consumer hardware constraints |
| **PEFT** | Full HuggingFace PEFT library integration across model families |
| **Instruction Tuning** | Alpaca-style datasets, custom chat templates |
| **Custom Training Loops** | PyTorch-native loops with warmup schedulers, label smoothing |

**Models fine-tuned for real tasks:**
- `BERT` → Text classification, NER, semantic similarity
- `T5` → Multi-task text-to-text, summarization, Q&A
- `BART` → Abstractive summarization, seq2seq generation
- `LLaMA 2/3` → Local deployment with GGUF, LoRA adaptation
- `GPT` → Instruction following, domain Q&A
- `DeepSeek` → Code generation, reasoning-heavy tasks

</details>

<details>
<summary><b>🔬 RAG Pipelines — Advanced, not basic</b></summary>
<br/>

```
Raw Documents
     │
     ▼
Intelligent Chunking  ──── semantic / recursive / hierarchical
     │
     ▼
Embedding Generation  ──── OpenAI · HuggingFace · Cohere
     │
     ▼
Vector Store          ──── Pinecone · ChromaDB · FAISS · Weaviate
     │
     ▼
Hybrid Search         ──── Dense (embeddings) + Sparse (BM25)
     │
     ▼
Re-Ranking            ──── Cohere Rerank · Cross-Encoder
     │
     ▼
LLM Response          ──── Grounded · Cited · Hallucination-Free
```

**Advanced RAG patterns I implement:**
- **Multi-Query RAG** — Multiple query variants for broader recall
- **Self-RAG** — Model decides when retrieval is needed
- **Parent-Child Chunking** — Precise retrieval with full context return
- **Agentic RAG** — Agents that query, update, and reason over knowledge bases
- **Graph RAG** — Knowledge graphs for complex relational reasoning

</details>

<details>
<summary><b>🔬 Image Generation Models — GAN to Diffusion</b></summary>
<br/>

| Model | What I build with it |
|---|---|
| **GAN** | Adversarial image synthesis from scratch, latent space manipulation |
| **cGAN** | Conditional generation — control what the model outputs |
| **ESRGAN** | 4x/8x super-resolution, restoring degraded images |
| **Pix2Pix** | Paired image translation — sketches to photos, maps to satellite |
| **Stable Diffusion** | Custom pipelines, txt2img, img2img, inpainting |
| **ControlNet** | Pose/edge/depth-guided generation for precise visual outputs |
| **Diffusion LoRA** | Fine-tuning diffusion models on custom image datasets |

</details>

<details>
<summary><b>🔬 Transformer Architecture — Built from scratch in PyTorch</b></summary>
<br/>

Every component implemented from first principles. No copy-paste. No shortcuts.

```python
class TransformerFromScratch:
    ✅ Multi-Head Self-Attention      # Q, K, V projections, scaled dot-product
    ✅ Positional Encoding            # Sinusoidal frequencies, learnable variants
    ✅ Feed-Forward Network           # Two-layer MLP with GELU activation
    ✅ Layer Normalization            # Pre-LN architecture for training stability
    ✅ Encoder Stack                  # N-layer stacked with residual connections
    ✅ Decoder Stack                  # Masked self-attention + cross-attention
    ✅ Causal Masking                 # Autoregressive generation support
    ✅ Training Loop                  # Warmup scheduler, label smoothing, gradient clipping
```

This is proof of **mathematical ownership** — I understand what's happening inside the model, not just how to call it.

</details>

<details>
<summary><b>🔬 AI Agents & Autonomous Workflows</b></summary>
<br/>

**Agent architectures I design:**

| Pattern | Description |
|---|---|
| **ReAct** | Reason-then-Act loop until goal completion |
| **Tool-Use** | Web search, code execution, DB queries, API calls |
| **Multi-Agent** | Planner + Executor + Critic agents via LangGraph |
| **Memory** | Buffer memory, entity memory, vectorstore long-term recall |
| **Streaming** | Token-by-token reasoning streamed to frontend in real-time |

**Real automation pipelines:**
- 🗂️ Classify and auto-respond to customer support tickets
- 📊 Pull live DB data → generate formatted business reports
- 📧 Research → draft → send personalized outreach autonomously
- 🔍 Multi-step research agents with web browsing and synthesis

</details>

---


## ◈ What I Can Build For You

<div align="center">

| 🧠 AI Systems | 🌐 Web Platforms | ⚙️ Business Automation |
|:---|:---|:---|
| Custom LLM fine-tuned for your domain | Next.js 14 + MERN full-stack apps | AI agents running 24/7 without humans |
| RAG over your internal knowledge base | AI-integrated, real-time web platforms | Auto customer service & support bots |
| Conversational AI copilots & chatbots | Unique, creative UI — never templated | Automated reporting from live data |
| Image generation & vision pipelines | REST/GraphQL APIs for AI workflows | End-to-end workflow orchestration |
| Multi-agent autonomous systems | Cloud-deployed, scalable architecture | Intelligent content generation pipelines |

</div>
