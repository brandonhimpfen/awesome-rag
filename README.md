# Awesome RAG (Retrieval-Augmented Generation) [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, frameworks, and resources for Retrieval-Augmented Generation (RAG) — systems that combine LLMs with external knowledge retrieval for more accurate, grounded answers.

## Contents

- [Frameworks](#frameworks)
- [Vector Databases](#vector-databases)
- [Embedding Models](#embedding-models)
- [Pipelines & Orchestration](#pipelines--orchestration)
- [Evaluation & Benchmarking](#evaluation--benchmarking)
- [Examples](#examples)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Frameworks

- [LlamaIndex](https://github.com/run-llama/llama_index) – Data framework for building RAG apps with retrieval, agents, and advanced pipelines.
- [LangChain](https://github.com/langchain-ai/langchain) – Industry-standard framework with RAG chains, retrievers, memory, and eval tools.
- [Haystack](https://github.com/deepset-ai/haystack) – End-to-end RAG pipeline framework with search, indexing, and orchestration.
- [Marqo](https://github.com/marqo-ai/marqo) – Neural search engine for RAG with built-in vector indexing and document enrichment.
- [OpenSearch](https://github.com/opensearch-project/OpenSearch) – Search engine with vector search and hybrid retrieval for RAG setups.
- [Jina](https://github.com/jina-ai/jina) – Framework for multimodal retrieval and generative search.
- [Milvus Lite](https://github.com/milvus-io/milvus-lite) – Lightweight local vector DB ideal for prototyping RAG apps.

## Vector Databases

- [Pinecone](https://www.pinecone.io/) – Managed vector database optimized for RAG at scale.
- [Weaviate](https://github.com/weaviate/weaviate) – Open-source vector DB with hybrid search, modules, and semantic tooling.
- [Milvus](https://github.com/milvus-io/milvus) – High-performance, cloud-native vector DB.
- [qdrant](https://github.com/qdrant/qdrant) – Open-source vector search engine with filters, HNSW, and payloads.
- [Chroma](https://github.com/chroma-core/chroma) – Local-first vector database widely used in prototyping and small deployments.
- [Redis Vector Search](https://redis.io/docs/latest/develop/interact/search-and-query/vector-search/) – Redis module for hybrid text + vector search.

## Embedding Models

- [OpenAI Text Embeddings](https://platform.openai.com/docs/guides/embeddings) – High-quality embeddings for semantic search and RAG.
- [HuggingFace Embeddings](https://huggingface.co/models?pipeline_tag=sentence-similarity) – Library of open embedding models from small to large.
- [Voyage Embeddings](https://voyageai.com/) – High-performance multilingual and domain-specific embeddings.
- [Cohere Embeddings](https://docs.cohere.com/docs/embeddings) – Strong semantic embeddings with reranking support.
- [Nomic Embeddings](https://github.com/nomic-ai/atlas) – Embeddings designed for large-scale, interactive datasets.

## Pipelines & Orchestration

- [LangGraph](https://github.com/langchain-ai/langgraph) – Graph-based RAG workflows with state management and multi-step reasoning.
- [LlamaIndex Pipelines](https://github.com/run-llama/llama_index) – End-to-end pipelines for chunking, retrieval, reranking, and evaluation.
- [Deepset Cloud](https://www.deepset.ai/cloud) – Fully managed RAG pipelines built on Haystack.
- [FastRAG](https://github.com/bojone/fastrank) – Minimal, efficient RAG pipeline with reranking.

## Evaluation & Benchmarking

- [RAGAS](https://github.com/explodinggradients/ragas) – Automated evaluation metrics for RAG quality, grounding, and hallucinations.
- [TruLens](https://github.com/truera/trulens) – Evaluation and monitoring for RAG pipelines.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) – Open-source LLM observability and RAG evaluation toolkit.
- [LangChain Evaluators](https://python.langchain.com/docs/guides/evaluation/) – Built-in evaluators for RAG, retrieval, and chain performance.

## Examples

- [LlamaIndex RAG Examples](https://github.com/run-llama/llama_index/tree/main/examples) – End-to-end tutorials and sample apps.
- [LangChain RAG Templates](https://github.com/langchain-ai/langchain/tree/master/templates) – Official RAG app templates including agents + retrieval.
- [Haystack RAG Examples](https://github.com/deepset-ai/haystack/tree/main/examples) – Starter implementations for RAG pipelines.
- [Multimodal RAG (Jina)](https://github.com/jina-ai) – Image + text RAG examples using Jina.
- [OpenAI RAG Cookbook Examples](https://github.com/openai/openai-cookbook) – Retrieval + function calling + tool use demos.

## Learning Resources

- [RAG 101 – LangChain](https://python.langchain.com/docs/use_cases/question_answering/) – Intro guides for building RAG pipelines.
- [LlamaIndex RAG Guide](https://docs.llamaindex.ai/en/stable/) – High-level and deep-dive RAG documentation.
- [Haystack RAG Theory](https://docs.haystack.deepset.ai/docs) – Concepts, architectures, and tutorials.
- [Multimodal RAG Guides](https://github.com/jina-ai/jina) – Tutorials for text, image, and video retrieval.
- [Advanced RAG: Retrieval, Reranking, and Tool Use](https://github.com/topics/rag) – Topic-level overview across GitHub.

## Related Awesome Lists

- [Awesome AI](https://github.com/awesomelistsio/awesome-ai)
- [Awesome AI Infrastructure](https://github.com/awesomelistsio/awesome-ai-infrastructure)
- [Awesome AI Agents](https://github.com/awesomelistsio/awesome-ai-agents)
- [Awesome AI Research Papers](https://github.com/awesomelistsio/awesome-ai-research-papers)

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
