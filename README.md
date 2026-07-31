<div align="center">

# 🧠 Awesome AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of Enterprise AI, LLMs, GenAI, AI Agents, MCP, governance, security, MLOps, and production-ready AI tools.**

RAG, vector databases, orchestration frameworks, and enterprise AI resources.

<!-- Repository badges -->

[![GitHub stars](https://img.shields.io/github/stars/seyhunak/awesome-ai?style=for-the-badge&logo=github&color=FFD700)](https://github.com/seyhunak/awesome-ai/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/seyhunak/awesome-ai?style=for-the-badge&logo=github&color=8A2BE2)](https://github.com/seyhunak/awesome-ai/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/seyhunak/awesome-ai?style=for-the-badge&logo=github&color=00BFFF)](https://github.com/seyhunak/awesome-ai/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/seyhunak/awesome-ai?style=for-the-badge&logo=github&color=FF69B4)](https://github.com/seyhunak/awesome-ai/graphs/contributors)

[![Link Check](https://img.shields.io/github/actions/workflow/status/seyhunak/awesome-ai/link-check.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=links)](https://github.com/seyhunak/awesome-ai/actions/workflows/link-check.yml)
[![License: MIT](https://img.shields.io/github/license/seyhunak/awesome-ai?style=flat-square&color=green)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![Last commit](https://img.shields.io/github/last-commit/seyhunak/awesome-ai?style=flat-square&logo=git&logoColor=white)](https://github.com/seyhunak/awesome-ai/commits/main)
[![Commit activity](https://img.shields.io/github/commit-activity/m/seyhunak/awesome-ai?style=flat-square)](https://github.com/seyhunak/awesome-ai/pulse)
[![Issues](https://img.shields.io/github/issues/seyhunak/awesome-ai?style=flat-square&logo=github)](https://github.com/seyhunak/awesome-ai/issues)
[![Pull requests](https://img.shields.io/github/issues-pr/seyhunak/awesome-ai?style=flat-square&logo=github)](https://github.com/seyhunak/awesome-ai/pulls)
[![Repo size](https://img.shields.io/github/repo-size/seyhunak/awesome-ai?style=flat-square)](https://github.com/seyhunak/awesome-ai)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-v2.1-blueviolet.svg?style=flat-square)](CODE_OF_CONDUCT.md)

<!-- Author badges -->

[![GitHub followers](https://img.shields.io/github/followers/seyhunak?style=social&label=Follow%20%40seyhunak)](https://github.com/seyhunak)
[![Website](https://img.shields.io/badge/Website-seyhunakyurek.com-000000?style=flat-square&logo=safari&logoColor=white)](https://seyhunakyurek.com)
[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg?style=flat-square&logo=markdown)](https://commonmark.org)

</div>

---

## 📖 About

This list is opinionated and **production-first**. Entries are selected for teams that have to ship, operate, secure, and govern AI systems — not for demos. Where a category has an obvious default, it is marked with ⭐.

**Legend:** ⭐ widely adopted default · 🔓 open source · 💰 commercial / paid tier · ☁️ managed service · 🆓 free

---

## 📑 Table of Contents

| | Build | | Measure, Secure & Operate |
|---|---|---|---|
| 🤖 | [Foundation Models (LLMs, VLMs, SLMs)](#-foundation-models-llms-vlms-slms) | 📊 | [Benchmarks](#-benchmarks) |
| 💬 | [Prompt Engineering](#-prompt-engineering) | 📐 | [Metrics](#-metrics) |
| 🧠 | [RAG](#-rag) | 🛡️ | [AI Security & Guardrails](#️-ai-security--guardrails) |
| 🔍 | [Embeddings & Vector Databases](#-embeddings--vector-databases) | 🏢 | [Enterprise AI](#-enterprise-ai) |
| 🤝 | [AI Agents](#-ai-agents) | ☁️ | [Cloud AI (Azure, AWS, GCP)](#️-cloud-ai-azure-aws-gcp) |
| 🔌 | [MCP (Model Context Protocol)](#-mcp-model-context-protocol) | 📦 | [MLOps & LLMOps](#-mlops--llmops) |
| 🎓 | [Agent Skills](#-agent-skills) | 🚀 | [Deployment](#-deployment) |
| 🛠️ | [Agent Frameworks](#️-agent-frameworks) | 📚 | [Courses & Learning](#-courses--learning) |
| 🏗️ | [AI & ML Frameworks](#️-ai--ml-frameworks) | 🎥 | [Videos & Talks](#-videos--talks) |
| ⚡ | [AI SDKs](#-ai-sdks) | 📰 | [Newsletters & Blogs](#-newsletters--blogs) |
| 🧰 | [Developer Tooling](#-developer-tooling) | 🌍 | [Open Source Projects](#-open-source-projects) |
| 🧪 | [Evaluation & Observability](#-evaluation--observability) | 💼 | [Real-world Case Studies](#-real-world-case-studies) |

[Contributing](#-contributing) · [Author](#-author) · [License](#-license)

---

## 🤖 Foundation Models (LLMs, VLMs, SLMs)

### Frontier & Proprietary Models

| Model Family | Provider | Highlights | Access |
|---|---|---|---|
| [Claude](https://www.anthropic.com/claude) ⭐ | Anthropic | Claude 5 family (Fable, Opus, Sonnet) + Haiku — strong reasoning, coding, long context, agentic tool use | [API](https://docs.anthropic.com) · [Console](https://console.anthropic.com) |
| [GPT](https://openai.com/api/) | OpenAI | Broad general-purpose family with reasoning variants | [API](https://platform.openai.com/docs) |
| [Gemini](https://deepmind.google/technologies/gemini/) | Google DeepMind | Natively multimodal, very long context, tight GCP integration | [API](https://ai.google.dev) |
| [Grok](https://x.ai) | xAI | Real-time-leaning general models | [API](https://docs.x.ai) |
| [Command](https://cohere.com/command) | Cohere | Enterprise/RAG-oriented, strong multilingual + citations | [API](https://docs.cohere.com) |
| [Nova](https://aws.amazon.com/ai/generative-ai/nova/) | Amazon | Cost-tiered family, native to Bedrock | [Bedrock](https://aws.amazon.com/bedrock/) |
| [Mistral Large](https://mistral.ai/technology/) | Mistral AI | EU-based provider, open + commercial mix | [API](https://docs.mistral.ai) |

### Open-Weight Models

| Model Family | Org | Notes | License |
|---|---|---|---|
| [Llama](https://www.llama.com) ⭐ | Meta | The de-facto open baseline; huge fine-tune/tooling ecosystem | Llama Community |
| [Qwen](https://github.com/QwenLM/Qwen3) ⭐ | Alibaba | Dense + MoE, very strong multilingual & coding, many sizes | Apache-2.0 (most) |
| [DeepSeek](https://github.com/deepseek-ai) | DeepSeek | MoE + reasoning models with strong price/performance | MIT (most) |
| [Mistral / Mixtral](https://github.com/mistralai/mistral-inference) | Mistral AI | Efficient dense and MoE models | Apache-2.0 |
| [Gemma](https://ai.google.dev/gemma) | Google | Lightweight open siblings of Gemini | Gemma Terms |
| [Phi](https://azure.microsoft.com/products/phi) | Microsoft | Small models trained on curated "textbook" data | MIT |
| [GLM](https://github.com/zai-org/GLM-4) | Z.ai (Zhipu) | Strong bilingual + agentic/coding variants | MIT / Apache-2.0 |
| [Kimi](https://github.com/MoonshotAI) | Moonshot AI | Very large MoE, long-context and agentic focus | Modified MIT |
| [Granite](https://github.com/ibm-granite) | IBM | Enterprise-governed, indemnified, watsonx-native | Apache-2.0 |
| [OLMo](https://allenai.org/olmo) | Ai2 | Fully open: weights, data, code, logs — best for research | Apache-2.0 |
| [Falcon](https://falconllm.tii.ae) | TII | Multilingual open family | Apache-2.0 |
| [SmolLM](https://github.com/huggingface/smollm) | Hugging Face | Genuinely small (135M–1.7B), on-device oriented | Apache-2.0 |

### Vision-Language & Multimodal (VLMs)

| Project | Description |
|---|---|
| [Qwen-VL](https://github.com/QwenLM/Qwen3-VL) | Leading open VLM family — documents, charts, video, GUI grounding |
| [InternVL](https://github.com/OpenGVLab/InternVL) | Open multimodal models competitive with proprietary VLMs |
| [Pixtral](https://mistral.ai/news/pixtral-12b) | Mistral's open multimodal model |
| [Molmo](https://molmo.allenai.org) | Ai2 open VLM with pointing/grounding capability |
| [Whisper](https://github.com/openai/whisper) | Robust open speech-to-text across many languages |
| [CLIP](https://github.com/openai/CLIP) / [OpenCLIP](https://github.com/mlfoundations/open_clip) | Foundational image-text embedding models |

### Model Access, Routing & Local Runtimes

| Tool | Description |
|---|---|
| [Hugging Face Hub](https://huggingface.co/models) ⭐ 🔓 | The model registry of record — weights, datasets, Spaces, leaderboards |
| [OpenRouter](https://openrouter.ai) ☁️ | One API across hundreds of models with routing, fallbacks and price transparency |
| [Ollama](https://github.com/ollama/ollama) ⭐ 🔓 | Dead-simple local model runner with a familiar CLI/API |
| [LM Studio](https://lmstudio.ai) 🆓 | Desktop GUI for running and serving local models |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) 🔓 | The C/C++ inference engine underpinning much of local AI (GGUF) |
| [MLX](https://github.com/ml-explore/mlx) 🔓 | Apple-silicon array framework for fast on-device training/inference |
| [Together AI](https://www.together.ai) · [Fireworks](https://fireworks.ai) · [Groq](https://groq.com) · [Cerebras](https://www.cerebras.ai) ☁️ | High-throughput / low-latency hosted open-model inference |
| [Replicate](https://replicate.com) ☁️ | Run and fine-tune open models via API, pay-per-second |
| [Artificial Analysis](https://artificialanalysis.ai) 🆓 | Independent benchmarks of quality, speed and price across providers |
| [LMArena](https://lmarena.ai) 🆓 | Crowd-sourced pairwise model comparison leaderboard |

**[⬆ back to top](#-table-of-contents)**

---

## 💬 Prompt Engineering

### Guides & References

| Resource | Description |
|---|---|
| [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) ⭐ | The most practical vendor guide — clarity, examples, XML structure, thinking, chaining |
| [Anthropic Prompt Library](https://docs.anthropic.com/en/resources/prompt-library/library) | Ready-made, well-structured prompts across dozens of tasks |
| [OpenAI Prompt Engineering](https://platform.openai.com/docs/guides/prompt-engineering) | Vendor guidance and reasoning-model prompting patterns |
| [Google Prompting Guidance](https://ai.google.dev/gemini-api/docs/prompting-strategies) | Gemini-specific strategies and multimodal prompting |
| [Prompt Engineering Guide](https://www.promptingguide.ai) 🆓 | Comprehensive, paper-backed technique catalogue |
| [Learn Prompting](https://learnprompting.org) 🆓 | Structured course from basics to adversarial prompting |
| [Anthropic Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) | Hands-on notebook course, chapter by chapter |
| [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) ⭐ | Runnable recipes: tool use, RAG, vision, classification, evals |

### Core Techniques

| Technique | What it does | Reference |
|---|---|---|
| Few-shot prompting | Demonstrations steer format and behavior more reliably than instructions alone | [Paper](https://arxiv.org/abs/2005.14165) |
| Chain-of-Thought | Ask for intermediate reasoning before the answer | [Paper](https://arxiv.org/abs/2201.11903) |
| Self-consistency | Sample multiple reasoning paths, take the majority answer | [Paper](https://arxiv.org/abs/2203.11171) |
| ReAct | Interleave reasoning with tool calls — the basis of most agents | [Paper](https://arxiv.org/abs/2210.03629) |
| Reflexion / self-critique | Let the model review and revise its own output | [Paper](https://arxiv.org/abs/2303.11366) |
| Tree of Thoughts | Explore and score branching reasoning paths | [Paper](https://arxiv.org/abs/2305.10601) |
| Prompt caching | Cache long, stable prefixes to cut cost and latency dramatically | [Docs](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching) |
| Structured output | Constrain generation to a schema instead of parsing prose | [Guide](https://python.useinstructor.com) |

### Tooling

| Tool | Description |
|---|---|
| [DSPy](https://github.com/stanfordnlp/dspy) ⭐ 🔓 | Program — don't prompt. Declarative modules with automatic prompt/weight optimization |
| [promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 🔓 | Test, compare and red-team prompts with assertions in CI |
| [Instructor](https://github.com/567-labs/instructor) 🔓 | Pydantic-typed structured outputs with validation and retries |
| [BAML](https://github.com/BoundaryML/baml) 🔓 | A dedicated language for prompts as typed functions, with tests |
| [Outlines](https://github.com/dottxt-ai/outlines) 🔓 | Guaranteed-valid structured generation (JSON, regex, grammars) |
| [Guidance](https://github.com/guidance-ai/guidance) 🔓 | Constrained generation with interleaved control flow |
| [TextGrad](https://github.com/zou-group/textgrad) 🔓 | Backpropagate natural-language "gradients" to optimize prompts |
| [Priompt](https://github.com/anysphere/priompt) 🔓 | Priority-based JSX prompt composition for context budgeting |

**[⬆ back to top](#-table-of-contents)**

---

## 🧠 RAG

> **Rule of thumb:** retrieval quality dominates generation quality. Invest in parsing, chunking and reranking before swapping models.

### Frameworks

| Tool | Description |
|---|---|
| [LlamaIndex](https://github.com/run-llama/llama_index) ⭐ 🔓 | The most complete data framework for RAG — connectors, indexes, query engines, workflows |
| [LangChain](https://github.com/langchain-ai/langchain) ⭐ 🔓 | Ubiquitous building blocks and integrations across the entire stack |
| [Haystack](https://github.com/deepset-ai/haystack) 🔓 | Production-minded, explicitly-wired pipelines from deepset |
| [RAGFlow](https://github.com/infiniflow/ragflow) 🔓 | Deep document understanding RAG engine with a full UI |
| [R2R](https://github.com/SciPhi-AI/R2R) 🔓 | RAG-as-a-service with ingestion, graphs, auth and observability built in |
| [txtai](https://github.com/neuml/txtai) 🔓 | All-in-one embeddings database for semantic search and RAG |
| [Cognita](https://github.com/truefoundry/cognita) 🔓 | Modular, config-driven RAG framework for production teams |
| [Verba](https://github.com/weaviate/Verba) 🔓 | Open-source RAG application built on Weaviate |
| [Dify](https://github.com/langgenius/dify) ⭐ 🔓 | Visual LLM app platform with RAG pipeline, agents and observability |

### Document Parsing & Ingestion

| Tool | Description |
|---|---|
| [Docling](https://github.com/docling-project/docling) ⭐ 🔓 | IBM's high-fidelity document converter — layout, tables, formulas → structured output |
| [Unstructured](https://github.com/Unstructured-IO/unstructured) 🔓 | Preprocess 25+ file types into clean, chunk-ready elements |
| [MinerU](https://github.com/opendatalab/MinerU) 🔓 | High-quality PDF → Markdown/JSON extraction, strong on scientific docs |
| [Marker](https://github.com/datalab-to/marker) 🔓 | Fast, accurate PDF-to-Markdown with equation and table support |
| [LlamaParse](https://www.llamaindex.ai/llamaparse) 💰 ☁️ | Managed parser tuned for complex/tabular documents |
| [Firecrawl](https://github.com/firecrawl/firecrawl) ⭐ 🔓 | Crawl and scrape sites into clean LLM-ready markdown |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) 🔓 | Async, LLM-friendly web crawler and scraper |
| [Jina Reader](https://jina.ai/reader/) 🆓 | Prefix any URL with `r.jina.ai` to get markdown |
| [Chonkie](https://github.com/chonkie-inc/chonkie) 🔓 | Fast, no-nonsense chunking library with many strategies |

### Retrieval & Reranking

| Tool | Description |
|---|---|
| [Cohere Rerank](https://cohere.com/rerank) ⭐ ☁️ | The default cross-encoder reranker — often the single biggest quality win |
| [BGE Reranker](https://github.com/FlagOpen/FlagEmbedding) 🔓 | Strong open reranker family from BAAI |
| [Jina Reranker](https://jina.ai/reranker/) ☁️ | Multilingual and long-context reranking models |
| [RAGatouille](https://github.com/AnswerDotAI/RAGatouille) 🔓 | Late-interaction (ColBERT) retrieval made usable |
| [rerankers](https://github.com/AnswerDotAI/rerankers) 🔓 | One tiny API over every reranking method |
| [rank_bm25](https://github.com/dorianbrown/rank_bm25) 🔓 | Classic lexical retrieval — still essential in hybrid search |

### Advanced RAG Patterns

| Pattern | Why it matters | Reference |
|---|---|---|
| Hybrid search (BM25 + dense) | Lexical recall covers what embeddings miss (IDs, names, rare terms) | [Guide](https://weaviate.io/blog/hybrid-search-explained) |
| Contextual Retrieval | Prepend chunk-specific context before embedding; large recall gains | [Anthropic](https://www.anthropic.com/news/contextual-retrieval) |
| [GraphRAG](https://github.com/microsoft/graphrag) | Build a knowledge graph for global, corpus-wide questions | Microsoft |
| [LightRAG](https://github.com/HKUDS/LightRAG) | Simpler, cheaper graph-augmented retrieval | HKUDS |
| [RAPTOR](https://github.com/parthsarthi03/raptor) | Recursive clustering + summarization into a retrieval tree | Stanford |
| [Self-RAG](https://github.com/AkariAsai/self-rag) | Model decides when to retrieve and critiques what it retrieved | Paper |
| [Corrective RAG](https://arxiv.org/abs/2401.15884) | Grade retrieved docs, fall back to web search when weak | Paper |
| [Neo4j GraphRAG](https://github.com/neo4j/neo4j-graphrag-python) | Official graph + vector retrieval package | Neo4j |

### RAG Evaluation

| Tool | Description |
|---|---|
| [Ragas](https://github.com/explodinggradients/ragas) ⭐ 🔓 | The standard RAG metrics suite — faithfulness, relevancy, context precision/recall |
| [DeepEval](https://github.com/confident-ai/deepeval) 🔓 | Pytest-style LLM evaluation with RAG-specific metrics |
| [TruLens](https://github.com/truera/trulens) 🔓 | Feedback functions and the "RAG triad" for tracking quality |
| [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG) 🔓 | Research toolkit to reproduce and compare RAG methods |

**[⬆ back to top](#-table-of-contents)**

---

## 🔍 Embeddings & Vector Databases

### Embedding Models

| Model | Provider | Notes |
|---|---|---|
| [Voyage AI](https://www.voyageai.com) ⭐ ☁️ | Voyage | Anthropic-recommended; strong general + domain-specific (code, finance, legal) models |
| [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) ☁️ | OpenAI | Solid general-purpose default with adjustable dimensions |
| [Cohere Embed](https://cohere.com/embed) ☁️ | Cohere | Excellent multilingual and compressed (int8/binary) embeddings |
| [BGE](https://github.com/FlagOpen/FlagEmbedding) ⭐ 🔓 | BAAI | The leading open embedding family, many sizes and languages |
| [Jina Embeddings](https://jina.ai/embeddings/) 🔓 ☁️ | Jina AI | Long-context and multimodal open embeddings |
| [Nomic Embed](https://github.com/nomic-ai/contrastors) 🔓 | Nomic | Fully open (weights + data + code) long-context embeddings |
| [E5 / multilingual-e5](https://github.com/microsoft/unilm/tree/master/e5) 🔓 | Microsoft | Strong, well-studied open baselines |
| [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers) ⭐ 🔓 | UKP Lab | The library for using and fine-tuning embedding models |
| [Model2Vec](https://github.com/MinishLab/model2vec) 🔓 | Minish Lab | Distill encoders into static embeddings — orders of magnitude faster |
| [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) 🆓 | HF | Compare embedding models before you commit |

### Vector Databases

| Database | Model | Best for | License |
|---|---|---|---|
| [pgvector](https://github.com/pgvector/pgvector) ⭐ 🔓 | Postgres extension | Teams already on Postgres — start here before adding infrastructure | PostgreSQL |
| [Qdrant](https://github.com/qdrant/qdrant) ⭐ 🔓 ☁️ | Standalone / cloud | Rich filtering, quantization, excellent performance-per-euro | Apache-2.0 |
| [Weaviate](https://github.com/weaviate/weaviate) 🔓 ☁️ | Standalone / cloud | Built-in hybrid search, modules and multi-tenancy | BSD-3 |
| [Milvus](https://github.com/milvus-io/milvus) 🔓 ☁️ | Distributed | Billion-scale workloads and GPU indexing | Apache-2.0 |
| [Chroma](https://github.com/chroma-core/chroma) 🔓 | Embedded / server | Prototyping and local-first apps | Apache-2.0 |
| [LanceDB](https://github.com/lancedb/lancedb) 🔓 ☁️ | Embedded / serverless | Multimodal, object-storage-native, zero-copy versioning | Apache-2.0 |
| [Pinecone](https://www.pinecone.io) 💰 ☁️ | Managed | Fully managed serverless vector search with minimal ops | Proprietary |
| [Turbopuffer](https://turbopuffer.com) 💰 ☁️ | Managed | Object-storage-backed search at very low cost per vector | Proprietary |
| [Vespa](https://github.com/vespa-engine/vespa) 🔓 ☁️ | Distributed | Serious hybrid ranking and real-time recommendation at scale | Apache-2.0 |
| [Elasticsearch](https://www.elastic.co/elasticsearch/vector-database) / [OpenSearch](https://opensearch.org/platform/search/vector-database.html) | Search engine | Adding vectors to an existing search deployment | Elastic v2 / Apache-2.0 |
| [Redis Vector](https://redis.io/docs/latest/develop/interact/search-and-query/advanced-concepts/vectors/) 🔓 ☁️ | In-memory | Lowest-latency lookups, semantic caching | RSALv2/SSPL |
| [MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search) 💰 ☁️ | Document DB | Vectors next to operational documents | Proprietary |
| [Supabase Vector](https://supabase.com/docs/guides/ai) 🔓 ☁️ | Postgres platform | pgvector with auth, storage and edge functions attached | Apache-2.0 |
| [ClickHouse](https://clickhouse.com/use-cases/machine-learning-and-data-science) 🔓 ☁️ | OLAP | Analytics + vector filtering over huge tables | Apache-2.0 |

### ANN Libraries (bring your own store)

| Library | Description |
|---|---|
| [FAISS](https://github.com/facebookresearch/faiss) ⭐ 🔓 | Meta's similarity-search library — the reference implementation for ANN |
| [hnswlib](https://github.com/nmslib/hnswlib) 🔓 | Fast, minimal header-only HNSW |
| [USearch](https://github.com/unum-cloud/usearch) 🔓 | Compact, multi-language engine with many metrics and quantization |
| [ScaNN](https://github.com/google-research/google-research/tree/master/scann) 🔓 | Google's high-recall, high-throughput ANN |
| [Annoy](https://github.com/spotify/annoy) 🔓 | Memory-mapped, read-only indexes from Spotify |
| [DiskANN](https://github.com/microsoft/DiskANN) 🔓 | SSD-resident indexes for datasets far larger than RAM |

**[⬆ back to top](#-table-of-contents)**

---

## 🤝 AI Agents

### Coding Agents

| Agent | Description |
|---|---|
| [Claude Code](https://github.com/anthropics/claude-code) ⭐ 💰 | Anthropic's agentic coding tool — terminal, IDE, desktop and web, with hooks, subagents, skills and MCP |
| [OpenAI Codex](https://github.com/openai/codex) 💰 | OpenAI's coding agent CLI and cloud environment |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) 🔓 | Google's open-source terminal agent |
| [Cursor](https://cursor.com) 💰 | AI-native editor with deep codebase context and background agents |
| [Cline](https://github.com/cline/cline) 🔓 | Autonomous coding agent inside VS Code, bring-your-own-model |
| [Aider](https://github.com/Aider-AI/aider) 🔓 | Pair programming in the terminal, git-commit-native |
| [OpenHands](https://github.com/OpenHands/OpenHands) 🔓 | Full agent platform that codes, browses and runs commands in a sandbox |
| [Goose](https://github.com/block/goose) 🔓 | Block's extensible on-machine agent, MCP-first |
| [Continue](https://github.com/continuedev/continue) 🔓 | Build and run custom autocomplete/chat/agent flows in your IDE |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) 🔓 | The research agent that popularized agent-computer interfaces |
| [Plandex](https://github.com/plandex-ai/plandex) 🔓 | Terminal agent designed for large, multi-file, long-running tasks |
| [Devin](https://devin.ai) 💰 | Cognition's autonomous software engineer |

### Browser & Computer-Use Agents

| Tool | Description |
|---|---|
| [browser-use](https://github.com/browser-use/browser-use) ⭐ 🔓 | Let agents drive a real browser — the most widely used option |
| [Stagehand](https://github.com/browserbase/stagehand) 🔓 | Playwright plus `act`/`extract`/`observe` primitives; deterministic where it matters |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) 🔓 | Accessibility-tree browser control exposed over MCP |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) 🔓 | LLM + vision workflow automation for browser tasks |
| [Computer Use (Claude)](https://docs.anthropic.com/en/docs/agents-and-tools/computer-use) 💰 | Screen-, mouse- and keyboard-level control reference implementation |
| [E2B](https://github.com/e2b-dev/E2B) 🔓 ☁️ | Secure cloud sandboxes for running agent-generated code |
| [Daytona](https://github.com/daytonaio/daytona) 🔓 ☁️ | Fast, isolated runtimes for agent workloads |

### Autonomous & Multi-Agent Systems

| Project | Description |
|---|---|
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) 🔓 | Multi-agent software company simulation with SOP-driven roles |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) 🔓 | The original autonomous agent, now a workflow platform |
| [Open Interpreter](https://github.com/openinterpreter/open-interpreter) 🔓 | Natural-language interface to run code locally |
| [Letta](https://github.com/letta-ai/letta) 🔓 | Stateful agents with long-term memory (formerly MemGPT) |
| [CAMEL](https://github.com/camel-ai/camel) 🔓 | Research framework for multi-agent communication at scale |
| [Suna](https://github.com/kortix-ai/suna) 🔓 | Open-source generalist assistant with browser, files and shell |

### Agent Benchmarks

See [Benchmarks → Agents & Tool Use](#agents--tool-use) for SWE-bench, Terminal-Bench, τ-bench, BFCL, GAIA, OSWorld and WebArena, and [Metrics → Agent Metrics](#agent-metrics) for what to measure on your own traffic.

**[⬆ back to top](#-table-of-contents)**

---

## 🔌 MCP (Model Context Protocol)

> MCP is the open standard for connecting AI applications to tools, data and prompts — "USB-C for AI apps". It is now the default integration layer across Anthropic, OpenAI, Google and Microsoft tooling.

### Specification & Official Resources

| Resource | Description |
|---|---|
| [modelcontextprotocol.io](https://modelcontextprotocol.io) ⭐ | Official documentation, concepts and tutorials |
| [Specification](https://modelcontextprotocol.io/specification) | The normative protocol spec, versioned by date |
| [Reference Servers](https://github.com/modelcontextprotocol/servers) ⭐ | Official server implementations and a large community index |
| [MCP Registry](https://github.com/modelcontextprotocol/registry) | Official community registry of available servers |
| [MCP Inspector](https://github.com/modelcontextprotocol/inspector) ⭐ | Interactive developer tool for testing and debugging servers |
| [Anthropic MCP docs](https://docs.anthropic.com/en/docs/mcp) | Connecting MCP servers to Claude apps and the API |

### SDKs

| Language | SDK |
|---|---|
| Python | [python-sdk](https://github.com/modelcontextprotocol/python-sdk) ⭐ |
| TypeScript | [typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) ⭐ |
| Java | [java-sdk](https://github.com/modelcontextprotocol/java-sdk) |
| Kotlin | [kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk) |
| C# / .NET | [csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk) |
| Go | [go-sdk](https://github.com/modelcontextprotocol/go-sdk) |
| Rust | [rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) |
| Swift | [swift-sdk](https://github.com/modelcontextprotocol/swift-sdk) |
| Ruby | [ruby-sdk](https://github.com/modelcontextprotocol/ruby-sdk) |

### Frameworks & Infrastructure

| Tool | Description |
|---|---|
| [FastMCP](https://github.com/jlowin/fastmcp) ⭐ 🔓 | The fast, Pythonic way to build MCP servers and clients |
| [mcp-use](https://github.com/mcp-use/mcp-use) 🔓 | Connect any LLM to any MCP server in a few lines |
| [mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🔓 | Build agents using MCP with composable workflow patterns |
| [Cloudflare Remote MCP](https://developers.cloudflare.com/agents/model-context-protocol/) ☁️ | Deploy authenticated remote MCP servers on Workers |
| [Docker MCP Toolkit](https://docs.docker.com/ai/mcp-catalog-and-toolkit/) 🔓 | Containerized, signed MCP servers with a managed gateway |
| [MCP Gateway (IBM)](https://github.com/IBM/mcp-context-forge) 🔓 | Federate, secure and observe many MCP servers behind one endpoint |

### Directories & Ecosystem

| Directory | Description |
|---|---|
| [Smithery](https://smithery.ai) | Large registry with one-click install and hosted deployment |
| [Glama MCP](https://glama.ai/mcp/servers) | Indexed directory with security and quality scoring |
| [PulseMCP](https://www.pulsemcp.com) | Servers, clients and a weekly ecosystem newsletter |
| [mcpservers.org](https://mcpservers.org) | Curated, human-reviewed server listing |
| [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) | The community's own curated list |

### Enterprise Considerations

| Topic | Guidance |
|---|---|
| Authorization | Remote servers should implement the [OAuth 2.1 authorization spec](https://modelcontextprotocol.io/specification/draft/basic/authorization) — never ship static shared secrets |
| Transport | Prefer **Streamable HTTP** for remote servers; stdio for local-only tools |
| Tool poisoning | Treat third-party tool descriptions as untrusted input — they enter the model's context |
| Least privilege | Scope each server to one system with the narrowest credentials that work |
| Auditability | Log every tool invocation with arguments, identity and outcome |
| Vetting | Pin versions and review source before installing community servers |

**[⬆ back to top](#-table-of-contents)**

---

## 🎓 Agent Skills

> If MCP gives an agent **tools and data**, Agent Skills give it **procedural knowledge** — how *this* team does code review, ships a release, or formats a report. A skill is a folder with a `SKILL.md` file; agents load the name and description at startup and pull in the full instructions only when a task matches.
>
> This section deliberately favors skills **written and used by the teams that maintain the product they describe**, over bulk-generated skill dumps. A skill encoding a real team's hard-won conventions is worth a hundred generated from a framework's README.

### The Standard

| Resource | Description |
|---|---|
| [agentskills.io](https://agentskills.io) ⭐ | Home of the open standard — overview, quickstart and client showcase |
| [Specification](https://agentskills.io/specification) ⭐ | The normative `SKILL.md` format: frontmatter, structure, progressive disclosure |
| [agentskills/agentskills](https://github.com/agentskills/agentskills) | Where the standard is developed in the open |
| [anthropics/skills](https://github.com/anthropics/skills) ⭐ 🔓 | Anthropic's reference implementation and production-grade example skills |
| [Equipping agents for the real world](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) ⭐ | The design rationale, and how Anthropic uses skills in its own products |
| [Claude Code skills docs](https://code.claude.com/docs/en/skills) | Authoring, installing and scoping skills in practice |
| [Claude platform docs](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) | Skills across the API, Agent SDK and Claude apps |

### Skills Shipped by the Teams That Own the Domain

The strongest signal that a skill is real: the people who maintain the framework, platform or product also maintain its skills, and ship them in the repo.

| Skills | Maintained by | What they encode |
|---|---|---|
| [Laravel Boost](https://laravel.com/docs/12.x/boost#agent-skills) ⭐ 🔓 | Laravel core team | Laravel conventions and best practices, so agents write idiomatic Laravel rather than generic PHP |
| [Anthropic document skills](https://github.com/anthropics/skills/tree/main/skills) ⭐ | Anthropic | The `pdf`, `docx`, `pptx` and `xlsx` skills that power Claude's real document editing |
| [Spring AI](https://spring.io/blog/2026/01/13/spring-ai-generic-agent-skills/) 🔓 | Spring team | Bringing skills to Spring AI agents in the Java ecosystem |
| [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery/tree/main/skills) 🔓 | Google AI Edge | Skills shipped alongside an on-device LLM application |
| [Goose](https://goose-docs.ai/docs/guides/context-engineering/using-skills) 🔓 | Block | Context engineering with skills in an open agent runtime |
| [Pulumi Neo](https://www.pulumi.com/docs/ai/skills/) | Pulumi | Infrastructure workflows constrained by org policy and approvals |
| [Databricks Genie Code](https://docs.databricks.com/aws/en/assistant/skills) | Databricks | Data engineering and analytics procedures inside the lakehouse |
| [Snowflake Cortex Code](https://docs.snowflake.com/en/user-guide/cortex-code/extensibility#extensibility-skills) | Snowflake | Extending an in-platform data agent with team procedures |
| [Qodo](https://www.qodo.ai/blog/how-i-use-qodos-agent-skills-to-auto-fix-issues-in-pull-requests/) | Qodo | A written-up account of using skills to auto-fix PR issues |
| [Letta](https://docs.letta.com/letta-code/skills/) 🔓 | Letta | Skills combined with persistent agent memory |
| [OpenHands](https://docs.openhands.dev/overview/skills) 🔓 | OpenHands | Skills for cloud coding agents at scale |
| [Firebender](https://docs.firebender.com/multi-agent/skills) | Firebender | Android-specific build, emulator and test workflows |

### Methodology Collections

Skills that encode a whole way of working, not a single task.

| Collection | Author | What it encodes |
|---|---|---|
| [Superpowers](https://github.com/obra/superpowers) ⭐ 🔓 | Jesse Vincent | A full development methodology — TDD red/green/refactor, systematic debugging, brainstorming before building, verification before completion, subagent-driven development, worktree management |
| [Netresearch marketplace](https://github.com/netresearch/claude-code-marketplace) 🔓 | Netresearch | An agency's working skills for TYPO3, PHP, Go, Docker, Jira, security and docs |
| [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) ⭐ | Anthropic | The skill for writing skills — start here before authoring your own |
| [mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) | Anthropic | Generating well-formed MCP servers, itself packaged as a skill |

### Directories & Curated Lists

| Directory | Notes |
|---|---|
| [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) ⭐ | Explicitly curates skills used by real engineering teams over bulk-generated ones |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | Large community-maintained collection across many agents |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Broad productivity-oriented catalogue |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | Curated skills, resources and authoring tools |
| [`agent-skills` topic](https://github.com/topics/agent-skills) | The raw firehose — useful for discovery, apply your own judgment |

> **Vetting a skill before you install it:** a skill is instructions your agent will follow and scripts it may execute. Read `SKILL.md` in full, check what `scripts/` actually does, prefer skills maintained by the owners of the domain, and pin a commit rather than tracking a moving branch.

### Client Support

The format is portable; the same `SKILL.md` works across a growing set of agents.

| Client | Skills documentation |
|---|---|
| [Claude Code](https://code.claude.com/docs/en/skills) ⭐ | Terminal, IDE, desktop and web |
| [OpenAI Codex](https://developers.openai.com/codex/skills/) | Codex CLI and cloud |
| [GitHub Copilot](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills) | Across Copilot agents |
| [VS Code](https://code.visualstudio.com/docs/copilot/customization/agent-skills) | Editor-native customization |
| [Cursor](https://cursor.com/docs/context/skills) | Skills as codebase context |
| [Gemini CLI](https://geminicli.com/docs/cli/skills/) 🔓 | Google's open terminal agent |
| [Goose](https://goose-docs.ai/docs/guides/context-engineering/using-skills) 🔓 | Block's extensible agent |
| [OpenCode](https://opencode.ai/docs/skills/) 🔓 | Terminal, IDE and desktop |
| [Amp](https://ampcode.com/manual#agent-skills) | Sourcegraph's coding agent |
| [Roo Code](https://docs.roocode.com/features/skills) 🔓 | Multi-mode agent team in your editor |
| [Factory](https://docs.factory.ai/cli/configuration/skills) | Droids across IDE and CI/CD |
| [Kiro](https://kiro.dev/docs/skills/) | Spec-driven development |
| [Junie](https://junie.jetbrains.com/docs/agent-skills.html) | JetBrains IDE agent |
| [Tabnine](https://docs.tabnine.com/main/getting-started/tabnine-cli/features/agent-skills) | Enterprise-controlled deployments |

### Writing Skills That Actually Get Used

| Practice | Why |
|---|---|
| **The description is the trigger** ⭐ | It is all the agent sees until activation. Write when to use it, not what it is — vague descriptions never fire |
| **Keep `SKILL.md` short** | It loads into context wholesale. Push detail into `references/` and link to it |
| **Use progressive disclosure** ⭐ | Name/description at startup, instructions on activation, referenced files on demand. Design for all three stages |
| **Prefer scripts over prose** | Deterministic steps belong in `scripts/`, not in instructions the model may paraphrase |
| **Encode judgment, not just steps** | The valuable part is *why* your team does it this way and when to deviate |
| **Version-control with the code** | A skill describing your repo's conventions belongs in your repo, reviewed like any other change |
| **Test it like code** | Run real tasks against it. A skill that never activates is worse than none — it creates false confidence |
| **One skill, one job** | Composable skills beat a monolith; the agent loads only what the task needs |

**[⬆ back to top](#-table-of-contents)**

---

## 🛠️ Agent Frameworks

### General-Purpose Orchestration

| Framework | Language | Distinctive strength |
|---|---|---|
| [LangGraph](https://github.com/langchain-ai/langgraph) ⭐ 🔓 | Python, JS | Graph-based, durable, stateful agents with human-in-the-loop and time travel |
| [CrewAI](https://github.com/crewAIInc/crewAI) ⭐ 🔓 | Python | Role-playing crews and deterministic flows; standalone of LangChain |
| [AutoGen](https://github.com/microsoft/autogen) 🔓 | Python, .NET | Event-driven multi-agent conversations from Microsoft Research |
| [AG2](https://github.com/ag2ai/ag2) 🔓 | Python | Community continuation of the original AutoGen line |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) 🔓 | Python, .NET | Convergence of AutoGen + Semantic Kernel for production agents |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) 🔓 | .NET, Python, Java | Enterprise .NET-first orchestration with planners and plugins |
| [PydanticAI](https://github.com/pydantic/pydantic-ai) ⭐ 🔓 | Python | Type-safe agents that feel like FastAPI; excellent validation and testing |
| [Mastra](https://github.com/mastra-ai/mastra) ⭐ 🔓 | TypeScript | Batteries-included TS framework — agents, workflows, RAG, evals, memory |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) 🔓 | Python, JS | Minimal primitives: agents, handoffs, guardrails, sessions, tracing |
| [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) ⭐ 🔓 | Python, TS | Build agents on the same harness that powers Claude Code |
| [Google ADK](https://github.com/google/adk-python) 🔓 | Python, Java | Code-first agent development, Vertex AI Agent Engine deployment |
| [Strands Agents](https://github.com/strands-agents/sdk-python) 🔓 | Python | AWS's model-driven SDK, integrates with Bedrock AgentCore |
| [Agno](https://github.com/agno-agi/agno) 🔓 | Python | High-performance runtime with built-in memory, knowledge and UI |
| [smolagents](https://github.com/huggingface/smolagents) 🔓 | Python | Minimal agents that think in code; ~1k lines of core logic |
| [LlamaIndex Workflows](https://github.com/run-llama/llama_index) 🔓 | Python, TS | Event-driven, async-first orchestration tightly coupled to retrieval |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) 🔓 | Python | Small, composable, strictly-typed agent building blocks |
| [Cloudflare Agents SDK](https://github.com/cloudflare/agents) 🔓 | TypeScript | Durable, stateful agents on Workers with WebSockets and scheduling |

### Visual & Low-Code Builders

| Tool | Description |
|---|---|
| [Dify](https://github.com/langgenius/dify) ⭐ 🔓 | Full LLMOps platform: visual workflows, RAG, agents, observability |
| [n8n](https://github.com/n8n-io/n8n) ⭐ 🔓 | Workflow automation with native AI/agent nodes and 400+ integrations |
| [Flowise](https://github.com/FlowiseAI/Flowise) 🔓 | Drag-and-drop LLM app builder |
| [Langflow](https://github.com/langflow-ai/langflow) 🔓 | Visual builder for agents and RAG flows, deployable as an API |
| [Rivet](https://github.com/Ironclad/rivet) 🔓 | Visual graph IDE for debugging complex prompt chains |

### Durable Execution (the unglamorous half of production agents)

| Tool | Description |
|---|---|
| [Temporal](https://github.com/temporalio/temporal) ⭐ 🔓 ☁️ | Durable workflow engine — the reference answer for long-running, retryable agents |
| [Inngest](https://github.com/inngest/inngest) 🔓 ☁️ | Event-driven durable functions with steps, retries and concurrency control |
| [Restate](https://github.com/restatedev/restate) 🔓 ☁️ | Durable execution with low-latency journaling |
| [Cloudflare Workflows](https://developers.cloudflare.com/workflows/) ☁️ | Durable multi-step execution at the edge |
| [Prefect](https://github.com/PrefectHQ/prefect) 🔓 ☁️ | Pythonic orchestration that adapts well to AI pipelines |

**[⬆ back to top](#-table-of-contents)**

---

## 🏗️ AI & ML Frameworks

> Agent frameworks orchestrate models. These frameworks *are* the layer models are built, trained and optimized in.

### Deep Learning Frameworks

| Framework | Org | Notes |
|---|---|---|
| [PyTorch](https://github.com/pytorch/pytorch) ⭐ 🔓 | PyTorch Foundation | The framework nearly all modern AI research and open models are written in |
| [JAX](https://github.com/jax-ml/jax) 🔓 | Google | Composable function transforms + XLA; dominant for large-scale TPU training |
| [TensorFlow](https://github.com/tensorflow/tensorflow) 🔓 | Google | Mature production ecosystem; still widespread in established deployments |
| [Keras](https://github.com/keras-team/keras) 🔓 | Keras team | High-level API that now runs on JAX, PyTorch or TensorFlow |
| [Flax NNX](https://github.com/google/flax) 🔓 | Google | The neural network library most JAX research builds on |
| [MLX](https://github.com/ml-explore/mlx) 🔓 | Apple | Array framework designed for Apple silicon unified memory |
| [tinygrad](https://github.com/tinygrad/tinygrad) 🔓 | tiny corp | Radically minimal framework — excellent for understanding the stack |
| [Candle](https://github.com/huggingface/candle) 🔓 | Hugging Face | Minimalist Rust ML framework for serverless and embedded inference |
| [Burn](https://github.com/tracel-ai/burn) 🔓 | Tracel AI | Rust deep learning framework with pluggable backends |
| [ONNX](https://github.com/onnx/onnx) 🔓 | LF AI | Open interchange format for moving models between frameworks |

### Model & Training Libraries

| Library | Description |
|---|---|
| [Transformers](https://github.com/huggingface/transformers) ⭐ 🔓 | The model-definition library of record for text, vision, audio and multimodal |
| [Diffusers](https://github.com/huggingface/diffusers) ⭐ 🔓 | State-of-the-art diffusion models for image, audio and video generation |
| [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers) 🔓 | Train and serve embedding and reranking models |
| [Accelerate](https://github.com/huggingface/accelerate) 🔓 | Run the same training script on any distributed configuration |
| [Lightning](https://github.com/Lightning-AI/pytorch-lightning) ⭐ 🔓 | Remove training boilerplate without giving up PyTorch control |
| [Composer](https://github.com/mosaicml/composer) 🔓 | MosaicML's speed-focused training library with algorithmic optimizations |
| [timm](https://github.com/huggingface/pytorch-image-models) 🔓 | The reference collection of vision backbones and training recipes |

### Distributed & Large-Scale Training

| Framework | Description |
|---|---|
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) ⭐ 🔓 | ZeRO sharding, offload and pipeline parallelism for very large models |
| [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) ⭐ 🔓 | NVIDIA's tensor/pipeline/sequence parallelism reference implementation |
| [PyTorch FSDP](https://docs.pytorch.org/docs/stable/fsdp.html) 🔓 | Native fully-sharded data parallel training |
| [torchtitan](https://github.com/pytorch/torchtitan) 🔓 | PyTorch-native reference for pretraining at scale with 4D parallelism |
| [Ray Train](https://github.com/ray-project/ray) 🔓 | Distributed training orchestration across heterogeneous clusters |
| [Colossal-AI](https://github.com/hpcaitech/ColossalAI) 🔓 | Unified parallelism toolkit for large model training |
| [Nanotron](https://github.com/huggingface/nanotron) 🔓 | Minimal, readable 3D-parallel pretraining library |
| [MaxText](https://github.com/AI-Hypercomputer/maxtext) 🔓 | High-performance JAX/TPU LLM training reference |
| [Levanter](https://github.com/stanford-crfm/levanter) 🔓 | Legible, scalable, bitwise-reproducible JAX training |

### Reinforcement Learning & Post-Training

| Library | Description |
|---|---|
| [TRL](https://github.com/huggingface/trl) ⭐ 🔓 | SFT, DPO, GRPO and PPO trainers that integrate with Transformers |
| [verl](https://github.com/volcengine/verl) ⭐ 🔓 | Production-grade RL library for LLM post-training (HybridFlow) |
| [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) 🔓 | Scalable RLHF built on Ray, vLLM and DeepSpeed |
| [TorchRL](https://github.com/pytorch/rl) 🔓 | PyTorch-native RL primitives and environments |
| [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) ⭐ 🔓 | The standard RL environment API (maintained fork of OpenAI Gym) |
| [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) 🔓 | Gymnasium for multi-agent environments |
| [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) 🔓 | Reliable, well-tested implementations of standard RL algorithms |
| [CleanRL](https://github.com/vwxyzjn/cleanrl) 🔓 | Single-file RL implementations built for readability |
| [Ray RLlib](https://docs.ray.io/en/latest/rllib/index.html) 🔓 | Scalable RL for production workloads |

### Classical ML & Structured Data

| Library | Description |
|---|---|
| [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 🔓 | The baseline that still solves most tabular problems — try it before an LLM |
| [XGBoost](https://github.com/dmlc/xgboost) ⭐ 🔓 | Gradient boosting that remains state of the art on tabular data |
| [LightGBM](https://github.com/microsoft/LightGBM) 🔓 | Fast, memory-efficient gradient boosting |
| [CatBoost](https://github.com/catboost/catboost) 🔓 | Gradient boosting with excellent categorical feature handling |
| [statsmodels](https://github.com/statsmodels/statsmodels) 🔓 | Statistical models and hypothesis testing with proper inference |
| [PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric) 🔓 | Graph neural networks on PyTorch |
| [DGL](https://github.com/dmlc/dgl) 🔓 | Deep graph library with multi-backend support |
| [Prophet](https://github.com/facebook/prophet) 🔓 | Interpretable forecasting for business time series |
| [Darts](https://github.com/unit8co/darts) 🔓 | Unified time series forecasting and anomaly detection |

**[⬆ back to top](#-table-of-contents)**

---

## ⚡ AI SDKs

### Provider SDKs

| Provider | SDKs |
|---|---|
| Anthropic | [Python](https://github.com/anthropics/anthropic-sdk-python) ⭐ · [TypeScript](https://github.com/anthropics/anthropic-sdk-typescript) · [Java](https://github.com/anthropics/anthropic-sdk-java) · [Go](https://github.com/anthropics/anthropic-sdk-go) · [Ruby](https://github.com/anthropics/anthropic-sdk-ruby) · [PHP](https://github.com/anthropics/anthropic-sdk-php) · [C#](https://github.com/anthropics/anthropic-sdk-csharp) |
| OpenAI | [Python](https://github.com/openai/openai-python) · [Node](https://github.com/openai/openai-node) · [Go](https://github.com/openai/openai-go) · [Java](https://github.com/openai/openai-java) |
| Google | [google-genai Python](https://github.com/googleapis/python-genai) · [JS](https://github.com/googleapis/js-genai) |
| Mistral | [Python](https://github.com/mistralai/client-python) · [TS](https://github.com/mistralai/client-ts) |
| Cohere | [Python](https://github.com/cohere-ai/cohere-python) · [TS](https://github.com/cohere-ai/cohere-typescript) |

### Cross-Provider & Application SDKs

| SDK | Description |
|---|---|
| [Vercel AI SDK](https://github.com/vercel/ai) ⭐ 🔓 | The TypeScript standard for AI apps — unified provider API, streaming, tools, generative UI |
| [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 🔓 | Call 100+ LLMs with the OpenAI format; proxy adds keys, budgets, routing and logs |
| [aisuite](https://github.com/andrewyng/aisuite) 🔓 | Thin, uniform interface across providers for easy comparison |
| [Instructor](https://github.com/567-labs/instructor) 🔓 | Structured, validated outputs across providers |
| [Mirascope](https://github.com/Mirascope/mirascope) 🔓 | LLM calls as typed Python functions |
| [Portkey Gateway](https://github.com/Portkey-AI/gateway) 🔓 ☁️ | Fast AI gateway with routing, fallbacks, caching and guardrails |
| [Chainlit](https://github.com/Chainlit/chainlit) 🔓 | Build and ship conversational AI UIs in pure Python |
| [Gradio](https://github.com/gradio-app/gradio) ⭐ 🔓 | Turn any model into a shareable web demo in a few lines |
| [Streamlit](https://github.com/streamlit/streamlit) 🔓 | Data and AI apps in Python, no frontend required |
| [assistant-ui](https://github.com/assistant-ui/assistant-ui) 🔓 | Composable React primitives for chat and agent UIs |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit) 🔓 | Drop in-app copilots and agentic UX into React apps |

**[⬆ back to top](#-table-of-contents)**

---

## 🧰 Developer Tooling

### Tokenization & Context Budgeting

| Tool | Description |
|---|---|
| [tiktoken](https://github.com/openai/tiktoken) ⭐ 🔓 | Fast BPE tokenizer — the standard way to count tokens before you send them |
| [Tokenizers](https://github.com/huggingface/tokenizers) 🔓 | Rust-backed tokenization used across the open ecosystem |
| [Token counting API](https://docs.anthropic.com/en/docs/build-with-claude/token-counting) 🆓 | Count tokens exactly as the provider will, including tools and images |
| [tokencost](https://github.com/AgentOps-AI/tokencost) 🔓 | Estimate USD cost of prompts and completions across providers |
| [ttok](https://github.com/simonw/ttok) 🔓 | Count and truncate text to a token budget from the shell |

### Playgrounds & Prompt IDEs

| Tool | Description |
|---|---|
| [Anthropic Console](https://console.anthropic.com) ⭐ | Workbench with prompt generator, improver, test cases and evaluations |
| [Google AI Studio](https://aistudio.google.com) 🆓 | Fast Gemini prototyping with multimodal input and code export |
| [OpenAI Playground](https://platform.openai.com/playground) | Model and parameter experimentation with function calling |
| [Langfuse Prompt Management](https://langfuse.com/docs/prompts) 🔓 | Version, label and deploy prompts without a code release |
| [Latitude](https://github.com/latitude-dev/latitude-llm) 🔓 | Open-source prompt engineering platform with evals and versioning |
| [Agenta](https://github.com/Agenta-AI/agenta) 🔓 | Prompt playground, versioning and evaluation for teams |
| [PromptLayer](https://www.promptlayer.com) 💰 | Prompt registry and observability aimed at non-engineer collaborators |

### Data Labeling & Curation

| Tool | Description |
|---|---|
| [Argilla](https://github.com/argilla-io/argilla) ⭐ 🔓 | Collaboration tool for AI engineers who care about data quality |
| [Label Studio](https://github.com/HumanSignal/label-studio) ⭐ 🔓 | Multi-type labeling for text, image, audio, video and time series |
| [doccano](https://github.com/doccano/doccano) 🔓 | Lightweight open-source text annotation |
| [Cleanlab](https://github.com/cleanlab/cleanlab) 🔓 | Automatically find label errors and data issues in your datasets |
| [Lilac](https://github.com/databricks/lilac) 🔓 | Explore, cluster and clean unstructured datasets before training |
| [Nomic Atlas](https://github.com/nomic-ai/nomic) 🔓 | Interactively visualize and inspect millions of embeddings |

### Synthetic Data Generation

| Tool | Description |
|---|---|
| [distilabel](https://github.com/argilla-io/distilabel) ⭐ 🔓 | Synthetic data and AI feedback pipelines for reliable dataset creation |
| [Curator](https://github.com/bespokelabsai/curator) 🔓 | Bespoke Labs' library for post-training and structured synthetic data |
| [DataDreamer](https://github.com/datadreamer-dev/DataDreamer) 🔓 | Reproducible synthetic data and prompting workflows for research |
| [NeMo Curator](https://github.com/NVIDIA-NeMo/Curator) 🔓 | GPU-accelerated curation, deduplication and filtering at scale |
| [SDV](https://github.com/sdv-dev/SDV) 🔓 | Synthetic tabular and relational data with privacy-preserving evaluation |

### Quantization & Model Optimization

| Tool | Description |
|---|---|
| [bitsandbytes](https://github.com/bitsandbytes-foundation/bitsandbytes) ⭐ 🔓 | 8-bit and 4-bit quantization primitives used throughout fine-tuning |
| [GGUF](https://huggingface.co/docs/hub/gguf) ⭐ | The dominant quantization format for local inference (produced by llama.cpp) |
| [llm-compressor](https://github.com/vllm-project/llm-compressor) 🔓 | Produce quantized, sparse checkpoints ready to serve on vLLM |
| [AutoAWQ](https://github.com/casper-hansen/AutoAWQ) 🔓 | Activation-aware weight quantization for 4-bit inference |
| [GPTQModel](https://github.com/ModelCloud/GPTQModel) 🔓 | Maintained GPTQ quantization toolkit |
| [torchao](https://github.com/pytorch/ao) 🔓 | Native PyTorch quantization and sparsity for training and inference |
| [Optimum](https://github.com/huggingface/optimum) 🔓 | Export and optimize Transformers for ONNX, OpenVINO and accelerators |
| [ExLlamaV2](https://github.com/turboderp-org/exllamav2) 🔓 | Fast quantized inference on consumer GPUs |

### Benchmarking & Load Testing

| Tool | Description |
|---|---|
| [GuideLLM](https://github.com/vllm-project/guidellm) ⭐ 🔓 | Evaluate real-world latency, throughput and capacity of an LLM deployment |
| [vLLM benchmarks](https://github.com/vllm-project/vllm/tree/main/benchmarks) 🔓 | Reference throughput and serving benchmark scripts |
| [LLMPerf](https://github.com/ray-project/llmperf) 🔓 | Load-test and compare LLM API providers on latency and consistency |
| [k6](https://github.com/grafana/k6) 🔓 | General-purpose load testing that adapts well to streaming endpoints |
| [nvitop](https://github.com/XuehaiPan/nvitop) 🔓 | Interactive GPU process monitoring — the `htop` of NVIDIA devices |

### Terminal & Agent Utilities

| Tool | Description |
|---|---|
| [llm](https://github.com/simonw/llm) ⭐ 🔓 | Simon Willison's CLI for prompting, logging and templating across models |
| [files-to-prompt](https://github.com/simonw/files-to-prompt) 🔓 | Concatenate a directory into a single, well-structured prompt |
| [Repomix](https://github.com/yamadashy/repomix) ⭐ 🔓 | Pack an entire repository into one AI-friendly file |
| [gitingest](https://github.com/coderamp-labs/gitingest) 🔓 | Turn any Git repo into a digestible text digest via URL |
| [aichat](https://github.com/sigoden/aichat) 🔓 | All-in-one CLI with shell assistant, RAG and function calling |
| [Context7](https://github.com/upstash/context7) 🔓 | Up-to-date library documentation served to coding agents over MCP |
| [strip-tags](https://github.com/simonw/strip-tags) 🔓 | Strip HTML down to the text an LLM actually needs |

**[⬆ back to top](#-table-of-contents)**

---

## 🧪 Evaluation & Observability

> If you ship without evals, you don't have a product — you have a demo. Instrument first, then iterate.

### Tracing & Observability Platforms

| Platform | Description |
|---|---|
| [Langfuse](https://github.com/langfuse/langfuse) ⭐ 🔓 ☁️ | Open-source LLM engineering platform — tracing, evals, prompt management, self-hostable |
| [LangSmith](https://www.langchain.com/langsmith) 💰 ☁️ | Deep tracing, datasets and evaluation; best-in-class for LangChain/LangGraph |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) 🔓 | Open-source, OpenTelemetry-native tracing and evaluation notebook-first |
| [Braintrust](https://www.braintrust.dev) 💰 ☁️ | Eval-centric workflow with playgrounds and CI integration |
| [W&B Weave](https://github.com/wandb/weave) 🔓 ☁️ | Tracing and evaluation inside the Weights & Biases ecosystem |
| [Opik](https://github.com/comet-ml/opik) 🔓 ☁️ | Comet's open-source tracing, evaluation and guardrails |
| [Helicone](https://github.com/Helicone/helicone) 🔓 ☁️ | One-line proxy for logging, caching, rate limiting and cost tracking |
| [OpenLLMetry](https://github.com/traceloop/openllmetry) 🔓 | OpenTelemetry extensions for LLM apps — vendor-neutral by design |
| [OpenTelemetry GenAI](https://opentelemetry.io/docs/specs/semconv/gen-ai/) 🆓 | The emerging standard semantic conventions for AI telemetry |
| [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/) 💰 ☁️ | LLM traces alongside your existing APM and infrastructure monitoring |

### Evaluation Frameworks

| Tool | Description |
|---|---|
| [promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 🔓 | Declarative evals and red-teaming that run in CI |
| [DeepEval](https://github.com/confident-ai/deepeval) ⭐ 🔓 | Pytest-like unit testing for LLM outputs with 40+ metrics |
| [Ragas](https://github.com/explodinggradients/ragas) 🔓 | Purpose-built RAG and agent metrics |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 🔓 | The UK AI Security Institute's rigorous evaluation framework |
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) 🔓 | The standard harness for academic benchmark reporting |
| [HELM](https://github.com/stanford-crfm/helm) 🔓 | Stanford's holistic, multi-metric model evaluation |
| [OpenAI Evals](https://github.com/openai/evals) 🔓 | Framework and registry of benchmark evals |
| [Giskard](https://github.com/Giskard-AI/giskard) 🔓 | Automated vulnerability and quality scanning for ML and LLM apps |
| [Evidently](https://github.com/evidentlyai/evidently) 🔓 | Data drift, quality and LLM evaluation with rich reports |
| [MLflow LLM Evaluate](https://mlflow.org/docs/latest/llms/llm-evaluate/) 🔓 | Evaluation integrated with experiment tracking and the model registry |

**[⬆ back to top](#-table-of-contents)**

---

## 📊 Benchmarks

> Public benchmarks tell you which models to shortlist. They do **not** tell you whether your system works — only a golden dataset drawn from your own traffic does that. Treat leaderboards as a filter, never as an acceptance test.

### Reasoning & Knowledge

| Benchmark | Measures |
|---|---|
| [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) ⭐ | Harder, less saturated successor to MMLU across 14 domains |
| [GPQA](https://github.com/idavidrein/gpqa) ⭐ | Graduate-level physics, chemistry and biology questions that resist search |
| [Humanity's Last Exam](https://github.com/centerforaisafety/hle) | Expert-written questions at the frontier of human knowledge |
| [ARC-AGI](https://github.com/fchollet/ARC-AGI) ⭐ | Abstract visual reasoning designed to resist memorization |
| [BIG-bench Hard](https://github.com/suzgunmirac/BIG-Bench-Hard) | The subset of BIG-bench where models historically underperformed humans |
| [MuSR](https://github.com/Zayne-Sprague/MuSR) | Multi-step soft reasoning over natural language narratives |
| [DROP](https://allenai.org/data/drop) | Discrete reasoning over paragraphs — arithmetic, counting, sorting |

### Mathematics

| Benchmark | Measures |
|---|---|
| [AIME](https://huggingface.co/datasets/AI-MO/aimo-validation-aime) ⭐ | Competition math; the current default frontier reasoning check |
| [MATH](https://github.com/hendrycks/math) | 12.5k competition problems with step-by-step solutions |
| [GSM8K](https://github.com/openai/grade-school-math) | Grade-school word problems — largely saturated, still a smoke test |
| [FrontierMath](https://epoch.ai/frontiermath) | Unpublished research-level problems designed to stay unsaturated |
| [MathArena](https://matharena.ai) | Evaluation on competitions held *after* model training cutoffs |

### Code & Software Engineering

| Benchmark | Measures |
|---|---|
| [SWE-bench](https://github.com/SWE-bench/SWE-bench) ⭐ | Resolving real GitHub issues in real repositories — the industry reference |
| [SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/) ⭐ | Human-validated 500-problem subset; the number most vendors report |
| [Terminal-Bench](https://github.com/laude-institute/terminal-bench) ⭐ | End-to-end task completion in a real terminal environment |
| [LiveCodeBench](https://github.com/LiveCodeBench/LiveCodeBench) | Contamination-free competitive programming, continuously refreshed |
| [BigCodeBench](https://github.com/bigcode-project/bigcodebench) | Realistic tasks requiring compositional use of many libraries |
| [HumanEval](https://github.com/openai/human-eval) | The classic function-synthesis benchmark — saturated, but ubiquitous |
| [MBPP](https://github.com/google-research/google-research/tree/master/mbpp) | Entry-level Python programming problems |
| [Aider Polyglot](https://aider.chat/docs/leaderboards/) | Editing existing code correctly across six languages |
| [Commit0](https://github.com/commit-0/commit0) | Writing entire libraries from scratch against a test suite |

### Agents & Tool Use

| Benchmark | Measures |
|---|---|
| [τ-bench / τ²-bench](https://github.com/sierra-research/tau-bench) ⭐ | Tool use plus policy adherence in realistic customer dialogues |
| [BFCL](https://github.com/ShishirPatil/gorilla/tree/main/berkeley-function-call-leaderboard) ⭐ | Berkeley Function Calling Leaderboard — the standard tool-calling test |
| [GAIA](https://huggingface.co/spaces/gaia-benchmark/leaderboard) | General assistant tasks needing tools, browsing and multi-step reasoning |
| [OSWorld](https://github.com/xlang-ai/OSWorld) | Open-ended computer-use tasks in a real operating system |
| [WebArena](https://github.com/web-arena-x/webarena) | Autonomous agents on realistic self-hosted websites |
| [AgentBench](https://github.com/THUDM/AgentBench) | Agent capability across eight distinct environments |
| [MLE-bench](https://github.com/openai/mle-bench) | Agents competing on real Kaggle machine learning tasks |

### Long Context & Retrieval

| Benchmark | Measures |
|---|---|
| [RULER](https://github.com/NVIDIA/RULER) ⭐ | What a model's *effective* context length actually is, beyond the spec sheet |
| [LongBench](https://github.com/THUDM/LongBench) | Bilingual, multi-task long-context understanding |
| [Needle in a Haystack](https://github.com/gkamradt/LLMTest_NeedleInAHaystack) | Retrieval of a single fact at varying depth and context length |
| [BEIR](https://github.com/beir-cellar/beir) ⭐ | Zero-shot retrieval generalization across 18 datasets |
| [MTEB](https://github.com/embeddings-benchmark/mteb) ⭐ | Massive text embedding benchmark across tasks and languages |
| [LoCoMo](https://github.com/snap-research/LoCoMo) | Very long-term conversational memory |

### Multimodal

| Benchmark | Measures |
|---|---|
| [MMMU](https://github.com/MMMU-Benchmark/MMMU) ⭐ | College-level multimodal understanding across 30 subjects |
| [MathVista](https://github.com/lupantech/MathVista) | Mathematical reasoning in visual contexts |
| [DocVQA](https://www.docvqa.org) | Question answering over document images — core to enterprise RAG |
| [ChartQA](https://github.com/vis-nlp/ChartQA) | Reasoning over charts and plots |
| [Video-MME](https://github.com/MME-Benchmarks/Video-MME) | Comprehensive video understanding evaluation |
| [ScreenSpot](https://github.com/njucckevin/SeeClick) | GUI element grounding — the basis of computer-use agents |

### Instruction Following, Safety & Truthfulness

| Benchmark | Measures |
|---|---|
| [IFEval](https://github.com/google-research/google-research/tree/master/instruction_following_eval) ⭐ | Verifiable instruction following ("write exactly 3 bullets in JSON") |
| [SimpleQA](https://github.com/openai/simple-evals) ⭐ | Short-form factuality and, crucially, calibrated abstention |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Resistance to reproducing common human misconceptions |
| [HaluEval](https://github.com/RUCAIBox/HaluEval) | Hallucination recognition across QA, dialogue and summarization |
| [HarmBench](https://github.com/centerforaisafety/HarmBench) | Standardized red-teaming and refusal robustness |
| [AgentHarm](https://huggingface.co/datasets/ai-safety-institute/AgentHarm) | Harmfulness of *agentic* behavior, not just generated text |
| [AIR-Bench 2024](https://github.com/stanford-crfm/air-bench-2024) | Safety evaluated against 314 risk categories drawn from real regulations |

### Multilingual

| Benchmark | Measures |
|---|---|
| [Global-MMLU](https://huggingface.co/datasets/CohereLabs/Global-MMLU) | Culturally-aware MMLU across 42 languages |
| [MGSM](https://huggingface.co/datasets/juletxara/mgsm) | Grade-school math reasoning in 10+ languages |
| [FLORES-200](https://github.com/facebookresearch/flores) | Machine translation across 200 languages |
| [XTREME](https://github.com/google-research/xtreme) | Cross-lingual transfer across 40 languages and 9 tasks |
| [Belebele](https://github.com/facebookresearch/belebele) | Reading comprehension parallel across 122 language variants |

### Live Leaderboards

| Leaderboard | Focus |
|---|---|
| [LMArena](https://lmarena.ai) ⭐ | Human preference via blind pairwise voting |
| [Artificial Analysis](https://artificialanalysis.ai) ⭐ | Quality vs. price vs. latency across providers |
| [LiveBench](https://livebench.ai) | Contamination-resistant, monthly-refreshed questions |
| [Open LLM Leaderboard](https://huggingface.co/open-llm-leaderboard) | Standardized open-model benchmarks |
| [SWE-bench Leaderboard](https://www.swebench.com) | Real-world software engineering task resolution |
| [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) | Embedding model quality across tasks and languages |
| [BFCL Leaderboard](https://gorilla.cs.berkeley.edu/leaderboard.html) | Function/tool calling accuracy |
| [Epoch AI Benchmarking Hub](https://epoch.ai/data/ai-benchmarking-dashboard) | Independent tracking of capability trends over time |

### Reading Benchmark Results Honestly

| Pitfall | What to do |
|---|---|
| **Contamination** | Test sets leak into training data. Prefer continuously-refreshed benchmarks (LiveBench, LiveCodeBench, MathArena) |
| **Saturation** | A benchmark above ~90% has stopped discriminating. Move up a tier |
| **Prompt sensitivity** | Scores swing several points on formatting alone. Compare only same-harness numbers |
| **Self-reported numbers** | Vendors pick favorable configurations. Prefer independent runs |
| **Pass@k inflation** | `pass@10` is not `pass@1`. Check which is quoted |
| **Averaging across subsets** | A strong average can hide a domain that matters to you. Read the breakdown |
| **Cost and latency omitted** | A 2-point gain for 10× the cost is usually a bad trade |

**[⬆ back to top](#-table-of-contents)**

---

## 📐 Metrics

> Pick metrics before you build. A metric you added after seeing results is a story, not a measurement.

### Retrieval Metrics

| Metric | Definition | Use when |
|---|---|---|
| **Recall@k** | Fraction of all relevant documents that appear in the top *k* | The ceiling on your RAG quality — measure this first |
| **Precision@k** | Fraction of the top *k* that are relevant | Context window is tight and noise hurts |
| **MRR** | Mean of `1/rank` of the first relevant result | Exactly one right answer exists (lookup, navigation) |
| **nDCG@k** | Gain discounted by log rank, normalized to the ideal ordering | Graded relevance and ranking order both matter |
| **MAP** | Mean of average precision across queries | Multiple relevant documents, order-sensitive |
| **Hit Rate@k** | Share of queries with ≥1 relevant result in top *k* | A blunt but readable executive-facing number |

> **In practice:** optimize retrieval for Recall@k with a generous *k*, then let a reranker fix precision. Improving the generator cannot recover a document retrieval never returned.

### RAG Metrics

| Metric | Question it answers | Typical source |
|---|---|---|
| **Faithfulness / Groundedness** ⭐ | Is every claim supported by retrieved context? | [Ragas](https://github.com/explodinggradients/ragas) |
| **Answer Relevancy** | Does the answer actually address the question asked? | Ragas, DeepEval |
| **Context Precision** | Are the retrieved chunks relevant and well-ranked? | Ragas |
| **Context Recall** | Was all information needed for the ground truth retrieved? | Ragas |
| **Noise Sensitivity** | Does irrelevant retrieved context degrade the answer? | Ragas |
| **Citation Accuracy** | Do the cited sources genuinely support the claims? | Custom / LLM judge |
| **Refusal Correctness** ⭐ | Does it decline when the context truly lacks the answer? | Custom |

### Generation Quality Metrics

| Metric | Type | Notes |
|---|---|---|
| **LLM-as-Judge** ⭐ | Model-graded | The workhorse for open-ended output. Requires its own validation against human labels |
| **Pairwise preference** ⭐ | Model/human | More reliable than absolute scoring — comparison beats calibration |
| **BERTScore** | Embedding | Semantic similarity to a reference; better than n-gram overlap |
| **ROUGE** | Lexical | Summarization overlap. Weak signal, but cheap and stable |
| **BLEU / chrF** | Lexical | Translation. Still standard in MT, poor for open generation |
| **Exact Match / F1** | Lexical | Extractive QA and structured field extraction |
| **Perplexity** | Probabilistic | Model fit during training — not a product quality metric |
| **Schema validity** ⭐ | Deterministic | Percentage of outputs that parse and validate. Cheap and unambiguous |

> **On LLM judges:** validate the judge before you trust it. Measure judge-vs-human agreement (Cohen's κ) on a labeled sample, control position and verbosity bias, and never judge with the same model and prompt that produced the output.

### Classification & Extraction Metrics

| Metric | Formula | Use when |
|---|---|---|
| **Precision** | `TP / (TP + FP)` | False positives are expensive (spam filters, auto-actions) |
| **Recall** | `TP / (TP + FN)` | Misses are expensive (safety, compliance, fraud) |
| **F1** | `2PR / (P + R)` | You need one balanced number |
| **Fβ** | Weighted harmonic mean | Recall matters β× more than precision |
| **PR-AUC** ⭐ | Area under precision-recall | Imbalanced classes — preferred over ROC-AUC here |
| **Cohen's κ** | Agreement above chance | Comparing model to human, or judge to human |
| **ECE** | Expected calibration error | Confidence scores drive downstream routing or escalation |

### Agent Metrics

| Metric | What it captures |
|---|---|
| **Task Success Rate** ⭐ | Did the agent achieve the goal, verified by an outcome check — not self-report |
| **Tool Selection Accuracy** | Right tool chosen for the step |
| **Tool Call Validity** | Arguments parse and satisfy the schema |
| **Steps to Completion** | Efficiency; sudden growth signals looping or confusion |
| **Cost per Task** ⭐ | Total tokens across every turn and subagent — the number finance asks about |
| **Loop / Stall Rate** | Runs hitting the step ceiling without terminating |
| **Recovery Rate** | Runs that hit an error and still finished successfully |
| **Human Intervention Rate** ⭐ | How often a person had to step in — the real autonomy measure |
| **Trajectory Match** | Did it follow an acceptable path, not just reach an acceptable end |

### Serving & Production Metrics

| Metric | Definition | Why it matters |
|---|---|---|
| **TTFT** ⭐ | Time to first token | Dominates *perceived* latency in streaming UIs |
| **TPOT / ITL** | Time per output token (inter-token latency) | Determines whether text renders faster than reading speed |
| **E2E Latency** | Total request time | The number that matters for non-streaming and batch |
| **Throughput** | Output tokens/sec, requests/sec | Capacity planning and cost per unit of work |
| **Goodput** ⭐ | Throughput of requests that *met* their SLO | Prevents "fast but useless" scaling wins |
| **Queue Time** | Wait before scheduling | Early warning of saturation |
| **Cache Hit Rate** ⭐ | Prompt-cache hits / total | Usually the biggest single cost lever |
| **Cost per Request/User** ⭐ | Spend attributed by tenant and feature | Unit economics; measure before scaling |
| **Error / Refusal Rate** | 4xx, 5xx, overloads, refusals | Split these — a refusal is a product signal, not an outage |

> **Report percentiles, not averages.** p50 hides the experience; p95 and p99 are what users complain about. Track TTFT and E2E separately — they fail for different reasons.

### Metric Selection by Use Case

| Use case | Primary metric | Guardrail metrics |
|---|---|---|
| RAG question answering | Faithfulness | Context Recall, refusal correctness, cost/query |
| Search & retrieval | nDCG@10 | Recall@50, p95 latency |
| Summarization | LLM-judge quality | Faithfulness, length adherence |
| Structured extraction | Field-level F1 | Schema validity rate, cost/document |
| Classification | PR-AUC or F1 | Calibration, per-class recall |
| Coding agent | Task success rate | Test pass rate, cost/task, human intervention |
| Customer support agent | Resolution rate | Escalation rate, policy violations, CSAT |
| Content generation | Pairwise preference | Safety violation rate, brand adherence |

**[⬆ back to top](#-table-of-contents)**

---

## 🛡️ AI Security & Guardrails

### Standards & Threat Models

| Resource | Description |
|---|---|
| [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) ⭐ | The canonical risk list — prompt injection, data leakage, supply chain, excessive agency |
| [OWASP Agentic AI Threats & Mitigations](https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/) | Threat taxonomy specific to autonomous agents |
| [MITRE ATLAS](https://atlas.mitre.org) ⭐ | Adversarial tactics and techniques against AI systems, ATT&CK-style |
| [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) ⭐ | Govern / Map / Measure / Manage — the framework most enterprise programs anchor to |
| [NIST Adversarial ML Taxonomy](https://csrc.nist.gov/pubs/ai/100/2/e2025/final) | Standard vocabulary for attacks and mitigations |
| [Google SAIF](https://saif.google) | Secure AI Framework with a practical risk self-assessment |
| [CSA AI Controls Matrix](https://cloudsecurityalliance.org/artifacts/ai-controls-matrix) | Control framework for securing AI in the cloud |

### Guardrails & Runtime Defense

| Tool | Description |
|---|---|
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) ⭐ 🔓 | Input/output validators ("guards") with a shared hub of checks |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) 🔓 | Programmable rails for topic, safety and execution control |
| [LLM Guard](https://github.com/protectai/llm-guard) 🔓 | Comprehensive scanner suite — injection, PII, toxicity, secrets |
| [Llama Guard / Purple Llama](https://github.com/meta-llama/PurpleLlama) 🔓 | Meta's safety classifiers and cybersecurity evals for LLM I/O |
| [Granite Guardian](https://github.com/ibm-granite/granite-guardian) 🔓 | IBM's risk detection models for prompts, responses and RAG groundedness |
| [ShieldGemma](https://ai.google.dev/gemma/docs/shieldgemma) 🔓 | Google's open content-safety classifiers |
| [Presidio](https://github.com/microsoft/presidio) ⭐ 🔓 | PII detection, anonymization and redaction for text and images |
| [Rebuff](https://github.com/protectai/rebuff) 🔓 | Multi-layered prompt-injection detection with canary tokens |
| [Bedrock Guardrails](https://aws.amazon.com/bedrock/guardrails/) ☁️ | Managed policy, PII and contextual-grounding filters |
| [Azure AI Content Safety](https://azure.microsoft.com/products/ai-services/ai-content-safety) ☁️ | Content filtering plus prompt-shield detection |

### Red Teaming & Testing

| Tool | Description |
|---|---|
| [garak](https://github.com/NVIDIA/garak) ⭐ 🔓 | LLM vulnerability scanner — the `nmap` of prompt attacks |
| [PyRIT](https://github.com/Azure/PyRIT) ⭐ 🔓 | Microsoft's Python Risk Identification Toolkit for generative AI |
| [promptfoo red team](https://www.promptfoo.dev/docs/red-team/) 🔓 | Automated adversarial test generation wired into CI |
| [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) 🔓 | Attacks and defenses across the full ML stack |
| [Counterfit](https://github.com/Azure/counterfit) 🔓 | CLI for automating AI security assessments |
| [HarmBench](https://github.com/centerforaisafety/HarmBench) 🔓 | Standardized evaluation of red-teaming and refusal robustness |

### Agent Security Patterns

| Pattern | Practice |
|---|---|
| Untrusted content isolation | Anything retrieved, scraped or returned by a tool is untrusted input — never let it grant new authority |
| Sandboxed execution | Run generated code in [E2B](https://github.com/e2b-dev/E2B), [Daytona](https://github.com/daytonaio/daytona), gVisor or Firecracker — never on the host |
| Human-in-the-loop gates | Require approval for irreversible, outward-facing or high-blast-radius actions |
| Least-privilege credentials | Scoped, short-lived tokens per tool; no ambient production credentials |
| Egress control | Allowlist network destinations to contain exfiltration via tool calls |
| Dual LLM / CaMeL | Separate the planner from the data-handling model so injected text can't change the plan ([paper](https://arxiv.org/abs/2503.18813)) |
| Full audit trail | Log prompts, tool calls, arguments, identities and outcomes for replay |

**[⬆ back to top](#-table-of-contents)**

---

## 🏢 Enterprise AI

### Governance & Compliance

| Framework | Scope |
|---|---|
| [EU AI Act](https://artificialintelligenceact.eu) ⭐ | Risk-tiered legal obligations for AI systems and GPAI models in the EU |
| [ISO/IEC 42001](https://www.iso.org/standard/42001) ⭐ | Certifiable AI management system standard — the "ISO 27001 of AI" |
| [ISO/IEC 23894](https://www.iso.org/standard/77304.html) | AI-specific risk management guidance |
| [NIST AI RMF + GenAI Profile](https://www.nist.gov/itl/ai-risk-management-framework) | Voluntary framework with a generative-AI-specific companion |
| [Model Cards](https://arxiv.org/abs/1810.03993) | Standard documentation for model intent, performance and limitations |
| [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) | Provenance and consent documentation for training data |
| [MLCommons AILuminate](https://mlcommons.org/ailuminate/) | Industry-standard AI safety benchmarking |

### Enterprise Platforms & Assistants

| Platform | Description |
|---|---|
| [Claude for Enterprise](https://www.anthropic.com/enterprise) ⭐ | SSO/SCIM, audit logs, expanded context, data-retention controls; Claude Code seats |
| [Microsoft 365 Copilot](https://www.microsoft.com/microsoft-365/copilot) | AI across Office, Graph-grounded, with Copilot Studio for custom agents |
| [Google Gemini Enterprise](https://cloud.google.com/gemini) | Gemini across Workspace and Cloud with enterprise controls |
| [ChatGPT Enterprise](https://openai.com/enterprise) | Managed ChatGPT with admin, compliance and connector controls |
| [Glean](https://www.glean.com) | Enterprise search and assistants over permission-aware company knowledge |
| [Writer](https://writer.com) | Full-stack enterprise generative AI with owned models and graph-based RAG |
| [Databricks Mosaic AI](https://www.databricks.com/product/artificial-intelligence) | Build, serve and govern models next to your lakehouse data |
| [Snowflake Cortex](https://www.snowflake.com/en/product/features/cortex/) | LLM functions and agents executed inside the data platform |
| [Palantir AIP](https://www.palantir.com/platforms/aip/) | Ontology-grounded AI with tight operational guardrails |
| [Salesforce Agentforce](https://www.salesforce.com/agentforce/) | Agents grounded in CRM data and business rules |
| [ServiceNow AI Agents](https://www.servicenow.com/products/ai-agents.html) | Agentic automation across ITSM and enterprise workflows |

### Adoption Checklist

| Stage | Key questions |
|---|---|
| **Use case selection** | Is there a measurable baseline? What is the cost of being wrong? Is a human already reviewing this output? |
| **Data readiness** | Where does ground truth live? Are permissions enforced at retrieval time, not just in the UI? |
| **Build vs. buy** | Does this differentiate us? Total cost including evals, on-call and model upgrades? |
| **Security review** | Threat-modelled against OWASP LLM Top 10 and MITRE ATLAS? Injection paths enumerated? |
| **Evaluation** | Golden dataset committed to version control? Regression gate in CI before deploy? |
| **Observability** | Traces, cost per request/user, and a feedback signal captured in production? |
| **Governance** | Model inventory, owner, risk tier, documented human oversight, retention policy? |
| **Change management** | Who is accountable when the model changes? Is there a rollback and a pinned version? |

**[⬆ back to top](#-table-of-contents)**

---

## ☁️ Cloud AI (Azure, AWS, GCP)

### Microsoft Azure

| Service | Purpose |
|---|---|
| [Azure AI Foundry](https://azure.microsoft.com/products/ai-foundry) ⭐ | Unified platform to build, evaluate and deploy AI apps and agents |
| [Azure OpenAI Service](https://azure.microsoft.com/products/ai-services/openai-service) | OpenAI models with Azure networking, identity and compliance |
| [Azure AI Search](https://azure.microsoft.com/products/ai-services/ai-search) | Hybrid + vector retrieval with integrated ingestion skills |
| [Azure AI Foundry Agent Service](https://azure.microsoft.com/products/ai-foundry/agent-service) | Managed agent runtime with tools, threads and tracing |
| [Copilot Studio](https://www.microsoft.com/microsoft-copilot/microsoft-copilot-studio) | Low-code custom copilots and agents over Microsoft data |
| [Azure Machine Learning](https://azure.microsoft.com/products/machine-learning) | Classic MLOps: training, registry, endpoints, pipelines |

### Amazon Web Services

| Service | Purpose |
|---|---|
| [Amazon Bedrock](https://aws.amazon.com/bedrock/) ⭐ | Serverless access to many model providers with guardrails and evaluations |
| [Bedrock AgentCore](https://aws.amazon.com/bedrock/agentcore/) | Secure, managed runtime for agents at scale (memory, identity, tools, browser) |
| [Bedrock Knowledge Bases](https://aws.amazon.com/bedrock/knowledge-bases/) | Managed RAG over your data sources |
| [Amazon SageMaker AI](https://aws.amazon.com/sagemaker/ai/) | Train, tune and host models with full MLOps tooling |
| [Amazon Q](https://aws.amazon.com/q/) | Business and developer assistants across AWS and enterprise data |
| [Amazon OpenSearch Serverless](https://aws.amazon.com/opensearch-service/features/serverless/) | Managed vector engine for RAG workloads |

### Google Cloud

| Service | Purpose |
|---|---|
| [Vertex AI](https://cloud.google.com/vertex-ai) ⭐ | End-to-end platform for models, tuning, evaluation and serving |
| [Gemini API](https://ai.google.dev) | Direct developer access to Gemini models |
| [Vertex AI Agent Builder / Engine](https://cloud.google.com/products/agent-builder) | Build, deploy and scale agents with ADK |
| [Vertex AI Search](https://cloud.google.com/enterprise-search) | Google-quality retrieval over enterprise data |
| [Vertex AI Vector Search](https://cloud.google.com/vertex-ai/docs/vector-search/overview) | Billion-scale ANN service built on ScaNN |
| [BigQuery ML](https://cloud.google.com/bigquery/docs/bqml-introduction) | Generate embeddings and call LLMs directly in SQL |

### Cross-Cloud & Alternatives

| Provider | Purpose |
|---|---|
| [Cloudflare AI](https://developers.cloudflare.com/workers-ai/) ⭐ | Workers AI, AI Gateway, Vectorize and Agents SDK at the edge |
| [NVIDIA NIM](https://developer.nvidia.com/nim) | Containerized, optimized inference microservices for any environment |
| [IBM watsonx](https://www.ibm.com/watsonx) | Governed enterprise AI with indemnified Granite models |
| [Oracle OCI Generative AI](https://www.oracle.com/artificial-intelligence/generative-ai/) | Managed GenAI with dedicated clusters |
| [Modal](https://modal.com) · [RunPod](https://www.runpod.io) · [Baseten](https://www.baseten.co) | Serverless GPU compute for custom model workloads |

**[⬆ back to top](#-table-of-contents)**

---

## 📦 MLOps & LLMOps

### Experiment Tracking & Registries

| Tool | Description |
|---|---|
| [MLflow](https://github.com/mlflow/mlflow) ⭐ 🔓 | Tracking, projects, models and registry — with first-class GenAI support |
| [Weights & Biases](https://wandb.ai) 💰 ☁️ | Experiment tracking, sweeps, artifacts and model management |
| [ClearML](https://github.com/clearml/clearml) 🔓 | End-to-end MLOps: experiments, orchestration, data and serving |
| [Neptune](https://neptune.ai) 💰 ☁️ | Tracking built for very long, large-scale training runs |
| [DVC](https://github.com/iterative/dvc) 🔓 | Git-native data and model versioning |
| [LakeFS](https://github.com/treeverse/lakeFS) 🔓 | Git-like branching and commits over object storage |

### Pipelines & Orchestration

| Tool | Description |
|---|---|
| [ZenML](https://github.com/zenml-io/zenml) ⭐ 🔓 | Portable MLOps + LLMOps pipelines that run on any stack |
| [Kubeflow](https://github.com/kubeflow/kubeflow) 🔓 | The Kubernetes-native ML toolkit |
| [Metaflow](https://github.com/Netflix/metaflow) 🔓 | Netflix's human-centric framework for real-life ML/AI projects |
| [Flyte](https://github.com/flyteorg/flyte) 🔓 | Strongly-typed, reproducible, Kubernetes-native workflows |
| [Dagster](https://github.com/dagster-io/dagster) 🔓 | Asset-oriented orchestration with strong data-quality semantics |
| [Airflow](https://github.com/apache/airflow) 🔓 | The ubiquitous scheduler, now with AI/LLM provider packages |
| [Ray](https://github.com/ray-project/ray) ⭐ 🔓 | Distributed compute underpinning much of modern training and serving |
| [SkyPilot](https://github.com/skypilot-org/skypilot) 🔓 | Run jobs on the cheapest available GPUs across clouds |
| [Feast](https://github.com/feast-dev/feast) 🔓 | Open-source feature store for online/offline consistency |

### Fine-Tuning & Post-Training

| Tool | Description |
|---|---|
| [Unsloth](https://github.com/unslothai/unsloth) ⭐ 🔓 | Dramatically faster, lower-memory fine-tuning for popular open models |
| [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) ⭐ 🔓 | Unified fine-tuning for 100+ models with a web UI |
| [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) 🔓 | Config-driven fine-tuning covering the full method matrix |
| [TRL](https://github.com/huggingface/trl) ⭐ 🔓 | SFT, DPO, GRPO and PPO from Hugging Face |
| [PEFT](https://github.com/huggingface/peft) 🔓 | LoRA/QLoRA and other parameter-efficient methods |
| [torchtune](https://github.com/meta-pytorch/torchtune) 🔓 | Native PyTorch library for LLM post-training |
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) 🔓 | ZeRO optimization for training very large models |
| [Liger Kernel](https://github.com/linkedin/Liger-Kernel) 🔓 | Triton kernels that cut training memory substantially |
| [verl](https://github.com/volcengine/verl) 🔓 | Production RL library for LLM post-training |

### Cost & Gateway Management

| Tool | Description |
|---|---|
| [LiteLLM Proxy](https://github.com/BerriAI/litellm) ⭐ 🔓 | Virtual keys, budgets, rate limits, fallbacks and spend tracking |
| [Portkey](https://github.com/Portkey-AI/gateway) 🔓 ☁️ | AI gateway with caching, retries, guardrails and analytics |
| [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/) ☁️ | Caching, rate limiting and observability in front of any provider |
| [Kong AI Gateway](https://konghq.com/products/kong-ai-gateway) 🔓 ☁️ | Enterprise API gateway extended with AI-specific plugins |
| [Envoy AI Gateway](https://github.com/envoyproxy/ai-gateway) 🔓 | CNCF-aligned gateway for LLM/AI traffic |
| [Prompt caching](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching) | Often the single largest cost lever — cache stable prefixes |
| [Batch APIs](https://docs.anthropic.com/en/docs/build-with-claude/batch-processing) | ~50% discounts for asynchronous, non-latency-sensitive work |

**[⬆ back to top](#-table-of-contents)**

---

## 🚀 Deployment

### High-Throughput Inference Servers

| Engine | Description |
|---|---|
| [vLLM](https://github.com/vllm-project/vllm) ⭐ 🔓 | The default open serving engine — PagedAttention, continuous batching, OpenAI-compatible API |
| [SGLang](https://github.com/sgl-project/sglang) ⭐ 🔓 | Fast serving with RadixAttention prefix caching; excellent for agentic/structured workloads |
| [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) 🔓 | NVIDIA's maximum-performance compiled inference |
| [Text Generation Inference](https://github.com/huggingface/text-generation-inference) 🔓 | Hugging Face's production serving stack |
| [LMDeploy](https://github.com/InternLM/lmdeploy) 🔓 | Efficient compression, deployment and serving toolkit |
| [Triton Inference Server](https://github.com/triton-inference-server/server) 🔓 | Multi-framework, multi-model serving with dynamic batching |
| [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) 🔓 | Compose multi-model, multi-stage inference graphs |
| [BentoML](https://github.com/bentoml/BentoML) 🔓 | Package and ship any model as a production service |
| [KServe](https://github.com/kserve/kserve) 🔓 | Kubernetes-native, standards-based model serving |

### Edge, Local & On-Device

| Tool | Description |
|---|---|
| [llama.cpp](https://github.com/ggml-org/llama.cpp) ⭐ 🔓 | CPU/GPU inference anywhere, from laptops to Raspberry Pi |
| [Ollama](https://github.com/ollama/ollama) ⭐ 🔓 | The friendliest way to run and serve local models |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) 🔓 | Cross-platform accelerated inference including browsers |
| [ExecuTorch](https://github.com/pytorch/executorch) 🔓 | PyTorch on mobile and embedded devices |
| [MLC LLM](https://github.com/mlc-ai/mlc-llm) 🔓 | Compile and deploy LLMs to almost any hardware backend |
| [OpenVINO](https://github.com/openvinotoolkit/openvino) 🔓 | Intel-optimized inference for CPU/iGPU/NPU |
| [LocalAI](https://github.com/mudler/LocalAI) 🔓 | Drop-in OpenAI-compatible API you can self-host |
| [Xinference](https://github.com/xorbitsai/inference) 🔓 | Serve LLMs, embeddings and rerankers with one command |

### Serverless & Managed Inference

| Provider | Description |
|---|---|
| [Modal](https://modal.com) ⭐ ☁️ | Python-native serverless GPUs with fast cold starts |
| [Baseten](https://www.baseten.co) ☁️ | Dedicated deployments with autoscaling and observability |
| [Together AI](https://www.together.ai) · [Fireworks AI](https://fireworks.ai) ☁️ | Fast hosted open models plus fine-tuning |
| [Groq](https://groq.com) · [Cerebras](https://www.cerebras.ai) · [SambaNova](https://sambanova.ai) ☁️ | Custom silicon for very low-latency inference |
| [Replicate](https://replicate.com) ☁️ | Pay-per-second hosting for open and custom models |
| [HF Inference Endpoints](https://huggingface.co/inference-endpoints) ☁️ | One-click dedicated endpoints from the Hub |

### Production Checklist

- [ ] **Version pinning** — pin model IDs; never let a silent upgrade change behavior
- [ ] **Streaming** — stream tokens; long non-streaming calls will hit gateway timeouts
- [ ] **Timeouts & retries** — exponential backoff with jitter, and a hard request budget
- [ ] **Fallback chain** — a secondary provider or smaller model for outages and overload
- [ ] **Prompt caching** — cache stable system prompts and long shared context
- [ ] **Cost attribution** — tag every request with tenant, feature and user
- [ ] **Rate limiting** — per-user and per-tenant quotas before the provider enforces its own
- [ ] **Structured logging** — request/response, latency, tokens, cache hits, tool calls
- [ ] **Eval gate in CI** — block deploys that regress your golden dataset
- [ ] **Canary rollout** — shift traffic gradually on any model or prompt change
- [ ] **Kill switch** — disable a feature or agent without a redeploy
- [ ] **Feedback capture** — thumbs, corrections and downstream outcomes into your eval set

**[⬆ back to top](#-table-of-contents)**

---

## 📚 Courses & Learning

| Course | Provider | Level |
|---|---|---|
| [Anthropic Academy](https://www.anthropic.com/learn) ⭐ 🆓 | Anthropic | Beginner → Advanced |
| [Claude Code in Action](https://anthropic.skilljar.com) 🆓 | Anthropic | Intermediate |
| [Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) ⭐ 🆓 | Anthropic | Beginner |
| [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) ⭐ 🆓 | DeepLearning.AI | All levels |
| [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) ⭐ 🆓 | Andrej Karpathy | Intermediate |
| [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) 🆓 | Hugging Face | Beginner → Intermediate |
| [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) ⭐ 🆓 | Hugging Face | Intermediate |
| [Hugging Face MCP Course](https://huggingface.co/learn/mcp-course) 🆓 | Hugging Face | Intermediate |
| [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) ⭐ 🆓 | Microsoft | Beginner |
| [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) 🆓 | Microsoft | Beginner |
| [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) 🆓 | Microsoft | Beginner |
| [Stanford CS336: Language Modeling from Scratch](https://stanford-cs336.github.io) 🆓 | Stanford | Advanced |
| [Stanford CS224N: NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) 🆓 | Stanford | Advanced |
| [LangChain Academy](https://academy.langchain.com) 🆓 | LangChain | Intermediate |
| [Google Cloud Generative AI Path](https://www.cloudskillsboost.google/paths/118) 🆓 | Google | Beginner → Intermediate |
| [Practical Deep Learning for Coders](https://course.fast.ai) 🆓 | fast.ai | Beginner → Advanced |
| [smol-course](https://github.com/huggingface/smol-course) 🆓 | Hugging Face | Intermediate |

### Books

| Book | Author | Focus |
|---|---|---|
| [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) ⭐ | Chip Huyen | Building applications on foundation models |
| [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) ⭐ | Chip Huyen | Production ML system design |
| [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch) | Sebastian Raschka | Implementing an LLM end to end |
| [Hands-On Large Language Models](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/) | Alammar & Grootendorst | Visual, practical LLM engineering |
| [Prompt Engineering for LLMs](https://www.oreilly.com/library/view/prompt-engineering-for/9781098156145/) | Berryman & Ziegler | Prompt design as an engineering discipline |
| [Designing Data-Intensive Applications](https://dataintensive.net) | Martin Kleppmann | The systems foundation AI infrastructure rests on |

**[⬆ back to top](#-table-of-contents)**

---

## 🎥 Videos & Talks

| Talk | Speaker | Why watch |
|---|---|---|
| [Deep Dive into LLMs like ChatGPT](https://www.youtube.com/watch?v=7xTGNNLPyMI) ⭐ | Andrej Karpathy | The best single explanation of how modern LLMs actually work |
| [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) ⭐ | Andrej Karpathy | The one-hour mental model everyone should share with their team |
| [Let's build GPT: from scratch, in code](https://www.youtube.com/watch?v=kCc8FmEb1nY) ⭐ | Andrej Karpathy | Build a transformer line by line |
| [Software Is Changing (Again)](https://www.youtube.com/watch?v=LCEmiRjPEtQ) | Andrej Karpathy | "Software 3.0" and what it means for engineering teams |
| [But what is a GPT? / Attention explained](https://www.youtube.com/watch?v=wjZofJX0v4M) ⭐ | 3Blue1Brown | The clearest visual intuition for transformers and attention |
| [Anthropic YouTube](https://www.youtube.com/@anthropic-ai) | Anthropic | Model launches, research explainers and Claude Code deep dives |
| [AI Engineer Conference](https://www.youtube.com/@aiDotEngineer) ⭐ | AI Engineer | The largest archive of practitioner talks on shipping AI |
| [Latent Space](https://www.latent.space) | swyx & Alessio | Long-form interviews with the people building the stack |
| [Stanford MLSys Seminar](https://www.youtube.com/playlist?list=PLSrTvUm384I9PV10koj_cqit9OfbJXEkq) | Stanford | Systems-level view of ML infrastructure |
| [Hugging Face YouTube](https://www.youtube.com/@HuggingFace) | Hugging Face | Open-model tooling walkthroughs |

**[⬆ back to top](#-table-of-contents)**

---

## 📰 Newsletters & Blogs

### Engineering & Research Blogs

| Blog | Author / Org | Focus |
|---|---|---|
| [Anthropic Engineering](https://www.anthropic.com/engineering) ⭐ | Anthropic | Agent design, context engineering, Claude Code internals |
| [Anthropic Research](https://www.anthropic.com/research) ⭐ | Anthropic | Interpretability, alignment and safety research |
| [Simon Willison's Weblog](https://simonwillison.net) ⭐ | Simon Willison | The most reliable running commentary on what actually changed |
| [Lil'Log](https://lilianweng.github.io) ⭐ | Lilian Weng | Definitive deep dives on agents, hallucination and RL |
| [Interconnects](https://www.interconnects.ai) | Nathan Lambert | Post-training, RLHF and open-model policy |
| [Ahead of AI](https://magazine.sebastianraschka.com) | Sebastian Raschka | Careful technical explainers and paper reviews |
| [Chip Huyen](https://huyenchip.com/blog/) | Chip Huyen | AI engineering and production system design |
| [Eugene Yan](https://eugeneyan.com) ⭐ | Eugene Yan | Patterns for building LLM systems that work |
| [Hamel Husain](https://hamel.dev) ⭐ | Hamel Husain | Evals, fine-tuning and hard-won practitioner lessons |
| [Google DeepMind Blog](https://deepmind.google/discover/blog/) | DeepMind | Research and model announcements |
| [Hugging Face Blog](https://huggingface.co/blog) | Hugging Face | Open-model releases and practical tutorials |
| [Answer.AI](https://www.answer.ai) | Jeremy Howard et al. | Practical R&D from the fast.ai lineage |
| [Netflix Tech Blog](https://netflixtechblog.com) · [Uber Engineering](https://www.uber.com/blog/engineering/) · [Airbnb Engineering](https://medium.com/airbnb-engineering) | Various | Real production ML/AI architecture writeups |

### Newsletters

| Newsletter | Cadence | Focus |
|---|---|---|
| [The Batch](https://www.deeplearning.ai/the-batch/) ⭐ | Weekly | Andrew Ng's balanced industry roundup |
| [Import AI](https://importai.substack.com) ⭐ | Weekly | Jack Clark on research, policy and capability trends |
| [TLDR AI](https://tldr.tech/ai) | Daily | Five-minute daily digest |
| [Ben's Bites](https://bensbites.com) | Daily | Product- and startup-oriented AI news |
| [Last Week in AI](https://lastweekin.ai) | Weekly | Summaries plus a podcast |
| [AI Snake Oil](https://www.aisnakeoil.com) | Occasional | Princeton researchers on separating hype from evidence |
| [Latent Space](https://www.latent.space) | Weekly | AI engineering practice and interviews |
| [PulseMCP](https://www.pulsemcp.com/newsletter) | Weekly | MCP ecosystem news and new servers |
| [Data Machina](https://datamachina.substack.com) | Weekly | Dense technical link roundup |

**[⬆ back to top](#-table-of-contents)**

---

## 🌍 Open Source Projects

> Core libraries — PyTorch, JAX, Transformers, scikit-learn and friends — live in [AI & ML Frameworks](#️-ai--ml-frameworks). This section covers the applications and utilities built on top of them.

### Chat UIs & Self-Hosted Apps

| Project | Description |
|---|---|
| [Open WebUI](https://github.com/open-webui/open-webui) ⭐ | Feature-rich, offline-capable self-hosted AI interface |
| [LibreChat](https://github.com/danny-avila/LibreChat) ⭐ | Multi-provider ChatGPT-style app with agents, RAG and auth |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one desktop/docker app for documents and agents |
| [Jan](https://github.com/menloresearch/jan) | Offline-first, open-source ChatGPT alternative |
| [Lobe Chat](https://github.com/lobehub/lobe-chat) | Modern multi-modal chat framework with a plugin ecosystem |
| [Khoj](https://github.com/khoj-ai/khoj) | Self-hostable AI second brain over your own documents |
| [Perplexica](https://github.com/ItzCrazyKns/Perplexica) | Open-source AI answer engine |
| [SearXNG](https://github.com/searxng/searxng) | Privacy-respecting metasearch — the retrieval backbone for many OSS agents |

### Speech, Vision & Creative

| Project | Description |
|---|---|
| [Whisper](https://github.com/openai/whisper) ⭐ | Robust multilingual speech recognition |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | CTranslate2 reimplementation, several times faster |
| [WhisperX](https://github.com/m-bain/whisperX) | Word-level timestamps and speaker diarization |
| [Kokoro](https://github.com/hexgrad/kokoro) | Small, high-quality open TTS |
| [F5-TTS](https://github.com/SWivid/F5-TTS) | Fast, natural zero-shot voice cloning |
| [Piper](https://github.com/OHF-Voice/piper1-gpl) | Fast local neural TTS for edge devices |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) ⭐ | Node-based generative pipeline engine with a huge ecosystem |
| [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) | Real-time detection, segmentation and tracking |
| [Segment Anything](https://github.com/facebookresearch/segment-anything) | Promptable segmentation foundation model |

### Data & Utilities

| Project | Description |
|---|---|
| [Polars](https://github.com/pola-rs/polars) ⭐ | Blazing-fast DataFrames for AI data preparation |
| [DuckDB](https://github.com/duckdb/duckdb) ⭐ | In-process analytical SQL — ideal for eval and dataset work |
| [Pydantic](https://github.com/pydantic/pydantic) ⭐ | Validation layer underpinning most Python AI tooling |
| [Datasets](https://github.com/huggingface/datasets) | Load, stream and process datasets of any size efficiently |
| [datatrove](https://github.com/huggingface/datatrove) | Large-scale text data processing pipelines for pretraining corpora |
| [Apache Arrow](https://github.com/apache/arrow) | The columnar memory format most AI data tooling interchanges through |

**[⬆ back to top](#-table-of-contents)**

---

## 💼 Real-world Case Studies

### Curated Collections

| Collection | Description |
|---|---|
| [ZenML LLMOps Database](https://www.zenml.io/llmops-database) ⭐ | 500+ documented production GenAI deployments, summarized and searchable |
| [Anthropic Customer Stories](https://www.anthropic.com/customers) | How enterprises deploy Claude, with reported outcomes |
| [Google Cloud: Real-world gen AI use cases](https://cloud.google.com/transform/101-real-world-generative-ai-use-cases-from-industry-leaders) | Hundreds of named customer implementations |
| [Microsoft AI Transformation Stories](https://www.microsoft.com/en-us/ai/ai-customer-stories) | Cross-industry deployment writeups |
| [AWS Generative AI Customer Stories](https://aws.amazon.com/ai/generative-ai/customers/) | Bedrock and SageMaker production references |
| [Evidently AI LLM Case Studies](https://www.evidentlyai.com/blog/llm-applications) | Practitioner-focused breakdowns of shipped LLM apps |

### Notable Engineering Writeups

| Company | Use case | Takeaway |
|---|---|---|
| [LinkedIn](https://www.linkedin.com/blog/engineering/generative-ai/musings-on-building-a-generative-ai-product) ⭐ | Generative AI product | Honest account of the last 20% — evals, latency and quality plateaus |
| [Uber](https://www.uber.com/blog/query-gpt/) | QueryGPT: natural language → SQL | Multi-agent decomposition beat a single large prompt |
| [Uber](https://www.uber.com/blog/from-predictive-to-generative-ai/) | Platform evolution | Migrating an established ML platform to serve GenAI |
| [Airbnb](https://medium.com/airbnb-engineering/automation-platform-v2-improving-conversational-ai-at-airbnb-d86b9a2bb2a6) | Conversational AI platform | Constrain agents with workflows rather than trusting free-form autonomy |
| [Airbnb](https://medium.com/airbnb-engineering/accelerating-large-scale-test-migration-with-llms-9565c208023b) | Migrating 3.5k test files with LLMs | Retry loops with expanded context beat prompt perfection |
| [DoorDash](https://careersatdoordash.com/blog/large-language-modules-based-dasher-support-automation/) | Support automation | RAG plus an LLM Judge to control hallucination in customer-facing replies |
| [Discord](https://discord.com/blog/developing-rapidly-with-generative-ai) | Shipping GenAI features | A pragmatic prototype → eval → productionize loop |
| [GitHub](https://github.blog/news-insights/product-news/github-copilot-workspace/) | Copilot Workspace | Designing agentic developer UX around review and correction |
| [Grab](https://engineering.grab.com/llm-powered-data-classification) | Data classification at scale | LLMs for governance and metadata, not just chat |
| [Klarna](https://www.klarna.com/international/press/klarna-ai-assistant-handles-two-thirds-of-customer-service-chats-in-its-first-month/) | Customer service assistant | Widely-cited deployment numbers — and a useful lesson in later rebalancing toward humans |
| [Bloomberg](https://arxiv.org/abs/2303.17564) | BloombergGPT | Domain-specific pretraining, and why most teams should not repeat it |
| [Replit](https://blog.replit.com/automated-self-testing) | Agent self-testing at scale | REPL-based verification instead of expensive computer-use checking |
| [Anthropic](https://www.anthropic.com/engineering/built-multi-agent-research-system) ⭐ | Multi-agent research system | Orchestrator–worker patterns, and where multi-agent genuinely pays off |
| [Anthropic](https://www.anthropic.com/engineering/building-effective-agents) ⭐ | Building effective agents | Start simple: most "agent" problems are solved by workflows |

**[⬆ back to top](#-table-of-contents)**

---

## 🤝 Contributing

Contributions are very welcome — this list is only as good as the people maintaining it.

**Before opening a PR, please check that your entry:**

1. ✅ Is **production-relevant** — something a team would actually deploy, not a weekend demo
2. ✅ Is **actively maintained** — recent commits, releases or documentation updates
3. ✅ Is **not already listed** under another section
4. ✅ Uses the **canonical link** — the project's repository or official documentation
5. ✅ Follows the existing **table format** and has a one-line, non-marketing description
6. ✅ Is placed in the **most specific** applicable section

**How to contribute:**

```bash
# 1. Fork and clone
git clone https://github.com/<your-username>/awesome-ai.git
cd awesome-ai

# 2. Create a branch
git checkout -b add-awesome-tool

# 3. Edit README.md, then commit
git commit -am "Add <Tool> to <Section>"

# 4. Push and open a pull request
git push origin add-awesome-tool
```

Found a dead link, a project that has been archived, or a description that is no longer accurate? [Open an issue](https://github.com/seyhunak/awesome-ai/issues/new) — corrections are as valuable as additions.

**[⬆ back to top](#-table-of-contents)**

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=seyhunak/awesome-ai&type=Date)](https://star-history.com/#seyhunak/awesome-ai&Date)

If this list is useful to you, please consider **starring** it — it helps other engineers find it.

---

## 👤 Author

<div align="center">

### **Seyhun Akyürek**

[![Website](https://img.shields.io/badge/Website-seyhunakyurek.com-000000?style=for-the-badge&logo=safari&logoColor=white)](https://seyhunakyurek.com)
[![GitHub](https://img.shields.io/badge/GitHub-@seyhunak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seyhunak)
[![X](https://img.shields.io/badge/X-@seyhunak-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/seyhunak)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-seyhunak-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seyhunak)

[![GitHub followers](https://img.shields.io/github/followers/seyhunak?style=social&label=Follow)](https://github.com/seyhunak)
[![GitHub stars](https://img.shields.io/github/stars/seyhunak/awesome-ai?style=social&label=Star)](https://github.com/seyhunak/awesome-ai)

</div>

---

## 📄 License

<div align="center">

[![CC0](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

Released under the [MIT License](LICENSE).

Copyright © 2026 [Seyhun Akyürek](https://seyhunakyurek.com)

<sub>All trademarks, product names and logos belong to their respective owners.<br>
Listing here does not imply endorsement by, or affiliation with, any listed project or vendor.</sub>

<br><br>

**[⬆ back to top](#-table-of-contents)**

<sub>Made with ❤️ for the AI engineering community</sub>

</div>
