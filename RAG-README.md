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
