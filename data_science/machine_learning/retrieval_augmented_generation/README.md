# RETRIEVAL AUGMENTED GENERATION (RAG)

<!-- ![Cheat sheet](/retrieval_augmented_generation/images/rag-cheat-sheet-final.svg) -->
![Cheat sheet](https://d3ddy8balm3goa.cloudfront.net/llamaindex/rag-cheat-sheet-final.svg)


# Quick links
- Cheat sheet - [A Cheat Sheet & Recipes For Building Advanced RAG](https://www.llamaindex.ai/blog/a-cheat-sheet-and-some-recipes-for-building-advanced-rag-803a9d94c41b)

- Cookbook - OpenAI: [Evaluate RAG with LlamaIndex](https://www.llamaindex.ai/blog/openai-cookbook-evaluating-rag-systems-fe393c61fb93)



# Reading list
## Read

- Pinecone blog - [Retrieval augmented generation](https://www.pinecone.io/learn/retrieval-augmented-generation/)
    - see related resources in [Examples](#examples)
    - problem statement
    - high-level description of RAG
    - comment on pre-training, fine-tuning, and prompt-engineering
    - friendly discussion of embedding and 'semantic search' in relation to 'retriever' component of RAG
    - > "vector databases allow querying of data in natural language"
    - Pinecone also supports 'hybrid search'

- Pinecone blog - [Retrieval re-rank](https://www.pinecone.io/learn/refine-with-rerank/)
    - re-order context retrieved from a vector DB and return only top-n to further improve relevance to query
    - improve utilisation of finite length context window
    - highlights benefits of incorporating 'reranking' into 'semantic search'
    - illustration and explanation of the 'lost in middle' phenomenon

## Unread

- Jay Alammar - [The Illustrated Retrieval Transformer](https://jalammar.github.io/illustrated-retrieval-transformer/)

- LlamaIndex blog  - [Introducing RAGs: Your Personalized ChatGPT Experience Over Your Data](https://www.llamaindex.ai/blog/introducing-rags-your-personalized-chatgpt-experience-over-your-data-2b9d140769b1)

- LlamaIndex blog  - [RAGArch: Building a No-Code RAG Pipeline Configuration & One-Click RAG Code Generation Tool Powered by LlamaIndex](https://www.llamaindex.ai/blog/ragarch-building-a-no-code-rag-pipeline-configuration-one-click-rag-code-generation-tool-powered-b6e8eeb70089)

- LlamaIndex blog  - [Simplify your RAG application architecture with LlamaIndex + PostgresML](https://www.llamaindex.ai/blog/simplify-your-rag-application-architecture-with-llamaindex-postgresml)

- LlamaIndex blog  - [Secure RAG with LlamaIndex and LLM Guard by Protect AI](https://www.llamaindex.ai/blog/secure-rag-with-llamaindex-and-llm-guard-by-protect-ai)

- LlamaIndex blog  - [One-click Open Source RAG Observability with Langfuse](https://www.llamaindex.ai/blog/one-click-open-source-rag-observability-with-langfuse)

- LlamaIndex blog  - [Building a Fully Open Source Retriever with Nomic Embed and LlamaIndex](https://www.llamaindex.ai/blog/building-a-fully-open-source-retriever-with-nomic-embed-and-llamaindex-fc3d7f36d3e4)

- LlamaIndex blog  - [LlamaIndex: Enhancing Retrieval Performance with Alpha Tuning in Hybrid Search in RAG](https://www.llamaindex.ai/blog/llamaindex-enhancing-retrieval-performance-with-alpha-tuning-in-hybrid-search-in-rag-135d0c9b8a00)

- LlamaIndex blog  - [Agentic RAG With LlamaIndex](https://www.llamaindex.ai/blog/agentic-rag-with-llamaindex-2721b8a49ff6)

- LlamaIndex blog  - [Building Multi-Tenancy RAG System with LlamaIndex](https://www.llamaindex.ai/blog/building-multi-tenancy-rag-system-with-llamaindex-0d6ab4e0c44b) - serve multiple users independently

- LlamaIndex blog  - [Supercharge your LlamaIndex RAG Pipeline with UpTrain Evaluations](https://www.llamaindex.ai/blog/supercharge-your-llamaindex-rag-pipeline-with-uptrain-evaluations)

- LlamaIndex blog  - [LlamaIndex: RAG Evaluation Showdown with GPT-4 vs. Open-Source Prometheus Model](https://www.llamaindex.ai/blog/llamaindex-rag-evaluation-showdown-with-gpt-4-vs-open-source-prometheus-model-14cdca608277)



# Watch list
## Watched
- [Intro to RAG](https://www.youtube.com/watch?v=Y08Nn23o_mY) by Matthew Berman - outline of RAG for beginners
- [Stanford CS25 - Retrieval Augmented Language Models](https://www.youtube.com/watch?v=mE7IDf2SmJg) - seminar presentation
    - highlights the different RAG architectures and regimes ranging from commercially used solutions to in-the-lab academic research
    - highlights current challenges
    - proposes future work and further experimentation
- [Fully local RAG agents with Llama 3.1](https://www.youtube.com/watch?v=nPpgh_KaNng) using LangChain - code-along/tutorial
    - see Corrective RAG in [Examples](#examples)
    - demonstrates how to build a RAG application with LangChain
    - demonstrates tool-use (web search) when the model doesn't have the answer
    - demonstrates application evaluation using LangSmith

## To watch


# Course list
- Free [Advanced RAG Certification course with Activeloop and LlamaIndex](https://www.llamaindex.ai/blog/join-thousands-in-our-free-advanced-rag-certification-created-with-activeloop-ad63f24f27bb)


# Examples
- [Pinecone](https://docs.pinecone.io/examples/notebooks) - notebooks using LangChain framework together with OpenAI models and Pinecone vector DataBase.
    - [Pinecone Github](https://github.com/pinecone-io/examples)
- LangChain [corrective RAG](https://github.com/langchain-ai/langgraph/blob/main/examples/tutorials/rag-agent-testing-local.ipynb) notebook
- [AWS SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html) - notebooks using meta LLMs and SageMaker.
