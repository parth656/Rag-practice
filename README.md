# RAG Practice

A practice repository for learning retrieval-augmented generation (RAG). Document the individual exercises as they are added; the exact loaders, embedding model, vector store, and LLM provider should be confirmed from the source files.

## RAG in brief

A RAG application retrieves relevant passages from a document collection and supplies them to a language model as context for answering a question. Retrieval quality and answer faithfulness should be evaluated separately.

## Typical workflow

```text
Documents -> Load and clean -> Split into chunks
          -> Embed -> Index -> Retrieve
          -> Generate answer with context
```

## Getting started

```bash
git clone https://github.com/parth656/Rag-practice.git
cd Rag-practice
```

Inspect the project files and use the dependency manifest and entry point provided by each exercise. If there is no dependency manifest yet, create a virtual environment and record the exact dependencies before adding runnable examples.

## What each exercise should document

- Objective and input documents
- Loader and text-splitting strategy
- Embedding model and vector store
- Retriever settings and prompt template
- LLM provider and required environment variables
- Example question, answer, and source passages
- Limitations, latency, and evaluation results

## Security

Do not commit API keys, confidential documents, or generated indexes containing private information. Treat retrieved text as untrusted input and test prompt-injection cases.

## Status

Learning workspace. Add a verified quick start once the current exercise structure is established.
