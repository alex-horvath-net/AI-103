# AI-103 Questions and Answers
<details>
<summary><h2>Question Index</h2></summary>

Question counts include all questions in descendant topics.

- [1 Plan and manage an Azure AI solution (25–30%)](#1-plan-and-manage-an-azure-ai-solution-25-30) (38)
  - [1.1 Choose the appropriate Foundry services for generative AI and agents](#1-1-choose-the-appropriate-foundry-services-for-generative-ai-and-agents) (10)
    - [1.1.1 Choose an appropriate model for each task, including large language models (LLMs), small language models, multimodal models, and Foundry Tools](#1-1-1-choose-an-appropriate-model-for-each-task-including-large-language-models-llms-small-language-models-multimodal-models-and-foundry-tools) (2)
    - [1.1.2 Choose the appropriate Foundry services for generative tasks, grounding, vector search, agent workflows, or multimodal processing](#1-1-2-choose-the-appropriate-foundry-services-for-generative-tasks-grounding-vector-search-agent-workflows-or-multimodal-processing) (2)
    - [1.1.3 Choose an appropriate method for retrieval and indexing](#1-1-3-choose-an-appropriate-method-for-retrieval-and-indexing) (2)
    - [1.1.4 Choose appropriate memory, tool, and knowledge integration services for agent solutions](#1-1-4-choose-appropriate-memory-tool-and-knowledge-integration-services-for-agent-solutions) (4)
  - [1.2 Set up AI solutions in Foundry](#1-2-set-up-ai-solutions-in-foundry) (9)
    - [1.2.1 Design Azure infrastructure for AI apps and agent-based solutions](#1-2-1-design-azure-infrastructure-for-ai-apps-and-agent-based-solutions) (4)
    - [1.2.2 Choose appropriate deployment options](#1-2-2-choose-appropriate-deployment-options) (3)
    - [1.2.3 Configure model and agent deployments](#1-2-3-configure-model-and-agent-deployments) (0)
    - [1.2.4 Integrate Foundry projects with continuous integration and continuous deployment (CI/CD) pipelines](#1-2-4-integrate-foundry-projects-with-continuous-integration-and-continuous-deployment-ci-cd-pipelines) (2)
  - [1.3 Manage, monitor, and secure AI systems](#1-3-manage-monitor-and-secure-ai-systems) (11)
    - [1.3.1 Manage quotas, scaling, rate limits, and cost footprints for model and agent workloads](#1-3-1-manage-quotas-scaling-rate-limits-and-cost-footprints-for-model-and-agent-workloads) (3)
    - [1.3.2 Monitor model performance, drift, safety events, and grounding quality](#1-3-2-monitor-model-performance-drift-safety-events-and-grounding-quality) (1)
    - [1.3.3 Monitor data ingestion quality, search index health, and relevance performance](#1-3-3-monitor-data-ingestion-quality-search-index-health-and-relevance-performance) (0)
    - [1.3.4 Configure security, including managed identity, private networking, keyless credentials, and role policies](#1-3-4-configure-security-including-managed-identity-private-networking-keyless-credentials-and-role-policies) (7)
  - [1.4 Implement responsible AI across generative AI and agentic systems](#1-4-implement-responsible-ai-across-generative-ai-and-agentic-systems) (8)
    - [1.4.1 Configure safety filters, guardrails, risk detection, and content moderation](#1-4-1-configure-safety-filters-guardrails-risk-detection-and-content-moderation) (1)
    - [1.4.2 Apply responsible AI instrumentation, including evaluators, safety evaluations, and explanation tooling](#1-4-2-apply-responsible-ai-instrumentation-including-evaluators-safety-evaluations-and-explanation-tooling) (4)
    - [1.4.3 Implement auditing through trace logging, provenance metadata, and approval workflows](#1-4-3-implement-auditing-through-trace-logging-provenance-metadata-and-approval-workflows) (1)
    - [1.4.4 Govern agent behavior with oversight modes, constraints, and tool-access controls](#1-4-4-govern-agent-behavior-with-oversight-modes-constraints-and-tool-access-controls) (2)
- [2 Implement generative AI and agentic solutions (30–35%)](#2-implement-generative-ai-and-agentic-solutions-30-35) (84)
  - [2.1 Build generative applications by using Foundry](#2-1-build-generative-applications-by-using-foundry) (19)
    - [2.1.1 Deploy and consume LLMs, small models, code models, and multimodal models](#2-1-1-deploy-and-consume-llms-small-models-code-models-and-multimodal-models) (0)
    - [2.1.2 Implement retrieval-augmented generation (RAG) in an application](#2-1-2-implement-retrieval-augmented-generation-rag-in-an-application) (2)
    - [2.1.3 Design workflows, tool-augmented flows, and multistep reasoning pipelines](#2-1-3-design-workflows-tool-augmented-flows-and-multistep-reasoning-pipelines) (4)
    - [2.1.4 Evaluate models and apps, including detecting fabrications, relevance, quality, and safety](#2-1-4-evaluate-models-and-apps-including-detecting-fabrications-relevance-quality-and-safety) (6)
    - [2.1.5 Integrate generative workflows into applications by using Foundry SDKs and connectors](#2-1-5-integrate-generative-workflows-into-applications-by-using-foundry-sdks-and-connectors) (5)
    - [2.1.6 Configure an application to connect to a Foundry project](#2-1-6-configure-an-application-to-connect-to-a-foundry-project) (2)
  - [2.2 Build agents by using Foundry](#2-2-build-agents-by-using-foundry) (47)
    - [2.2.1 Define agent roles, goals, conversation-tracking approach, and tool schemas](#2-2-1-define-agent-roles-goals-conversation-tracking-approach-and-tool-schemas) (2)
    - [2.2.2 Build agents that integrate retrieval, function-calling, and conversation memory](#2-2-2-build-agents-that-integrate-retrieval-function-calling-and-conversation-memory) (11)
    - [2.2.3 Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions](#2-2-3-integrate-agent-tools-including-apis-knowledge-stores-search-content-understanding-and-custom-functions) (22)
    - [2.2.4 Implement orchestrated multi-agent solutions](#2-2-4-implement-orchestrated-multi-agent-solutions) (7)
    - [2.2.5 Build autonomous or semiautonomous workflows with safeguards and approval flow controls](#2-2-5-build-autonomous-or-semiautonomous-workflows-with-safeguards-and-approval-flow-controls) (2)
    - [2.2.6 Integrate monitoring into deployed agents, evaluate agent behavior, and perform error analysis](#2-2-6-integrate-monitoring-into-deployed-agents-evaluate-agent-behavior-and-perform-error-analysis) (3)
  - [2.3 Optimize and operationalize generative AI systems](#2-3-optimize-and-operationalize-generative-ai-systems) (18)
    - [2.3.1 Tune generation behavior, such as prompt engineering and adjusting model parameters](#2-3-1-tune-generation-behavior-such-as-prompt-engineering-and-adjusting-model-parameters) (9)
    - [2.3.2 Implement model reflection, chain-of-thought evaluations, and self-critique loops](#2-3-2-implement-model-reflection-chain-of-thought-evaluations-and-self-critique-loops) (4)
    - [2.3.3 Set up observability by implementing tracing, token analytics, safety signals, and latency breakdowns](#2-3-3-set-up-observability-by-implementing-tracing-token-analytics-safety-signals-and-latency-breakdowns) (4)
    - [2.3.4 Orchestrate multiple models, flows, or hybrid LLM and rules engines](#2-3-4-orchestrate-multiple-models-flows-or-hybrid-llm-and-rules-engines) (1)
- [3 Implement computer vision solutions (10–15%)](#3-implement-computer-vision-solutions-10-15) (34)
  - [3.1 Design and implement image- and video-generation solutions](#3-1-design-and-implement-image-and-video-generation-solutions) (11)
    - [3.1.1 Implement a solution that generates images from text prompts and reference media](#3-1-1-implement-a-solution-that-generates-images-from-text-prompts-and-reference-media) (4)
    - [3.1.2 Implement a solution that generates videos from text prompts and reference media](#3-1-2-implement-a-solution-that-generates-videos-from-text-prompts-and-reference-media) (3)
    - [3.1.3 Configure image-editing workflows, including inpainting, mask-based edits, and prompt-driven modifications](#3-1-3-configure-image-editing-workflows-including-inpainting-mask-based-edits-and-prompt-driven-modifications) (2)
    - [3.1.4 Implement workflows to edit generated videos](#3-1-4-implement-workflows-to-edit-generated-videos) (2)
    - [3.1.5 Select and apply appropriate generation and editing controls provided by the platform](#3-1-5-select-and-apply-appropriate-generation-and-editing-controls-provided-by-the-platform) (0)
  - [3.2 Design and implement multimodal understanding workflows](#3-2-design-and-implement-multimodal-understanding-workflows) (14)
    - [3.2.1 Build a solution that analyzes visual context by using multimodal models](#3-2-1-build-a-solution-that-analyzes-visual-context-by-using-multimodal-models) (4)
    - [3.2.2 Configure apps to produce concise or detailed captions for single or multiple images](#3-2-2-configure-apps-to-produce-concise-or-detailed-captions-for-single-or-multiple-images) (0)
    - [3.2.3 Implement a solution that enables question-answering grounded in visual evidence](#3-2-3-implement-a-solution-that-enables-question-answering-grounded-in-visual-evidence) (0)
    - [3.2.4 Configure generation of alt-text and extended image descriptions aligned to accessibility guidelines](#3-2-4-configure-generation-of-alt-text-and-extended-image-descriptions-aligned-to-accessibility-guidelines) (0)
    - [3.2.5 Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics](#3-2-5-implement-visual-understanding-by-configuring-azure-content-understanding-in-foundry-tools-to-extract-visual-characteristics) (4)
    - [3.2.6 Implement video analysis workflows to process and interpret video segments](#3-2-6-implement-video-analysis-workflows-to-process-and-interpret-video-segments) (1)
    - [3.2.7 Configure single-task and pro-mode Content Understanding pipelines](#3-2-7-configure-single-task-and-pro-mode-content-understanding-pipelines) (2)
    - [3.2.8 Implement solutions that identify objects, components, or regions within images or video](#3-2-8-implement-solutions-that-identify-objects-components-or-regions-within-images-or-video) (3)
  - [3.3 Implement responsible AI for multimodal content](#3-3-implement-responsible-ai-for-multimodal-content) (9)
    - [3.3.1 Implement filters to classify unsafe or disallowed visual content](#3-3-1-implement-filters-to-classify-unsafe-or-disallowed-visual-content) (2)
    - [3.3.2 Detect and mitigate indirect prompt injection by using embedded text in images](#3-3-2-detect-and-mitigate-indirect-prompt-injection-by-using-embedded-text-in-images) (7)
    - [3.3.3 Enforce visual policy rules, such as applying watermarks, flagging prohibited symbols, upholding brand usage requirements, and detecting potentially inappropriate content](#3-3-3-enforce-visual-policy-rules-such-as-applying-watermarks-flagging-prohibited-symbols-upholding-brand-usage-requirements-and-detecting-potentially-inappropriate-content) (0)
- [4. Implement text analysis solutions (10–15%)](#4-implement-text-analysis-solutions-10-15) (29)
  - [4.1 Apply language model text analysis](#4-1-apply-language-model-text-analysis) (8)
    - [4.1.1 Implement solutions to extract entities, topics, summaries, and structured JSON outputs by using generative prompting and Foundry Tools](#4-1-1-implement-solutions-to-extract-entities-topics-summaries-and-structured-json-outputs-by-using-generative-prompting-and-foundry-tools) (1)
    - [4.1.2 Configure detection of sentiment, tone, safety issues, and sensitive content](#4-1-2-configure-detection-of-sentiment-tone-safety-issues-and-sensitive-content) (3)
    - [4.1.3 Build solutions that translate text by using Azure Translator in Foundry Tools or LLM-powered translation flows](#4-1-3-build-solutions-that-translate-text-by-using-azure-translator-in-foundry-tools-or-llm-powered-translation-flows) (2)
    - [4.1.4 Customize language model outputs for domain tasks, such as compliance summarization and domain extraction](#4-1-4-customize-language-model-outputs-for-domain-tasks-such-as-compliance-summarization-and-domain-extraction) (2)
  - [4.2 Implement speech solutions](#4-2-implement-speech-solutions) (21)
    - [4.2.1 Implement workflows to convert speech to text and text to speech for agentic interactions](#4-2-1-implement-workflows-to-convert-speech-to-text-and-text-to-speech-for-agentic-interactions) (8)
    - [4.2.2 Integrate speech as an agent modality, including custom speech models](#4-2-2-integrate-speech-as-an-agent-modality-including-custom-speech-models) (10)
    - [4.2.3 Enable multimodal reasoning from audio inputs](#4-2-3-enable-multimodal-reasoning-from-audio-inputs) (1)
    - [4.2.4 Translate speech into other languages by using language models and Foundry Tools](#4-2-4-translate-speech-into-other-languages-by-using-language-models-and-foundry-tools) (2)
- [5 Implement information extraction solutions (10–15%)](#5-implement-information-extraction-solutions-10-15) (28)
  - [5.1 Build retrieval and grounding pipelines](#5-1-build-retrieval-and-grounding-pipelines) (12)
    - [5.1.1 Ingest and index content, such as documents, images, audio, and video](#5-1-1-ingest-and-index-content-such-as-documents-images-audio-and-video) (1)
    - [5.1.2 Configure semantic search, hybrid search, and vector search for grounding](#5-1-2-configure-semantic-search-hybrid-search-and-vector-search-for-grounding) (3)
    - [5.1.3 Implement enrichment by using custom or built-in skills for text, images, and layout](#5-1-3-implement-enrichment-by-using-custom-or-built-in-skills-for-text-images-and-layout) (7)
    - [5.1.4 Configure RAG ingestion flow, including documents and using optical character recognition (OCR)](#5-1-4-configure-rag-ingestion-flow-including-documents-and-using-optical-character-recognition-ocr) (1)
    - [5.1.5 Connect retrieval pipelines directly to workflows and agent tools](#5-1-5-connect-retrieval-pipelines-directly-to-workflows-and-agent-tools) (0)
  - [5.2 Extract content from documents](#5-2-extract-content-from-documents) (16)
    - [5.2.1 Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction](#5-2-1-extract-information-by-using-multimodal-pipelines-that-combine-ocr-layout-analysis-and-field-extraction) (8)
    - [5.2.2 Produce clean, grounded representations to use with agents and RAG by using Content Understanding](#5-2-2-produce-clean-grounded-representations-to-use-with-agents-and-rag-by-using-content-understanding) (2)
    - [5.2.3 Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding](#5-2-3-implement-analyzers-for-generating-structured-or-markdown-outputs-for-downstream-reasoning-by-using-content-understanding) (6)

  </details>

  <details>
<summary><h1>1 Plan and manage an Azure AI solution (25–30%)</h1></summary>
<details>
<summary><h2>1.1 Choose the appropriate Foundry services for generative AI and agents</h2></summary>
<details>
<summary><h3>1.1.1 Choose an appropriate model for each task, including large language models (LLMs), small language models, multimodal models, and Foundry Tools</h3></summary>

#### Questions


QA-001
---
You have a Microsoft Foundry project.
You plan to build a customer support solution that contains an agent. The solution must meet the following requirements:
Provide accurate, context-aware responses grounded in internal product documentation stored in Azure AI Search.
Require deep, multi-step reasoning across long contexts.
Generate detailed natural language responses.
Which type of model should you use to power the agent?

A. a multimodal model

B. a small language model (SLM)

C. a key phrase extraction model

> D. a large language model (LLM) Most Voted



QA-002
---
Which model benchmark indicates the model's ability to process prompts and return comprehensive responses quickly?

- A. Quality index
- B. Cost
- C. Throughput **(Correct)**

</details>
<details>
<summary><h3>1.1.2 Choose the appropriate Foundry services for generative tasks, grounding, vector search, agent workflows, or multimodal processing</h3></summary>

#### Questions


QA-003
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to recommend a solution to support the planned changes and technical requirements for Agent1 to use the product information stored in storage1.
What should you include in the recommendation?

A. Azure Translator in Foundry Tools

B. Grounding with Bing Search

> C. Azure AI Search Most Voted

D. Azure Document intelligence in Foundry Tools


QA-004
---
Which component of Microsoft Foundry provides pre-built services for common AI tasks?

- A. Foundry Tools **(Correct)**
- B. Foundry Models
- C. Foundry IQ

</details>
<details>
<summary><h3>1.1.3 Choose an appropriate method for retrieval and indexing</h3></summary>

#### Questions


QA-005
---
You have a chat app in a Microsoft Foundry project and an Azure AI Search vectorized index.
You need to connect to the index to meet the following requirements:
Complex questions must retrieve information from multiple chunks.
Multi-turn conversations must influence retrieval planning.
Retrievals must run in parallel to reduce latency.
Which retrieval approach should you use?

A. iterative retrieval

> B. agentic Retrieval Augmented Generation (RAG) Most Voted

C. chain of thought

D. classic Retrieval Augmented Generation (RAG)


QA-006
---
You have a Microsoft Foundry project.

You need to deploy a model from the model catalog to support a search solution for internal policy documents. The model must generate vector representations of the text in the documents and of user queries.

Which type of model should you use?

> A. an embedding model

B. an image generation model

C. a large language model (LLM)

D. a small language model (SLM)



</details>
<details>
<summary><h3>1.1.4 Choose appropriate memory, tool, and knowledge integration services for agent solutions</h3></summary>

#### Questions


QA-007
---
You are planning a Microsoft Foundry project named Project1 that will contain multiple agents. Each agent will access the same Azure AI Search resource.
You need to recommend a solution to centrally manage the Azure AI Search credentials within Project1. The solution must be implemented across all the agents.
What should you recommend?

A. Enable role-based access control (RBAC) for the Azure AI Search resource.

B. Disable key-based access control on the Azure AI Search resource.

>C. Add a connection to the Azure AI Search resource.

D. Create a managed private endpoint that connects to the Azure AI Search resource.
 
Correct Answer: C 🗳️
Community vote distribution
C (100%)


QA-008
---

This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.

To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.

A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.


To start the case study -

To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.


Overview -


Company Information -

Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.


Existing Environment -


Identity Environment -

Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.

Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.

The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.

Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.


Generative Environment -

Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.


Project1 -

Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.

Agent1 has the following configurations:

• Agent1 uses a base model deployment.
• A safety evaluation pipeline is NOT enabled.
• Tool invocation approval workflows are NOT enabled.
• Conversation memory constraints are NOT configured.

Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.

Project1 is deployed to an Azure region located in the European Union (EU).

Agent1Dev Team will use Project1 to optimize and maintain Agent1.


Project2 -

Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.

Development of the solution is incomplete.


Data Environment -

Contoso stores product-related information in Azure resources that support AI applications.

The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.

The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.


Problem Statements -

Contoso identifies the following issues:

• Agent1 has only general knowledge of the Contoso products.
• A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
• Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
• The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.


Requirements -


Planned Changes -

Contoso plans to implement the following changes:

• Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
• Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
• Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
• Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
• Complete the development of the video creation solution.


Technical Requirements -

Contoso identifies the following technical requirements:

• The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
• The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
• Responses generated by using the product sheet information must be relevant, complete, and accurate.
• Agent1 must be able to use the product sheets to answer natural language questions about product details.
• The model version used by Agent1 must remain consistent to ensure stable responses.
• The data processed by the model must remain within the EU.

Security and Compliance Requirements

Contoso identifies the following security and compliance requirements:

• API keys must NOT be used to access Foundry-deployed models.
• Access to the Azure resources must follow the principle of least privilege.
• The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
• Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
• Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
• Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
• The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.


Business Requirements -

Contoso identifies the following business requirements:

• Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
• Agent1 must answer questions only about the products sold by Contoso.


You need to configure personalized user interactions for Agent1. The solution must meet the business requirements.

What should you include in the solution?

A. knowledge

> B. memory

C. guardrails

D. tools


QA-009
---
Which data source option provides real-time access to SharePoint content with Microsoft 365 governance?

- A. SharePoint Indexed, which pre-processes SharePoint content into Azure AI Search.
- B. SharePoint Remote, which queries SharePoint sites and libraries in real-time. **(Correct)**
- C. Azure Blob Storage, which connects to SharePoint files stored as blobs.


QA-010
---
What is the purpose of scoring profiles in Foundry IQ knowledge bases?

- A. To encrypt sensitive fields and protect confidential information during retrieval.
- B. To boost specific fields or attributes so more important results surface first. **(Correct)**
- C. To configure how documents are chunked and embedded for semantic search.

</details>
</details>
<details>
<summary><h2>1.2 Set up AI solutions in Foundry</h2></summary>
<details>
<summary><h3>1.2.1 Design Azure infrastructure for AI apps and agent-based solutions</h3></summary>

#### Questions


QA-011
---
HOTSPOT

You plan to create a Microsoft Foundry project named Project1 that will contain an agent and use an Azure key vault named KV1.

You need to configure a connection from Project1 to KV1.

How should you complete the Bicep code? To answer, select the appropriate options in the answer area?

NOTE: Each correct selection is worth one point.

![alt text](image-53.png)

 
> Correct Answer: ![alt text](image-54.png)


QA-012
---
HOTSPOT

You have an Azure subscription.

You need to create a new resource that will generate fictional stores in response to user prompts. The solution must ensure that the resource uses a customer-managed key to protect data.

How should you complete the script? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-60.png)

 
> Correct Answer: ![alt text](image-61.png)


QA-013
---
HOTSPOT

You need to create a new resource that will be used to perform sentiment analysis and optical character recognition (OCR). The solution must meet the following requirements:

• Use a single key and endpoint to access multiple services.
• Consolidate billing for future services that you might use.
• Support the use of Azure Vision in Foundry Tools in the future.

How should you complete the HTTP request to create the new resource? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.
 
Correct Answer:


QA-014
---
Which web portal should you use to work with assets in a Microsoft Foundry project?

- A. The Azure portal
- B. Microsoft Copilot
- C. The Microsoft Foundry portal **(Correct)**

</details>
<details>
<summary><h3>1.2.2 Choose appropriate deployment options</h3></summary>

#### Questions


QA-015
---
HOTSPOT -

This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to configure the model deployment for Agent1 to meet the technical requirements.
What should you configure? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-2.png)

 
> Correct Answer: ![alt text](image-3.png)


QA-016
---
You have a Microsoft Foundry project.

You need to deploy a model from the model catalog to support real-time inference. The solution must meet the following requirements:

• Use key-based authentication.
• Support real-time REST API access.
• NOT consume the vCPU quota of the virtual machines in the Azure subscription.

Which type of deployment should you use?

A. serverless API

B. batch

C. self-hosted container

> D. standard


QA-017
---
Which deployment type in Microsoft Foundry is best for general use while offering the largest quota?

- A. Data Zone Batch
- B. Global Standard **(Correct)**
- C. Developer

</details>
<details>
<summary><h3>1.2.3 Configure model and agent deployments</h3></summary>

#### Questions

</details>
<details>
<summary><h3>1.2.4 Integrate Foundry projects with continuous integration and continuous deployment (CI/CD) pipelines</h3></summary>

#### Questions


QA-018
---
HOTSPOT -
You have a Microsoft Foundry project that contains an agent.
You use a GitHub Actions workflow for CI/CD.
You need to configure the workflow to automatically evaluate the agent when a pull request (PR) is created and prevent branches from merging if the evaluation results do NOT meet the defined thresholds.
How should you configure the workflow? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-30.png)
 
> Correct Answer: ![alt text](image-31.png)


QA-019
---
You have a Microsoft Foundry project that contains an agent and uses a GitHub repository. The repository contains a YAML file named File1 that defines the evaluation settings of the agent.

You need to create a GitHub Actions workflow that runs the evaluation defined in File1 when a pull request (PR) is opened. How should you configure the workflow?

A. Set project-endpoint to the endpoint of the project.

> B. Set evaluation-config to the path of the YAML file.

C. Set model-deployment-name to the deployed model.

D. Set tenant-id to the Microsoft Entra tenant ID




</details>
</details>
<details>
<summary><h2>1.3 Manage, monitor, and secure AI systems</h2></summary>
<details>
<summary><h3>1.3.1 Manage quotas, scaling, rate limits, and cost footprints for model and agent workloads</h3></summary>

#### Questions


QA-020
---
HOTSPOT -
You have a Microsoft Foundry project that contains an internal Q&A agent.
Users report the following issues when they ask the agent questions:
An increase in the following response: “No relevant information found”
Periodic HTTP 429 rate limit exceeded errors during peak hours
You need to identify whether each issue is caused by model unavailability, resource limits, or inference failures.
What should you do? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-18.png)

 
Correct Answer: ![alt text](image-19.png)


QA-021
---
You have a customer support agent built by using the Microsoft Foundry Agent Service. The agent calls an Azure OpenAI model deployment.
During load testing, calls intermittently fail and return an HTTP 429 rate limit exceeded error.
You need to handle throttling to reduce call failures and improve reliability under load. The solution must remain within the service and model limits.
What should you do?

A. Create a new thread and retry the calls immediately.

B. Reduce the number of registered tools.

> C. Implement a retry policy that uses exponential backoff and jitter. Most Voted
D. Spit uploaded content into smaller files.


QA-022
---
DRAG DROP


You have a Microsoft Foundry project that contains an agent. The agent uses threads and file uploads and calls an Azure OpenAI model deployment.

During load testing, calls intermittently fall and return an HTTP 429 rate limit exceeded error. Some user uploads fail and generate an HTTP 400 file size exceeded error.

You need to mitigate the errors and reduce call failures. The solution must remain within the service and model limits.

What should you do to resolve each error? To answer, drag the appropriate actions to the correct errors. Each action may be used once, more than once or not at all. You may need to drag the split bar between panes or scroll to view content.

NOTE: Each comet selection is worth one point.

![alt text](image-51.png)

 
> Correct Answer: ![alt text](image-52.png)



</details>
<details>
<summary><h3>1.3.2 Monitor model performance, drift, safety events, and grounding quality</h3></summary>

#### Questions


QA-023
---
You have a Microsoft Foundry project that uses Azure AI Search to ground an agent in internal documentation.
After a recent content update, users report that the agent’s answers have become less accurate.
You need to identify whether the retrieved content is negatively influencing the model’s generated responses.
Which observability signal should you review?

A. indexer status and failure history

B. latency breakdown traces

C. prediction drift metrics

> D. groundedness evaluation metrics


</details>
<details>
<summary><h3>1.3.3 Monitor data ingestion quality, search index health, and relevance performance</h3></summary>

#### Questions

</details>
<details>
<summary><h3>1.3.4 Configure security, including managed identity, private networking, keyless credentials, and role policies</h3></summary>

#### Questions


QA-024
---
You have a Microsoft Foundry project that contains a model deployment.
You have an application that calls the deployment by using the Azure OpenAI v1 API and DefaultAzureCredential.
The developers at your company receive HTTP 403 errors when they send inference requests, even after running az login.
You need to ensure that the developers can perform model inference. The solution must follow the principle of least privilege.
Which role-based access control (RBAC) role should you assign to the developers?

A. Cognitive Services User

> B. Cognitive Services OpenAI User Most Voted

C. Contributor

D. Cognitive Services Data Reader


QA-025
---
HOTSPOT

Case Study


This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.

To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.

A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.


To start the case study


To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.


Overview



Company Information


Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.


Existing Environment



Identity Environment


Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.

Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.

The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.

Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.


Generative Environment


Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.


Project1


Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.

Agent1 has the following configurations:

• Agent1 uses a base model deployment.
• A safety evaluation pipeline is NOT enabled.
• Tool invocation approval workflows are NOT enabled.
• Conversation memory constraints are NOT configured.

Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.

Project1 is deployed to an Azure region located in the European Union (EU).

Agent1Dev Team will use Project1 to optimize and maintain Agent1.


Project2


Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.

Development of the solution is incomplete.


Data Environment


Contoso stores product-related information in Azure resources that support AI applications.

The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.

The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.


Problem Statements


Contoso identifies the following issues:

• Agent1 has only general knowledge of the Contoso products.
• A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
• Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
• The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.


Requirements



Planned Changes


Contoso plans to implement the following changes:

• Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
• Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
• Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
• Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
• Complete the development of the video creation solution.


Technical Requirements


Contoso identifies the following technical requirements:

• The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
• The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
• Responses generated by using the product sheet information must be relevant, complete, and accurate.
• Agent1 must be able to use the product sheets to answer natural language questions about product details.
• The model version used by Agent1 must remain consistent to ensure stable responses.
• The data processed by the model must remain within the EU.

Security and Compliance Requirements

Contoso identifies the following security and compliance requirements:

• API keys must NOT be used to access Foundry-deployed models.
• Access to the Azure resources must follow the principle of least privilege.
• The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
• Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
• Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
• Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
• The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.


Business Requirements


Contoso identifies the following business requirements:

• Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
• Agent1 must answer questions only about the products sold by Contoso.


You need to ensure that Agent1Dev Team can access Agent1. The solution must meet the security and compliance requirements.

How should you complete the Python code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-36.png)

 
Correct Answer: ![alt text](image-37.png)


QA-026
---
HOTSPOT


You have a Microsoft Foundry project that contains an agent.

The agent uses a stored access key to retrieve secrets from an Azure key vault, which violates a keyless-credentials requirement.

You need to ensure that the agent can retrieve the secrets. The solution must follow the principle of least privilege.

What should you configure? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-46.png)

 
> Correct Answer: ![alt text](image-47.png)


QA-027
---
You have an Azure subscription that contains an Azure App Service app named App1.

You provision a Microsoft Foundry Service resource named CSAccount1.

You need to configure App1 to access CSAccount1. The solution must minimize administrative effort.

What should you use to configure App1?

> A. the endpoint URI and subscription key

B. the endpoint URI and an OAuth token

C. the endpoint URI and a shared access signature (SAS) token

D. a system assigned managed identity and an X.509 certificate


QA-028
---
DRAG DROP


You have a web app that uses Azure AI Search.

When reviewing activity you see greater than expected search query volumes. You suspect that the query key is compromised.

You need to prevent unauthorized access to the search endpoint and ensure that users only have read only access to the documents collection. The solution must minimize app downtime.

Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order.


![Original Question 112 drag-and-drop answer area](image-69.png)

<section class="exam-interaction html-recreation" aria-label="HTML recreation of Question 112 drag-and-drop answer area">
  <p class="replica-label">HTML recreation of the question exhibit</p>
  <div class="exam-actions">
    <h3>Actions</h3>
    <div class="exam-choice">Regenerate the primary admin key</div>
    <div class="exam-choice">Regenerate the secondary admin key</div>
    <div class="exam-choice">Change the app to use the secondary admin key</div>
    <div class="exam-choice">Add a new query key</div>
    <div class="exam-choice">Change the app to use the new query key</div>
    <div class="exam-choice">Delete the compromised query key</div>
  </div>
  <div class="exam-answer-area">
    <h3>Answer Area</h3>
    <div class="exam-slot"><span>1</span><span class="exam-drop-target">Drop the first action here</span></div>
    <div class="exam-slot"><span>2</span><span class="exam-drop-target">Drop the second action here</span></div>
    <div class="exam-slot"><span>3</span><span class="exam-drop-target">Drop the third action here</span></div>
  </div>
</section>
 
> **Correct Answer:**
>
> 1. Add a new query key.
> 2. Change the app to use the new query key.
> 3. Delete the compromised query key.

![Original recorded Question 112 answer image](image-70.png)

<section class="answer-correction" aria-label="Corrected HTML answer for Question 112">
  <p class="replica-label">Corrected HTML answer</p>
  <ol>
    <li>Add a new query key.</li>
    <li>Change the app to use the new query key.</li>
    <li>Delete the compromised query key.</li>
  </ol>
</section>


QA-029
---
You are developing an application that will use Azure AI Search for internal documents.

You need to implement document-level filtering for Azure AI Search.

Which three actions should you include in the solution? Each correct answer presents part of the solution.

NOTE: Each correct selection is worth one point.

> A. Add allowed groups to each index entry

B. Create one index per group.

C. Send access tokens from Microsoft Entra ID, with the search request.

D. Retrieve all the groups.

> E. Retrieve the group memberships of the user
> F. Supply the groups as a filter for the search requests


QA-030
---
What authentication method is used when connecting the Azure Language MCP server to a Foundry agent?

- A. OAuth 2.0 authentication with a client certificate and tenant ID.
- B. Key-based authentication using the Ocp-Apim-Subscription-Key credential. **(Correct)**
- C. Anonymous access that requires no authentication or credentials.

</details>
</details>
<details>
<summary><h2>1.4 Implement responsible AI across generative AI and agentic systems</h2></summary>
<details>
<summary><h3>1.4.1 Configure safety filters, guardrails, risk detection, and content moderation</h3></summary>

#### Questions


QA-031
---
What capability of Microsoft Foundry helps mitigate harmful content generation at the Safety System level?

- A. DALL-E model support
- B. Fine-tuning
- C. Guardrails **(Correct)**

</details>
<details>
<summary><h3>1.4.2 Apply responsible AI instrumentation, including evaluators, safety evaluations, and explanation tooling</h3></summary>

#### Questions


QA-032
---
HOTSPOT


You have a Microsoft Foundry project that contains a customer support application.

You create an evaluation named Run1 that has the following configurations:

• Includes risk and safety metrics
• Includes the protected material evaluation
• Includes harmful content metrics that use a medium severity threshold

You create an evaluation named Run2 that has the following configurations:

• Includes risk and safety metrics
• Includes the protected material evaluation
• Includes harmful content metrics that use a high severity threshold

You run both evaluations against a dataset named DB1 and receive the following results:

• Content harm defect rate of Run1: 12%
• Content harm defect rate of Run2: 4%
• Protected material evaluation of Run1: 6%
• Protected material evaluation of Run1: 6%

You start a fine-tuning job by using DB1. The job fails during automatic RAI checks for multiple content harm types.

You discover that the content filtering configuration is set to high severity.

For each of the following statements, select Yes if the statement is true. Otherwise, select No.

NOTE: Each correct selection is worth one point.

![alt text](image-48.png)

 
> Correct Answer:


QA-033
---
You are developing a new sales system that will process user-generated video and text from a public-facing website.

You plan to notify users that their data has been processed by the sales system.

Which responsible AI principle does this help meet?

A. fairness

> B. transparency

C. inclusiveness

D. reliability and safety


QA-034
---
Why should you consider creating an AI Impact Assessment when designing a generative AI solution?

- A. To make a legal case that indemnifies you from responsibility for harms caused by the solution
- B. To document the purpose, expected use, and potential harms for the solution **(Correct)**
- C. To evaluate the cost of cloud services required to implement your solution


QA-035
---
Why should you consider a phased delivery plan for your generative AI solution?

- A. To enable you to gather feedback and identify issues before releasing the solution more broadly **(Correct)**
- B. To eliminate the need to map, measure, mitigate, and manage potential harms
- C. To enable you to charge more for the solution

</details>
<details>
<summary><h3>1.4.3 Implement auditing through trace logging, provenance metadata, and approval workflows</h3></summary>

#### Questions


QA-036
---
DRAG DROP


You have a Microsoft Foundry project that contains a multi-agent solution. The agents use tool calling to query internal systems.

You need to implement responsible AI auditing to meet the following requirements:

• Capture all the nested operations across the entire agent run.
• Record tool invocation arguments and retuned results as metadata.

What should you use for each requirement? To answer, drag the appropriate options to the correct targets Each option may be used once, more than once, or not at all. You may need o dag the split bar between panes or scroll to view content.

NOTE: Each correct selection is worth one point.

![alt text](image-49.png)

 
> Correct Answer: ![alt text](image-50.png)


</details>
<details>
<summary><h3>1.4.4 Govern agent behavior with oversight modes, constraints, and tool-access controls</h3></summary>

#### Questions


QA-037
---
HOTSPOT -
You have a Microsoft Foundry project that contains an agent.
The agent uses tools to retrieve internal content and call external APIs. The agent is configured to let the model decide when to call the tools.
You need to publish the agent for a compliance workflow. The solution must meet the following requirements:
Each workflow run must include a retrieval step before generating a response.
Tool calls must authenticate by using the published agent’s own identity.
Tool access must use an identity isolated from other project resources.
Tool access must use support audit tracing.
What should you do? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-20.png)

 
> Correct Answer: ![alt text](image-21.png)


QA-038
---
Which of the following is NOT a recommended security practice for AI agents?

- A. Using role-based access controls
- B. Implementing prompt filtering and validation
- C. Maintaining comprehensive logging and traceability
- D. Allowing agents unrestricted access to all enterprise data **(Correct)**

</details>
</details>
</details>
<details>
<summary><h1>2 Implement generative AI and agentic solutions (30–35%)</h1></summary>
<details>
<summary><h2>2.1 Build generative applications by using Foundry</h2></summary>
<details>
<summary><h3>2.1.1 Deploy and consume LLMs, small models, code models, and multimodal models</h3></summary>

#### Questions

</details>
<details>
<summary><h3>2.1.2 Implement retrieval-augmented generation (RAG) in an application</h3></summary>

#### Questions


QA-039
---
When should you use Retrieval Augmented Generation (RAG) instead of relying on prompt engineering alone?

- A. When you want the model to respond in a consistent style and format.
- B. When the model needs access to domain-specific or current data that it wasn't trained on. **(Correct)**
- C. When you want to reduce the length of prompts sent to the model.


QA-040
---
What is the primary advantage of Retrieval Augmented Generation (RAG) over simple AI agents?

- A. RAG eliminates the need for large language models by relying entirely on document retrieval.
- B. RAG enables agents to ground responses in current organizational information and provide source transparency. **(Correct)**
- C. RAG automatically retrains the language model whenever organizational documents change.

</details>
<details>
<summary><h3>2.1.3 Design workflows, tool-augmented flows, and multistep reasoning pipelines</h3></summary>

#### Questions


QA-041
---
HOTSPOT -
You have a Microsoft Foundry project that contains a workflow for a customer support triage process.
You have an Ask a question node that stores user responses in a local variable named Var01.
You need to create the following Power Fx expressions:
An if/else condition expression that ensures that Var01 contains a value
A Send message expression that returns the stored user response in uppercase
How should you configure the expressions? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-10.png)

 
> Correct Answer: ![alt text](image-11.png)


QA-042
---
Which type of node in a Foundry workflow is used to invoke an AI agent?

- A. Logic node
- B. Agent node **(Correct)**
- C. Data transformation node


QA-043
---
Which node type would you use to handle multiple tickets in a workflow without duplicating nodes?

- A. If/Else node
- B. For-Each node **(Correct)**
- C. Send message node


QA-044
---
Which of the following best describes how structured agent outputs are used in workflows?

- A. They are ignored once generated, since agents always handle routing automatically
- B. They provide predictable data that can be stored in variables, evaluated with conditions, and trigger workflow steps **(Correct)**
- C. They replace the need for loops and If/Else nodes

</details>
<details>
<summary><h3>2.1.4 Evaluate models and apps, including detecting fabrications, relevance, quality, and safety</h3></summary>

#### Questions


QA-045
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to recommend a solution to assess the responses generated by Agent1 when the agent uses the product information stored in storage1. The solution must meet the technical requirements.
What should you include in the recommendation?

A. a Retrieval Augmented Generation (RAG) evaluator

B. a custom guardrail

C. model fine-tuning

> D. a groundedness evaluator Most Voted


QA-046
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You run an evaluation flow that scores responses for completeness and blocks responses that fall below a defined threshold.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-047
---
You have a Microsoft Foundry project that contains a Retrieval Augmented Generation (RAG) chat solution used by customer support agents.

You are adding an automated pre-production evaluation step to a CI/CD pipeline named Pipeline1. The evaluation will run against a labeled test dataset that contains support questions and the expected grounding context.

You need to ensure that Pipeline1 fails if unsupported content or a retrieval mismatch exceeds a defined threshold:
• responses include claims not supported by the retrieved source content
• retrieved source content does not align with the labeled expected context

Which two built-in evaluators should you use in Pipeline1? Each correct answer presents pat of the solution.

NOTE: Each correct selection is worth one point.

> A. Retrieval

B. Fluency

C. Coherence

> D. Groundedness

E. Response Completeness


QA-048
---
HOTSPOT


You have a Microsoft Founcy project that contains a Retrieval Augmented Generation (RAG) solution.

You need to run a pre-production evaluation by using labeled CSV dataset that contains the query, context, response and ground truth. The evaluation must measure the following:

• Whether responses address the user query
• Whether responses are supported by the provided context
• Whether responses contain sensitive or proprietary information

Which AI quality evaluation metrics should you use? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-38.png)

 
> Correct Answer: ![alt text](image-39.png)


QA-049
---
You plan to configure an evaluation in Microsoft Foundry for a Retrieval Augmented Generation (RAG) chat app.

You need to provide scores for groundedness, relevance, and harmful content categories.

Which two evaluation categories can you use? Each correct answer presents a complete solution.

NOTE: Each correct selection is worth one point.

> A. risk and safety metrics

B. fluency evaluator

C. similarity evaluators

D. AI quality (NLP) metrics

> E. AI quality (AI assisted) metrics


QA-050
---
Which evaluation metric measures linguistic correctness and natural language quality?

- A. Fluency **(Correct)**
- B. Groundedness
- C. Relevance

</details>
<details>
<summary><h3>2.1.5 Integrate generative workflows into applications by using Foundry SDKs and connectors</h3></summary>

#### Questions


QA-051
---
HOTSPOT -
You have a Python application named App1 that integrates with a Microsoft Foundry project named Project1.
You need to ensure that App1 meets the following requirements:
Authenticates by using a Microsoft Entra managed identity
Sends prompts to a deployed model by using the Azure OpenAI Responses API
How should you complete the Python code? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-8.png)

 
> Correct Answer: ![alt text](image-9.png)


QA-052
---
Which endpoint offers the broadest support for OpenAI APIs with Foundry Models?

- A. The Foundry project endpoint
- B. The Azure OpenAI endpoint **(Correct)**
- C. The Foundry Tools endpoint


QA-053
---
Which package must you install to use the Microsoft Foundry SDK in Python?

- A. Package `azure-foundry`
- B. Package `azure-ai-projects` **(Correct)**
- C. Package `microsoft-foundry-sdk`


QA-054
---
Which method do you use to generate responses with the Responses API?

- A. client.chat.completions.create()
- B. client.get\_response\_id()
- C. client.responses.create() **(Correct)**


QA-055
---
When building a Python client application, how do you reference a Foundry agent when calling the OpenAI Responses API?

- A. By passing the agent's API key as a request header to the endpoint.
- B. By specifying the agent name in the agent\_reference field in extra\_body. **(Correct)**
- C. By passing the agent's endpoint URL as the model parameter value.

</details>
<details>
<summary><h3>2.1.6 Configure an application to connect to a Foundry project</h3></summary>

#### Questions


QA-056
---
You are building a web app named App1 that generates responses by using a model deployed to a Microsoft Foundry project named Project1.
Before sending the prompts to the model, App1 must retrieve documents by using Azure AI Search.
You need to integrate Project1 and App1. The solution must meet the following requirements:
Multiple client applications must use the same search configuration.
A security policy must prevent key-based authentication.
Administrative effort must be minimized.
What should you do?

A. Create a custom HTTP connection in Foundry and manually configure Azure AI Search endpoints per application.

> B. Configure an Azure AI Search connection in Project1 and reference the connection in each application. Most Voted

C. Call Azure AI Search directly from each application by using Microsoft Entra authentication.

D. Enable a managed identity for each application and call Azure AI Search directly.


QA-057
---
Which extension should you use in Visual Studio Code to work with Foundry projects?

- A. Python extension for Visual Studio Code
- B. GitHub Copilot
- C. Foundry Toolkit for Visual Studio Code **(Correct)**

</details>
</details>
<details>
<summary><h2>2.2 Build agents by using Foundry</h2></summary>
<details>
<summary><h3>2.2.1 Define agent roles, goals, conversation-tracking approach, and tool schemas</h3></summary>

#### Questions


QA-058
---
What are the key steps to create a Microsoft Foundry Agent using the Microsoft Agent Framework?

- A. Deploy a custom AI model before creating an agent definition in the Azure portal.
- B. Initialize the agent by defining a model in the `AgentThread` constructor.
- C. Create an `AzureAIAgentClient`, define a ChatAgent with instructions and tools, and create an `AgentThread` for conversations. **(Correct)**


QA-059
---
Which component in the Microsoft Agent Framework manages conversation state and stores messages?

- A. AgentThread **(Correct)**
- B. ChatAgent
- C. AzureAIAgentClient

</details>
<details>
<summary><h3>2.2.2 Build agents that integrate retrieval, function-calling, and conversation memory</h3></summary>

#### Questions


QA-060
---
You have a Microsoft Foundry project that contains an agent. The agent has a Model Context Protocol (MCP) tool that queries a knowledge base stored in Azure AI Search.
Some agent runs return answers from the base model without invoking the knowledge base, which results in responses without grounded citations.
You are provided with the following code snippet that runs the agent.
image16
You need to add the correct tool _choice parameter to the code to deterministically force the agent to invoke the MCP tool on each run.
What should you add?

> A. tool_choice={“required”} Most Voted

B. tool_choice={“auto”}

C. tool_choice={“type”:“knowledge_base”}

D. tool_choice ={“type”:“mcp”}


QA-061
---
You have a customer support agent that uses the Microsoft Foundry Agent Service.
Sometimes, customers return to a session days later to continue the same support case, and the agent must resume with the full historical context. The agent must provide the following:
Multi-turn continuity within the session
Cross-session continuity for the same case
Access to the full interaction history, including user messages, agent messages, tool calls, and tool outputs
You need to ensure that the agent automatically reloads the complete history on each new turn.
What should you do?

> A. Create and reuse a conversation by storing the conversation’s ID and supplying the ID on subsequent requests. Most Voted

B. Persist only the final model response stored in the client application and prepend the response to future prompts.

C. Enable memory summarization on the agent definition to persist the context automatically.


QA-062
---
HOTSPOT -
You need to recommend a plan to create a customer support agent by using the Microsoft Foundry Agent Service. The agent must meet the following requirements:
Retain user preferences across multiple conversations.
Enable users to provide contextual grounding by directly uploading documents during a chat.
Which Foundry capability should you recommend for each requirement? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-28.png)

 
> Correct Answer: ![alt text](image-29.png)


QA-063
---
You have a Microsoft Foundry project that contains a support-ticket triage agent built by using the Foundry Agent Service.

The agent uses tool to classify the ticket type and sot the ticket priority.

Sometimes, the same support case continues across multiple sessions over several days.

You need to persist state by using a durable ID to ensure that the agent can automatically reuse the full interaction history. The solution must preserve previous user messages, tool calls and tool outputs across turns and sessions.

Which runtime component should you use?

A. output item

B. agent

> C. conversation

D. response


QA-064
---
You have a Microsoft Foundry project that contains an agent for a customer support chat app. The agent uses a memory store and a memory search tool.

You need to ensure that the conversation history does NOT persist across separate sessions.

To what should you set the scope of the memory tool?

> A. session

B. {{$conversationId}}

C. {{$userId}}

D. global
 
Correct Answer: A 🗳️


QA-065
---
DRAG DROP
-

You have a Microsoft Foundry project that contains an agent.

You need to enable long-term memory to ensure that the agent can recall user preferences across separate conversations. Stored memories must be isolated per authenticated user without the client application manually generating user IDs.

How should you complete the Python code? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all.

NOTE: Each correct selection is worth one point.

![alt text](image-40.png)

 
> Correct Answer: ![alt text](image-41.png)


QA-066
---
HOTSPOT
-

You have a Microsoft Foundry project.

You need to create a customer support agent that meets the following requirements:
• Grounds responses only in company policy documents stored in curated repositories
• Retains customer preferences across separate chat sessions

How should you configure the agent? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-55.png)

 
> Correct Answer: ![alt text](image-56.png)


QA-067
---
What is the primary benefit of using Microsoft Foundry Agent Service compared to building agents with standard APIs?

- A. It provides access to more powerful AI models
- B. It requires no Azure subscription
- C. It handles tool calling, state management, and infrastructure automatically **(Correct)**
- D. It only works with the Azure portal


QA-068
---
How does Microsoft Foundry Agent Service handle conversation state?

- A. By requiring developers to manually manage conversation history
- B. Through external database connections
- C. Through the Responses API which automatically manages conversation context **(Correct)**
- D. Using local file storage on the client device


QA-069
---
What happens when an agent determines it needs a tool to respond to a user request?

- A. The agent asks the user for permission to use the tool
- B. The agent stops processing and waits for developer input
- C. The agent automatically invokes the tool, processes results, and incorporates them into its response **(Correct)**
- D. The agent sends the request to a separate processing queue


QA-070
---
Why is it critical to specify retrieval behavior in agent instructions?

- A. Without proper instructions, agents might answer from training data instead of the knowledge base, provide unverifiable responses, or fail to cite sources. **(Correct)**
- B. Instructions determine the semantic ranking algorithm that Foundry IQ applies to search results.
- C. Instructions enable the agent to automatically update knowledge base content when it detects outdated information.

</details>
<details>
<summary><h3>2.2.3 Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions</h3></summary>

#### Questions


QA-071
---
You have a Microsoft Foundry project named Project1 that contains an agent. The agent uses an OpenAPI 3.0 specification to call an external weather service.
The weather service requires a key to be passed in an HTTP header. The key value is stored as a connection in Project1.
You need to ensure that the key value from the connection is included automatically whenever the OpenAPI tool is invoked.
What should you configure in the OpenAPI specification?

A. a header parameter defined for each operation

B. an Azure Key Vault connection

> C. an API key security scheme Most Voted

D. a Bearer token security scheme


QA-072
---
You have a Microsoft Foundry project named Project1 that contains the following:
An OpenAPI tool that calls an external API
A project connection named Connection1 that stores the API key of the external API
When an agent calls the OpenAPI tool, the API returns a 401 unauthorized error, and traces show that the API key header is NOT being sent.
You need to ensure that the OpenAPI tool automatically includes the API key from Connection1 on all requests.
What should you do?

A. Enable identity passthrough so that the tool uses the Microsoft Entra token of the caller.

B. Add the API key header manually to the OpenAPI specification.

C. Configure the tool to use the default connection of Project1.

> D. Connect the tool to Connection1. Most Voted


QA-073
---
DRAG DROP -
You have a Microsoft Foundry project that contains a deployed ticket-triage agent.
You discover that sometimes the agent responds without calling any tools, even when a tool is required.
You need to ensure that the agent calls a tool during execution.
How should you complete the Python code? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-22.png)

 
Correct Answer: ![alt text](image-23.png)


QA-074
---
DRAG DROP -
You have a Microsoft Foundry project that contains an agent used by the financial analysts at your company.
You need to optimize the agent workflow by providing additional data access and processing capabilities. The solution must meet the following requirements:
Ensure that the agent can perform calculations during conversations.
Ensure that the agent can access up-to-date information from public websites.
Ensure that the agent can retrieve information from documents uploaded directly to the agent.
What should you use for each requirement? To answer, drag the appropriate tools to the correct requirements. Each tool may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-24.png)

 
> Correct Answer: ![alt text](image-25.png)


QA-075
---
You have a Microsoft Foundry project that contains an agent. The agent uses two tools to perform the following actions:

• Use Azure AI Search to retrieve answers from a private product documentation index.
• Use the web search tool to retrieve public information on the internet.

You need to ensure that for a specific run, the agent deterministically retrieves information only from the internet.

To what should you set tool_choice?

> A. {“type”: “bing_grouding”}

B. {“type”: “azure_ai-search”}

C. “auto”

D. “required”


QA-076
---
Which tool should you use when a model needs to answer questions from your own uploaded policy documents?

- A. web\_search
- B. file\_search **(Correct)**
- C. code\_interpreter


QA-077
---
In a function-calling workflow, what should your application do after the model returns a function\_call item?

- A. Wait for the model to run the function automatically
- B. Run the function in your code and send a function\_call\_output back to the model **(Correct)**
- C. Convert the function call into a web\_search request


QA-078
---
Which statement about the code\_interpreter tool is correct?

- A. It can run Python code in a sandboxed runtime to help solve tasks **(Correct)**
- B. It can browse external websites directly during code execution
- C. It only supports file uploads and can't perform calculations


QA-079
---
What are custom tools, and how can they help you develop effective agents with Microsoft Foundry Agent Service?

- A. Callable functions that an agent can use to extend its capabilities. **(Correct)**
- B. Extensions for Visual Studio Code that make it easier to create and deploy agents.
- C. Fine-tuned models that the agent can use to generate custom output.


QA-080
---
You need to integrate functionality from an OpenAPI 3.0-based web service into an agent solution. What should you do?

- A. Add the JSON schema of the web service to the agent's instructions.
- B. Rewrite the web service as a Python function and hard-code it in your agent app.
- C. Add the web service as an OpenAPI specification tool to the agent definition **(Correct)**


QA-081
---
Your agent application code includes a local function that you want the agent to call. What kind of tool should you add to the agent's definition?

- A. Function calling **(Correct)**
- B. Code interpreter
- C. Azure Functions


QA-082
---
What role does the MCP server play in the MCP agent tool integration?

- A. Runs the AI agent and processes user prompts directly.
- B. Manages network connections between multiple agents.
- C. Hosts tool definitions and makes them available for discovery by the client. **(Correct)**


QA-083
---
How does an MCP client retrieve available tools from the MCP server?

- A. By calling `session.list_tools()` to get the current tool catalog. **(Correct)**
- B. By reading a static JSON file from the server directory.
- C. By subscribing to server events via a WebSocket connection.


QA-084
---
Why should MCP tools be wrapped in async functions on the client-side?

- A. To allow the agent to wait for user input.
- B. To enable asynchronous invocation so the agent can call tools without blocking. **(Correct)**
- C. To convert the functions into REST API endpoints automatically.


QA-085
---
What is the main difference between shared scope and organization scope when publishing an agent?

- A. Shared scope requires more Azure resources
- B. Organization scope requires admin approval before the agent is available to all users **(Correct)**
- C. Shared scope only works in the Foundry playground
- D. Organization scope provides better agent performance


QA-086
---
What is Microsoft Work IQ?

- A. A machine learning model for workplace analytics
- B. A CLI and MCP server that connects AI agents to Microsoft 365 data **(Correct)**
- C. A replacement for Microsoft Teams
- D. A Visual Studio Code extension for building agents


QA-087
---
When should you consider using the Microsoft 365 Agents Toolkit instead of direct publishing from Foundry?

- A. For all production deployments
- B. When you need custom SSO, middleware logic, or multi-environment deployment **(Correct)**
- C. When publishing to shared scope
- D. When your agent doesn't use any tools


QA-088
---
How do you add custom functionality to a Microsoft Foundry Agent in the Microsoft Agent Framework?

- A. Configure custom functions in the Azure portal and link them to the agent through connection strings.
- B. Create Python functions with proper type annotations and descriptions, then pass them to the ChatAgent's tools parameter. **(Correct)**
- C. Modify the AI model's architecture to integrate the custom functionality directly.


QA-089
---
What is the primary role of the Azure Language MCP server?

- A. To train and fine-tune custom language models for use by AI agents.
- B. To expose Azure Language text analysis capabilities as MCP tools for agents. **(Correct)**
- C. To deploy and manage large language models in an Azure subscription.


QA-090
---
How does an agent determine which Azure Language MCP tool to call when processing a user's prompt?

- A. The developer writes routing logic to direct each prompt to a specific tool.
- B. The agent matches the prompt to tool descriptions received from the MCP server. **(Correct)**
- C. The MCP server analyzes the prompt and automatically routes it to a tool.


QA-091
---
What Azure resource does the Foundry portal automatically create when you publish an agent to Microsoft Teams?

- A. Azure Functions
- B. Azure Bot Service **(Correct)**
- C. Azure Cosmos DB
- D. Azure Logic Apps


QA-092
---
What happens to tool permissions when you publish an agent from Foundry to Teams?

- A. Permissions are automatically transferred to the published agent
- B. Tools are disabled after publishing
- C. The published agent gets a new identity and needs permissions reassigned **(Correct)**
- D. Permissions only work in organization scope

</details>
<details>
<summary><h3>2.2.4 Implement orchestrated multi-agent solutions</h3></summary>

#### Questions


QA-093
---
You have a Microsoft Foundry project that contains three agents as shown in the following table.
![alt text](image-13.png)
You need to orchestrate the agents to ensure that the customer requests meet the following requirements:
Support a deterministic, step-based process that uses conditional branching and shared state across the agents.
Optionally trigger a ticket action based on the triage result.
The solution must minimize development effort.
What should you include in the solution?

> A. a workflow Most Voted

B. threads and runs without a workflow

C. a multi-agent group chat session

D. separate agent runs coordinated in the application code


QA-094
---
What's the first step in the Microsoft Agent Framework's unified orchestration workflow?

- A. Select and create an orchestration pattern
- B. Define your agents and describe their capabilities **(Correct)**
- C. Start a runtime to manage execution


QA-095
---
For brainstorming and collaborative problem solving among multiple agents, which orchestration pattern is most suitable?

- A. Group Chat **(Correct)**
- B. Magentic
- C. Sequential


QA-096
---
Which pattern dynamically transfers control between agents based on context or rules?

- A. Handoff **(Correct)**
- B. Concurrent
- C. Sequential


QA-097
---
What is the primary role of an A2A server?

- A. It executes business logic for the agent directly.
- B. It routes requests between clients and connected agents. **(Correct)**
- C. It stores static agent responses for reuse.


QA-098
---
What does the Agent Executor do in an A2A agent?

- A. Manages network connections between clients and servers.
- B. Processes incoming requests and generates responses or events. **(Correct)**
- C. Provides a GUI for monitoring agent activity.


QA-099
---
What is an agent card used for in A2A?

- A. It stores the agent's API key for authentication.
- B. It provides metadata about the agent, such as its capabilities and available functions. **(Correct)**
- C. It visualizes the agent's workflow in a GUI dashboard.

</details>
<details>
<summary><h3>2.2.5 Build autonomous or semiautonomous workflows with safeguards and approval flow controls</h3></summary>

#### Questions


QA-100
---
HOTSPOT -
You have a Microsoft Foundry project that contains an agent named PaymentAgent.
PaymentAgent includes a function tool that issues customer refunds by using an external API.
You are creating a workflow in YAML.
You need to ensure that the workflow pauses for human approval and continues with the refund step only after approval is granted.
How should you complete the workflow definition? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-14.png)

 
> Correct Answer: ![alt text](image-15.png)


QA-101
---
HOTSPOT
-

You have a Microsoft Foundry project that contains two agents named PolicyWriter and RskReviewer.

PolicyWriter generates daft updates for customer polices, and RiskReviewer reviews the drafts.

In the visual builder, you need to create a workflow that meets the following requirements:

• Finalizes low-risk updates without manual intervention
• Ensures predictable execution across the agents
• Requires user approval for highs updates

What should you configure? To answer, select the appropriate options in the answer area.

NOTE: Each comet selection is worth one point.

![alt text](image-42.png)

 
> Correct Answer: ![alt text](image-43.png)

</details>
<details>
<summary><h3>2.2.6 Integrate monitoring into deployed agents, evaluate agent behavior, and perform error analysis</h3></summary>

#### Questions


QA-102
---
DRAG DROP -
You have a Microsoft Foundry project that contains a customer support agent grounded in internal documentation.
After a recent update, users report the following issues:
Some answers are unsupported by retrieved documents.
A small number of responses are flagged for policy violations.
You need to evaluate each issue.
Which observability signals should you use for each issue? To answer, drag the appropriate observability signals to the correct issues. Each observability signal may be used once, more than once, or not at all. You may need to drag the spit bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-16.png)

 
> Correct Answer: ![alt text](image-17.png)


QA-103
---
You have a Microsoft Foundry project that contains a customer support agent. The agent calls an internal knowledge API tool before generating responses.
Users report the following issues:
Some requests take more than 15 seconds to complete.
Some responses are incorrect, even when the knowledge API returns the expected data.
You need to inspect individual agent runs to view the ordered sequence of large language model (LLM) calls, tool invocations, and timing information.
Which observability capability should you use?

A. token usage

B. monitoring

C. safety metrics

> D. tracing Most Voted


QA-104
---
You have a Microsoft Foundry project that contains an agent named Agent1.

Agent runs successful, but Foundry Control Plane does NOT display values for error rates, runs, and token usage, and the Traces tab is empty.

You need to ensure that Found Control Plane displays the appropriate values for Agent1.

What should you do?

A. Update Agent1 to a new version.

B. Restart Agent from Foundry Control Plan

C. Assign to a Log Analytics workspace to Agent1.

> D. Enable Application Insights for Agent1.




</details>
</details>
<details>
<summary><h2>2.3 Optimize and operationalize generative AI systems</h2></summary>
<details>
<summary><h3>2.3.1 Tune generation behavior, such as prompt engineering and adjusting model parameters</h3></summary>

#### Questions


QA-105
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to configure Agent1 to answer customer questions about only the Contoso products. The solution must meet the business requirements.
What should you do?

> A. Modify the system message instructions. Most Voted

B. Add few-shot examples.

C. Apply top-p sampling.

D. Increase the value of the temperature parameter.


QA-106
---
HOTSPOT -
You have a Microsoft Foundry project that contains a deployed chat model.
You have a Python service that sends API requests to the model. The service is integrated with an automated validation system that compares generated outputs against approved response patterns.
Stakeholders report that small wording differences are causing validation mismatches.
You need to update the request parameters to improve output stability. The solution must maximize reasoning quality.
How should you complete the Python code? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-26.png)

 
> Correct Answer: ![alt text](image-27.png)


QA-107
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You increase the value of the temperature parameter.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-108
---
You have a Microsoft Foundry project that contains a customer support agent built on a deployed chat model.

The agent responses are validated by using an automated testing system that compares generated answers to stored expected outputs. Identical prompts must return consistent response to prevent automated test failures.

You need to reduce response variability, without modifying the prompt or reducing factual accuracy.

What should you do for the model?

A. Increase the max_tokens parameter.

B. Remove stop sequences from the requests.

> C. Decrease the temperature parameter.

D. Increase the temperature parameter.


QA-109
---
You are developing prompts for a Micosoft Foundry project that classifies incoming support tickets by category.

You need to improve accuracy by showing the model how correct classifications look, without retaining the model or storing knowledge permanently.

Which prompt engineering approach should you use?

A. Retrieval Augmented Generation (RAG)
B. zero-shot learning

C. chain of thought

> D. few-shot learning


QA-110
---
What is the primary purpose of a system message in a prompt?

- A. To define the model's role, behavior, and output constraints. **(Correct)**
- B. To provide training data that permanently changes the model.
- C. To retrieve data from an external data source.


QA-111
---
What does the temperature parameter control in a language model?

- A. The maximum number of tokens the model can generate.
- B. The randomness and creativity of the model's responses. **(Correct)**
- C. The speed at which the model processes requests.


QA-112
---
What does fine-tuning optimize in a language model?

- A. The factual accuracy of responses by connecting to external data.
- B. The consistency of the model's behavior, style, and output format. **(Correct)**
- C. The number of tokens the model can process in a single request.


QA-113
---
You're building a chat application that needs to answer questions using your company's product catalog while maintaining a specific brand voice. Which combination of strategies is most appropriate?

- A. Prompt engineering only, with detailed system messages.
- B. RAG for the product catalog data, fine-tuning for the brand voice, and prompt engineering for conversation-specific instructions. **(Correct)**
- C. Fine-tuning only, with the product catalog included in the training data.

</details>
<details>
<summary><h3>2.3.2 Implement model reflection, chain-of-thought evaluations, and self-critique loops</h3></summary>

#### Questions


QA-114
---
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
You need to improve response completeness. The solution must be implemented in the logic of the application code before responses are returned.
What should you do?

> A. Add a retry evaluation before the responses are returned. Most Voted

B. Decrease the value of the max_tokens parameter.

C. Switch to Retrieval Augmented Generation (RAG).

D. Replace the model with a smaller deployment.


QA-115
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You increase the value of the max_tokens parameter.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-116
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You add a reflection pass that regenerates the response if the required clauses are missing.
Does this meet the goal?

> A. Yes Most Voted

B. No


QA-117
---
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.

You need to improve response completeness. The solution must be implemented in the logic of the application code before responses are returned.

What should you do?

> A. Add a retry evaluation before the responses are returned.

B. Decrease the value of the temperature parameter.

C. Increase the value of the presence_penalty parameter

D. Replace the model with a smaller deployment.


</details>
<details>
<summary><h3>2.3.3 Set up observability by implementing tracing, token analytics, safety signals, and latency breakdowns</h3></summary>

#### Questions


QA-118
---
HOTSPOT -
Your company is piloting a customer support agent in a Microsoft Foundry project name Project1. Project1 is connected to an existing Application Insights resource, and the company’s support team reviews runs in the Traces tab.
The Foundry Agent Service is configured to perform the following actions:
Retrieve the Application Insights connection string by calling project_client.telemetry.get_application_insights_connection_string().
Call configure_azure_monitor(connection_string=...) to enable telemetry.
A separate LangChain service is configured to use OpenTelemetry and has the following configurations:
Uses AzureAIOpenTelemetryTracer(connection_string=..., enable_content_recording=False)
Passes the tracer by using config={“callbacks”:[azure_tracer]}
Company policy has the following requirements:
Telemetry from LangChain and OpenTelemetry must be distinguishable within the same Application Insights resource.
Secrets and credentials must NOT be stored in prompts, tool arguments, or span attributes.
For each of the following statements, select Yes if the statement is true. Otherwise, select No.
NOTE: Each correct selection is worth one point.
![alt text](image-4.png)

 
> Correct Answer: ![alt text](image-5.png)


QA-119
---
You have a Microsoft Foundry project that contains a high-traffic agent.
After a recent update, operational costs increase significantly.
Monitoring confirms that the volume of user traffic to the agent remains unchanged.
You suspect that changes to the request or response characteristics are causing the increase. You need to identify whether the additional costs are driven by the model input size, the model output size, or expanded tool usage.
Which observability capability should you use?

A. latency

B. evaluation metrics

C. run success rate

> D. token usage Most Voted


QA-120
---
You have a Microsoft Foundry project that contains a prompt agent used by a customer support web app.
The agent is invoked from a Python service that does NOT run in the Foundry portal.
You need to implement end-to-end tracing to capture latency breakdowns and exceptions across agent runs.
Which two components can you use? Each correct answer presents a complete solution.
NOTE: Each correct selection is worth one point.

A. a Log Analytics workspace

> B. Application Insights Most Voted

> C. OpenTelemetry Most Voted

D. the Azure Monitor Agent

E. Microsoft Sentinel


QA-121
---
You have a web app named App1 that processes user prompts by integrating with a Microsoft Foundry project named Project1. App1 performs the following actions:

• Sends prompts directly to a model by using the Azure OpenAI Responses API
• Invokes the Azure AI Content Safety tool by using a Foundry connection within the same request

You need to configure end-to-end visibility into each step of the request workflow.

What should you do?

A. Enable logging by using the client SDK for Content Safety.

B. Enable logging by using Foundry Local.

> C. Enable application tracing in Project1.

D. Route requests through the Azure OpenAI endpoint.


</details>
<details>
<summary><h3>2.3.4 Orchestrate multiple models, flows, or hybrid LLM and rules engines</h3></summary>

#### Questions


QA-122
---
You have a Microsoft Foundry project that serves a high-volume chat app.
Most requests are simple FAQs, but some require advanced reasoning.
You need to reduce costs and latency for common queries, without degrading the quality of the responses to complex questions.
What should you do?

A. Route all the requests to a smaller model.

> B. Use a model cascade that routes the requests to different models. Most Voted

C. Increase the value of the max_tokens parameter for all the requests.

D. Route all the requests to the most capable model.




</details>
</details>
</details>
<details>
<summary><h1>3 Implement computer vision solutions (10–15%)</h1></summary>
<details>
<summary><h2>3.1 Design and implement image- and video-generation solutions</h2></summary>
<details>
<summary><h3>3.1.1 Implement a solution that generates images from text prompts and reference media</h3></summary>

#### Questions


QA-123
---
You have a Microsoft Foundry project that contains an agent and an image generation model deployment.
The agent generates original images from user-supplied product photos.
You need to ensure that the generated images maintain the product identity and visual characteristics of the provided photo.
What should you do?

> A. Set the input_fidelity parameter to high. Most Voted

B. Apply a groundedness detection filter.

C. Include a prompt and input image in the request.

D. Decrease the value of the temperature parameter.


QA-124
---
You have an Azure subscription.

You plan to build an app that will use the Azure AI DALL-E model.

You need to deploy the model.

What should you use?

A. the Azure SDK for Python and PowerShell cmdlets.

B. the Azure SDK for JavaScript and Azure Machine Learning Studio.

> C. Microsoft Foundry and the Azure Command Line Interface (CLI)

D. the Azure portal and Microsoft Graph API


QA-125
---
You want to find a model in Microsoft Foundry to generate images. Which inference task should you filter by?

- A. Text to image **(Correct)**
- B. Image to text
- C. Embeddings


QA-126
---
Which OpenAI API can you use with image-generation models?

- A. Video
- B. Image **(Correct)**
- C. Graphics

</details>
<details>
<summary><h3>3.1.2 Implement a solution that generates videos from text prompts and reference media</h3></summary>

#### Questions


QA-127
---
HOTSPOT
-


Case Study
-

This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.

To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.

A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.


To start the case study
-

To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.


Overview
-


Company Information
-

Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.


Existing Environment
-


Identity Environment
-

Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.

Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.

The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.

Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.


Generative Environment
-

Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.


Project1
-

Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.

Agent1 has the following configurations:

• Agent1 uses a base model deployment.
• A safety evaluation pipeline is NOT enabled.
• Tool invocation approval workflows are NOT enabled.
• Conversation memory constraints are NOT configured.

Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.

Project1 is deployed to an Azure region located in the European Union (EU).

Agent1Dev Team will use Project1 to optimize and maintain Agent1.


Project2
-

Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.

Development of the solution is incomplete.


Data Environment
-

Contoso stores product-related information in Azure resources that support AI applications.

The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.

The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.


Problem Statements
-

Contoso identifies the following issues:

• Agent1 has only general knowledge of the Contoso products.
• A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
• Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
• The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.


Requirements
-


Planned Changes
-

Contoso plans to implement the following changes:

• Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
• Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
• Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
• Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
• Complete the development of the video creation solution.


Technical Requirements
-

Contoso identifies the following technical requirements:

• The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
• The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
• Responses generated by using the product sheet information must be relevant, complete, and accurate.
• Agent1 must be able to use the product sheets to answer natural language questions about product details.
• The model version used by Agent1 must remain consistent to ensure stable responses.
• The data processed by the model must remain within the EU.

Security and Compliance Requirements

Contoso identifies the following security and compliance requirements:

• API keys must NOT be used to access Foundry-deployed models.
• Access to the Azure resources must follow the principle of least privilege.
• The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
• Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
• Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
• Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
• The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.


Business Requirements
-

Contoso identifies the following business requirements:

• Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
• Agent1 must answer questions only about the products sold by Contoso.


You need to ensure that the marketing department can generate videos by using the model deployed to Project2.

How should you complete the Python code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.
![alt text](image-34.png)
> Correct Answear: ![alt text](image-35.png)

 
Correct Answer:


QA-128
---
What video durations does Sora 2 support?

- A. 1 to 20 seconds in 1-second increments
- B. 4, 8, or 12 seconds **(Correct)**
- C. Any duration up to 60 seconds


QA-129
---
What is required when using a reference image with Sora 2?

- A. The image must be smaller than 1 MB
- B. The image resolution must match the target video size **(Correct)**
- C. The image must contain at least one human face

</details>
<details>
<summary><h3>3.1.3 Configure image-editing workflows, including inpainting, mask-based edits, and prompt-driven modifications</h3></summary>

#### Questions


QA-130
---
You are creating an image-editing workflow in a Microsoft Foundry project.
The workflow must meet the following requirements:
Ensure that background objects can be removed by applying a mask-based inpainting edit.
Preserve the original lighting and style of the edited images.
Use the built-in image editing controls, NOT a custom model.
You need to ensure that image edits apply exclusively inside the masked area.
How should you configure the workflow?

A. Set generation mode to image_variation and provide the original image as a reference.

B. Enable text_to_image mode and a prompt describing the desired background removal.

C. Enable image_to_image mode and a high-strength value to regenerate the full image based on the prompt.

> D. Enable mask_inpainting and supply both the input image and a mask indicating which part of the image to modify. Most Voted


QA-131
---
You have a Microsoft Foundry project that generates product marketing images from text prompts.
After publishing several images, the legal team at your company identifies a competitor’s logo on a sign in the background of an image.
You need to remove only the logo, while preserving the rest of the image.
What should you do?

> A. Apply a mask-based inpainting edit to the part of the image that contains the logo. Most Voted

B. Increase the prompt guidance strength.

C. Modify the original prompt to exclude brand names.

D. Rerun the prompt by using a different random seed.


</details>
<details>
<summary><h3>3.1.4 Implement workflows to edit generated videos</h3></summary>

#### Questions


QA-132
---
You have a Microsoft Foundry project that generates short promotional product videos.

After several clips are approved, reviewers notice a small watermark in the top-right corner of some videos.

You need to remove the watermark without regenerating the videos.

What should you do?

A. Modify the original prompt to exclude watermarks.

B. Crop the video by using the size parameter.

C. Increase the guidance scale.

> D. Apply a mask-based inpainting edit to the affected part of the video.


QA-133
---
What is the remix feature used for in Sora 2?

- A. Combining multiple videos into one
- B. Making targeted adjustments to an existing video without regenerating from scratch **(Correct)**
- C. Adding background music to generated videos

</details>
<details>
<summary><h3>3.1.5 Select and apply appropriate generation and editing controls provided by the platform</h3></summary>

#### Questions

</details>
</details>
<details>
<summary><h2>3.2 Design and implement multimodal understanding workflows</h2></summary>
<details>
<summary><h3>3.2.1 Build a solution that analyzes visual context by using multimodal models</h3></summary>

#### Questions


QA-134
---
You have a web app named App1 that sends requests to a multimodal chat model deployment in a Microsoft Foundry project.

User messages can contain both text and images.

Currently, App1 includes image URL: as plain text inside the message content so the model cannot recognize them as images.

Traces show that the requests contain a single text message instead of a multimodal content array.

You need to send the message as a structured array that includes both the text portion and the image reference to ensure that the model can process the image correctly.

What should you do?

> A. Set the user message content array to include items that have type: text and type: image_url.

B. Encode the image to base64 and include the encoded data inside the content string of the user message.

C. Add the image URL to the request metadata section, so the model can resolve the processing issue automatically.

D. Place the image URL inside the System Message and set type to image_url so the model loads the image at initialization.


QA-135
---
Which kind of model can you use to respond to visual input?

- A. Only OpenAI GPT models
- B. Embedding models
- C. Multimodal models **(Correct)**


QA-136
---
How can you submit a prompt that asks a model to analyze an image?

- A. Submit one prompt with an image-based message followed by another prompt with a text-based message.
- B. Submit a prompt that contains a multi-part user message, containing both text content and image content. **(Correct)**
- C. Submit the image as the system message and the instruction or question as the user message.


QA-137
---
How can you include an image in a message?

- A. As a URL or as binary data **(Correct)**
- B. Only as a URL
- C. Only as binary data

</details>
<details>
<summary><h3>3.2.2 Configure apps to produce concise or detailed captions for single or multiple images</h3></summary>

#### Questions

</details>
<details>
<summary><h3>3.2.3 Implement a solution that enables question-answering grounded in visual evidence</h3></summary>

#### Questions

</details>
<details>
<summary><h3>3.2.4 Configure generation of alt-text and extended image descriptions aligned to accessibility guidelines</h3></summary>

#### Questions

</details>
<details>
<summary><h3>3.2.5 Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics</h3></summary>

#### Questions


QA-138
---
What is the purpose of grounding in Content Understanding?

- A. To connect Content Understanding to Azure storage
- B. To identify the specific regions in content where each value was extracted **(Correct)**
- C. To filter out harmful content from images


QA-139
---
What does a confidence score of 0.95 indicate for an extracted field?

- A. The extraction failed and needs manual review
- B. The value can be trusted for automated processing **(Correct)**
- C. The field was classified rather than extracted


QA-140
---
What kinds of AI solution is Azure Content Understanding designed to help you build?

- A. Chatbots that automatically translate between multiple spoken and written languages.
- B. Analyzers that extract information from documents, images, videos, and audio files. **(Correct)**
- C. Image generators that create visualizations based on descriptions.


QA-141
---
Which graphical tool should you use to create an Azure Content Understanding project?

- A. Microsoft Visual Studio.
- B. Azure Machine Learning studio.
- C. Content Understanding Studio. **(Correct)**

</details>
<details>
<summary><h3>3.2.6 Implement video analysis workflows to process and interpret video segments</h3></summary>

#### Questions


QA-142
---
DRAG DROP
-

You have a Microsoft Foundry project that uses Azure Content Understanding in Foundry Tools to analyze marketing videos.

Video segmentation is enabled.

You need to configure an analyzer to output a generated JSON field that describes the color scheme of each video segment.

How should you configure the analyzer? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.

NOTE: Each correct selection is worth one point.

![alt text](image-44.png)

 
> Correct Answer: ![alt text](image-45.png)


</details>
<details>
<summary><h3>3.2.7 Configure single-task and pro-mode Content Understanding pipelines</h3></summary>

#### Questions


QA-143
---
DRAG DROP -
You have a Microsoft Foundry project that processes procurement documents submitted by suppliers.
You need to implement two pipelines by using Azure Content Understanding in Foundry Tools. The solution must meet the following requirements:
Include a pipeline named Pipeline1 that supports cost-effective, high-volume processing of standalone PDF invoices.
Include a pipeline named Pipeline2 that supports cross-document validation by using multi-step reasoning and reference data.
How should you configure each pipeline? To answer, drag the appropriate configurations to the correct pipelines. Each configuration may be used once, more than once, of not at all. You may need to drag the split bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-6.png)

 
> Correct Answer: ![alt text](image-7.png)


QA-144
---
You have an invoice-processing application named App1 that uses Azure Constant Understanding in Foundry Tools.

You are building a new Content Understanding pipeline named Pipeline1 that must meet the following requirements:

• Compare an invoice to its related purchase order
• Validate the voice against static vendor contact documents
• Return a single structured output that includes discrepancy findings

You need to configure Pipeline1 and expose the pipeline as a single analyzer endpoint. What should you configure?

A. a single-file task in standard mode that uses the vendor contract provided as an additional document during analysis.

B. a single-file task in standard mode that uses confidence scores enabled for the extracted fields.

> C. a multiple-file task in pro mode that uses the vendor contract files as reference data

D. a multi-file task in standard mode that uses the invoice and purchase order as input to the analyzer


</details>
<details>
<summary><h3>3.2.8 Implement solutions that identify objects, components, or regions within images or video</h3></summary>

#### Questions


QA-145
---
HOTSPOT
-

You develop a test method to verify the results retrieved from a call to the Azure Vision in Foundry Tools API. The call is used to analyze the existence of company logos in images. The call returns a collection of brands named brands.

You have the following code segment:
![alt text](image-57.png)


For each of the following statements, select Yes if the statement is true. Otherwise, select No.

NOTE: Each correct selection is worth one point.

![alt text](image-58.png)

 
> Correct Answer: ![alt text](image-59.png)


QA-146
---
DRAG DROP
-

You are developing an application that will detect faulty components produced on a factory production line. The components are specific to your business.

You need to use the Azure Custom Vision API to help detect common faults.

Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order.


![alt text](image-67.png)
 
> Correct Answer: ![alt text](image-68.png)


QA-147
---
HOTSPOT
-

You are building a model to detect objects in images.

The performance of the model based on training data is shown in the following exhibit.

![alt text](image-73.png)

Use the drop-down menus to select the answer choice that completes each statement based on the information presented in the graphic.

NOTE: Each correct selection is worth one point.

![alt text](image-71.png)

 
> Correct Answer: ![alt text](image-72.png)



</details>
</details>
<details>
<summary><h2>3.3 Implement responsible AI for multimodal content</h2></summary>
<details>
<summary><h3>3.3.1 Implement filters to classify unsafe or disallowed visual content</h3></summary>

#### Questions


QA-148
---
HOTSPOT -
You have a Microsoft Foundry project that contains a customer support agent built by using the Foundry Agent Service.
The agent uploads user-provided screenshots to Azure Storage through a ticketing tool and receives a blob URL for additional reasoning.
You need to use image moderation during agent runs and prevent harmful content from being returned during runs. Azure AI Content Safety must access the images by using the blob URL. The solution must follow the principle of least privilege.
What should you configure for Content Safety? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-12.png)

 
> Correct Answer: image12


QA-149
---
You are deploying a support agent that enables users to upload photos.
You need to automatically classify uploaded images for harmful content. The solution must block content based on severity levels.
What should you do?

A. Apply keyword scanning to optical character recognition (OCR) output by using Azure Vision in Foundry Tools.

B. Enable prompt shields.

C. Use blocklists.

>D. Implement image moderation. Most Voted


</details>
<details>
<summary><h3>3.3.2 Detect and mitigate indirect prompt injection by using embedded text in images</h3></summary>

#### Questions


QA-150
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to configure Agent1 to meet the security and compliance requirements.
What should you use?

A. self-harm content filtering

> B. prompt shields Most Voted

C. Personally identifiable information (PII) Detection

D. violence content filtering


QA-151
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure a prompt shield for user prompts.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-152
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure image moderation to block unsafe content before processing the images.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-153
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure a prompt shield for documents.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-154
---
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure protected material detection.
Does this meet the goal?

A. Yes

> B. No Most Voted


QA-155
---
HOTSPOT -
You have a Microsoft Foundry project that contains an agent.
The agent accepts user-uploaded screenshots and uses a multimodal chat model.
Some screenshots contain potentially malicious embedded text.
You need to prevent a prompt injection attack and ensure that third-party content is treated as lower trust.
How should you configure prompt shields for document attacks? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-32.png)

 
> Correct Answer: ![alt text](image-33.png)


QA-156
---
You have an app named App1 that uses a Microsoft Foundry multimodal model deployment.
App1 runs optical character recognition (OCR) on uploaded images and appends the OCR output to the prompt as additional context.
Some uploaded images contain embedded text.
You need to prevent potentially malicious instructions from being processed by the model.
What should you use?

A. image moderation

> B. prompt shields for documents Most Voted

C. protected material text

D. prompt shields for user prompts


</details>
<details>
<summary><h3>3.3.3 Enforce visual policy rules, such as applying watermarks, flagging prohibited symbols, upholding brand usage requirements, and detecting potentially inappropriate content</h3></summary>

#### Questions

</details>
</details>
</details>
<details>
<summary><h1>4. Implement text analysis solutions (10–15%)</h1></summary></h1></summary>
<details>
<summary><h2>4.1 Apply language model text analysis</h2></summary>
<details>
<summary><h3>4.1.1 Implement solutions to extract entities, topics, summaries, and structured JSON outputs by using generative prompting and Foundry Tools</h3></summary>

#### Questions


QA-157
---
How should you create an application that analyzes news articles and extracts key people, places, and dates that are mentioned for indexing?

- A. Use a generative AI model with a custom function tool that matches strings using a regular expression.
- B. Use Azure Language in Foundry Tools to extract PII entities.
- C. Use Azure Language in Foundry Tools to extract named entities. **(Correct)**

</details>
<details>
<summary><h3>4.1.2 Configure detection of sentiment, tone, safety issues, and sensitive content</h3></summary>

#### Questions


QA-158
---
HOTSPOT
-

You have a Python application collects customer comments before posting them to a public forum.

You need to send a text comment to Azure AI Content Safety and return the self-harm severity from the response.

How should you complete the code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-62.png)

 
> Correct Answer: ![alt text](image-63.png)


QA-159
---
HOTSPOT
-

You have a Python application that redacts sensitive information before sending prompt text to a language model. The application has the following code:

![alt text](image-64.png)

For each of the following statements, select Yes if the statement is true. Otherwise, select No.

NOTE: Each correct selection is worth one point.

![alt text](image-65.png)

 
> Correct Answer: ![alt text](image-66.png)


QA-160
---
You want to publish extracts from customer testimonials on a web site. You need to remove personal details from the text before publishing it. What should you do?

- A. Use Azure Language in Foundry Tools to find and redact PII entities. **(Correct)**
- B. Use Azure Language in Foundry Tools to detect the language and publish only the testimonials in English.
- C. Use a gpt-4.1 model to create new AI-generated customer reviews.

</details>
<details>
<summary><h3>4.1.3 Build solutions that translate text by using Azure Translator in Foundry Tools or LLM-powered translation flows</h3></summary>

#### Questions


QA-161
---
What function of an Azure Translator **TextTranslationClient** object should you use to convert the Chinese word "你好" to the English word "Hello"?

- A. get\_supported\_language
- B. translate
- C. transliterate **(Correct)**


QA-162
---
What function of an Azure Translator **TextTranslationClient** object should you use to convert the Russian word "спасибо" in Cyrillic characters to "spasibo" in Latin characters?

- A. get\_supported\_language
- B. translate **(Correct)**
- C. transliterate

</details>
<details>
<summary><h3>4.1.4 Customize language model outputs for domain tasks, such as compliance summarization and domain extraction</h3></summary>

#### Questions


QA-163
---
You have a custom named entity recognition (NER) project in Azure Language in Foundry Tools for support tickets. The schema for the project contains an entity type named ContactInfo.

In tagged training files, ContactInfo is used for phone numbers, email addresses, and social media handles.

Model evaluation shows low precision for ContactInfo, including false positives in which nearby text is extracted as ContactInfo.

You need to improve the precision of the project.

What should you do before retraining the model?

A. Lower the confidence threshold for ContactInfo.

B. Trigger an auto-labeling job.

C. Add more support tickets as training data and label more ContactInfo entities.

> D. Replace ContactInfo by using Phone, Email, and SocialMedia entities. Relabel every matching span.


QA-164
---
You are designing a content management system.

You need to ensure that the reading experience is optimized for users who have reduced comprehension and learning differences, such as dyslexia. The solution must minimize development effort.

Which Azure service should you include in the solution?

A. Azure Document Intelligence in Foundry Tools

B. Azure Language in Foundry Tools

> C. Azure AI Immersive Reader

D. Azure Translator in Foundry Tools



</details>
</details>
<details>
<summary><h2>4.2 Implement speech solutions</h2></summary>
<details>
<summary><h3>4.2.1 Implement workflows to convert speech to text and text to speech for agentic interactions</h3></summary>

#### Questions


QA-165
---
You are building a speech processing solution in Microsoft Foundry for a customer support platform.
The platform will transcribe live phone calls, so that supervisors at your company can view call transcripts and detect issues while the calls are in progress. The call audio will arrive as a continuous stream from the telephony system.
You need to ensure that the call transcripts appear within only a few seconds of the audio stream.
What should you do?

A. Use text to speech by using a custom neural voice.

B. Use speech translation to generate the transcripts into multiple languages.

C. Run a batch transcription job on recorded audio files.

> D. Use real-time speech to text to process streaming audio input. Most Voted


QA-166
---
You are creating an agent workflow in a Microsoft Foundry project to support natural voice interactions.
The agent must receive continuous audio input, convert the input into text for reasoning, and then return spoken responses to a user. The workflow must meet the following requirements:
Support turn-taking dynamics, where the agent begins to generate the speech output before the user finishes speaking.
Operate with low latency to maintain conversational experience.
You need to enable both speech to text and text to speech in a real-time agent interaction.
What should you do?

A. Use batch transcription to convert the audio input and return text responses from the agent.

> B. Use real-time speech to text for incoming audio and text to speech for agent responses. Most Voted

C. Use an embeddings model to encode the audio, and then decode the audio into text and speech.

D. Use speech translation to convert the audio into another language and return the translated text.


QA-167
---
You are building a customer support web app named App1 in Microsoft Foundry that uses a GPT realtime model.

App1 must support:

• Live, low-latency voice conversations that use Azure OpenAI
• Streaming audio input from users and playback audio responses

You need to configure a connection method that supports real-time audio streaming in client application and targets approximately 100 ms latency.

Which connection method should you use?

A. RTMP

B. WebRTC

C. SIP

> D. WebSocket


QA-168
---
You are building a text-to-speech solution that uses Azure Speech in Foundry Tools to read instructions from the script in a text file.

You discover that the solution often pronounces technical terms incorrectly.

You need to prevent the incorrect pronunciations. The solution must minimize development effort.

What should you do?

A. From Speech Studio, train a custom neural voice

> B. Use Speech Synthesis Markup Language (SSML) to specify phonemes.

C. Use Speech Synthesis Markup Language (SSML) to apply say as rules.

D. Use Speech Synthesis Markup Language (SSML) to adjust the prosody of the voice.

E. From Azure OpenAI use the Whisper model.


QA-169
---
Which model can you use to synthesize speech from text?

- A. gpt-4o-mini
- B. gpt-4o-mini-tts **(Correct)**
- C. gpt-4o-mini-transcribe


QA-170
---
What information do you need from your Microsoft Foundry resource to consume it using the Azure Speech SDK?

- A. The endpoint and key **(Correct)**
- B. The primary and secondary keys
- C. The Azure subscription ID and resource group name


QA-171
---
Which object should you use to specify that the speech input to be transcribed to text is in an audio file?

- A. SpeechConfig
- B. AudioConfig **(Correct)**
- C. SpeechRecognizer


QA-172
---
How can you change the voice used in speech synthesis?

- A. Specify a SpeechSynthesisOutputFormat enumeration in the SpeechConfig object.
- B. Set the speech\_synthesis\_voice\_name property of the SpeechConfig object to the desired voice name. **(Correct)**
- C. Specify a filename in the AudioConfig object.

</details>
<details>
<summary><h3>4.2.2 Integrate speech as an agent modality, including custom speech models</h3></summary>

#### Questions


QA-173
---
You have a Microsoft Foundry project that contains an agent. The agent uses Azure Speech in Foundry Tools.
You fine-tune a baseline speech to text model for the en-us locale and publish the model.
The agent calls the Speech to text REST API and returns an error message indicating that the project ID is invalid.
You need to set the project property to the correct ID.
To what should you set the project property?

A. the project URL

> B. the custom speech project ID Most Voted

C. the project ID

D. the custom speech endpoint URL


QA-174
---
You have an Azure Speech in Foundry Tools resource that hosts a custom speech to text model deployed to a custom endpoint. An agent uses the endpoint to perform real-time speech recognition.
You are approaching the expiration date of the custom speech to text model.
What is the expected behavior when the model expires?

A. Speech recognition requests will return a 4xx error until a new custom model is deployed.

B. Speech recognition requests will continue to use the expired custom model until the model is removed manually.

> C. Speech recognition requests will fall back to the most recent base model for the same locale. Most Voted

D. The custom model will be deleted automatically when the model expires.


QA-175
---
What two core capabilities does the Azure Speech MCP server expose to agents?

- A. Language translation and text summarization.
- B. Speech-to-text recognition and text-to-speech synthesis. **(Correct)**
- C. Named entity recognition and sentiment analysis.


QA-176
---
Why does the Azure Speech MCP server require an Azure Storage account?

- A. To store the agent's instructions and configuration settings.
- B. To store input audio files and output audio files generated by the speech tools. **(Correct)**
- C. To cache the MCP server's tool definitions for faster discovery.


QA-177
---
What credentials are needed when connecting the Azure Speech MCP server to a Foundry agent?

- A. An OAuth 2.0 token and a managed identity endpoint URL.
- B. A Foundry resource key and a SAS URL for a blob container. **(Correct)**
- C. A client certificate and the Azure subscription ID.


QA-178
---
How can you specify a particular voice when using the text-to-speech tool through the agent?

- A. By configuring the voice in the MCP server settings before connecting.
- B. By including the voice name in your natural language prompt to the agent. **(Correct)**
- C. By setting an environment variable in the client application code.


QA-179
---
What are the two authentication methods supported by the Voice Live API?

- A. OAuth 2.0 and JWT (JSON Web Tokens)
- B. Basic authentication and API keys
- C. Microsoft Entra (keyless) and API key **(Correct)**


QA-180
---
Which protocol is used for avatar streaming integration in Voice Live API?

- A. HTTP/2
- B. WebRTC **(Correct)**
- C. gRPC


QA-181
---
How do you configure and test Voice Live agent integration in the Foundry Portal?

- A. You can't - Voice Live is only accessible through the REST API or Python SDK.
- B. In the Azure Speech in Foundry Tools Voice Live playground
- C. Enable Voice mode in the agent playground **(Correct)**


QA-182
---
How can you stop audio playback when a user interrupts the voice agent?

- A. You can't - the user must wait for the agent to finish.
- B. Handle the ServerEventType.INPUT\_AUDIO\_BUFFER\_SPEECH\_STARTED event **(Correct)**
- C. Reset the Voice Live session and clear the conversation history

</details>
<details>
<summary><h3>4.2.3 Enable multimodal reasoning from audio inputs</h3></summary>

#### Questions


QA-183
---
Which model can you use to generate text from speech?

- A. gpt-4o-mini
- B. gpt-4o-mini-tts
- C. gpt-4o-mini-transcribe **(Correct)**

</details>
<details>
<summary><h3>4.2.4 Translate speech into other languages by using language models and Foundry Tools</h3></summary>

#### Questions


QA-184
---
You have an application named App1 that uses Azure Speech in Foundry Tools to transcribe live calls.
Transcript segments often contain both English and Spanish. App1 sends each segment to Azure Translator in Foundry Tools to translate to another language.
Sometimes, mixed-language segments result in incomplete or incorrect translations.
You need to reduce translation errors. The solution must ensure that the entire transcript is translated successfully.
What should you do before sending the segments to Translator?

A. Use document translation to translate the entire transcript as a single document.

> B. Split the mixed-language segments into single-language segments and translate each segment separately. Most Voted

C. Enable automatic language detection for the translation request.

D. Specify English as the source language in the translation request for all the segments.


QA-185
---
Which Azure Speech SDK object should you use to specify the language(s) into which you want speech translated?

- A. SpeechConfig
- B. SpeechTranslationConfig
- C. AudioConfig **(Correct)**

</details>
</details>
</details>
<details>
<summary><h1>5 Implement information extraction solutions (10–15%)</h1></summary>
<details>
<summary><h2>5.1 Build retrieval and grounding pipelines</h2></summary>
<details>
<summary><h3>5.1.1 Ingest and index content, such as documents, images, audio, and video</h3></summary>

#### Questions


QA-186
---
Which component of an Azure AI Search solution is scheduled to extract and enrich data to populate an index?

- A. Indexer **(Correct)**
- B. Projection
- C. Query

</details>
<details>
<summary><h3>5.1.2 Configure semantic search, hybrid search, and vector search for grounding</h3></summary>

#### Questions


QA-187
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to configure an indexing pipeline for Agent1 to retrieve the relevant product information in storage1. The solution must meet the technical requirement.
Which two built-in skills should you use? Each correct answer presents part of the solution.
NOTE: Each correct selection is worth one point.

> A. Azure OpenAI Embedding Most Voted

B. Entity Recognition

> C. Text Split Most Voted

D. Merge

E. Language Detection

F. key phrase extraction


QA-188
---
You have a Microsoft Foundry project that contains an agent.

The agent uses Azure AI Search for Retrieval Augmented Generation (RAG).

You plan to ingest and index PDF product manuals.

You need to build a solution that supports semantic similarity matching. The solution must ensure that the agent retrieves relevant data when user questions use different wording than the product manuals.

Which indexing approach should you use?

> A. vector search

B. semantic ranking

C. suggesters

D. analyzers


QA-189
---
You have a Microsoft Foundry agent that grounds responses from an Azure Search index that contains the following:

• Searchable text fields for product names and product codes
• A vector field that stores embeddings for product descriptions

You need to ensure that users can query the index by using the following:

• Exact product names or codes
• Natural language descriptions of the products

What should you configure?

A. vector search only

> B. hybrid search

C. keyword search only

D. semantic search only


</details>
<details>
<summary><h3>5.1.3 Implement enrichment by using custom or built-in skills for text, images, and layout</h3></summary>

#### Questions


QA-190
---
You have a Microsoft Foundry project that contains an agent.
The agent uses Azure AI Search as the retriever.
You plan to ingest PDF into an Azure AI Search index to ensure that the agent can ground responses in texts in both documents and embedded images.
Users require citations that link to the source files.
You need to ensure that during indexing, the images are extracted into a structure that can be used as input for the built-in optical character recognition (OCR) skill.
Which indexing approach should you use?

> A. an indexer to extract image data into a normalized_images collection Most Voted

B. a Shaper skill to restructure the OCR input

C. a skillset to run the OCR skill directly against the content field of the index

D. the outputFieldMappings parameter to write image data to a searchable field


QA-191
---
You have an Azure AI Search indexer that ingests PDF policy manuals.

Client applications must display page-level citations that have bounding polygons for both text and images.

You need to add a single built-in multimodal content extraction skill to the Azure AI Search skillset. The solution must meet the following requirements:

• Provide text and image location metadata.
• Extract tables that span multiple pages.

What should you add?

A. Document Extraction

> B. Azure Content Understanding in Foundry Tools

C. GenAI Prompt

D. Document Layout


QA-192
---
You are building an Azure AI Search indexing pipeline named Pipeline1 that ingests invoices stored in Azure Blob Storage. The invoices are stored as scanned images.

You need to enable users to search invoice data across the invoice fields.

Which built-in skill should you add to the skillset of Pipeline1?

A. Text Split

B. Text Translation

> C. optical character recognition (OCR)

D. Image Analysis


QA-193
---
You have an Azure AI Search indexer that ingest PDF policy manuals.

Client applications must display page-level citations that have bounding polygons for both text and images.

You need to add a single built-in multimodal content extraction skill to the Azure AI Search skillset. The solution must meet the following requirements:

• Provide text and image location metadata.
• Extract tables that span multiple pages.

What should you add?

A. Document Layout

B. Document Extraction

> C. Azure Content Understanding

D. GenAI Prompt


QA-194
---
HOTSPOT
-

You are creating an enrichment pipeline that will use Azure AI Search. The knowledge store contains unstructured JSON data and the text from scanned PDF documents.

Which projection type should you use for each data type? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-74.png)

 
> Correct Answer: ![alt text](image-75.png)


QA-195
---
Which service supports built-in AI skills in Azure AI Search?

- A. Azure Functions
- B. Foundry Tools **(Correct)**
- C. Azure Cosmos DB


QA-196
---
Which kind of projection results in a relational data schema for extracted fields?

- A. File
- B. Object
- C. Table **(Correct)**

</details>
<details>
<summary><h3>5.1.4 Configure RAG ingestion flow, including documents and using optical character recognition (OCR)</h3></summary>

#### Questions


QA-197
---
You have a Microsoft Foundry project that contains an agent.
The agent uses a knowledge source built from documents stored in Azure Blob Storage. The documents include digitally scanned PDFs that contain multipage tables.
You have an ingestion job that extracts only plain text, causing loss of table structure, headings, and page-number metadata.
Users frequently ask questions that require the retrieval of specific table rows across the pages.
You need to configure an ingestion job for a Retrieval Augmented Generation (RAG) pipeline that performs optical character recognition (OCR) on scanned PDFs, preserves tables and headings as structure-aware chunks, and stores page-number metadata with each chunk.
How should you configure the ingestion job?

> A. Use advanced data parsing to reingest the documents. Most Voted

B. Use OCR and page-level chunking.

C. Use page-level OCR extraction and store each page as a single chunk.

D. Use basic parsing and fixed-size chunking.


</details>
<details>
<summary><h3>5.1.5 Connect retrieval pipelines directly to workflows and agent tools</h3></summary>

#### Questions

</details>
</details>
<details>
<summary><h2>5.2 Extract content from documents</h2></summary>
<details>
<summary><h3>5.2.1 Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction</h3></summary>

#### Questions


QA-198
---
Which prebuilt analyzer would you use to extract vendor names and item totals from a purchase receipt?

- A. prebuilt-image
- B. prebuilt-invoice
- C. prebuilt-receipt **(Correct)**


QA-199
---
You have a Microsoft Foundry project that contains an agent.
The agent ingests scanned PDF vendor invoices that contain tables and embedded QR codes.
The agent must preserve the PDF layout in the extracted output to ensure that downstream processing can reference sections and tables.
You plan to call Azure Content Understanding in Foundry Tools.
You need to extract content and layout elements and detect QR codes without requiring a language model deployment.
Which built-in analyzer should you use?

A. prebuilt-documentFieldSchema

B. prebuilt-read

C. prebuilt-documentSearch

> D. prebuilt-layout Most Voted


QA-200
---
You have an application that processes scanned PDF invoices. The invoices have varied layouts and include multipage tables.
You have a pipeline that uses optical character recognition (OCR) and extracts totals and invoice numbers. The results are often incorrect because the document structure is ignored.
You need to implement a solution that provides OCR, layout analysis, and template-generalizing field extraction. The solution must NOT require training a custom model. The solution must minimize administrative effort.
What should you include in the solution?

A. Azure Language in Foundry Tools

> B. Azure Content Understanding in Foundry Tools Most Voted

C. an Azure Machine Learning model


QA-201
---
This is a case study. Case studies are not timed separately from other exam sections. You can use as much exam time as you would like to complete each case study. However, there might be additional case studies or other exam sections. Manage your time to ensure that you can complete all the exam sections in the time provided. Pay attention to the Exam Progress at the top of the screen so you have sufficient time to complete any exam sections that follow this case study.
To answer the case study questions, you will bed to reference information that is provided in the case. Case studies and associated questions might contain exhibits or other resources that provide more information about the scenario described in the case. Information provided in an individual question does not apply to the other questions in the case study.
A Review Screen will appear at the end of this case study. From the Review Screen, you can review and change your answers before you move to the next exam section. After you leave this case study, you will NOT be able to return to it.

To start the case study -
To display the first question in this case study, select the “Next” button. To the left of the question, a menu provides links to information such as business requirements, the existing environment, and problem statements. Please read through all this information before answering any questions. When you are ready to answer a question, select the “Question” button to return to the question.

Overview -

Company Information -
Contoso, Ltd is a multinational retail company that builds, deploys, and manages generative AI and agent-based solutions by using Microsoft Foundry.

Existing Environment -

Identity Environment -
Contoso uses Microsoft Entra ID for identity management, authentication, and authorization capabilities that enable agents to access organizational resources and services.
Contoso recently formed a new AI engineering team named Agent1Dev Team to optimize and maintain existing AI solutions.
The team collaborates with solution architects, DevOps engineers, and security engineers to design, implement. monitor, and secure AI applications.
Contoso also has a team named Agent1Test Team that is responsible for validating AI solutions before the solution deployments.

Generative Environment -
Contoso has a Microsoft Foundry deployment that contains two projects named Project1 and Project2.

Project1 -
Project1 contains a customer support agent named Agent1 that assists customers with product inquiries and troubleshooting requests.
Agent1 has the following configurations:
Agent1 uses a base model deployment.
A safety evaluation pipeline is NOT enabled.
Tool invocation approval workflows are NOT enabled.
Conversation memory constraints are NOT configured.
Agent1 interacts with customers by using digital support channels and answers general questions about Contoso products.
Project1 is deployed to an Azure region located in the European Union (EU).
Agent1Dev Team will use Project1 to optimize and maintain Agent1.

Project2 -
Project2 contains a deployed video generation model. The marketing department at Contoso has access to Project2 and plans to use the model to develop a video creation solution.
Development of the solution is incomplete.

Data Environment -
Contoso stores product-related information in Azure resources that support AI applications.
The Azure environment contains an Azure Blob Storage account named storage1 that stores product detail sheets for all the Contoso products.
The product sheets include specifications, feature descriptions, and product support information that Agent1 can use to answer customer questions. The product sheets are stored in the PDF format.

Problem Statements -
Contoso identifies the following issues:
Agent1 has only general knowledge of the Contoso products.
A recent chat interaction with Agent1 was analyzed for sentiment. The results of the analysis have NOT been processed yet.
Agent1 does NOT use the detailed product information in the product sheets stored in storage1 when responding to customer questions.
The finance department at Contoso reports that vendor invoices must be reviewed manually to ensure that the invoices match the terms defined in the vendor contracts. The invoices contain tables, logos, and varied layouts that make the documents difficult to process consistently.

Requirements -

Planned Changes -
Contoso plans to implement the following changes:
Implement a solution for Project1 that analyzes the vendor invoices by evaluating both the visual layout and the textual content of the invoices, so that the invoice details can be verified against the vendor contract terms.
Update the base model deployment used by Agent1 and standardize the model version to ensure continuity and consistent responses.
Enable Agent1 to retrieve and use the detailed product information from the product sheets stored in storage1.
Implement an indexing solution for the product sheets that Agent1 can use to answer customer questions.
Complete the development of the video creation solution.

Technical Requirements -
Contoso identifies the following technical requirements:
The model deployment used by Agent1 must support scalable, high-throughput generative AI workloads and dynamically scale to handle variable customer support traffic, without requiring reserved throughput capacity.
The product sheets must be processed by using an indexing pipeline that enables semantic and vector search, so that Agent1 can retrieve the relevant product information.
Responses generated by using the product sheet information must be relevant, complete, and accurate.
Agent1 must be able to use the product sheets to answer natural language questions about product details.
The model version used by Agent1 must remain consistent to ensure stable responses.
The data processed by the model must remain within the EU.
Security and Compliance Requirements
Contoso identifies the following security and compliance requirements:
API keys must NOT be used to access Foundry-deployed models.
Access to the Azure resources must follow the principle of least privilege.
The developers at Contoso must authenticate to Microsoft Foundry resources by using Microsoft Entra authentication.
Access to Project1 must be assigned to the members of Agent1Dev Team by using a security group named SC_Agent1_Dev.
Access to Project1 must be assigned to the members of Agent1Test Team by using a security group named SC_Agent1_Test.
Agent1 must never reveal customer information, even if a document that contains customer data is added erroneously to the product sheet repository in storage1.
The product sheets might contain images that include embedded text. Agent1 must be protected from malicious instructions potentially hidden within the images.

Business Requirements -
Contoso identifies the following business requirements:
Users that interact with Agent1 must have a personalized experience in future interactions, including the ability for Agent1 to retain conversation context and recall relevant information from previous interactions.
Agent1 must answer questions only about the products sold by Contoso.
You need to recommend an invoice review solution that resolves the issue reported by the finance department.
What should you include in the recommendation?

A. chat completions

B. Azure Document Intelligence in Foundry Tools

> C. Azure Content Understanding in Foundry Tools Most Voted

D. Image Analysis


QA-202
---
You have a Microsoft Foundry project named Project1.
Project1 contains an application that processes PDF vendor invoices.
You need to configure Azure Document Intelligence in Foundry Tools to generate a Markdown output that preserves the sections and table structure of the PDFs. The solution must minimize development effort.
What should you do?

A. Configure output=figures when you analyze the PDF.

B. Configure content=markdown when you analyze the document.

C. Increase the confidence threshold.

> D. Set the output_content_format=ContentFormat.MARKDOWN value.


QA-203
---
You need to extract text and table structure from a set of documents that have varying formats. You don't need to identify specific labeled fields. Which Document Intelligence model should you use?

- A. The read model.
- B. The layout model. **(Correct)**
- C. The invoice model.


QA-204
---
You're building a custom model in Azure Document Intelligence. What training artifacts are required when training with the REST API?

- A. Only the sample form documents in a blob container.
- B. Sample forms along with ocr.json, labels.json, and fields.json files in a blob container. **(Correct)**
- C. A minimum of 100 labeled forms and a trained classifier.


QA-205
---
A company processes both invoices and receipts. They want a single endpoint that routes each document to the correct extraction model. What should they use?

- A. A custom neural model.
- B. A prebuilt read model.
- C. A composed model or a custom classifier paired with extraction models. **(Correct)**

</details>
<details>
<summary><h3>5.2.2 Produce clean, grounded representations to use with agents and RAG by using Content Understanding</h3></summary>

#### Questions


QA-206
---
You have a Microsoft Foundry project that contains an agent.
The knowledge source for the agent is a set of scanned PDF troubleshooting guides stored in Azure Blob Storage. The guide pages contain two-column layouts and tables.
You use Azure Content Understanding in Foundry Tools to process the PDFs.
You plan to ingest the processed content into an index for Retrieval Augmented Generation (RAG) and store extracted fields for downstream automation.
Stakeholders must be able to verify where each extracted field value came from in the original PDF and route low-reliability extractions for manual review.
You need to ensure that the Content Understanding document analyzer output includes a per-field confidence score and source grounding to locations within the source document.
What should you do?

A. Set enableSegment to true.

B. Provide labeled samples.

> C. Enable estimateFieldSourceAndConfidence. Most Voted

D. Configure the analyzer to use generative extraction for all fields.


QA-207
---
You have a Microsoft Foundry project that contains an agent.

The agent uses Azure Content Understanding in Foundry Too to process vendor onboarding packets. The packs include digital PDFs that contain tables and hyperlinks.

The extracted content is indexed for search and provided to a downstream agent in the Markdown format.

You need to generate a Markdown output that has a layout and a semantic structure optimized for Retrieval Augmented Generation (RAG) workflows.

Which built-in analyzer should you use?

A. prebuilt-documentFieldSchema

> B. prebuilt-documentSearch

C. prebuilt-read

D. prebuilt-layout


</details>
<details>
<summary><h3>5.2.3 Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding</h3></summary>

#### Questions


QA-208
---
You have a Microsoft Foundry project that contains an agent.
You need to process mixed-format documents that contain scanned text, tables, and multicolumn layouts. The extracted content must preserve the document structure and be converted into the Markdown format for downstream reasoning.
What should you configure first?

A. an Azure Language in Foundry Tools text analysis model deployment

B. a generative chat completion request

C. an Azure OpenAI Responses API call that uses a multimodal model

> D. an Azure Content Understanding in Foundry Tools analyzer Most Voted


QA-209
---
You have a Microsoft Foundry project that ingests scanned PDF invoices stored in Azure Blob Storage. Each invoice contains printed fine items and has a table-based layout.
Extracted results are stored as structured JSON and used as grounding data for an agent in a Retrieval Augmented Generation (RAG) solution.
You need to create a single analyzer that meets the following requirements:
Extracts the invoice number, invoice date, vendor name, and total amount across varying templates
Returns confidence scores so that results with confidence below 0.80 can be routed for supervisor review
What should you use?

A. a Foundry agent that has groundedness guardrails enabled to extract invoice fields and confidence scores

> B. a custom Azure Content Understanding in Foundry Tools analyzer that defines the required fields as the extracted fields and the returned confidence scores for routing Most Voted

C. the Azure Content Understanding in Foundry Tools prebuilt-layout analyzer

D. the Azure Content Understanding in Foundry Tools prebuilt-documentSearch analyzer and search.score from the Azure AI Search results for routing


QA-210
---
What should you define for the information you want to extract from content?

- A. A schema. **(Correct)**
- B. An index.
- C. A cluster.


QA-211
---
What configuration values are needed to use the Azure Content Understanding API?

- A. The name of the resource group where the Azure service is deployed.
- B. The Azure subscription ID and tenant ID.
- C. The endpoint and key for the Foundry resource. **(Correct)**


QA-212
---
What must be specified when calling the *analyze* method to extract fields from content?

- A. The name of the Foundry resource.
- B. The name of the analyzer. **(Correct)**
- C. The Operation-Location returned when the analyzer was created.


QA-213
---
How are the extracted fields returned?

- A. As type-specific values. **(Correct)**
- B. As a list of strings.
- C. As a single blob.

</details>
</details>
</details>
