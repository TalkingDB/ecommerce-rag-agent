<!-- short-readme -->
<h1 align="center">E-commerce Domain Support Assistant (RAG)</h1>

<p align="center"><b>A support chatbot for Indian e-commerce, kept unchanged as a benchmark subject.</b></p>

<p align="center"><a href="#try-it">Try it</a> · <a href="docs/reference.md">Full reference</a></p>

<p align="center"><a href="https://github.com/TalkingDB/ecommerce-rag-agent/stargazers"><img src="https://img.shields.io/github/stars/TalkingDB/ecommerce-rag-agent?style=social" alt="GitHub stars"></a></p>

It answers questions about returns, refunds and exchanges (Meesho), consumer law and a product manual, only from those documents, with [RAG](https://en.wikipedia.org/wiki/Retrieval-augmented_generation) on LangChain, Qdrant and FastAPI.

## What it does

- [talkingdb-benchmarks/ecommerce-rag](https://github.com/TalkingDB/talkingdb-benchmarks/tree/main/ecommerce-rag) runs this code exactly as pinned.
- OpenAI by default, or Ollama on your own computer.
- Everything else, architecture to limitations, is in the [full reference](docs/reference.md).

## Try it

```bash
cp .env.example .env                   # add your key, or set the providers to ollama
python scripts/download_documents.py
docker compose up --build              # chat UI on http://localhost:8501
```

Status: benchmark subject, not a TalkingDB product.

## Where it fits

Benchmarked by [talkingdb-benchmarks](https://github.com/TalkingDB/talkingdb-benchmarks).

## Learn more

| Page | Read it to |
| :--- | :--- |
| [Full reference](docs/reference.md) | read everything that used to be on this page |
