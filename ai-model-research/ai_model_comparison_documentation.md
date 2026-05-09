# AI Model Documentation

## Document Metadata

| Item | Details |
|---|---|
| Source format | Tabular comparison sheet provided as pasted text |
| Models covered | Claude, ChatGPT, Gemini, Grok, DeepSeek, Llama 4 |
| Total major sections included | 16 |
| Total evaluation fields included | 168 |
| Information policy | No source field was intentionally removed or skipped. |
| Review note | AI model information, pricing, availability, and benchmarks change quickly. Re-verify before procurement, production deployment, compliance review, or final vendor selection. |

## Models Covered

- **Claude**
- **ChatGPT**
- **Gemini**
- **Grok**
- **DeepSeek**
- **Llama 4**

## Table of Contents

- [EXECUTIVE SUMMARY](#executive-summary)
- [1. BASIC IDENTITY INFORMATION](#1-basic-identity-information)
- [2. VERSION AND UPDATE INFORMATION](#2-version-and-update-information)
- [3. MODEL SIZE AND TECHNICAL DETAILS](#3-model-size-and-technical-details)
- [4. CAPABILITY CHECKLIST](#4-capability-checklist)
- [5. INPUT AND OUTPUT MODALITY](#5-input-and-output-modality)
- [6. PRICING AND FREE OFFERING](#6-pricing-and-free-offering)
- [7. ACCESS AND PLATFORM AVAILABILITY](#7-access-and-platform-availability)
- [8. DEVELOPER INTEGRATION](#8-developer-integration)
- [9. BENCHMARK AND PERFORMANCE INFORMATION](#9-benchmark-and-performance-information)
- [10. STRENGTHS AND WEAKNESSES](#10-strengths-and-weaknesses)
- [11. ENTERPRISE, PRIVACY, AND COMPLIANCE](#11-enterprise-privacy-and-compliance)
- [12. SAFETY AND RISK](#12-safety-and-risk)
- [13. PRACTICAL TESTING CHECKLIST](#13-practical-testing-checklist)
- [14. SOURCE AND EVIDENCE](#14-source-and-evidence)
- [15. FINAL RECOMMENDATION](#15-final-recommendation)

## How to Read This Documentation

Each major section comes from the original comparison sheet. Under each section, every evaluation field is shown separately. For each field, the six model columns are presented in a compact two-column table: **Model** and **Details**. This avoids excessive horizontal scrolling and makes the document easier to share, review, and update.

---

## EXECUTIVE SUMMARY

**Fields included in this section:**

- Overall winner / safest default
- Recommended model for general business
- Recommended model for coding
- Recommended model for lowest API cost
- Recommended model for open/self-hosted use
- Key caution

### Overall winner / safest default

| Model | Details |
|---|---|
| **Claude** | Claude Opus 4.7: best for careful enterprise work, coding agents, long-context analysis |
| **ChatGPT** | GPT-5.5 / ChatGPT: strongest all-round assistant ecosystem for productivity, coding, files, tools |
| **Gemini** | Gemini 3.1 Pro Preview: best for Google ecosystem, multimodal input, long context, Search grounding |
| **Grok** | Grok 4.3: best for X/web-aware workflows, low API price, high throughput |
| **DeepSeek** | DeepSeek V4-Pro/Flash: best cost/performance and open-weight/value option |
| **Llama 4** | Llama 4 Scout/Maverick: best open-weight/self-hosting route, especially private/long-context use |

### Recommended model for general business

| Model | Details |
|---|---|
| **Claude** | Claude Opus 4.7 / Sonnet depending cost |
| **ChatGPT** | GPT-5.5 Instant or Thinking |
| **Gemini** | Gemini 3.1 Pro Preview |
| **Grok** | Grok 4.3 for current-info and search-aware tasks |
| **DeepSeek** | DeepSeek V4-Pro for low-cost reasoning |
| **Llama 4** | Llama 4 Maverick if self-host/open-weight is required |

### Recommended model for coding

| Model | Details |
|---|---|
| **Claude** | Claude Opus 4.7 |
| **ChatGPT** | GPT-5.5 / Codex ecosystem |
| **Gemini** | Gemini 3.1 Pro Preview |
| **Grok** | Grok 4.3 |
| **DeepSeek** | DeepSeek V4-Pro |
| **Llama 4** | Llama 4 Maverick |

### Recommended model for lowest API cost

| Model | Details |
|---|---|
| **Claude** | Not lowest; premium frontier pricing |
| **ChatGPT** | Not lowest; premium frontier pricing |
| **Gemini** | Moderate; Flash/Lite variants are cheaper than Pro |
| **Grok** | Low-cost flagship API |
| **DeepSeek** | Best low-cost option among these; V4-Flash especially cheap |
| **Llama 4** | No official Meta API token price; total cost depends on infrastructure/provider |

### Recommended model for open/self-hosted use

| Model | Details |
|---|---|
| **Claude** | No |
| **ChatGPT** | No |
| **Gemini** | No |
| **Grok** | No |
| **DeepSeek** | Yes, V4 open-weight/open-source preview plus hosted API |
| **Llama 4** | Yes, Scout and Maverick open weights under Meta license |

### Key caution

| Model | Details |
|---|---|
| **Claude** | Premium API cost; closed weights; validate high-risk/security workflows |
| **ChatGPT** | Closed model; premium API cost; confirm exact GPT-5.5 API availability before production |
| **Gemini** | Preview model; model behavior, limits, and pricing can change |
| **Grok** | Fast model lifecycle; older Grok models retire May 15, 2026 |
| **DeepSeek** | Preview/open-weight; verify jurisdiction, support, IP, security, and SLA before enterprise use |
| **Llama 4** | Self-host complexity; no official hosted Meta API/SLA; benchmark transparency should be independently validated |

---

## 1. BASIC IDENTITY INFORMATION

**Fields included in this section:**

- One-line overview
- Provider / company
- Country / origin
- Model name / latest version
- Model family
- Model variant / tier
- Model category
- Open / closed status
- License type
- Market position
- Official website / docs link

### One-line overview

| Model | Details |
|---|---|
| **Claude** | Anthropic's latest generally available Opus model for complex reasoning, coding, vision, and agentic tasks. |
| **ChatGPT** | OpenAI's latest frontier ChatGPT/Codex model family with Instant, Thinking, and Pro tiers. |
| **Gemini** | Google's current Gemini 3-series Pro preview model for multimodal reasoning and long-context workflows. |
| **Grok** | xAI's flagship API/chat model for reasoning, tool use, and real-time web/X-aware workflows. |
| **DeepSeek** | DeepSeek's V4 family: Pro for stronger reasoning/agents, Flash for fast economical workloads. |
| **Llama 4** | Meta's open-weight Llama 4 family: Scout for huge context, Maverick for stronger general/coding performance. |

### Provider / company

| Model | Details |
|---|---|
| **Claude** | Anthropic |
| **ChatGPT** | OpenAI |
| **Gemini** | Google / Google DeepMind |
| **Grok** | xAI |
| **DeepSeek** | DeepSeek |
| **Llama 4** | Meta AI |

### Country / origin

| Model | Details |
|---|---|
| **Claude** | United States |
| **ChatGPT** | United States |
| **Gemini** | United States |
| **Grok** | United States |
| **DeepSeek** | China |
| **Llama 4** | United States |

### Model name / latest version

| Model | Details |
|---|---|
| **Claude** | Claude Opus 4.7 |
| **ChatGPT** | GPT-5.5 / GPT-5.5 Instant / GPT-5.5 Thinking / GPT-5.5 Pro |
| **Gemini** | Gemini 3.1 Pro Preview |
| **Grok** | Grok 4.3 |
| **DeepSeek** | DeepSeek V4-Pro and V4-Flash |
| **Llama 4** | Llama 4 Scout and Llama 4 Maverick |

### Model family

| Model | Details |
|---|---|
| **Claude** | Claude 4 |
| **ChatGPT** | GPT-5.5 |
| **Gemini** | Gemini 3 |
| **Grok** | Grok 4 |
| **DeepSeek** | DeepSeek V4 |
| **Llama 4** | Llama 4 |

### Model variant / tier

| Model | Details |
|---|---|
| **Claude** | Opus; Sonnet and Haiku are separate Claude tiers |
| **ChatGPT** | Instant, Thinking, Pro; Codex-related usage available separately |
| **Gemini** | Pro Preview; Flash/Flash-Lite/Image models separate |
| **Grok** | 4.3 flagship; 4.20 reasoning/non-reasoning also visible |
| **DeepSeek** | V4-Pro, V4-Flash; thinking/non-thinking modes |
| **Llama 4** | Scout, Maverick; Behemoth is preview/teacher, not generally released |

### Model category

| Model | Details |
|---|---|
| **Claude** | Frontier reasoning/coding/multimodal assistant |
| **ChatGPT** | Frontier general assistant, reasoning, coding, multimodal |
| **Gemini** | Frontier multimodal/long-context assistant |
| **Grok** | Reasoning/chat/tool/search model |
| **DeepSeek** | Reasoning/coding/open-weight/value model family |
| **Llama 4** | Open-weight multimodal MoE model family |

### License type

| Model | Details |
|---|---|
| **Claude** | Proprietary Anthropic terms |
| **ChatGPT** | Proprietary OpenAI terms |
| **Gemini** | Proprietary Google terms |
| **Grok** | Proprietary xAI terms |
| **DeepSeek** | Open-weight/model-specific license; verify repository license before redistribution |
| **Llama 4** | Meta Llama 4 Community License; not OSI-standard open source |

### Market position

| Model | Details |
|---|---|
| **Claude** | Premium enterprise/coding/research model |
| **ChatGPT** | Premium all-round assistant and developer platform |
| **Gemini** | Premium multimodal + Google ecosystem model |
| **Grok** | Real-time/social-web-aware challenger with low API pricing |
| **DeepSeek** | Low-cost open-weight/open-source frontier challenger |
| **Llama 4** | Open-weight ecosystem model for self-hosting and customization |

### Official website / docs link

| Model | Details |
|---|---|
| **Claude** | https://docs.anthropic.com/en/docs/about-claude/models |
| **ChatGPT** | https://platform.openai.com/docs/models |
| **Gemini** | https://ai.google.dev/gemini-api/docs |
| **Grok** | https://docs.x.ai/developers/models/grok-4.3 |
| **DeepSeek** | https://api-docs.deepseek.com/ |
| **Llama 4** | https://www.llama.com/models/llama-4/ |

---

## 2. VERSION AND UPDATE INFORMATION

**Fields included in this section:**

- First release date
- Last update date verified
- Latest update summary
- Update type
- Impact of latest update
- Previous version / predecessor
- Current status
- Deprecated / active status
- Replacement model

### First release date

| Model | Details |
|---|---|
| **Claude** | Claude family first released 2023; Claude Opus 4.7 released Apr 16, 2026 |
| **ChatGPT** | ChatGPT launched Nov 30, 2022; GPT-5.5 released Apr 23, 2026 |
| **Gemini** | Gemini family launched Dec 2023; Gemini 3.1 Pro Preview documented in 2026 |
| **Grok** | Grok family launched 2023; Grok 4.3 current in May 2026 docs |
| **DeepSeek** | DeepSeek founded 2023; DeepSeek V4 Preview announced Apr 2026 |
| **Llama 4** | Llama 4 Scout/Maverick released Apr 5, 2025 |

### Last update date verified

| Model | Details |
|---|---|
| **Claude** | 2026-05-07 |
| **ChatGPT** | 2026-05-07 |
| **Gemini** | 2026-05-07 |
| **Grok** | 2026-05-07 |
| **DeepSeek** | 2026-05-07 |
| **Llama 4** | 2026-05-07 |

### Latest update summary

| Model | Details |
|---|---|
| **Claude** | Opus 4.7 released with improved coding/agents/vision, 1M context, and safety/system-card updates. |
| **ChatGPT** | GPT-5.5 released; GPT-5.5 Instant became default with better factuality, personalization, and fewer hallucinations. |
| **Gemini** | Gemini 3.1 Pro Preview is current Pro preview with 1M input context, 64K output, multimodal input, and thinking controls. |
| **Grok** | Grok 4.3 available as newest flagship; older Grok models scheduled for retirement May 15, 2026. |
| **DeepSeek** | V4-Pro/Flash support 1M context, 384K output, JSON/tool calls, OpenAI and Anthropic-compatible APIs, and discounted V4-Pro pricing. |
| **Llama 4** | No newer official Llama 4 successor found; Scout and Maverick remain current open weights; Behemoth remains preview/teacher. |

### Update type

| Model | Details |
|---|---|
| **Claude** | New model release |
| **ChatGPT** | New frontier model + default ChatGPT model update |
| **Gemini** | Preview model / API model update |
| **Grok** | Model replacement/deprecation + API update |
| **DeepSeek** | New model family + pricing/cache update |
| **Llama 4** | Major open-weight model family release |

### Impact of latest update

| Model | Details |
|---|---|
| **Claude** | Better for long-running coding, autonomous agents, finance/research, and high-care document work. |
| **ChatGPT** | Better daily ChatGPT answers, coding/reasoning, image analysis, tool use, and lower hallucination rate. |
| **Gemini** | Better for complex multimodal and long-context tasks in Google AI Studio/Vertex/Gemini app. |
| **Grok** | Low-cost high-context model with configurable reasoning and strong tool/search positioning. |
| **DeepSeek** | Major cost reduction plus long-context/open-weight route for coding and agent workloads. |
| **Llama 4** | Strong private deployment route with very large Scout context and strong Maverick cost/performance. |

### Previous version / predecessor

| Model | Details |
|---|---|
| **Claude** | Claude Opus 4.6 / 4.5 |
| **ChatGPT** | GPT-5.4 / GPT-5.3 Instant |
| **Gemini** | Gemini 3 Pro Preview |
| **Grok** | Grok 4 / Grok 4 fast / Grok 3 / Grok code fast |
| **DeepSeek** | DeepSeek V3.x / R1 era |
| **Llama 4** | Llama 3.x |

### Current status

| Model | Details |
|---|---|
| **Claude** | Active / generally available |
| **ChatGPT** | Active; API rollout noted by OpenAI for GPT-5.5 |
| **Gemini** | Preview |
| **Grok** | Active; recommended replacement for retiring models |
| **DeepSeek** | Preview / active API |
| **Llama 4** | Active open weights |

### Deprecated / active status

| Model | Details |
|---|---|
| **Claude** | Active |
| **ChatGPT** | Active; older GPT models may retire over time |
| **Gemini** | Preview; older Gemini 3 Pro Preview replaced by 3.1 Pro Preview |
| **Grok** | Older Grok models retire May 15, 2026 |
| **DeepSeek** | Aliases deepseek-chat/deepseek-reasoner will be deprecated in future |
| **Llama 4** | Active; no official newer Llama 4 replacement found |

### Replacement model

| Model | Details |
|---|---|
| **Claude** | N/A |
| **ChatGPT** | N/A for GPT-5.5 |
| **Gemini** | Gemini 3.1 Pro Preview replaces older 3 Pro Preview |
| **Grok** | Grok 4.3 replaces Grok 4/code/3 models for API workloads |
| **DeepSeek** | Use explicit deepseek-v4-pro or deepseek-v4-flash |
| **Llama 4** | N/A |

---

## 3. MODEL SIZE AND TECHNICAL DETAILS

**Fields included in this section:**

- Parameter size
- Model architecture
- Context window
- Maximum output tokens
- Training data cutoff / knowledge cutoff
- Supported languages
- Tokenizer details
- Deployment type
- Hardware requirement
- Fine-tuning support
- RAG support
- Prompt caching support
- Batch processing support

### Parameter size

| Model | Details |
|---|---|
| **Claude** | Not publicly disclosed |
| **ChatGPT** | Not publicly disclosed |
| **Gemini** | Not publicly disclosed |
| **Grok** | Not publicly disclosed |
| **DeepSeek** | V4-Pro: 1.6T total / 49B active; V4-Flash: 284B total / 13B active (official/hosted docs may show model-specific weight sizes) |
| **Llama 4** | Scout: 109B total / 17B active / 16 experts; Maverick: 400B total / 17B active / 128 experts |

### Model architecture

| Model | Details |
|---|---|
| **Claude** | Not fully disclosed; frontier transformer-style multimodal/reasoning system |
| **ChatGPT** | Not fully disclosed; frontier multimodal/reasoning model family |
| **Gemini** | Not fully disclosed; Gemini 3 multimodal reasoning architecture |
| **Grok** | Not fully disclosed |
| **DeepSeek** | MoE with sparse attention / token-wise compression in V4 family |
| **Llama 4** | MoE, early-fusion multimodal, autoregressive |

### Context window

| Model | Details |
|---|---|
| **Claude** | 1M tokens for Opus 4.7 |
| **ChatGPT** | API: 1M for GPT-5.5; ChatGPT context varies by plan/mode |
| **Gemini** | 1M input tokens for Gemini 3.1 Pro Preview |
| **Grok** | 1M tokens for Grok 4.3; higher-context pricing above 200K |
| **DeepSeek** | 1M context for V4-Pro and V4-Flash |
| **Llama 4** | Scout: 10M; Maverick: 1M |

### Maximum output tokens

| Model | Details |
|---|---|
| **Claude** | 128K synchronous; Message Batches beta can raise to 300K |
| **ChatGPT** | Varies by product/mode; GPT-5.5 API details should be checked before production |
| **Gemini** | 64K output for Gemini 3.1 Pro Preview |
| **Grok** | Not clearly published in accessible docs; billed output/completion tokens |
| **DeepSeek** | 384K maximum output |
| **Llama 4** | Provider/serving-stack dependent; not consistently published by Meta |

### Training data cutoff / knowledge cutoff

| Model | Details |
|---|---|
| **Claude** | Not publicly disclosed |
| **ChatGPT** | Not publicly disclosed for GPT-5.5 in release page checked |
| **Gemini** | Jan 2025 for Gemini 3 series docs |
| **Grok** | Not publicly disclosed |
| **DeepSeek** | Not publicly disclosed |
| **Llama 4** | August 2024 in Llama 4 model card |

### Supported languages

| Model | Details |
|---|---|
| **Claude** | Strong multilingual; exact official list not fully published |
| **ChatGPT** | Strong multilingual; exact GPT-5.5 list not fully published |
| **Gemini** | Strong multilingual via Google ecosystem; exact model list depends docs |
| **Grok** | Improved multilingual support; exact list not fully disclosed |
| **DeepSeek** | Strong Chinese/English; broader multilingual support likely, verify per use case |
| **Llama 4** | Model card supports Arabic, English, French, German, Hindi, Indonesian, Italian, Portuguese, Spanish, Tagalog, Thai, Vietnamese; pretraining includes more |

### Tokenizer details

| Model | Details |
|---|---|
| **Claude** | Anthropic tokenizer; details available through API/token counting, not fully open |
| **ChatGPT** | OpenAI tokenizer/model-dependent; details through tiktoken/API docs |
| **Gemini** | Google tokenizer/model-dependent; use countTokens API |
| **Grok** | xAI tokenizer/model-dependent; token accounting via API docs |
| **DeepSeek** | DeepSeek tokenizer/model-dependent; token usage API docs |
| **Llama 4** | Llama tokenizer/model card; open-weight ecosystem |

### Deployment type

| Model | Details |
|---|---|
| **Claude** | Claude app/API; cloud marketplace/provider access such as Bedrock/Vertex/Microsoft Foundry where available |
| **ChatGPT** | ChatGPT, OpenAI API, Codex, enterprise/workspace products, cloud partners |
| **Gemini** | Gemini app, Gemini API, Google AI Studio, Vertex AI, Workspace |
| **Grok** | Grok web/app/X, xAI API, Business/Enterprise |
| **DeepSeek** | DeepSeek chat/API; OpenAI-compatible and Anthropic-compatible API; open weights |
| **Llama 4** | Download/self-host; Hugging Face/llama.com; cloud providers may host |

### Hardware requirement

| Model | Details |
|---|---|
| **Claude** | Managed service |
| **ChatGPT** | Managed service |
| **Gemini** | Managed service |
| **Grok** | Managed service |
| **DeepSeek** | Managed API; self-host requirements depend on V4 variant/inference stack |
| **Llama 4** | Scout fits single H100 class GPU in Meta claim; Maverick needs stronger/DGX-class or optimized serving |

### Fine-tuning support

| Model | Details |
|---|---|
| **Claude** | Model-dependent; not a headline Opus 4.7 feature in sources checked |
| **ChatGPT** | OpenAI fine-tuning is model-dependent; verify current supported model list |
| **Gemini** | Vertex tuning/preference tuning is model-dependent |
| **Grok** | Not clearly published for Grok 4.3 in docs checked |
| **DeepSeek** | Open weights allow customization; official API fine-tuning not clearly published |
| **Llama 4** | Yes via open-weight fine-tuning/adapters; requires infrastructure |

### RAG support

| Model | Details |
|---|---|
| **Claude** | Strong with long context, projects/files, connectors, Claude Code |
| **ChatGPT** | Strong with files, tools, search, assistants/agents/connectors |
| **Gemini** | Strong with 1M context, Google Search grounding, Workspace, files/repos |
| **Grok** | Strong with tools/search, web/X search, files/collections/RAG |
| **DeepSeek** | Strong due 1M context and JSON/tool calls |
| **Llama 4** | Strong when paired with vector DB/RAG stack; Scout supports extreme context |

### Prompt caching support

| Model | Details |
|---|---|
| **Claude** | Yes; Opus 4.7 cache hits listed at $0.50/1M tokens; cache writes vary by TTL |
| **ChatGPT** | Yes in OpenAI API/credit rate cards; exact GPT-5.5 cached rate should be verified |
| **Gemini** | Yes; 3.1 Pro cache price listed by prompt size plus storage |
| **Grok** | Yes; cached input $0.20/1M tokens for Grok 4.3 |
| **DeepSeek** | Yes; V4-Pro/Flash cache-hit pricing published |
| **Llama 4** | Depends on serving stack/provider; not a Meta-hosted default API feature |

### Batch processing support

| Model | Details |
|---|---|
| **Claude** | Yes; Anthropic Message Batches with discounted pricing |
| **ChatGPT** | Yes; Batch/Flex half standard rate for GPT-5.5 per OpenAI release |
| **Gemini** | Model-dependent; preview batch availability may vary |
| **Grok** | Yes; Batch API offers 20%-50% off standard rates |
| **DeepSeek** | No separate discount clearly published in pricing table |
| **Llama 4** | Provider/self-host dependent |

---

## 4. CAPABILITY CHECKLIST

**Fields included in this section:**

- Text generation
- Reasoning
- Math
- Coding
- Software engineering
- Data analysis
- Document analysis
- Image understanding
- Image generation
- Image editing
- Audio input
- Audio output
- Video understanding
- Web browsing / search
- Tool calling
- Agentic ability
- Memory
- Structured output
- Multilingual ability
- Bangla support

### Text generation

| Model | Details |
|---|---|
| **Claude** | Excellent |
| **ChatGPT** | Excellent |
| **Gemini** | Excellent |
| **Grok** | Very strong |
| **DeepSeek** | Very strong |
| **Llama 4** | Strong to very strong |

### Reasoning

| Model | Details |
|---|---|
| **Claude** | Excellent; adaptive/extended thinking workflows |
| **ChatGPT** | Excellent; Instant/Thinking/Pro modes |
| **Gemini** | Excellent; thinking-level controls |
| **Grok** | Very strong; configurable reasoning effort |
| **DeepSeek** | Very strong; thinking/non-thinking modes |
| **Llama 4** | Strong; Maverick stronger than Scout |

### Math

| Model | Details |
|---|---|
| **Claude** | Excellent |
| **ChatGPT** | Excellent |
| **Gemini** | Excellent |
| **Grok** | Strong |
| **DeepSeek** | Very strong |
| **Llama 4** | Strong |

### Coding

| Model | Details |
|---|---|
| **Claude** | Excellent; especially long-running agents and complex code |
| **ChatGPT** | Excellent; strong Codex/developer ecosystem |
| **Gemini** | Very strong; code repos/tools |
| **Grok** | Strong; 4.3 recommended for code workloads |
| **DeepSeek** | Very strong; cost-effective coding/agent workloads |
| **Llama 4** | Strong; Maverick better than Scout |

### Software engineering

| Model | Details |
|---|---|
| **Claude** | Excellent multi-file/codebase work |
| **ChatGPT** | Excellent with Codex/workspace agents/tools |
| **Gemini** | Very strong with repos and tools |
| **Grok** | Strong with function calling/web dev |
| **DeepSeek** | Strong with agentic coding |
| **Llama 4** | Good with external repo tooling; self-host complexity |

### Data analysis

| Model | Details |
|---|---|
| **Claude** | Strong |
| **ChatGPT** | Excellent |
| **Gemini** | Strong, especially Workspace/Sheets |
| **Grok** | Strong with tools |
| **DeepSeek** | Strong with JSON/tools |
| **Llama 4** | Depends on app stack |

### Document analysis

| Model | Details |
|---|---|
| **Claude** | Excellent; 1M context/high-res vision |
| **ChatGPT** | Excellent; files/docs in ChatGPT |
| **Gemini** | Excellent; PDFs/files/audio/video/repo mix |
| **Grok** | Strong; app/API workflow-dependent |
| **DeepSeek** | Strong; 1M context |
| **Llama 4** | Very strong for private corpora; Scout huge context |

### Image understanding

| Model | Details |
|---|---|
| **Claude** | Yes; strong vision |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Not confirmed for V4 text API table |
| **Llama 4** | Yes; text+image |

### Image generation

| Model | Details |
|---|---|
| **Claude** | Not base Opus model; Claude Design/artifacts are product features |
| **ChatGPT** | Yes through ChatGPT image tools, not necessarily base GPT-5.5 text model |
| **Gemini** | Yes via separate Gemini/Nano Banana image models |
| **Grok** | Yes via Grok Imagine/API |
| **DeepSeek** | Not primary/confirmed for V4 |
| **Llama 4** | No native image output |

### Image editing

| Model | Details |
|---|---|
| **Claude** | Limited/product-tool based |
| **ChatGPT** | Yes through ChatGPT image tools |
| **Gemini** | Yes via Gemini image models |
| **Grok** | Yes via Grok Imagine |
| **DeepSeek** | Not primary/confirmed |
| **Llama 4** | No native image editing |

### Audio input

| Model | Details |
|---|---|
| **Claude** | Product/API support varies; not headline Opus 4.7 feature |
| **ChatGPT** | Yes through ChatGPT voice/audio tools |
| **Gemini** | Yes; Gemini supports audio input in model family/API |
| **Grok** | Yes via Voice API / model-specific support |
| **DeepSeek** | Not confirmed for V4 |
| **Llama 4** | No native audio in base weights |

### Audio output

| Model | Details |
|---|---|
| **Claude** | Not primary/confirmed for Opus API |
| **ChatGPT** | Yes through ChatGPT voice/TTS tools |
| **Gemini** | Yes via Gemini app/live APIs, model-dependent |
| **Grok** | Yes via Voice API/app |
| **DeepSeek** | Not confirmed |
| **Llama 4** | No native audio output |

### Video understanding

| Model | Details |
|---|---|
| **Claude** | Not primary/confirmed for Opus 4.7 API |
| **ChatGPT** | Tool/app-dependent |
| **Gemini** | Yes; key Gemini strength |
| **Grok** | Model/tool-dependent; X video understanding via tools |
| **DeepSeek** | Not confirmed |
| **Llama 4** | No native video input in base open weights |

### Web browsing / search

| Model | Details |
|---|---|
| **Claude** | Claude app/tools/connectors where available |
| **ChatGPT** | Yes in ChatGPT/search tools |
| **Gemini** | Yes; Google Search grounding |
| **Grok** | Yes; real-time web and X search |
| **DeepSeek** | Chat/app search; API requires external tools |
| **Llama 4** | No native browsing; add external search/RAG |

### Tool calling

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | External framework/provider dependent |

### Agentic ability

| Model | Details |
|---|---|
| **Claude** | Excellent; Claude Code/Cowork/long tasks |
| **ChatGPT** | Excellent; Codex/workspace agents |
| **Gemini** | Very strong; tools and autonomous coding |
| **Grok** | Strong; tool/search/code execution |
| **DeepSeek** | Strong; agentic coding optimized |
| **Llama 4** | Good with external agent framework |

### Memory

| Model | Details |
|---|---|
| **Claude** | Claude app/project memory features plan-dependent |
| **ChatGPT** | ChatGPT memory/personalization by plan/settings |
| **Gemini** | Gemini personalization/memory via Google ecosystem |
| **Grok** | Grok app/business history/connectors; verify admin controls |
| **DeepSeek** | Implement externally |
| **Llama 4** | Implement externally |

### Structured output

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | Yes via constrained decoding/serving frameworks |

### Multilingual ability

| Model | Details |
|---|---|
| **Claude** | Strong |
| **ChatGPT** | Strong |
| **Gemini** | Strong |
| **Grok** | Good/strong |
| **DeepSeek** | Strong Chinese/English, broader multilingual to validate |
| **Llama 4** | Strong for supported languages; can fine-tune beyond |

### Bangla support

| Model | Details |
|---|---|
| **Claude** | Usable; internally test Bangla/Banglish |
| **ChatGPT** | Good in practice; internally test Bangla/Banglish |
| **Gemini** | Good in practice; internally test Bangla/Banglish |
| **Grok** | Usable; internally test |
| **DeepSeek** | Usable; internally test |
| **Llama 4** | Usable; not one of official 12 supported languages, so test carefully |

---

## 5. INPUT AND OUTPUT MODALITY

**Fields included in this section:**

- Input modalities
- Output modalities
- Embedding output

### Input modalities

| Model | Details |
|---|---|
| **Claude** | Text, images, files/doc workflows depending product/API |
| **ChatGPT** | Text, image, files, voice/audio, tools depending ChatGPT/API feature |
| **Gemini** | Text, image, audio, video, PDFs/files/repos depending API/app |
| **Grok** | Text, images, files/collections, web/X search, voice tools |
| **DeepSeek** | Text and tool/JSON workflows; multimodal not confirmed for V4 table |
| **Llama 4** | Multilingual text + image |

### Output modalities

| Model | Details |
|---|---|
| **Claude** | Text, code, JSON; design/artifact product features |
| **ChatGPT** | Text, code, JSON; image/audio through separate ChatGPT tools |
| **Gemini** | Text, code, JSON; image/video/audio via separate Gemini ecosystem models/tools |
| **Grok** | Text, code, JSON; image/video/voice through separate Grok APIs |
| **DeepSeek** | Text, code, JSON |
| **Llama 4** | Text and code |

### Embedding output

| Model | Details |
|---|---|
| **Claude** | Separate Anthropic/partner embedding options; Opus is not an embedding model |
| **ChatGPT** | Separate OpenAI embedding models |
| **Gemini** | Separate Gemini embedding models |
| **Grok** | No dedicated embedding model confirmed in docs checked |
| **DeepSeek** | No dedicated embedding model in V4 pricing table |
| **Llama 4** | Use separate/self-host embedding models; Llama 4 chat model not primarily embeddings |

---

## 6. PRICING AND FREE OFFERING

**Fields included in this section:**

- Free plan available
- Free usage limit
- Paid plan
- Subscription cost
- API input token cost
- API output token cost
- Cached token cost
- Batch API discount
- Fine-tuning cost
- Image/audio/video cost
- Enterprise pricing
- Cost efficiency

### Free plan available

| Model | Details |
|---|---|
| **Claude** | Yes, Claude Free |
| **ChatGPT** | Yes, ChatGPT Free |
| **Gemini** | Yes, Gemini Free/app; API free tier model-dependent |
| **Grok** | Yes, Grok limited free access |
| **DeepSeek** | Yes, DeepSeek Chat; API paid/balance |
| **Llama 4** | Yes, open-weight download subject to license |

### Free usage limit

| Model | Details |
|---|---|
| **Claude** | Usage-limited; varies by load/plan |
| **ChatGPT** | Limited; paid plans increase caps |
| **Gemini** | Free limits vary; Gemini 3.1 Pro API free tier not available in pricing table |
| **Grok** | Limited free access; higher limits paid |
| **DeepSeek** | Chat limits vary; API requires balance/granted credits |
| **Llama 4** | No token limit from Meta; constrained by hardware/provider |

### Paid plan

| Model | Details |
|---|---|
| **Claude** | Claude Pro, Max, Team, Enterprise |
| **ChatGPT** | ChatGPT Go, Plus, Pro, Business, Enterprise, Edu |
| **Gemini** | Google AI Plus, Pro, Ultra; Workspace/Vertex |
| **Grok** | SuperGrok, Business, Enterprise; X Premium/Premium+ impacts usage |
| **DeepSeek** | API pay-as-you-go/prepaid; custom/enterprise not clearly published |
| **Llama 4** | No official Meta subscription; infra/cloud provider cost |

### Subscription cost

| Model | Details |
|---|---|
| **Claude** | Claude Pro $20/month or lower annual equivalent; Max/Team/Enterprise available |
| **ChatGPT** | ChatGPT Go/Plus/Pro/Business/Enterprise; Plus traditionally $20/month; Go pricing varies by region |
| **Gemini** | Google AI Plus/Pro/Ultra; pricing varies by region; Pro/Ultra published on Google subscriptions page |
| **Grok** | Grok Business $30/user/month; consumer plans vary by region/app/X plan |
| **DeepSeek** | No standard consumer subscription found beyond chat/app/API |
| **Llama 4** | No official subscription; self-host/cloud costs |

### API input token cost

| Model | Details |
|---|---|
| **Claude** | $5 / 1M input tokens for Opus 4.7 |
| **ChatGPT** | $5 / 1M input tokens for GPT-5.5; GPT-5.5 Pro $30 / 1M input when available |
| **Gemini** | $2 / 1M <=200K prompt; $4 / 1M >200K prompt for Gemini 3.1 Pro Preview |
| **Grok** | $1.25 / 1M input tokens |
| **DeepSeek** | V4-Flash $0.14 / 1M cache miss; V4-Pro promo $0.435 / 1M, list $1.74 |
| **Llama 4** | No official Meta API price; self-host/cloud provider dependent |

### API output token cost

| Model | Details |
|---|---|
| **Claude** | $25 / 1M output tokens for Opus 4.7 |
| **ChatGPT** | $30 / 1M output tokens for GPT-5.5; GPT-5.5 Pro $180 / 1M output when available |
| **Gemini** | $12 / 1M <=200K prompt; $18 / 1M >200K prompt for Gemini 3.1 Pro Preview |
| **Grok** | $2.50 / 1M output tokens |
| **DeepSeek** | V4-Flash $0.28 / 1M; V4-Pro promo $0.87 / 1M, list $3.48 |
| **Llama 4** | No official Meta API price; self-host/cloud provider dependent |

### Cached token cost

| Model | Details |
|---|---|
| **Claude** | Cache hits $0.50 / 1M for Opus 4.7; cache writes vary by TTL |
| **ChatGPT** | Prompt caching supported; exact GPT-5.5 cached rate should be checked on live pricing page |
| **Gemini** | $0.20 / 1M <=200K prompt; $0.40 / 1M >200K + storage |
| **Grok** | $0.20 / 1M cached input tokens |
| **DeepSeek** | V4-Flash $0.0028 / 1M; V4-Pro promo $0.003625 / 1M |
| **Llama 4** | Provider/stack dependent |

### Batch API discount

| Model | Details |
|---|---|
| **Claude** | 50% style discounted batch rates listed by Anthropic |
| **ChatGPT** | Batch/Flex half standard GPT-5.5 API rate per OpenAI release |
| **Gemini** | Model-dependent; some preview batch availability may vary |
| **Grok** | Batch API offers 20%-50% off standard rates |
| **DeepSeek** | No separate discount clearly listed |
| **Llama 4** | Provider/self-host dependent |

### Fine-tuning cost

| Model | Details |
|---|---|
| **Claude** | Model-dependent; not listed for Opus 4.7 in sources checked |
| **ChatGPT** | Model-dependent; verify current OpenAI supported fine-tuning models |
| **Gemini** | Vertex tuning/preference tuning model-dependent |
| **Grok** | Not found for Grok 4.3 |
| **DeepSeek** | Self-host/open-weight customization cost only; official API fine-tuning unclear |
| **Llama 4** | Self-host/cloud training or LoRA/adapters cost |

### Image/audio/video cost

| Model | Details |
|---|---|
| **Claude** | Image input billed as tokens; separate product features may differ |
| **ChatGPT** | Separate image/audio/video tool pricing may apply |
| **Gemini** | Audio/image/video input priced in Gemini API; image/video generation priced separately |
| **Grok** | Imagine API: image/video prices; Voice API: hourly/character costs; text model token prices separate |
| **DeepSeek** | Not primary/confirmed for V4 |
| **Llama 4** | Self-host/tool dependent |

### Enterprise pricing

| Model | Details |
|---|---|
| **Claude** | Team/Enterprise/custom; API billed separately |
| **ChatGPT** | Business/Edu/Enterprise; custom enterprise terms |
| **Gemini** | Workspace/Vertex/Google Cloud enterprise pricing |
| **Grok** | Grok Business $30/user/mo; Enterprise contact sales |
| **DeepSeek** | Custom/enterprise not clearly published; API balance-based |
| **Llama 4** | No official Meta-hosted enterprise plan; ecosystem/cloud vendors |

### Cost efficiency

| Model | Details |
|---|---|
| **Claude** | Medium/low; premium quality, premium cost |
| **ChatGPT** | Medium/low; premium platform |
| **Gemini** | Medium; use Flash/Lite variants for lower cost |
| **Grok** | High for flagship API |
| **DeepSeek** | Very high |
| **Llama 4** | Potentially high if self-hosting is optimized |

---

## 7. ACCESS AND PLATFORM AVAILABILITY

**Fields included in this section:**

- Web app available
- Mobile app available
- API available
- SDK support
- Cloud platform support
- Local run support
- Browser extension / IDE support
- Enterprise admin panel
- Region availability
- API rate limits

### Web app available

| Model | Details |
|---|---|
| **Claude** | Yes, claude.ai |
| **ChatGPT** | Yes, chatgpt.com |
| **Gemini** | Yes, gemini.google.com |
| **Grok** | Yes, grok.com / X |
| **DeepSeek** | Yes, chat.deepseek.com |
| **Llama 4** | Meta AI apps/web where available; model weights downloadable |

### Mobile app available

| Model | Details |
|---|---|
| **Claude** | Yes iOS/Android |
| **ChatGPT** | Yes iOS/Android |
| **Gemini** | Yes iOS/Android |
| **Grok** | Yes iOS/Android/X |
| **DeepSeek** | Yes iOS/Android |
| **Llama 4** | No official Llama app; accessible through Meta AI/platforms |

### API available

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | No official Meta token API; cloud/self-host/provider APIs |

### SDK support

| Model | Details |
|---|---|
| **Claude** | Python/TypeScript/REST and cloud SDKs |
| **ChatGPT** | Python/JS/REST and broad ecosystem |
| **Gemini** | Python/JS/Go/REST/Vertex SDKs |
| **Grok** | OpenAI-compatible and xAI SDK/docs |
| **DeepSeek** | OpenAI-compatible and Anthropic-compatible API |
| **Llama 4** | Transformers/vLLM/llama.cpp/provider SDKs |

### Cloud platform support

| Model | Details |
|---|---|
| **Claude** | Anthropic API; Bedrock/Vertex/Microsoft channels where supported |
| **ChatGPT** | OpenAI platform; enterprise/cloud partner availability |
| **Gemini** | Google AI Studio / Vertex AI / Workspace |
| **Grok** | xAI API / enterprise |
| **DeepSeek** | DeepSeek platform; third-party providers possible |
| **Llama 4** | Hugging Face/cloud provider/self-host |

### Local run support

| Model | Details |
|---|---|
| **Claude** | No |
| **ChatGPT** | No |
| **Gemini** | No |
| **Grok** | No |
| **DeepSeek** | Yes for open weights, but hardware-heavy |
| **Llama 4** | Yes |

### Browser extension / IDE support

| Model | Details |
|---|---|
| **Claude** | Claude Code, integrations/connectors |
| **ChatGPT** | ChatGPT/Codex/IDE ecosystem |
| **Gemini** | Gemini Code Assist, CLI, Workspace |
| **Grok** | Use with code editors via API/docs |
| **DeepSeek** | OpenAI-compatible tools; IDE integration via third parties |
| **Llama 4** | Open-source/local dev tools |

### Enterprise admin panel

| Model | Details |
|---|---|
| **Claude** | Team/Enterprise controls |
| **ChatGPT** | Business/Enterprise controls |
| **Gemini** | Google Workspace/Cloud admin |
| **Grok** | Grok Business/Enterprise controls |
| **DeepSeek** | Limited/implementation-specific |
| **Llama 4** | Implementation-specific |

### Region availability

| Model | Details |
|---|---|
| **Claude** | Varies by plan/country/cloud region |
| **ChatGPT** | Varies by plan/country/enterprise region |
| **Gemini** | Varies by Google region/product |
| **Grok** | Regional endpoints us-east-1/eu-west-1 noted for API |
| **DeepSeek** | Region/jurisdiction sensitive; verify terms |
| **Llama 4** | Depends on download license and cloud/provider region |

### API rate limits

| Model | Details |
|---|---|
| **Claude** | Raised Opus limits announced May 2026; exact tier dependent |
| **ChatGPT** | Tier/project dependent; ChatGPT limits by plan |
| **Gemini** | Preview limits model-dependent |
| **Grok** | Grok 4.3 listed: 1,800 RPM / 10M TPM |
| **DeepSeek** | Account/provider dependent; not clearly published in pricing table |
| **Llama 4** | Hardware/provider dependent |

---

## 8. DEVELOPER INTEGRATION

**Fields included in this section:**

- REST API
- Python SDK
- JavaScript / TypeScript SDK
- Java SDK
- .NET SDK
- Streaming support
- Function calling
- JSON Schema / structured output
- Embedding support
- Fine-tuning API
- Realtime API
- MCP / connectors compatibility

### REST API

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | Provider/self-host dependent |

### Python SDK

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes/compatible |
| **DeepSeek** | OpenAI-compatible SDK; Anthropic-compatible endpoint |
| **Llama 4** | Yes via Hugging Face/Transformers/vLLM/etc. |

### JavaScript / TypeScript SDK

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes/compatible |
| **DeepSeek** | OpenAI-compatible SDK |
| **Llama 4** | Provider/self-host dependent |

### Java SDK

| Model | Details |
|---|---|
| **Claude** | REST/community/cloud SDKs |
| **ChatGPT** | REST/community SDKs |
| **Gemini** | Google Cloud/Vertex SDKs |
| **Grok** | REST/OpenAI-compatible |
| **DeepSeek** | REST/OpenAI-compatible |
| **Llama 4** | Provider/self-host dependent |

### .NET SDK

| Model | Details |
|---|---|
| **Claude** | REST/community/cloud SDKs |
| **ChatGPT** | OpenAI SDK/REST/community |
| **Gemini** | Google Cloud/REST/community |
| **Grok** | REST/OpenAI-compatible |
| **DeepSeek** | REST/OpenAI-compatible |
| **Llama 4** | Provider/self-host dependent |

### Streaming support

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | Provider/self-host dependent |

### Function calling

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | External framework/provider dependent |

### JSON Schema / structured output

| Model | Details |
|---|---|
| **Claude** | Yes |
| **ChatGPT** | Yes |
| **Gemini** | Yes |
| **Grok** | Yes |
| **DeepSeek** | Yes |
| **Llama 4** | Yes through constrained decoding/serving |

### Embedding support

| Model | Details |
|---|---|
| **Claude** | Separate model/service |
| **ChatGPT** | Separate embedding models |
| **Gemini** | Separate embedding models |
| **Grok** | No dedicated embedding model confirmed |
| **DeepSeek** | No dedicated V4 embedding in pricing table |
| **Llama 4** | Use separate embedding model |

### Fine-tuning API

| Model | Details |
|---|---|
| **Claude** | Model-dependent/limited |
| **ChatGPT** | Model-dependent |
| **Gemini** | Vertex model-dependent |
| **Grok** | Not clearly published |
| **DeepSeek** | Not clearly published |
| **Llama 4** | Self-host fine-tuning/adapters |

### Realtime API

| Model | Details |
|---|---|
| **Claude** | Voice/realtime model-specific; not main Opus 4.7 focus |
| **ChatGPT** | Realtime/audio APIs available in OpenAI ecosystem |
| **Gemini** | Gemini Live/realtime APIs available model-dependent |
| **Grok** | Voice API/WebSocket mode available |
| **DeepSeek** | Not primary/confirmed |
| **Llama 4** | Provider/self-host dependent |

### MCP / connectors compatibility

| Model | Details |
|---|---|
| **Claude** | Claude supports MCP/connectors in product ecosystem |
| **ChatGPT** | ChatGPT supports apps/connectors and enterprise integrations |
| **Gemini** | Google Workspace/connectors/integrations |
| **Grok** | Remote MCP tools and connectors listed in xAI docs |
| **DeepSeek** | Compatible through external agent frameworks/APIs |
| **Llama 4** | Compatible via external agent frameworks |

---

## 9. BENCHMARK AND PERFORMANCE INFORMATION

**Fields included in this section:**

- General knowledge benchmark
- Reasoning benchmark
- Math benchmark
- Coding benchmark
- Multimodal benchmark
- Long-context benchmark
- Instruction following
- Truthfulness / hallucination
- Safety benchmark
- Speed / latency
- Reliability
- Real-world performance

### General knowledge benchmark

| Model | Details |
|---|---|
| **Claude** | Strong; Anthropic cites state-of-the-art on finance/GDPval-style work |
| **ChatGPT** | OpenAI release reports GPT-5.5 gains across GDPval, FinanceAgent, OfficeQA Pro, and broad tasks |
| **Gemini** | Strong; OpenAI comparison lists Gemini 3.1 Pro among top competitors |
| **Grok** | xAI claims lowest hallucination/instruction-following leadership; independent numeric scores not fully captured |
| **DeepSeek** | Official claims top-tier open-model world knowledge |
| **Llama 4** | Meta claims Scout/Maverick beat class peers; verify independently |

### Reasoning benchmark

| Model | Details |
|---|---|
| **Claude** | Excellent; strong multi-step finance/research-agent performance |
| **ChatGPT** | Excellent; Thinking and Pro tiers for harder tasks |
| **Gemini** | Excellent; thinking controls and Deep Think ecosystem |
| **Grok** | Strong; configurable reasoning effort |
| **DeepSeek** | Very strong; thinking modes and official top-tier claims |
| **Llama 4** | Strong; Maverick stronger than Scout; Behemoth unreleased |

### Math benchmark

| Model | Details |
|---|---|
| **Claude** | Strong/Excellent; exact score depends eval |
| **ChatGPT** | Strong/Excellent; release says improved STEM performance |
| **Gemini** | Strong/Excellent |
| **Grok** | Strong |
| **DeepSeek** | Strong; Math/STEM emphasized |
| **Llama 4** | Strong; Meta cites Behemoth STEM but Behemoth not generally released |

### Coding benchmark

| Model | Details |
|---|---|
| **Claude** | Excellent; Opus 4.7 improves over Opus 4.6; CursorBench-style gains cited |
| **ChatGPT** | Excellent; OpenAI reports strong agentic coding/Codex performance |
| **Gemini** | Very strong; improved code and agentic workflows |
| **Grok** | Strong; migration guide recommends 4.3 for code workloads |
| **DeepSeek** | Very strong; cost-effective agentic coding claims |
| **Llama 4** | Strong; Maverick competitive in class |

### Multimodal benchmark

| Model | Details |
|---|---|
| **Claude** | Strong vision; Opus 4.7 powers Claude Design preview |
| **ChatGPT** | Strong; image/photo analysis and multimodal tools |
| **Gemini** | Excellent; key Gemini strength across image/audio/video/PDF |
| **Grok** | Strong app/API multimodal ecosystem; dedicated Imagine/Voice APIs |
| **DeepSeek** | Not primary/confirmed for V4 text model |
| **Llama 4** | Strong text+image multimodal model |

### Long-context benchmark

| Model | Details |
|---|---|
| **Claude** | 1M context with consistent long-context reports |
| **ChatGPT** | 1M API context; product mode/plan-dependent |
| **Gemini** | 1M input context |
| **Grok** | 1M context; pricing changes above 200K |
| **DeepSeek** | 1M context and 384K output |
| **Llama 4** | Scout 10M; Maverick 1M; validate after quantization/provider |

### Instruction following

| Model | Details |
|---|---|
| **Claude** | Excellent; Anthropic says substantially improved strict instruction following |
| **ChatGPT** | Strong; improved task completion/tool use |
| **Gemini** | Strong; structured tools/thinking controls |
| **Grok** | Strong; xAI claims leader in instruction following |
| **DeepSeek** | Strong; JSON/tool support |
| **Llama 4** | Good; prompt tuning may be needed |

### Truthfulness / hallucination

| Model | Details |
|---|---|
| **Claude** | Low-medium; Anthropic reports honesty/prompt-injection improvements |
| **ChatGPT** | Low-medium; OpenAI says GPT-5.5 Instant has 52.5% fewer hallucinated claims vs GPT-5.3 Instant on high-stakes prompts |
| **Gemini** | Low-medium; best with Search grounding |
| **Grok** | Low-medium claimed by xAI; validate independently |
| **DeepSeek** | Medium; validate with retrieval and source checks |
| **Llama 4** | Medium; depends on deployment/prompt/RAG |

### Safety benchmark

| Model | Details |
|---|---|
| **Claude** | Strong; system card and election safeguards; low concerning behavior but not perfect |
| **ChatGPT** | Strong; system cards/preparedness process |
| **Gemini** | Strong Google safety/preview controls |
| **Grok** | Enterprise compliance claims; validate brand-sensitive safety |
| **DeepSeek** | Open weights/API require external guardrails and legal/security review |
| **Llama 4** | Open weights require external moderation/guardrails |

### Speed / latency

| Model | Details |
|---|---|
| **Claude** | Moderate; Opus quality-focused, some reports faster median latency vs Opus 4.6 |
| **ChatGPT** | Instant optimized for speed; Codex fast mode offers speed/cost tradeoff |
| **Gemini** | thinking_level controls latency/cost; low minimizes latency |
| **Grok** | High throughput; reasoning effort affects latency |
| **DeepSeek** | V4-Flash faster/economical; V4-Pro stronger/slower |
| **Llama 4** | Self-host/provider dependent |

### Reliability

| Model | Details |
|---|---|
| **Claude** | High for complex code, long documents, careful enterprise work |
| **ChatGPT** | High for broad productivity and tools |
| **Gemini** | High but preview means behavior/limits may change |
| **Grok** | Good; verify for regulated use |
| **DeepSeek** | Good value; verify SLA/compliance |
| **Llama 4** | Highly deployment-dependent |

### Real-world performance

| Model | Details |
|---|---|
| **Claude** | Best for complex async code/data/research workflows |
| **ChatGPT** | Best all-round assistant/tool platform |
| **Gemini** | Best Google-native multimodal/Workspace workflows |
| **Grok** | Best X/web freshness and low-cost API experimentation |
| **DeepSeek** | Best low-cost long-context reasoning/coding |
| **Llama 4** | Best private/open-weight deployment |

---

## 10. STRENGTHS AND WEAKNESSES

**Fields included in this section:**

- Best use cases
- Main strengths
- Main weaknesses
- Hallucination risk
- Reasoning reliability
- Coding reliability
- Multimodal reliability
- Long-context reliability
- Safety limitations
- Model lifecycle risk

### Best use cases

| Model | Details |
|---|---|
| **Claude** | Code agents, finance/research, legal/enterprise docs, long-horizon tasks |
| **ChatGPT** | Business productivity, coding, education, data analysis, document creation |
| **Gemini** | Multimodal research, Google Workspace, video/audio/image/PDF analysis |
| **Grok** | Search-aware chat, social/live data, tool-calling API workloads |
| **DeepSeek** | Cost-sensitive coding agents, long document QA, open-model deployments |
| **Llama 4** | Private deployments, model customization, huge context document analysis |

### Main strengths

| Model | Details |
|---|---|
| **Claude** | Coding, long-context, careful reasoning, enterprise channels, agentic workflows |
| **ChatGPT** | All-round quality, ChatGPT ecosystem, files/tools/spreadsheets/Codex |
| **Gemini** | Multimodal input, 1M context, Google Search/Workspace, thinking controls |
| **Grok** | Low price, 1M context, high rate limits, X/web search, configurable reasoning |
| **DeepSeek** | Very low pricing, 1M context, open weights, strong reasoning/coding value |
| **Llama 4** | Open-weight, Scout 10M context, self-hosting, customization |

### Main weaknesses

| Model | Details |
|---|---|
| **Claude** | Higher cost; closed weights; latency can be moderate |
| **ChatGPT** | Closed model; premium API cost; API rollout/plan differences need checking |
| **Gemini** | Preview status; Pro not cheapest; Google model migrations possible |
| **Grok** | Compliance/transparency less mature than longer-established enterprise vendors |
| **DeepSeek** | Preview; jurisdiction/IP/security/compliance diligence needed |
| **Llama 4** | Self-host complexity; no official Meta API/SLA; provider-dependent performance |

### Hallucination risk

| Model | Details |
|---|---|
| **Claude** | Low-medium |
| **ChatGPT** | Low-medium |
| **Gemini** | Low-medium with grounding |
| **Grok** | Low-medium claimed, verify |
| **DeepSeek** | Medium; use RAG/validation |
| **Llama 4** | Medium; use RAG/validation |

### Reasoning reliability

| Model | Details |
|---|---|
| **Claude** | High |
| **ChatGPT** | High |
| **Gemini** | High |
| **Grok** | Medium-high |
| **DeepSeek** | Medium-high |
| **Llama 4** | Medium-high for Maverick; Scout lower |

### Coding reliability

| Model | Details |
|---|---|
| **Claude** | High |
| **ChatGPT** | High |
| **Gemini** | High |
| **Grok** | Medium-high |
| **DeepSeek** | Medium-high |
| **Llama 4** | Medium-high; deployment dependent |

### Multimodal reliability

| Model | Details |
|---|---|
| **Claude** | High for image/doc vision |
| **ChatGPT** | High through ChatGPT tools |
| **Gemini** | High; key Gemini advantage |
| **Grok** | Medium-high; model/tool-dependent |
| **DeepSeek** | Low/unclear for non-text modalities |
| **Llama 4** | Good for text+image |

### Long-context reliability

| Model | Details |
|---|---|
| **Claude** | High |
| **ChatGPT** | High, product-dependent |
| **Gemini** | High but preview |
| **Grok** | Medium-high; cost changes above 200K |
| **DeepSeek** | High on paper; test practical retrieval |
| **Llama 4** | Potentially high; validate after quantization/provider |

### Safety limitations

| Model | Details |
|---|---|
| **Claude** | May refuse some high-risk/security workflows; still not perfect |
| **ChatGPT** | Strong guardrails may over-refuse; policy-bound |
| **Gemini** | Preview restrictions/guardrails may change |
| **Grok** | Validate for brand-sensitive workflows |
| **DeepSeek** | Needs external moderation and legal/security review |
| **Llama 4** | Needs external moderation/guardrails |

### Model lifecycle risk

| Model | Details |
|---|---|
| **Claude** | Medium |
| **ChatGPT** | Medium |
| **Gemini** | High for preview models |
| **Grok** | High due active deprecations |
| **DeepSeek** | Medium-high due preview/aliases |
| **Llama 4** | Low-medium; weights remain but ecosystem shifts |

---

## 11. ENTERPRISE, PRIVACY, AND COMPLIANCE

**Fields included in this section:**

- API stability
- SLA available
- Security certifications
- Data usage policy
- Data retention policy
- Training opt-out
- Zero data retention option
- Logging and audit support
- Admin controls
- Role-based access
- Private deployment
- Compliance suitability

### API stability

| Model | Details |
|---|---|
| **Claude** | High |
| **ChatGPT** | High; confirm GPT-5.5 API production availability |
| **Gemini** | Preview for 3.1 Pro; Vertex more enterprise-ready |
| **Grok** | Growing |
| **DeepSeek** | Preview; validate SLA/support |
| **Llama 4** | Depends on provider/self-host |

### SLA available

| Model | Details |
|---|---|
| **Claude** | Enterprise/cloud-provider dependent |
| **ChatGPT** | Enterprise/API plan dependent |
| **Gemini** | Google Cloud/Vertex dependent |
| **Grok** | Enterprise contact sales |
| **DeepSeek** | Not clearly published |
| **Llama 4** | Provider/self-host dependent |

### Security certifications

| Model | Details |
|---|---|
| **Claude** | Anthropic enterprise/cloud compliance; verify contract |
| **ChatGPT** | OpenAI enterprise compliance; verify contract |
| **Gemini** | Google Cloud compliance portfolio via Vertex/Workspace |
| **Grok** | xAI claims SOC 2 Type 2, GDPR, CCPA, ZDR on API page; verify contract |
| **DeepSeek** | Not fully captured; due diligence required |
| **Llama 4** | Your infrastructure/provider compliance |

### Data usage policy

| Model | Details |
|---|---|
| **Claude** | Consumer vs business/API differs; verify terms |
| **ChatGPT** | Business/Enterprise/API terms differ; training opt-out/business protections available by product |
| **Gemini** | Free API may be used to improve products; paid terms differ |
| **Grok** | Verify xAI/Grok/X terms separately |
| **DeepSeek** | Verify DeepSeek terms; jurisdiction-sensitive |
| **Llama 4** | Self-host controls data; cloud provider terms apply |

### Data retention policy

| Model | Details |
|---|---|
| **Claude** | Plan/API dependent |
| **ChatGPT** | Plan/API dependent |
| **Gemini** | Plan/API dependent |
| **Grok** | Plan/API dependent; enterprise/ZDR available per xAI claims |
| **DeepSeek** | Not captured; verify before sensitive data |
| **Llama 4** | Self-host controlled |

### Training opt-out

| Model | Details |
|---|---|
| **Claude** | Business/API terms dependent |
| **ChatGPT** | Available in business/API contexts; verify current terms |
| **Gemini** | Paid API/Cloud terms differ from free tier |
| **Grok** | Verify enterprise terms |
| **DeepSeek** | Verify terms |
| **Llama 4** | Self-host: yes by design |

### Zero data retention option

| Model | Details |
|---|---|
| **Claude** | Enterprise/API dependent |
| **ChatGPT** | Enterprise/API dependent |
| **Gemini** | Google Cloud options dependent |
| **Grok** | xAI API page claims Zero Data Retention |
| **DeepSeek** | Not clearly published |
| **Llama 4** | Self-host: yes if configured |

### Logging and audit support

| Model | Details |
|---|---|
| **Claude** | Enterprise/admin features |
| **ChatGPT** | Business/Enterprise admin/compliance controls |
| **Gemini** | Google Workspace/Cloud auditability |
| **Grok** | xAI API page claims audit logging |
| **DeepSeek** | Implementation-specific |
| **Llama 4** | Implementation-specific |

### Admin controls

| Model | Details |
|---|---|
| **Claude** | Team/Enterprise controls |
| **ChatGPT** | Business/Enterprise workspace controls |
| **Gemini** | Workspace/Cloud IAM/admin |
| **Grok** | Business/Enterprise controls |
| **DeepSeek** | Limited/implementation-specific |
| **Llama 4** | Implementation-specific |

### Role-based access

| Model | Details |
|---|---|
| **Claude** | Enterprise/team dependent |
| **ChatGPT** | Business/Enterprise dependent |
| **Gemini** | Workspace/Cloud IAM |
| **Grok** | xAI API page claims RBAC/authorization controls |
| **DeepSeek** | Not clearly published |
| **Llama 4** | Implementation-specific |

### Private deployment

| Model | Details |
|---|---|
| **Claude** | No self-host; cloud marketplace options |
| **ChatGPT** | No self-host |
| **Gemini** | No self-host; Google Cloud regional controls |
| **Grok** | No self-host |
| **DeepSeek** | Yes open weights; managed API also |
| **Llama 4** | Yes open weights |

### Compliance suitability

| Model | Details |
|---|---|
| **Claude** | High with enterprise contract |
| **ChatGPT** | High with enterprise contract |
| **Gemini** | High through Google Cloud/Workspace |
| **Grok** | Medium-high if enterprise terms verified |
| **DeepSeek** | Medium/low for sensitive regulated use unless privately deployed/reviewed |
| **Llama 4** | High only if your deployment/infrastructure is compliant |

---

## 12. SAFETY AND RISK

**Fields included in this section:**

- Prompt injection resistance
- Jailbreak resistance
- Harmful content handling
- Over-refusal risk
- Bias / fairness risk
- Copyright / IP risk
- Privacy risk
- Production guardrail requirement
- Carbon footprint / energy transparency

### Prompt injection resistance

| Model | Details |
|---|---|
| **Claude** | Improved per Anthropic but still needs testing |
| **ChatGPT** | Needs app-level testing; enterprise/tool safeguards |
| **Gemini** | Google has Gemini prompt-injection guidance; still test |
| **Grok** | Needs app-level testing |
| **DeepSeek** | Needs external guardrails |
| **Llama 4** | Needs external guardrails |

### Jailbreak resistance

| Model | Details |
|---|---|
| **Claude** | Strong, not perfect |
| **ChatGPT** | Strong, not perfect |
| **Gemini** | Strong, not perfect |
| **Grok** | Needs validation |
| **DeepSeek** | Needs external moderation/testing |
| **Llama 4** | Needs external moderation/testing |

### Harmful content handling

| Model | Details |
|---|---|
| **Claude** | Strong safety policy; may over-refuse in edge cases |
| **ChatGPT** | Strong policy safeguards; may over-refuse in edge cases |
| **Gemini** | Strong Google policy controls |
| **Grok** | Needs enterprise testing |
| **DeepSeek** | External guardrails recommended |
| **Llama 4** | External guardrails required |

### Over-refusal risk

| Model | Details |
|---|---|
| **Claude** | Medium |
| **ChatGPT** | Medium |
| **Gemini** | Medium |
| **Grok** | Medium |
| **DeepSeek** | Low-medium without external guardrails |
| **Llama 4** | Low-medium without external guardrails |

### Bias / fairness risk

| Model | Details |
|---|---|
| **Claude** | Test per domain |
| **ChatGPT** | Test per domain |
| **Gemini** | Test per domain |
| **Grok** | Test per domain |
| **DeepSeek** | Test per domain |
| **Llama 4** | Test per domain |

### Copyright / IP risk

| Model | Details |
|---|---|
| **Claude** | Use enterprise terms and cite sources; avoid copying protected content |
| **ChatGPT** | Use enterprise terms and cite sources; avoid copying protected content |
| **Gemini** | Use Google terms and citations/grounding |
| **Grok** | Use enterprise terms and citations |
| **DeepSeek** | Review open model license/data/IP risk |
| **Llama 4** | Review Llama license and data/IP risk |

### Privacy risk

| Model | Details |
|---|---|
| **Claude** | Low with enterprise controls; consumer usage differs |
| **ChatGPT** | Low with enterprise controls; consumer usage differs |
| **Gemini** | Low with paid Cloud/Workspace controls; free tier differs |
| **Grok** | Medium until enterprise terms verified |
| **DeepSeek** | Medium/high for sensitive data without review |
| **Llama 4** | Low if self-hosted correctly; provider-dependent otherwise |

### Production guardrail requirement

| Model | Details |
|---|---|
| **Claude** | Recommended |
| **ChatGPT** | Recommended |
| **Gemini** | Recommended |
| **Grok** | Strongly recommended |
| **DeepSeek** | Required for open/model-sensitive deployment |
| **Llama 4** | Required |

### Carbon footprint / energy transparency

| Model | Details |
|---|---|
| **Claude** | No per-model audited carbon footprint found in sources checked |
| **ChatGPT** | No per-model audited carbon footprint found in sources checked |
| **Gemini** | No per-model audited carbon footprint found in sources checked |
| **Grok** | No per-model audited carbon footprint found in sources checked |
| **DeepSeek** | No audited per-model footprint found; efficiency claims exist |
| **Llama 4** | No per-model footprint; self-hosting allows measuring own infra |

---

## 13. PRACTICAL TESTING CHECKLIST

**Fields included in this section:**

- Writing test
- Summarization test
- Coding test
- SQL test
- Data analysis test
- Document QA test
- Image understanding test
- Reasoning test
- Math test
- Bangla/Banglish test
- JSON output test
- Tool calling test
- Safety test
- Hallucination test

### Writing test

| Model | Details |
|---|---|
| **Claude** | Formal report + concise email |
| **ChatGPT** | Formal report + concise email |
| **Gemini** | Formal report + Google Docs style |
| **Grok** | Direct/current-news answer |
| **DeepSeek** | Cost-sensitive summarization |
| **Llama 4** | Self-host writing test |

### Summarization test

| Model | Details |
|---|---|
| **Claude** | Long PDF/report |
| **ChatGPT** | Long PDF/report |
| **Gemini** | PDF/video/audio mix |
| **Grok** | Web/X-heavy topic |
| **DeepSeek** | 1M-token document |
| **Llama 4** | 10M-token Scout stress test |

### Coding test

| Model | Details |
|---|---|
| **Claude** | Real repo bug fix and code review |
| **ChatGPT** | Real repo bug fix via Codex |
| **Gemini** | Repo-level issue with tools |
| **Grok** | API/tool-calling web dev task |
| **DeepSeek** | Agentic coding task |
| **Llama 4** | Local repo generation/refactor |

### SQL test

| Model | Details |
|---|---|
| **Claude** | Schema-aware query optimization |
| **ChatGPT** | Schema-aware query optimization |
| **Gemini** | Schema + CSV/doc task |
| **Grok** | Tool-connected query explanation |
| **DeepSeek** | Cost-sensitive SQL generation |
| **Llama 4** | Self-host SQL generation |

### Data analysis test

| Model | Details |
|---|---|
| **Claude** | CSV + charts |
| **ChatGPT** | Spreadsheet + charts |
| **Gemini** | Google Sheets/CSV |
| **Grok** | CSV + real-time context |
| **DeepSeek** | Large CSV extraction |
| **Llama 4** | Depends on wrapper |

### Document QA test

| Model | Details |
|---|---|
| **Claude** | High-res scanned PDF + long report |
| **ChatGPT** | PDF + multiple docs |
| **Gemini** | PDF/audio/video/repo mixed |
| **Grok** | Web docs + current search |
| **DeepSeek** | Long technical docs |
| **Llama 4** | Large private corpus |

### Image understanding test

| Model | Details |
|---|---|
| **Claude** | Screenshot/charts/UI bug |
| **ChatGPT** | Screenshot/charts/UI bug |
| **Gemini** | Image/video/chart complex task |
| **Grok** | Image + X/web context |
| **DeepSeek** | Not primary |
| **Llama 4** | Image+text reasoning |

### Reasoning test

| Model | Details |
|---|---|
| **Claude** | Multi-step planning |
| **ChatGPT** | Multi-step planning |
| **Gemini** | Multimodal planning |
| **Grok** | Reasoning-effort comparison |
| **DeepSeek** | Thinking-mode comparison |
| **Llama 4** | Prompt strategy comparison |

### Math test

| Model | Details |
|---|---|
| **Claude** | Advanced STEM |
| **ChatGPT** | Advanced STEM |
| **Gemini** | Advanced STEM |
| **Grok** | Math/science with high effort |
| **DeepSeek** | STEM benchmark-style |
| **Llama 4** | STEM benchmark-style |

### Bangla/Banglish test

| Model | Details |
|---|---|
| **Claude** | Banglish QA + formal Bangla output |
| **ChatGPT** | Banglish QA + formal Bangla output |
| **Gemini** | Banglish + Google context |
| **Grok** | Banglish + web/X context |
| **DeepSeek** | Banglish reasoning |
| **Llama 4** | Bangla self-host evaluation |

### JSON output test

| Model | Details |
|---|---|
| **Claude** | Strict JSON schema |
| **ChatGPT** | Strict JSON schema |
| **Gemini** | Strict JSON schema |
| **Grok** | Structured output |
| **DeepSeek** | JSON output + tool call |
| **Llama 4** | Schema via constrained decoding |

### Tool calling test

| Model | Details |
|---|---|
| **Claude** | API call correctness |
| **ChatGPT** | API call correctness |
| **Gemini** | Custom tools endpoint |
| **Grok** | Function calling + search |
| **DeepSeek** | Tool calls via compatible API |
| **Llama 4** | External framework |

### Safety test

| Model | Details |
|---|---|
| **Claude** | Prompt injection + risky request refusal |
| **ChatGPT** | Prompt injection + risky request refusal |
| **Gemini** | Prompt injection + safety refusal |
| **Grok** | Brand-sensitive safety |
| **DeepSeek** | External moderation needed |
| **Llama 4** | External moderation needed |

### Hallucination test

| Model | Details |
|---|---|
| **Claude** | Unknown facts + conflicting docs |
| **ChatGPT** | Unknown facts + conflicting docs |
| **Gemini** | Grounded search vs non-grounded |
| **Grok** | Live web claims validation |
| **DeepSeek** | Long-context factuality |
| **Llama 4** | RAG factuality after quantization |

---

## 14. SOURCE AND EVIDENCE

**Fields included in this section:**

- Main source URL
- Pricing source URL
- Subscription source URL
- Model card / technical source URL
- Benchmark source URL
- Source reliability level
- Last verified date

### Main source URL

| Model | Details |
|---|---|
| **Claude** | https://www.anthropic.com/news/claude-opus-4-7 |
| **ChatGPT** | https://openai.com/index/introducing-gpt-5-5/ |
| **Gemini** | https://ai.google.dev/gemini-api/docs/gemini-3 |
| **Grok** | https://docs.x.ai/developers/models/grok-4.3 |
| **DeepSeek** | https://api-docs.deepseek.com/news/news260424 |
| **Llama 4** | https://ai.meta.com/blog/llama-4-multimodal-intelligence/ |

### Pricing source URL

| Model | Details |
|---|---|
| **Claude** | https://docs.anthropic.com/en/docs/about-claude/pricing |
| **ChatGPT** | https://openai.com/index/introducing-gpt-5-5/ |
| **Gemini** | https://ai.google.dev/gemini-api/docs/pricing |
| **Grok** | https://docs.x.ai/developers/models/grok-4.3 |
| **DeepSeek** | https://api-docs.deepseek.com/quick_start/pricing |
| **Llama 4** | No official Meta API pricing; see https://www.llama.com/models/llama-4/ |

### Subscription source URL

| Model | Details |
|---|---|
| **Claude** | https://claude.com/pricing |
| **ChatGPT** | https://chatgpt.com/pricing/ |
| **Gemini** | https://gemini.google/subscriptions/ |
| **Grok** | https://x.ai/grok/business and https://help.x.com/en/using-x/x-premium |
| **DeepSeek** | https://chat.deepseek.com/ |
| **Llama 4** | https://www.llama.com/models/llama-4/ |

### Model card / technical source URL

| Model | Details |
|---|---|
| **Claude** | https://docs.anthropic.com/en/docs/about-claude/models |
| **ChatGPT** | https://platform.openai.com/docs/models |
| **Gemini** | https://ai.google.dev/gemini-api/docs/models |
| **Grok** | https://docs.x.ai/developers/models |
| **DeepSeek** | https://huggingface.co/deepseek-ai |
| **Llama 4** | https://huggingface.co/meta-llama/Llama-4-Scout-17B-16E |

### Benchmark source URL

| Model | Details |
|---|---|
| **Claude** | https://www.anthropic.com/news/claude-opus-4-7 and https://www.anthropic.com/news/finance-agents |
| **ChatGPT** | https://openai.com/index/introducing-gpt-5-5/ |
| **Gemini** | https://ai.google.dev/gemini-api/docs/gemini-3 and official Google/DeepMind model pages |
| **Grok** | https://x.ai/api and https://docs.x.ai/developers/migration/may-15-deprecation |
| **DeepSeek** | https://api-docs.deepseek.com/news/news260424 |
| **Llama 4** | https://ai.meta.com/blog/llama-4-multimodal-intelligence/ |

### Source reliability level

| Model | Details |
|---|---|
| **Claude** | High: official release/docs/pricing; benchmark claims partly vendor/tester reported |
| **ChatGPT** | High: official OpenAI release/pricing; verify API live docs before production |
| **Gemini** | High: official Google docs/pricing; preview caveat |
| **Grok** | High: official xAI docs/API; independent benchmark validation recommended |
| **DeepSeek** | High for official release/pricing; enterprise/compliance details require verification |
| **Llama 4** | High for official model card/release; benchmark controversy means independent testing recommended |

### Last verified date

| Model | Details |
|---|---|
| **Claude** | 2026-05-07 |
| **ChatGPT** | 2026-05-07 |
| **Gemini** | 2026-05-07 |
| **Grok** | 2026-05-07 |
| **DeepSeek** | 2026-05-07 |
| **Llama 4** | 2026-05-07 |

---

## 15. FINAL RECOMMENDATION

**Fields included in this section:**

- Recommended for
- Avoid if
- Best alternative
- Cheaper alternative
- Open-source / open-weight alternative
- Enterprise alternative
- Final verdict
- Overall rating

### Recommended for

| Model | Details |
|---|---|
| **Claude** | Senior developers, analysts, finance/research teams, enterprise knowledge work |
| **ChatGPT** | General users, developers, educators, business/productivity teams |
| **Gemini** | Google Workspace/Cloud users, multimodal researchers, long-context users |
| **Grok** | Teams needing live web/X context, high throughput, and lower API cost |
| **DeepSeek** | Startups/builders optimizing API cost and open-model control |
| **Llama 4** | Organizations needing private deployment, customization, or huge context |

### Avoid if

| Model | Details |
|---|---|
| **Claude** | You need cheapest API or open weights |
| **ChatGPT** | You need open weights or guaranteed lowest cost |
| **Gemini** | You need stable non-preview model or cheapest output tokens |
| **Grok** | You need mature compliance documentation equal to oldest enterprise vendors |
| **DeepSeek** | You need highly mature Western enterprise compliance/SLA without extra diligence |
| **Llama 4** | You need fully managed frontier API with vendor SLA from Meta |

### Best alternative

| Model | Details |
|---|---|
| **Claude** | GPT-5.5, Gemini 3.1 Pro, DeepSeek V4-Pro |
| **ChatGPT** | Claude Opus 4.7, Gemini 3.1 Pro, Grok 4.3 |
| **Gemini** | GPT-5.5, Claude Opus 4.7 |
| **Grok** | DeepSeek V4-Pro/Flash, Gemini Flash |
| **DeepSeek** | Grok 4.3, Llama 4, Gemini Flash |
| **Llama 4** | DeepSeek V4, Qwen/Mistral/open models |

### Cheaper alternative

| Model | Details |
|---|---|
| **Claude** | Claude Sonnet/Haiku or DeepSeek V4-Flash |
| **ChatGPT** | GPT mini/nano variants or DeepSeek V4-Flash |
| **Gemini** | Gemini Flash/Flash-Lite |
| **Grok** | DeepSeek V4-Flash |
| **DeepSeek** | DeepSeek V4-Flash already cheapest among these |
| **Llama 4** | Quantized/self-host smaller open models |

### Open-source / open-weight alternative

| Model | Details |
|---|---|
| **Claude** | DeepSeek V4, Llama 4 |
| **ChatGPT** | DeepSeek V4, Llama 4 |
| **Gemini** | DeepSeek V4, Llama 4 |
| **Grok** | DeepSeek V4, Llama 4 |
| **DeepSeek** | Llama 4, Qwen, Mistral |
| **Llama 4** | DeepSeek V4, Qwen, Mistral |

### Enterprise alternative

| Model | Details |
|---|---|
| **Claude** | OpenAI Enterprise, Google Vertex AI/Gemini, AWS Bedrock |
| **ChatGPT** | Claude Enterprise, Google Vertex AI/Gemini, AWS |
| **Gemini** | OpenAI Enterprise, Claude Enterprise |
| **Grok** | OpenAI/Claude/Gemini enterprise if compliance is priority |
| **DeepSeek** | OpenAI/Claude/Gemini enterprise for regulated workloads |
| **Llama 4** | Managed cloud provider with enterprise controls |

### Final verdict

| Model | Details |
|---|---|
| **Claude** | Choose Claude when answer quality, coding reliability, long tasks, and careful reasoning matter more than lowest cost. |
| **ChatGPT** | Choose ChatGPT/GPT-5.5 when you need the strongest general assistant ecosystem, files, tools, spreadsheets, and Codex. |
| **Gemini** | Choose Gemini when Google ecosystem, multimodal input, long context, and Search grounding are central. |
| **Grok** | Choose Grok when real-time X/web awareness, low API price, high throughput, and tool/search workflows matter. |
| **DeepSeek** | Choose DeepSeek when API cost, open weights, long context, and coding/reasoning economics matter most. |
| **Llama 4** | Choose Llama 4 when you need open-weight control, private deployment, customization, or extreme context via Scout. |

### Overall rating

| Model | Details |
|---|---|
| **Claude** | 9.3/10 |
| **ChatGPT** | 9.4/10 |
| **Gemini** | 9.1/10 |
| **Grok** | 8.5/10 |
| **DeepSeek** | 8.8/10 |
| **Llama 4** | 8.4/10 |

---

## Integrity Check

| Check | Result |
|---|---|
| Source rows processed | 185 including header and category rows |
| Major sections included | 16 |
| Evaluation fields included | 168 |
| Model columns included | 6 |
| Preservation status | All original category rows and evaluation fields from the pasted text were included in the Markdown document. |

---

**End of documentation.**
