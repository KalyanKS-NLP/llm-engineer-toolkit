# 👨🏻‍💻 LLM Engineer Toolkit 
This repository contains a curated list of 120+ LLM libraries category wise.
<p align="center">
  <a href="https://www.linkedin.com/in/kalyanksnlp/">
    <img src="https://custom-icon-badges.demolab.com/badge/Kalyan%20KS-0A66C2?logo=linkedin-white&logoColor=fff" alt="LinkedIn">
  </a>
  <a href="https://x.com/kalyan_kpl">
    <img src="https://img.shields.io/badge/Kalyan%20KS-%23000000.svg?logo=X&logoColor=white" alt="Twitter">
  </a>
   <a href="https://www.youtube.com/@kalyanksnlp">
    <img src="https://img.shields.io/badge/Kalyan%20KS-%23FF0000.svg?logo=YouTube&logoColor=white" alt="Twitter">
  </a>
	
</p>

## Quick links
||||
|---|---|---|
| [🚀 LLM Training](#llm-training-and-fine-tuning) | [🧱 LLM Application Development](#llm-application-development) | [🩸LLM RAG](#llm-rag) | 
| [🟩 LLM Inference](#llm-inference)| [🚧 LLM Serving](#llm-serving) | [📤 LLM Data Extraction](#llm-data-extraction) |
| [🌠 LLM Data Generation](#llm-data-generation) | [💎 LLM Agents](#llm-agents)|[⚖️ LLM Evaluation](#llm-evaluation) | 
| [🔍 LLM Monitoring](#llm-monitoring) | [📅 LLM Prompts](#llm-prompts) | [📝 LLM Structured Outputs](#llm-structured-outputs) |
| [🛑 LLM Safety and Security](#llm-safety-and-security) | [💠 LLM Embedding Models](#llm-embedding-models) | [❇️ Others](#others) |


## LLM Training and Fine-Tuning
| Library             | Description                                                                                     | Link |
|---------------------|-------------------------------------------------------------------------------------------------|------|
| unsloth            | Fine-tune LLMs faster with less memory.                                                          | [Link](https://github.com/unslothai/unsloth) |
| PEFT                | State-of-the-art Parameter-Efficient Fine-Tuning library.                                       | [Link](https://github.com/huggingface/peft) |
| TRL                 | Train transformer language models with reinforcement learning.                                  | [Link](https://github.com/huggingface/trl) |
| Transformers       | Transformers provides thousands of pretrained models to perform tasks on different modalities such as text, vision, and audio. | [Link](https://github.com/huggingface/transformers) |
| Axolotl           | Tool designed to streamline post-training for various AI models.                                 | [Link](https://github.com/axolotl-ai-cloud/axolotl/) |
| LLMBox             | A comprehensive library for implementing LLMs, including a unified training pipeline and comprehensive model evaluation. | [Link](https://github.com/RUCAIBox/LLMBox) |
| LitGPT             | Train and fine-tune LLM lightning fast.                                                          | [Link](https://github.com/Lightning-AI/litgpt) |
| Mergoo            | A library for easily merging multiple LLM experts, and efficiently train the merged LLM.         | [Link](https://github.com/Leeroo-AI/mergoo) |
| Llama-Factory      | Easy and efficient LLM fine-tuning.                                                              | [Link](https://github.com/hiyouga/LLaMA-Factory) |
| Ludwig            | Low-code framework for building custom LLMs, neural networks, and other AI models.               | [Link](https://github.com/ludwig-ai/ludwig) |
| Txtinstruct       | A framework for training instruction-tuned models.                                               | [Link](https://github.com/neuml/txtinstruct) |
| Lamini            | An integrated LLM inference and tuning platform.                                                 | [Link](https://github.com/lamini-ai/lamini) |
| XTuring           | xTuring provides fast, efficient and simple fine-tuning of open-source LLMs, such as Mistral, LLaMA, GPT-J, and more. | [Link](https://github.com/stochasticai/xTuring) |
| RL4LMs            | A modular RL library to fine-tune language models to human preferences.                          | [Link](https://github.com/allenai/RL4LMs) |
| DeepSpeed         | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. | [Link](https://github.com/deepspeedai/DeepSpeed) |
| torchtune         | A PyTorch-native library specifically designed for fine-tuning LLMs.                             | [Link](https://github.com/pytorch/torchtune) |
| PyTorch Lightning | A library that offers a high-level interface for pretraining and fine-tuning LLMs.               | [Link](https://github.com/Lightning-AI/pytorch-lightning) |


## LLM Application Development
<p align = "center"> <b> Frameworks </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| LangChain    | LangChain is a framework for developing applications powered by large language models (LLMs).          | [Link](https://github.com/langchain-ai/langchain) |
| Llama Index  | LlamaIndex is a data framework for your LLM applications.                                              | [Link](https://github.com/run-llama/llama_index) |
| HayStack     | Haystack is an end-to-end LLM framework that allows you to build applications powered by LLMs, Transformer models, vector search and more. | [Link](https://github.com/deepset-ai/haystack) |
| Prompt flow  | A suite of development tools designed to streamline the end-to-end development cycle of LLM-based AI applications. | [Link](https://github.com/microsoft/promptflow) |
| Griptape     | A modular Python framework for building AI-powered applications.                                        | [Link](https://github.com/griptape-ai/griptape) |
| Weave        | Weave is a toolkit for developing Generative AI applications.                                          | [Link](https://github.com/wandb/weave) |
| Llama Stack  | Build Llama Apps.                                                                                      | [Link](https://github.com/meta-llama/llama-stack) |

<p align = "center"> <b> Multi API Access </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| LiteLLM      | Library to call 100+ LLM APIs in OpenAI format.                                                        | [Link](https://github.com/BerriAI/litellm) |
| AI Gateway   | A Blazing Fast AI Gateway with integrated Guardrails. Route to 200+ LLMs, 50+ AI Guardrails with 1 fast & friendly API.                                                 | [Link](https://github.com/Portkey-AI/gateway) |

<p align = "center"> <b> Routers </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| RouteLLM     | Framework for serving and evaluating LLM routers - save LLM costs without compromising quality. Drop-in replacement for OpenAI's client to route simpler queries to cheaper models.                                                      | [Link](https://github.com/lm-sys/RouteLLM) |


<p align = "center"> <b> Memory </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| mem0         | The Memory layer for your AI apps.                                                                     | [Link](https://github.com/mem0ai/mem0) |
| Memoripy     | An AI memory layer with short- and long-term storage, semantic clustering, and optional memory decay for context-aware applications. | [Link](https://github.com/caspianmoon/memoripy) |

<p align = "center"> <b> Interface </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| Streamlit    | A faster way to build and share data apps. Streamlit lets you transform Python scripts into interactive web apps in minutes                                                             | [Link](https://github.com/streamlit/streamlit) |
| Gradio       | Build and share delightful machine learning apps, all in Python.                                       | [Link](https://github.com/gradio-app/gradio) |
| AI SDK UI    | Build chat and generative user interfaces.                                                             | [Link](https://sdk.vercel.ai/docs/introduction) |
| AI-Gradio    | Create AI apps powered by various AI providers.                                                        | [Link](https://github.com/AK391/ai-gradio) |
| Simpleaichat | Python package for easily interfacing with chat apps, with robust features and minimal code complexity. | [Link](https://github.com/minimaxir/simpleaichat) |
| Chainlit     | Build production-ready Conversational AI applications in minutes.                                      | [Link](https://github.com/Chainlit/chainlit) |


<p align = "center"> <b> Low Code </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| LangFlow     | LangFlow is a low-code app builder for RAG and multi-agent AI applications. It’s Python-based and agnostic to any model, API, or database.                           | [Link](https://github.com/langflow-ai/langflow) |

<p align = "center"> <b> Cache </b> </p>

| Library        | Description                                                                                               | Link  |
|--------------|------------------------------------------------------------------------------------------------------|-------|
| GPTCache     | A Library for Creating Semantic Cache for LLM Queries. Slash Your LLM API Costs by 10x 💰, Boost Speed by 100x. Fully integrated with LangChain and LlamaIndex.                               | [Link](https://github.com/zilliztech/gptcache) |


## LLM RAG

| Library         | Description                                                                                                      | Link  |
|---------------|----------------------------------------------------------------------------------------------------------------|-------|
| FastGraph RAG | Streamlined and promptable Fast GraphRAG framework designed for interpretable, high-precision, agent-driven retrieval workflows. | [Link](https://github.com/circlemind-ai/fast-graphrag) |
| Chonkie       | RAG chunking library that is lightweight, lightning-fast, and easy to use.                                      | [Link](https://github.com/chonkie-ai/chonkie) |
| RAGChecker    | A Fine-grained Framework For Diagnosing RAG.                                                                   | [Link](https://github.com/amazon-science/RAGChecker) |
| RAG to Riches | Build, scale, and deploy state-of-the-art Retrieval-Augmented Generation applications.                         | [Link](https://github.com/SciPhi-AI/R2R) |
| BeyondLLM     | Beyond LLM offers an all-in-one toolkit for experimentation, evaluation, and deployment of Retrieval-Augmented Generation (RAG) systems. | [Link](https://github.com/aiplanethub/beyondllm) |
| SQLite-Vec    | A vector search SQLite extension that runs anywhere!                                                           | [Link](https://github.com/asg017/sqlite-vec) |
| fastRAG       | fastRAG is a research framework for efficient and optimized retrieval-augmented generative pipelines, incorporating state-of-the-art LLMs and Information Retrieval. | [Link](https://github.com/IntelLabs/fastRAG) |
| FlashRAG      | A Python Toolkit for Efficient RAG Research.                                                                   | [Link](https://github.com/RUC-NLPIR/FlashRAG) |
| Llmware       | Unified framework for building enterprise RAG pipelines with small, specialized models.                        | [Link](https://github.com/llmware-ai/llmware) |
| Rerankers     | A lightweight unified API for various reranking models.                                                        | [Link](https://github.com/AnswerDotAI/rerankers) |
| Vectara       | Build Agentic RAG applications.                                                                                | [Link](https://vectara.github.io/py-vectara-agentic/latest/) |


## LLM Inference

| Library         | Description                                                                                               | Link  |
|---------------|------------------------------------------------------------------------------------------------------|-------|
| LLM Compressor | Transformers-compatible library for applying various compression algorithms to LLMs for optimized deployment. | [Link](https://github.com/vllm-project/llm-compressor) |
| LightLLM      | Python-based LLM inference and serving framework, notable for its lightweight design, easy scalability, and high-speed performance. | [Link](https://github.com/ModelTC/lightllm) |
| vLLM         | High-throughput and memory-efficient inference and serving engine for LLMs.                            | [Link](https://github.com/vllm-project/vllm) |
| torchchat     | Run PyTorch LLMs locally on servers, desktop, and mobile.                                              | [Link](https://github.com/pytorch/torchchat) |
| TensorRT-LLM  | TensorRT-LLM is a library for optimizing Large Language Model (LLM) inference.                        | [Link](https://github.com/NVIDIA/TensorRT-LLM) |
| WebLLM        | High-performance In-browser LLM Inference Engine.                                                     | [Link](https://github.com/mlc-ai/web-llm) |


## LLM Serving

| Library   | Description                                                              | Link  |
|-----------|--------------------------------------------------------------------------|-------|
| Langcorn  | Serving LangChain LLM apps and agents automagically with FastAPI.       | [Link](https://github.com/msoedov/langcorn) |
| LitServe  | Lightning-fast serving engine for any AI model of any size. It augments FastAPI with features like batching, streaming, and GPU autoscaling.           | [Link](https://github.com/Lightning-AI/LitServe) |


## LLM Data Extraction

| Library         | Description                                                                                                                           | Link  |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------|-------|
| Crawl4AI       | Open-source LLM Friendly Web Crawler & Scraper.                                                                                      | [Link](https://github.com/unclecode/crawl4ai) |
| ScrapeGraphAI  | A web scraping Python library that uses LLM and direct graph logic to create scraping pipelines for websites and local documents (XML, HTML, JSON, Markdown, etc.). | [Link](https://github.com/ScrapeGraphAI/Scrapegraph-ai) |
| Docling        | Docling parses documents and exports them to the desired format with ease and speed.                                                  | [Link](https://github.com/DS4SD/docling) |
| Llama Parse    | GenAI-native document parser that can parse complex document data for any downstream LLM use case (RAG, agents).                     | [Link](https://github.com/run-llama/llama_cloud_services) |
| PyMuPDF4LLM    | PyMuPDF4LLM library makes it easier to extract PDF content in the format you need for LLM & RAG environments.                        | [Link](https://pymupdf.readthedocs.io/en/latest/pymupdf4llm/) |
| Crawlee        | A web scraping and browser automation library.                                                                                         | [Link](https://github.com/apify/crawlee-python) |
| MegaParse      | Parser for every type of document.                                                                                                    | [Link](https://github.com/quivrhq/megaparse) |
| ExtractThinker | Document Intelligence library for LLMs.                                                                                               | [Link](https://github.com/enoch3712/ExtractThinker) |


## LLM Data Generation

| Library       | Description                                                                                          | Link  |
|--------------|--------------------------------------------------------------------------------------------------|-------|
| DataDreamer  | DataDreamer is a powerful open-source Python library for prompting, synthetic data generation, and training workflows. | [Link](https://github.com/datadreamer-dev/DataDreamer) |
| fabricator   | A flexible open-source framework to generate datasets with large language models.                   | [Link](https://github.com/flairNLP/fabricator) |
| Promptwright | Synthetic Dataset Generation Library.                                                               | [Link](https://github.com/stacklok/promptwright) |
| EasyInstruct | An Easy-to-use Instruction Processing Framework for Large Language Models.                          | [Link](https://github.com/zjunlp/EasyInstruct) |


## LLM Agents

| Library         | Description                                                                                                 | Link  |
|----------------|---------------------------------------------------------------------------------------------------------|-------|
| CrewAI        | Framework for orchestrating role-playing, autonomous AI agents.                                          | [Link](https://github.com/crewAIInc/crewAI) |
| LangGraph     | Build resilient language agents as graphs.                                                               | [Link](https://github.com/langchain-ai/langgraph) |
| Agno          | Build AI Agents with memory, knowledge, tools, and reasoning. Chat with them using a beautiful Agent UI.  | [Link](https://github.com/agno-agi/agno) |
| AutoGen       | An open-source framework for building AI agent systems.                                                  | [Link](https://github.com/microsoft/autogen) |
| Smolagents    | Library to build powerful agents in a few lines of code.                                                 | [Link](https://github.com/huggingface/smolagents) |
| Pydantic AI | Python agent framework to build production grade applications with Generative AI. | [Link](https://ai.pydantic.dev/) |
| gradio-tools  | A Python library for converting Gradio apps into tools that can be leveraged by an LLM-based agent to complete its task. | [Link](https://github.com/freddyaboulton/gradio-tools) |
| Composio      | Production Ready Toolset for AI Agents.                                                                  | [Link](https://github.com/ComposioHQ/composio) |
| Atomic Agents | Building AI agents, atomically.                                                                         | [Link](https://github.com/BrainBlend-AI/atomic-agents) |
| Memary        | Open Source Memory Layer For Autonomous Agents.                                                          | [Link](https://github.com/kingjulio8238/Memary) |
| Browser Use   | Make websites accessible for AI agents.                                                                 | [Link](https://github.com/browser-use/browser-use) |
| OpenWebAgent   | An Open Toolkit to Enable Web Agents on Large Language Models.                                           | [Link](https://github.com/THUDM/OpenWebAgent/) |
| Lagent        | A lightweight framework for building LLM-based agents.                                                   | [Link](https://github.com/InternLM/lagent) |
| LazyLLM       | A Low-code Development Tool For Building Multi-agent LLMs Applications.                                  | [Link](https://github.com/LazyAGI/LazyLLM) |
| Swarms        | The Enterprise-Grade Production-Ready Multi-Agent Orchestration Framework.                               | [Link](https://github.com/kyegomez/swarms) |
| ChatArena     | ChatArena is a library that provides multi-agent language game environments and facilitates research about autonomous LLM agents and their social interactions. | [Link](https://github.com/Farama-Foundation/chatarena) |
| Swarm         | Educational framework exploring ergonomic, lightweight multi-agent orchestration.                        | [Link](https://github.com/openai/swarm) |
| AgentStack    | The fastest way to build robust AI agents.                                                               | [Link](https://github.com/AgentOps-AI/AgentStack) |
| Archgw        | Intelligent gateway for Agents.                                                                          | [Link](https://github.com/katanemo/archgw) |
| Flow          | A lightweight task engine for building AI agents.                                                        | [Link](https://github.com/lmnr-ai/flow) |
| AgentOps      | Python SDK for AI agent monitoring.                                                                      | [Link](https://github.com/AgentOps-AI/agentops) |
| Langroid      | Multi-Agent framework.                                                                                   | [Link](https://github.com/langroid/langroid) |
| Agentarium    | Framework for creating and managing simulations populated with AI-powered agents.                        | [Link](https://github.com/Thytu/Agentarium) |
| Upsonic       | Reliable AI agent framework that supports MCP.                                                          | [Link](https://github.com/upsonic/upsonic) |


## LLM Evaluation

| Library     | Description                                                                                                         | Link  |
|------------|-----------------------------------------------------------------------------------------------------------------|-------|
| Ragas      | Ragas is your ultimate toolkit for evaluating and optimizing Large Language Model (LLM) applications.            | [Link](https://github.com/explodinggradients/ragas) |
| Giskard    | Open-Source Evaluation & Testing for ML & LLM systems.                                                           | [Link](https://github.com/Giskard-AI/giskard) |
| DeepEval | LLM Evaluation Framework | [Link](https://github.com/confident-ai/deepeval) |
| Lighteval  | All-in-one toolkit for evaluating LLMs.                                                                         | [Link](https://github.com/huggingface/lighteval) |
| Trulens | Evaluation and Tracking for LLM Experiments | [Link](https://github.com/truera/trulens) | 
| PromptBench | A unified evaluation framework for large language models.                                                        | [Link](https://github.com/microsoft/promptbench) |
| LangTest   | Deliver Safe & Effective Language Models. 60+ Test Types for Comparing LLM & NLP Models on Accuracy, Bias, Fairness, Robustness & More. | [Link](https://github.com/JohnSnowLabs/langtest) |
| EvalPlus   | A rigorous evaluation framework for LLM4Code.                                                                    | [Link](https://github.com/evalplus/evalplus) |
| FastChat   | An open platform for training, serving, and evaluating large language model-based chatbots.                      | [Link](https://github.com/lm-sys/FastChat) |
| judges     | A small library of LLM judges.                                                                                   | [Link](https://github.com/quotient-ai/judges) |
| Evals      | Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks.            | [Link](https://github.com/openai/evals) |
| AgentEvals | Evaluators and utilities for evaluating the performance of your agents.                                         | [Link](https://github.com/langchain-ai/agentevals) |
| LLMBox     | A comprehensive library for implementing LLMs, including a unified training pipeline and comprehensive model evaluation. | [Link](https://github.com/RUCAIBox/LLMBox) |
| Opik       | An open-source end-to-end LLM Development Platform which also includes LLM evaluation.                           | [Link](https://github.com/comet-ml/opik) |



## LLM Monitoring

| Library              | Description                                                                                       | Link  |
|----------------------|-------------------------------------------------------------------------------------------------|-------|
| Opik                | An open-source end-to-end LLM Development Platform which also includes LLM monitoring.          | [Link](https://github.com/comet-ml/opik) |
| LangSmith           | Provides tools for logging, monitoring, and improving your LLM applications.                     | [Link](https://github.com/langchain-ai/langsmith-sdk) |
| Weights & Biases (W&B) | W&B provides features for tracking LLM performance.                                          | [Link](https://github.com/wandb) |
| Helicone            | Open source LLM-Observability Platform for Developers. One-line integration for monitoring, metrics, evals, agent tracing, prompt management, playground, etc. | [Link](https://github.com/Helicone/helicone) |
| Evidently          | An open-source ML and LLM observability framework.                                                | [Link](https://github.com/evidentlyai/evidently) |
| Phoenix            | An open-source AI observability platform designed for experimentation, evaluation, and troubleshooting. | [Link](https://github.com/Arize-ai/phoenix) |
| Observers          | A Lightweight Library for AI Observability.                                                       | [Link](https://github.com/cfahlgren1/observers) |


## LLM Prompts

| Library             | Description                                                                                                      | Link  |
|---------------------|----------------------------------------------------------------------------------------------------------------|-------|
| PCToolkit          | A Unified Plug-and-Play Prompt Compression Toolkit of Large Language Models.                                   | [Link](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression) |
| Selective Context  | Selective Context compresses your prompt and context to allow LLMs (such as ChatGPT) to process 2x more content. | [Link](https://pypi.org/project/selective-context/) |
| LLMLingua          | Library for compressing prompts to accelerate LLM inference.                                                  | [Link](https://github.com/microsoft/LLMLingua) |
| betterprompt       | Test suite for LLM prompts before pushing them to production.                                                 | [Link](https://github.com/stjordanis/betterprompt) |
| Promptify         | Solve NLP Problems with LLMs & easily generate different NLP Task prompts for popular generative models like GPT, PaLM, and more with Promptify. | [Link](https://github.com/promptslab/Promptify) |
| PromptSource      | PromptSource is a toolkit for creating, sharing, and using natural language prompts.                          | [Link](https://pypi.org/project/promptsource/) |
| DSPy              | DSPy is the open-source framework for programming—rather than prompting—language models.                      | [Link](https://github.com/stanfordnlp/dspy) |
| Py-priompt        | Prompt design library.                                                                                        | [Link](https://github.com/zenbase-ai/py-priompt) |
| Promptimizer      | Prompt optimization library.                                                                                  | [Link](https://github.com/hinthornw/promptimizer) |


## LLM Structured Outputs
| Library |	Description |	Link |
|------------|--------------------------------------------------------|------|
|Instructor |	Python library for working with structured outputs from large language models (LLMs). Built on top of Pydantic, it provides a simple, transparent, and user-friendly API. | [Link](https://github.com/instructor-ai/instructor) |
| XGrammar   | An open-source library for efficient, flexible, and portable structured generation. | [Link](https://github.com/mlc-ai/xgrammar) |
| Outlines   | Robust (structured) text generation | [Link](https://github.com/dottxt-ai/outlines) |
| Guidance   | Guidance is an efficient programming paradigm for steering language models. | [Link](https://github.com/guidance-ai/guidance) |
| LMQL      | A language for constraint-guided and efficient LLM programming. | [Link](https://github.com/eth-sri/lmql) |
| Jsonformer | A Bulletproof Way to Generate Structured JSON from Language Models. | [Link](https://github.com/1rgs/jsonformer) |


## LLM Safety and Security
| Library         | Description  | Link |
|---------------|-----------------------------------------------------------|------|
| JailbreakEval | A collection of automated evaluators for assessing jailbreak attempts. | [Link](https://github.com/ThuCCSLab/JailbreakEval) |
| EasyJailbreak | An easy-to-use Python framework to generate adversarial jailbreak prompts. | [Link](https://github.com/EasyJailbreak/EasyJailbreak) |
| Guardrails    | Adding guardrails to large language models. | [Link](https://github.com/guardrails-ai/guardrails) |
| LLM Guard     | The Security Toolkit for LLM Interactions. | [Link](https://github.com/protectai/llm-guard) |
| AuditNLG      | AuditNLG is an open-source library that can help reduce the risks associated with using generative AI systems for language. | [Link](https://github.com/salesforce/AuditNLG) |
| NeMo Guardrails | NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems. | [Link](https://github.com/NVIDIA/NeMo-Guardrails) |
| Garak        | LLM vulnerability scanner | [Link](https://github.com/NVIDIA/garak) |


## LLM Embedding Models
| Library                   | Description                                         | Link |
|---------------------------|-----------------------------------------------------|------|
| Sentence-Transformers     | State-of-the-Art Text Embeddings                   | [Link](https://github.com/UKPLab/sentence-transformers) |
| Model2Vec                | Fast State-of-the-Art Static Embeddings             | [Link](https://github.com/MinishLab/model2vec) |
| Text Embedding Inference | A blazing fast inference solution for text embeddings models. TEI enables high-performance extraction for the most popular models, including FlagEmbedding, Ember, GTE and E5. | [Link](https://github.com/huggingface/text-embeddings-inference) |


## Others
| Library                 | Description  | Link |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------|------|
| Text Machina           | A modular and extensible Python framework, designed to aid in the creation of high-quality, unbiased datasets to build robust models for MGT-related tasks such as detection, attribution, and boundary detection. | [Link](https://github.com/Genaios/TextMachina) |
| LLM Reasoners          | A library for advanced large language model reasoning. | [Link](https://github.com/maitrix-org/llm-reasoners) |
| EasyEdit               | An Easy-to-use Knowledge Editing Framework for Large Language Models. | [Link](https://github.com/zjunlp/EasyEdit) |
| CodeTF                 | CodeTF: One-stop Transformer Library for State-of-the-art Code LLM. | [Link](https://github.com/salesforce/CodeTF) |
| spacy-llm              | This package integrates Large Language Models (LLMs) into spaCy, featuring a modular system for fast prototyping and prompting, and turning unstructured responses into robust outputs for various NLP tasks. | [Link](https://github.com/explosion/spacy-llm) |
| pandas-ai              | Chat with your database (SQL, CSV, pandas, polars, MongoDB, NoSQL, etc.). | [Link](https://github.com/Sinaptik-AI/pandas-ai) |
| LLM Transparency Tool  | An open-source interactive toolkit for analyzing internal workings of Transformer-based language models. | [Link](https://github.com/facebookresearch/llm-transparency-tool) |
| Vanna                  | Chat with your SQL database. Accurate Text-to-SQL Generation via LLMs using RAG. | [Link](https://github.com/vanna-ai/vanna) |
| mergekit               | Tools for merging pretrained large language models. | [Link](https://github.com/arcee-ai/MergeKit) |
| MarkLLM                | An Open-Source Toolkit for LLM Watermarking. | [Link](https://github.com/THU-BPM/MarkLLM) |
| LLMSanitize            | An open-source library for contamination detection in NLP datasets and Large Language Models (LLMs). | [Link](https://github.com/ntunlp/LLMSanitize) |
| Annotateai             | Automatically annotate papers using LLMs. | [Link](https://github.com/neuml/annotateai) |
| LLM Reasoner          | Make any LLM think like OpenAI o1 and DeepSeek R1. | [Link](https://github.com/harishsg993010/LLM-Reasoner) |


## ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=KalyanKS-NLP/llm-engineer-toolkit&type=Date)](https://star-history.com/#)

Please consider giving a star, if you find this repository useful. 

