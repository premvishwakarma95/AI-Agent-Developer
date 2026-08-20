# RAG

RAG stands for **Retrieval-Augmented Generation**.

It is a technique that lets an AI answer questions using your own data—such as PDFs, documentation, database records, or previous call summaries—instead of relying only on its trained knowledge.

## How RAG Works

```mermaid
flowchart TD
    A[User asks a question] --> B[Convert question into an embedding]
    B --> C[Search the vector database]
    C --> D[Retrieve relevant information]
    D --> E[Send question and context to the LLM]
    E --> F[Generate the final answer]
```


## What is Embedding in RAG?
An embedding is a numerical representation of text that helps a computer understand its meaning.  
For example:
```bash
"I like programming"
        ↓
[0.12, -0.45, 0.78, 0.31, ...]
```
