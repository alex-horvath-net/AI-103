# AI-103 — Enhanced Questions and Answers

This file contains expanded explanations for QA-003 and QA-004 from `AI-103.md`.

## QA-003 — Choose the appropriate Foundry service for grounding product information

### Scenario

Contoso stores product-detail PDFs in Azure Blob Storage. Agent1 must use those documents to answer natural-language product questions. The solution must include an indexing pipeline with semantic and vector search, and the responses must be relevant, complete, and accurate.

### Correct answer

**C. Azure AI Search**

### Why this is correct

Azure AI Search is the service that indexes the product documents and retrieves the relevant content for Agent1. It supports the required **semantic search** and **vector search** capabilities, which are the decisive requirements in this question.

The resulting pattern is:

```text
Blob Storage PDFs → indexing pipeline → Azure AI Search → retrieved product content → Agent1 response
```

### Why the other options are incorrect

- **A. Azure Translator:** translates text between languages. It does not create a searchable index for Contoso’s product PDFs.
- **B. Grounding with Bing Search:** retrieves information from the public web. The requirement is to retrieve information from Contoso’s private documents in Blob Storage.
- **D. Azure Document Intelligence in Foundry Tools:** can extract text, tables, and document layout. It may help during document ingestion, but it is not the required semantic/vector search index and retrieval service.

### Exam clue

**Semantic search + vector search + indexing private documents → Azure AI Search.**

### Source

[AI-103.md](https://github.com/alex-horvath-net/ai-103/blob/main/AI-103.md)

## QA-004 — Identify the Foundry component that provides pre-built AI task services

### Question

Which component of Microsoft Foundry provides pre-built services for common AI tasks?

### Correct answer

**A. Foundry Tools**

### Why this is correct

Foundry Tools provide ready-made services for common AI tasks, such as language processing, speech, translation, vision, and document processing. They are specialised capabilities that an application can consume without deploying or building a general-purpose foundation model.

### Why the other options are incorrect

- **B. Foundry Models:** provides access to model deployments used for generation and reasoning. Models are the AI engines; they are not the collection of pre-built task-specific services.
- **C. Foundry IQ:** provides managed knowledge and retrieval capabilities for grounding agents and responses. It is a knowledge/retrieval layer, not the general-purpose set of pre-built AI task services.

### Exam distinction

| Component | Primary role |
|---|---|
| **Foundry Tools** | Pre-built services for common AI tasks |
| **Foundry Models** | Model deployments for generation and reasoning |
| **Foundry IQ** | Managed knowledge and retrieval for grounding |

### Exam clue

**Pre-built AI task service → Foundry Tools.**

### Source

[AI-103.md](https://github.com/alex-horvath-net/ai-103/blob/main/AI-103.md)

## QA-005 — Choose the appropriate retrieval approach

### Scenario

A chat application must retrieve information from an Azure AI Search vector index. Complex questions may require multiple chunks, previous conversation turns must influence retrieval planning, and retrievals should run in parallel.

### Correct answer

**B. Agentic Retrieval Augmented Generation (RAG)**

### Why this is correct

Agentic RAG uses an agent or language model to plan retrieval. It can decompose a complex question into multiple subqueries, use multi-turn conversation context, retrieve from multiple chunks, and run independent retrievals in parallel before producing a grounded answer.

### Why the other options are incorrect

- **A. Iterative retrieval:** retrieves in sequential stages. It does not inherently provide agentic planning and parallel retrieval.
- **C. Chain of thought:** describes a reasoning process; it is not a retrieval architecture for connecting a chat application to Azure AI Search.
- **D. Classic RAG:** normally performs a simpler retrieve-then-generate flow. It does not inherently decompose complex conversational questions or plan and parallelise multiple retrievals.

### Exam clue

**Complex conversational questions + multiple chunks + parallel retrieval → Agentic RAG.**

## QA-006 — Select the model type used to create search vectors

### Scenario

A search solution needs vector representations of internal policy documents and user queries.

### Correct answer

**A. An embedding model**

### Why this is correct

An embedding model converts text into numerical vectors. Azure AI Search compares document vectors with query vectors to find semantically similar content.

### Why the other options are incorrect

- **B. Image generation model:** creates images; it does not convert document text and queries into search vectors.
- **C. Large language model (LLM):** is primarily used for language understanding and generation. It is not the specific model type selected to generate embeddings.
- **D. Small language model (SLM):** is a smaller generative language model. It is not an embedding model unless explicitly designed and deployed for embeddings.

### Exam clue

**Generate vector representations for documents and queries → embedding model.**

## QA-007 — Centrally manage a shared Azure AI Search connection

### Scenario

Several agents in one Foundry project must use the same Azure AI Search resource. The credentials and connection details should be centrally managed and reusable by all agents.

### Correct answer

**C. Add a connection to the Azure AI Search resource.**

### Why this is correct

A Foundry connection stores the resource connection details and authentication configuration at project level so multiple agents can use the same Azure AI Search resource consistently.

### Why the other options are incorrect

- **A. Enable role-based access control (RBAC):** RBAC controls authorisation and permissions. It does not create a reusable project-level resource connection.
- **B. Disable key-based access control:** changes an authentication option but does not centrally manage the connection for all agents.
- **D. Create a managed private endpoint:** provides private network connectivity. It does not manage the shared credentials or project connection configuration.

### Exam clue

**Centrally reuse a resource and its credentials across agents → add a connection.**

## QA-008 — Configure personalised interactions across future conversations

### Scenario

Users need a personalised experience, and Agent1 must retain conversation context and recall relevant information from earlier interactions.

### Correct answer

**B. Memory**

### Why this is correct

Memory preserves useful information from previous interactions so the agent can use it in later conversations and provide a personalised experience.

### Why the other options are incorrect

- **A. Knowledge:** provides external facts, such as product information. It does not remember an individual user’s previous conversations.
- **C. Guardrails:** constrain behaviour and help prevent unsafe or prohibited responses. They do not store conversation context.
- **D. Tools:** perform actions or access external services. They do not provide conversational memory by themselves.

### Exam clue

**Personalised future interactions and retained context → memory.**

## QA-009 — Select real-time governed access to SharePoint content

### Scenario

An agent needs real-time access to SharePoint sites and libraries while retaining Microsoft 365 governance.

### Correct answer

**B. SharePoint Remote**

### Why this is correct

SharePoint Remote queries SharePoint content directly in real time and preserves the governance model of Microsoft 365.

### Why the other options are incorrect

- **A. SharePoint Indexed:** pre-processes SharePoint content into a search index. It is not direct real-time querying of SharePoint.
- **C. Azure Blob Storage:** is a separate storage service and does not provide governed, live access to SharePoint sites and libraries.

### Exam clue

**Real-time SharePoint access with Microsoft 365 governance → SharePoint Remote.**

## QA-010 — Understand scoring profiles in Foundry IQ knowledge bases

### Scenario

The search solution must make results containing more important fields or attributes appear earlier in the ranking.

### Correct answer

**B. To boost specific fields or attributes so more important results surface first.**

### Why this is correct

A scoring profile changes result ranking by giving selected fields or attributes greater importance. This allows business-relevant results to rank higher.

### Why the other options are incorrect

- **A. Encrypt sensitive fields:** encryption is a security and data-protection concern, not a scoring-profile function.
- **C. Configure document chunking and embeddings:** chunking and embedding belong to document-processing and vector-index configuration, not result ranking.

### Exam clue

**Boost important fields in search ranking → scoring profile.**
