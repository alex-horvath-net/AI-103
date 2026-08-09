# AI-103: Official Course Questions and Answers

> **Objective version:** Skills measured as of April 16, 2026. The hierarchy below exactly follows the official AI-103 study guide. Questions and choices are reproduced from the official Microsoft Learn module assessments; explanations are concise study annotations.

**Extraction scope and deduplication**

- The official AI-103 course currently exposes **30 module assessments containing 96 questions**. Those questions are included once below.
- Matching knowledge checks in the official Microsoft video series are listed as duplicate sources on the same entry instead of being repeated.
- The official exercise site and repository contain lab instructions, validation prompts and sample application data, but no separate knowledge-check, quiz, review-question or assessment sections. Lab prompts and sample datasets were therefore not invented or misclassified as exam questions.
- Source priority is applied when wording has aged: the Episode 1 transcript says “Microsoft AI Toolkit,” while the current official module assessment says **Foundry Toolkit for Visual Studio Code**; the current assessment is authoritative.

- [Official course](https://learn.microsoft.com/en-us/training/courses/ai-103t00)
- [Official exercises](https://microsoftlearning.github.io/mslearn-ai-studio/)
- [Official exercise repository](https://github.com/microsoftlearning/mslearn-ai-studio)
- [Official video series](https://www.youtube.com/playlist?list=PLWGIg_TYLeEQ)

## Skills measured as of April 16, 2026

### Plan and manage an Azure AI solution (25–30%)

#### Choose the appropriate Foundry services for generative AI and agents

##### Choose an appropriate model for each task, including large language models (LLMs), small language models, multimodal models, and Foundry Tools

###### QA001 M02-Q01. Which model benchmark indicates the model's ability to process prompts and return comprehensive responses quickly?

- A. Quality index
- B. Cost
- C. Throughput **(Correct)**

**Correct answer:** C. Throughput

**Why it is correct:** Throughput measures how rapidly a model can process requests and produce responses; quality and cost measure different properties.

**Why the other options are incorrect:**

- **A. Quality index:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Throughput measures how rapidly a model can process requests and produce responses; quality and cost measure different properties.
- **B. Cost:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Throughput measures how rapidly a model can process requests and produce responses; quality and cost measure different properties.

**Tested concept:** Choose an appropriate model for each task, including large language models (LLMs), small language models, multimodal models, and Foundry Tools

**Likely exam trap:** Match the benchmark/deployment/evaluator to the exact operational property, not the most impressive-sounding option.

**Sources:**

- [Microsoft Learn — Select, deploy, and evaluate Microsoft Foundry models assessment](https://learn.microsoft.com/en-us/training/modules/model-catalog-evaluate/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=71gi8ULxPZQ)

##### Choose the appropriate Foundry services for generative tasks, grounding, vector search, agent workflows, or multimodal processing

###### QA002 M01-Q02. Which component of Microsoft Foundry provides pre-built services for common AI tasks?

- A. Foundry Tools **(Correct)**
- B. Foundry Models
- C. Foundry IQ

**Correct answer:** A. Foundry Tools

**Why it is correct:** Foundry Tools are prebuilt task services; Foundry Models are model deployments and Foundry IQ provides knowledge and retrieval capabilities.

**Why the other options are incorrect:**

- **B. Foundry Models:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry Tools are prebuilt task services; Foundry Models are model deployments and Foundry IQ provides knowledge and retrieval capabilities.
- **C. Foundry IQ:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry Tools are prebuilt task services; Foundry Models are model deployments and Foundry IQ provides knowledge and retrieval capabilities.

**Tested concept:** Choose the appropriate Foundry services for generative tasks, grounding, vector search, agent workflows, or multimodal processing

**Likely exam trap:** Do not confuse the resource-management portal, Foundry project portal, Foundry components, or a renamed VS Code extension.

**Sources:**

- [Microsoft Learn — Plan and Prepare to Develop AI Solutions on Azure assessment](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PE_7sP3uN5k)

##### Choose an appropriate method for retrieval and indexing

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Choose appropriate memory, tool, and knowledge integration services for agent solutions

###### QA003 M10-Q02. Which data source option provides real-time access to SharePoint content with Microsoft 365 governance?

- A. SharePoint Indexed, which pre-processes SharePoint content into Azure AI Search.
- B. SharePoint Remote, which queries SharePoint sites and libraries in real-time. **(Correct)**
- C. Azure Blob Storage, which connects to SharePoint files stored as blobs.

**Correct answer:** B. SharePoint Remote, which queries SharePoint sites and libraries in real-time.

**Why it is correct:** SharePoint Remote queries governed SharePoint content in real time; SharePoint Indexed pre-processes content into a search index.

**Why the other options are incorrect:**

- **A. SharePoint Indexed, which pre-processes SharePoint content into Azure AI Search.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: SharePoint Remote queries governed SharePoint content in real time; SharePoint Indexed pre-processes content into a search index.
- **C. Azure Blob Storage, which connects to SharePoint files stored as blobs.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: SharePoint Remote queries governed SharePoint content in real time; SharePoint Indexed pre-processes content into a search index.

**Tested concept:** Choose appropriate memory, tool, and knowledge integration services for agent solutions

**Likely exam trap:** RAG retrieves current evidence; it does not retrain the model or guarantee citation use without instructions/evaluation.

**Sources:**

- [Microsoft Learn — Build knowledge-enhanced AI agents with Foundry IQ assessment](https://learn.microsoft.com/en-us/training/modules/introduction-foundry-iq/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=c9zns7PX0Io)

###### QA004 M10-Q03. What is the purpose of scoring profiles in Foundry IQ knowledge bases?

- A. To encrypt sensitive fields and protect confidential information during retrieval.
- B. To boost specific fields or attributes so more important results surface first. **(Correct)**
- C. To configure how documents are chunked and embedded for semantic search.

**Correct answer:** B. To boost specific fields or attributes so more important results surface first.

**Why it is correct:** Scoring profiles boost fields/attributes for ranking; encryption and chunking/embedding are configured elsewhere.

**Why the other options are incorrect:**

- **A. To encrypt sensitive fields and protect confidential information during retrieval.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Scoring profiles boost fields/attributes for ranking; encryption and chunking/embedding are configured elsewhere.
- **C. To configure how documents are chunked and embedded for semantic search.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Scoring profiles boost fields/attributes for ranking; encryption and chunking/embedding are configured elsewhere.

**Tested concept:** Choose appropriate memory, tool, and knowledge integration services for agent solutions

**Likely exam trap:** RAG retrieves current evidence; it does not retrain the model or guarantee citation use without instructions/evaluation.

**Sources:**

- [Microsoft Learn — Build knowledge-enhanced AI agents with Foundry IQ assessment](https://learn.microsoft.com/en-us/training/modules/introduction-foundry-iq/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=c9zns7PX0Io)

#### Set up AI solutions in Foundry

##### Design Azure infrastructure for AI apps and agent-based solutions

###### QA005 M01-Q01. Which web portal should you use to work with assets in a Microsoft Foundry project?

- A. The Azure portal
- B. Microsoft Copilot
- C. The Microsoft Foundry portal **(Correct)**

**Correct answer:** C. The Microsoft Foundry portal

**Why it is correct:** The Microsoft Foundry portal is the workspace for project assets; the Azure portal manages Azure resources and Copilot is an assistant.

**Why the other options are incorrect:**

- **A. The Azure portal:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Microsoft Foundry portal is the workspace for project assets; the Azure portal manages Azure resources and Copilot is an assistant.
- **B. Microsoft Copilot:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Microsoft Foundry portal is the workspace for project assets; the Azure portal manages Azure resources and Copilot is an assistant.

**Tested concept:** Design Azure infrastructure for AI apps and agent-based solutions

**Likely exam trap:** Do not confuse the resource-management portal, Foundry project portal, Foundry components, or a renamed VS Code extension.

**Sources:**

- [Microsoft Learn — Plan and Prepare to Develop AI Solutions on Azure assessment](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PE_7sP3uN5k)

##### Choose appropriate deployment options

###### QA006 M02-Q02. Which deployment type in Microsoft Foundry is best for general use while offering the largest quota?

- A. Data Zone Batch
- B. Global Standard **(Correct)**
- C. Developer

**Correct answer:** B. Global Standard

**Why it is correct:** Global Standard is the general-purpose deployment option with the broadest global capacity/quota among these choices; Batch is asynchronous and Developer is temporary evaluation capacity.

**Why the other options are incorrect:**

- **A. Data Zone Batch:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Global Standard is the general-purpose deployment option with the broadest global capacity/quota among these choices; Batch is asynchronous and Developer is temporary evaluation capacity.
- **C. Developer:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Global Standard is the general-purpose deployment option with the broadest global capacity/quota among these choices; Batch is asynchronous and Developer is temporary evaluation capacity.

**Tested concept:** Choose appropriate deployment options

**Likely exam trap:** Match the benchmark/deployment/evaluator to the exact operational property, not the most impressive-sounding option.

**Sources:**

- [Microsoft Learn — Select, deploy, and evaluate Microsoft Foundry models assessment](https://learn.microsoft.com/en-us/training/modules/model-catalog-evaluate/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=71gi8ULxPZQ)

##### Configure model and agent deployments

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Integrate Foundry projects with continuous integration and continuous deployment (CI/CD) pipelines

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Manage, monitor, and secure AI systems

##### Manage quotas, scaling, rate limits, and cost footprints for model and agent workloads

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Monitor model performance, drift, safety events, and grounding quality

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Monitor data ingestion quality, search index health, and relevance performance

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Configure security, including managed identity, private networking, keyless credentials, and role policies

###### QA007 M17-Q04. What authentication method is used when connecting the Azure Language MCP server to a Foundry agent?

- A. OAuth 2.0 authentication with a client certificate and tenant ID.
- B. Key-based authentication using the Ocp-Apim-Subscription-Key credential. **(Correct)**
- C. Anonymous access that requires no authentication or credentials.

**Correct answer:** B. Key-based authentication using the Ocp-Apim-Subscription-Key credential.

**Why it is correct:** The course MCP connection uses the Azure Language key in `Ocp-Apim-Subscription-Key`; the listed certificate and anonymous options are not used.

**Why the other options are incorrect:**

- **A. OAuth 2.0 authentication with a client certificate and tenant ID.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course MCP connection uses the Azure Language key in `Ocp-Apim-Subscription-Key`; the listed certificate and anonymous options are not used.
- **C. Anonymous access that requires no authentication or credentials.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course MCP connection uses the Azure Language key in `Ocp-Apim-Subscription-Key`; the listed certificate and anonymous options are not used.

**Tested concept:** Configure security, including managed identity, private networking, keyless credentials, and role policies

**Likely exam trap:** Tool discovery does not equal authentication, and agent references are not ordinary model names.

**Sources:**

- [Microsoft Learn — Develop a Text Analysis Agent with the Azure Language MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-text-analysis-agent-language-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=O1tc09coYO4)

#### Implement responsible AI across generative AI and agentic systems

##### Configure safety filters, guardrails, risk detection, and content moderation

###### QA008 M06-Q02. What capability of Microsoft Foundry helps mitigate harmful content generation at the Safety System level?

- A. DALL-E model support
- B. Fine-tuning
- C. Guardrails **(Correct)**

**Correct answer:** C. Guardrails

**Why it is correct:** Guardrails are the Foundry safety-system capability for detecting or blocking harmful inputs/outputs; model family and fine-tuning are not equivalent controls.

**Why the other options are incorrect:**

- **A. DALL-E model support:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Guardrails are the Foundry safety-system capability for detecting or blocking harmful inputs/outputs; model family and fine-tuning are not equivalent controls.
- **B. Fine-tuning:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Guardrails are the Foundry safety-system capability for detecting or blocking harmful inputs/outputs; model family and fine-tuning are not equivalent controls.

**Tested concept:** Configure safety filters, guardrails, risk detection, and content moderation

**Likely exam trap:** Responsible AI is a lifecycle of mapping, measurement, mitigation and management—not one filter.

**Sources:**

- [Microsoft Learn — Implement a responsible generative AI solution in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=H5wPr-Ca2UM)

##### Apply responsible AI instrumentation, including evaluators, safety evaluations, and explanation tooling

###### QA009 M06-Q01. Why should you consider creating an AI Impact Assessment when designing a generative AI solution?

- A. To make a legal case that indemnifies you from responsibility for harms caused by the solution
- B. To document the purpose, expected use, and potential harms for the solution **(Correct)**
- C. To evaluate the cost of cloud services required to implement your solution

**Correct answer:** B. To document the purpose, expected use, and potential harms for the solution

**Why it is correct:** An AI Impact Assessment documents purpose, intended use, affected stakeholders and potential harms; it is not indemnity or a cloud-cost estimate.

**Why the other options are incorrect:**

- **A. To make a legal case that indemnifies you from responsibility for harms caused by the solution:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An AI Impact Assessment documents purpose, intended use, affected stakeholders and potential harms; it is not indemnity or a cloud-cost estimate.
- **C. To evaluate the cost of cloud services required to implement your solution:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An AI Impact Assessment documents purpose, intended use, affected stakeholders and potential harms; it is not indemnity or a cloud-cost estimate.

**Tested concept:** Apply responsible AI instrumentation, including evaluators, safety evaluations, and explanation tooling

**Likely exam trap:** Responsible AI is a lifecycle of mapping, measurement, mitigation and management—not one filter.

**Sources:**

- [Microsoft Learn — Implement a responsible generative AI solution in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=H5wPr-Ca2UM)

###### QA010 M06-Q03. Why should you consider a phased delivery plan for your generative AI solution?

- A. To enable you to gather feedback and identify issues before releasing the solution more broadly **(Correct)**
- B. To eliminate the need to map, measure, mitigate, and manage potential harms
- C. To enable you to charge more for the solution

**Correct answer:** A. To enable you to gather feedback and identify issues before releasing the solution more broadly

**Why it is correct:** Phased delivery exposes issues to feedback and monitoring before wider release; it does not remove responsible-AI duties or exist to raise price.

**Why the other options are incorrect:**

- **B. To eliminate the need to map, measure, mitigate, and manage potential harms:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Phased delivery exposes issues to feedback and monitoring before wider release; it does not remove responsible-AI duties or exist to raise price.
- **C. To enable you to charge more for the solution:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Phased delivery exposes issues to feedback and monitoring before wider release; it does not remove responsible-AI duties or exist to raise price.

**Tested concept:** Apply responsible AI instrumentation, including evaluators, safety evaluations, and explanation tooling

**Likely exam trap:** Responsible AI is a lifecycle of mapping, measurement, mitigation and management—not one filter.

**Sources:**

- [Microsoft Learn — Implement a responsible generative AI solution in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/responsible-ai-studio/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=H5wPr-Ca2UM)

##### Implement auditing through trace logging, provenance metadata, and approval workflows

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Govern agent behavior with oversight modes, constraints, and tool-access controls

###### QA011 M07-Q03. Which of the following is NOT a recommended security practice for AI agents?

- A. Using role-based access controls
- B. Implementing prompt filtering and validation
- C. Maintaining comprehensive logging and traceability
- D. Allowing agents unrestricted access to all enterprise data **(Correct)**

**Correct answer:** D. Allowing agents unrestricted access to all enterprise data

**Why it is correct:** Unrestricted enterprise-data access violates least privilege; RBAC, filtering/validation and traceability are recommended safeguards.

**Why the other options are incorrect:**

- **A. Using role-based access controls:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Unrestricted enterprise-data access violates least privilege; RBAC, filtering/validation and traceability are recommended safeguards.
- **B. Implementing prompt filtering and validation:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Unrestricted enterprise-data access violates least privilege; RBAC, filtering/validation and traceability are recommended safeguards.
- **C. Maintaining comprehensive logging and traceability:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Unrestricted enterprise-data access violates least privilege; RBAC, filtering/validation and traceability are recommended safeguards.

**Tested concept:** Govern agent behavior with oversight modes, constraints, and tool-access controls

**Likely exam trap:** Managed agent state/tool execution does not remove least privilege, validation or human approval where risk requires it.

**Sources:**

- [Microsoft Learn — Develop AI agents with Microsoft Foundry and Visual Studio Code assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-azure-vs-code/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=EmBPT_tIs8Y)

### Implement generative AI and agentic solutions (30–35%)

#### Build generative applications by using Foundry

##### Deploy and consume LLMs, small models, code models, and multimodal models

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement retrieval-augmented generation (RAG) in an application

###### QA012 M05-Q02. When should you use Retrieval Augmented Generation (RAG) instead of relying on prompt engineering alone?

- A. When you want the model to respond in a consistent style and format.
- B. When the model needs access to domain-specific or current data that it wasn't trained on. **(Correct)**
- C. When you want to reduce the length of prompts sent to the model.

**Correct answer:** B. When the model needs access to domain-specific or current data that it wasn't trained on.

**Why it is correct:** RAG supplies current or private domain evidence at query time; style/format belongs in prompting and RAG does not inherently shorten prompts.

**Why the other options are incorrect:**

- **A. When you want the model to respond in a consistent style and format.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG supplies current or private domain evidence at query time; style/format belongs in prompting and RAG does not inherently shorten prompts.
- **C. When you want to reduce the length of prompts sent to the model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG supplies current or private domain evidence at query time; style/format belongs in prompting and RAG does not inherently shorten prompts.

**Tested concept:** Implement retrieval-augmented generation (RAG) in an application

**Likely exam trap:** Prompting changes instructions, RAG changes context, fine-tuning changes behavior, and temperature changes sampling.

**Sources:**

- [Microsoft Learn — Optimize generative AI model performance with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Ocx76q4p9ME)

###### QA013 M10-Q01. What is the primary advantage of Retrieval Augmented Generation (RAG) over simple AI agents?

- A. RAG eliminates the need for large language models by relying entirely on document retrieval.
- B. RAG enables agents to ground responses in current organizational information and provide source transparency. **(Correct)**
- C. RAG automatically retrains the language model whenever organizational documents change.

**Correct answer:** B. RAG enables agents to ground responses in current organizational information and provide source transparency.

**Why it is correct:** RAG grounds answers in current organizational information with source transparency; it still uses a model and does not retrain it on every update.

**Why the other options are incorrect:**

- **A. RAG eliminates the need for large language models by relying entirely on document retrieval.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG grounds answers in current organizational information with source transparency; it still uses a model and does not retrain it on every update.
- **C. RAG automatically retrains the language model whenever organizational documents change.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG grounds answers in current organizational information with source transparency; it still uses a model and does not retrain it on every update.

**Tested concept:** Implement retrieval-augmented generation (RAG) in an application

**Likely exam trap:** RAG retrieves current evidence; it does not retrain the model or guarantee citation use without instructions/evaluation.

**Sources:**

- [Microsoft Learn — Build knowledge-enhanced AI agents with Foundry IQ assessment](https://learn.microsoft.com/en-us/training/modules/introduction-foundry-iq/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=c9zns7PX0Io)

##### Design workflows, tool-augmented flows, and multistep reasoning pipelines

###### QA014 M12-Q01. Which type of node in a Foundry workflow is used to invoke an AI agent?

- A. Logic node
- B. Agent node **(Correct)**
- C. Data transformation node

**Correct answer:** B. Agent node

**Why it is correct:** An Agent node invokes an AI agent; logic and transformation nodes perform different workflow duties.

**Why the other options are incorrect:**

- **A. Logic node:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An Agent node invokes an AI agent; logic and transformation nodes perform different workflow duties.
- **C. Data transformation node:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An Agent node invokes an AI agent; logic and transformation nodes perform different workflow duties.

**Tested concept:** Design workflows, tool-augmented flows, and multistep reasoning pipelines

**Likely exam trap:** Agent, loop and condition nodes have different responsibilities; structured output feeds control flow rather than replacing it.

**Sources:**

- [Microsoft Learn — Get started with building agent-driven workflows using Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-workflows-microsoft-foundry/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=ChGunV55YiU)

###### QA015 M12-Q02. Which node type would you use to handle multiple tickets in a workflow without duplicating nodes?

- A. If/Else node
- B. For-Each node **(Correct)**
- C. Send message node

**Correct answer:** B. For-Each node

**Why it is correct:** A For-Each node iterates over multiple tickets without duplicating graph nodes; If/Else branches and Send message does not iterate.

**Why the other options are incorrect:**

- **A. If/Else node:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A For-Each node iterates over multiple tickets without duplicating graph nodes; If/Else branches and Send message does not iterate.
- **C. Send message node:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A For-Each node iterates over multiple tickets without duplicating graph nodes; If/Else branches and Send message does not iterate.

**Tested concept:** Design workflows, tool-augmented flows, and multistep reasoning pipelines

**Likely exam trap:** Agent, loop and condition nodes have different responsibilities; structured output feeds control flow rather than replacing it.

**Sources:**

- [Microsoft Learn — Get started with building agent-driven workflows using Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-workflows-microsoft-foundry/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=ChGunV55YiU)

###### QA016 M12-Q03. Which of the following best describes how structured agent outputs are used in workflows?

- A. They are ignored once generated, since agents always handle routing automatically
- B. They provide predictable data that can be stored in variables, evaluated with conditions, and trigger workflow steps **(Correct)**
- C. They replace the need for loops and If/Else nodes

**Correct answer:** B. They provide predictable data that can be stored in variables, evaluated with conditions, and trigger workflow steps

**Why it is correct:** Structured outputs create predictable variables for conditions and subsequent steps; they do not remove control-flow nodes or become ignored.

**Why the other options are incorrect:**

- **A. They are ignored once generated, since agents always handle routing automatically:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Structured outputs create predictable variables for conditions and subsequent steps; they do not remove control-flow nodes or become ignored.
- **C. They replace the need for loops and If/Else nodes:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Structured outputs create predictable variables for conditions and subsequent steps; they do not remove control-flow nodes or become ignored.

**Tested concept:** Design workflows, tool-augmented flows, and multistep reasoning pipelines

**Likely exam trap:** Agent, loop and condition nodes have different responsibilities; structured output feeds control flow rather than replacing it.

**Sources:**

- [Microsoft Learn — Get started with building agent-driven workflows using Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-workflows-microsoft-foundry/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=ChGunV55YiU)

##### Evaluate models and apps, including detecting fabrications, relevance, quality, and safety

###### QA017 M02-Q03. Which evaluation metric measures linguistic correctness and natural language quality?

- A. Fluency **(Correct)**
- B. Groundedness
- C. Relevance

**Correct answer:** A. Fluency

**Why it is correct:** Fluency measures linguistic correctness and naturalness; groundedness measures support by context and relevance measures fit to the request.

**Why the other options are incorrect:**

- **B. Groundedness:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Fluency measures linguistic correctness and naturalness; groundedness measures support by context and relevance measures fit to the request.
- **C. Relevance:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Fluency measures linguistic correctness and naturalness; groundedness measures support by context and relevance measures fit to the request.

**Tested concept:** Evaluate models and apps, including detecting fabrications, relevance, quality, and safety

**Likely exam trap:** Match the benchmark/deployment/evaluator to the exact operational property, not the most impressive-sounding option.

**Sources:**

- [Microsoft Learn — Select, deploy, and evaluate Microsoft Foundry models assessment](https://learn.microsoft.com/en-us/training/modules/model-catalog-evaluate/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=71gi8ULxPZQ)

##### Integrate generative workflows into applications by using Foundry SDKs and connectors

###### QA018 M03-Q01. Which endpoint offers the broadest support for OpenAI APIs with Foundry Models?

- A. The Foundry project endpoint
- B. The Azure OpenAI endpoint **(Correct)**
- C. The Foundry Tools endpoint

**Correct answer:** B. The Azure OpenAI endpoint

**Why it is correct:** The Azure OpenAI endpoint exposes the broadest OpenAI-compatible API surface; the project endpoint adds Foundry project capabilities.

**Why the other options are incorrect:**

- **A. The Foundry project endpoint:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Azure OpenAI endpoint exposes the broadest OpenAI-compatible API surface; the project endpoint adds Foundry project capabilities.
- **C. The Foundry Tools endpoint:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Azure OpenAI endpoint exposes the broadest OpenAI-compatible API surface; the project endpoint adds Foundry project capabilities.

**Tested concept:** Integrate generative workflows into applications by using Foundry SDKs and connectors

**Likely exam trap:** Keep project endpoint, Azure OpenAI endpoint, SDK package and API method names distinct.

**Sources:**

- [Microsoft Learn — Develop a generative AI chat app with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/foundry-sdk/07-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tXPry-BRVRs)

###### QA019 M03-Q02. Which package must you install to use the Microsoft Foundry SDK in Python?

- A. Package `azure-foundry`
- B. Package `azure-ai-projects` **(Correct)**
- C. Package `microsoft-foundry-sdk`

**Correct answer:** B. Package `azure-ai-projects`

**Why it is correct:** The official Python package is `azure-ai-projects`; the other package names are not the Foundry SDK package.

**Why the other options are incorrect:**

- **A. Package `azure-foundry`:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The official Python package is `azure-ai-projects`; the other package names are not the Foundry SDK package.
- **C. Package `microsoft-foundry-sdk`:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The official Python package is `azure-ai-projects`; the other package names are not the Foundry SDK package.

**Tested concept:** Integrate generative workflows into applications by using Foundry SDKs and connectors

**Likely exam trap:** Keep project endpoint, Azure OpenAI endpoint, SDK package and API method names distinct.

**Sources:**

- [Microsoft Learn — Develop a generative AI chat app with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/foundry-sdk/07-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tXPry-BRVRs)

###### QA020 M03-Q03. Which method do you use to generate responses with the Responses API?

- A. client.chat.completions.create()
- B. client.get\_response\_id()
- C. client.responses.create() **(Correct)**

**Correct answer:** C. client.responses.create()

**Why it is correct:** The Responses API is invoked with `client.responses.create()`; `chat.completions.create()` calls a different API and the other method is not the generation call.

**Why the other options are incorrect:**

- **A. client.chat.completions.create():** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Responses API is invoked with `client.responses.create()`; `chat.completions.create()` calls a different API and the other method is not the generation call.
- **B. client.get\_response\_id():** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Responses API is invoked with `client.responses.create()`; `chat.completions.create()` calls a different API and the other method is not the generation call.

**Tested concept:** Integrate generative workflows into applications by using Foundry SDKs and connectors

**Likely exam trap:** Keep project endpoint, Azure OpenAI endpoint, SDK package and API method names distinct.

**Sources:**

- [Microsoft Learn — Develop a generative AI chat app with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/foundry-sdk/07-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tXPry-BRVRs)

###### QA021 M17-Q03. When building a Python client application, how do you reference a Foundry agent when calling the OpenAI Responses API?

- A. By passing the agent's API key as a request header to the endpoint.
- B. By specifying the agent name in the agent\_reference field in extra\_body. **(Correct)**
- C. By passing the agent's endpoint URL as the model parameter value.

**Correct answer:** B. By specifying the agent name in the agent\_reference field in extra\_body.

**Why it is correct:** The Foundry agent is referenced through `agent_reference` in `extra_body`; an agent API key header or endpoint-as-model is not the course API pattern.

**Why the other options are incorrect:**

- **A. By passing the agent's API key as a request header to the endpoint.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Foundry agent is referenced through `agent_reference` in `extra_body`; an agent API key header or endpoint-as-model is not the course API pattern.
- **C. By passing the agent's endpoint URL as the model parameter value.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Foundry agent is referenced through `agent_reference` in `extra_body`; an agent API key header or endpoint-as-model is not the course API pattern.

**Tested concept:** Integrate generative workflows into applications by using Foundry SDKs and connectors

**Likely exam trap:** Tool discovery does not equal authentication, and agent references are not ordinary model names.

**Sources:**

- [Microsoft Learn — Develop a Text Analysis Agent with the Azure Language MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-text-analysis-agent-language-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=O1tc09coYO4)

##### Configure an application to connect to a Foundry project

###### QA022 M01-Q03. Which extension should you use in Visual Studio Code to work with Foundry projects?

- A. Python extension for Visual Studio Code
- B. GitHub Copilot
- C. Foundry Toolkit for Visual Studio Code **(Correct)**

**Correct answer:** C. Foundry Toolkit for Visual Studio Code

**Why it is correct:** The current course assessment names Foundry Toolkit for Visual Studio Code as the project extension; the video says the older name Microsoft AI Toolkit.

**Why the other options are incorrect:**

- **A. Python extension for Visual Studio Code:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The current course assessment names Foundry Toolkit for Visual Studio Code as the project extension; the video says the older name Microsoft AI Toolkit.
- **B. GitHub Copilot:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The current course assessment names Foundry Toolkit for Visual Studio Code as the project extension; the video says the older name Microsoft AI Toolkit.

**Tested concept:** Configure an application to connect to a Foundry project

**Likely exam trap:** Do not confuse the resource-management portal, Foundry project portal, Foundry components, or a renamed VS Code extension.

**Sources:**

- [Microsoft Learn — Plan and Prepare to Develop AI Solutions on Azure assessment](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PE_7sP3uN5k)

#### Build agents by using Foundry

##### Define agent roles, goals, conversation-tracking approach, and tool schemas

###### QA023 M13-Q01. What are the key steps to create a Microsoft Foundry Agent using the Microsoft Agent Framework?

- A. Deploy a custom AI model before creating an agent definition in the Azure portal.
- B. Initialize the agent by defining a model in the `AgentThread` constructor.
- C. Create an `AzureAIAgentClient`, define a ChatAgent with instructions and tools, and create an `AgentThread` for conversations. **(Correct)**

**Correct answer:** C. Create an `AzureAIAgentClient`, define a ChatAgent with instructions and tools, and create an `AgentThread` for conversations.

**Why it is correct:** The course pattern creates `AzureAIAgentClient`, defines a `ChatAgent` with instructions/tools, then creates an `AgentThread` for conversation state.

**Why the other options are incorrect:**

- **A. Deploy a custom AI model before creating an agent definition in the Azure portal.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course pattern creates `AzureAIAgentClient`, defines a `ChatAgent` with instructions/tools, then creates an `AgentThread` for conversation state.
- **B. Initialize the agent by defining a model in the `AgentThread` constructor.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course pattern creates `AzureAIAgentClient`, defines a `ChatAgent` with instructions/tools, then creates an `AgentThread` for conversation state.

**Tested concept:** Define agent roles, goals, conversation-tracking approach, and tool schemas

**Likely exam trap:** Separate client, agent definition and conversation thread; tools are attached capabilities.

**Sources:**

- [Microsoft Learn — Develop an AI agent with Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=WznrISPGx-g)

###### QA024 M13-Q02. Which component in the Microsoft Agent Framework manages conversation state and stores messages?

- A. AgentThread **(Correct)**
- B. ChatAgent
- C. AzureAIAgentClient

**Correct answer:** A. AgentThread

**Why it is correct:** `AgentThread` stores messages and conversation state; `ChatAgent` defines behavior and the client connects to the service.

**Why the other options are incorrect:**

- **B. ChatAgent:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `AgentThread` stores messages and conversation state; `ChatAgent` defines behavior and the client connects to the service.
- **C. AzureAIAgentClient:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `AgentThread` stores messages and conversation state; `ChatAgent` defines behavior and the client connects to the service.

**Tested concept:** Define agent roles, goals, conversation-tracking approach, and tool schemas

**Likely exam trap:** Separate client, agent definition and conversation thread; tools are attached capabilities.

**Sources:**

- [Microsoft Learn — Develop an AI agent with Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=WznrISPGx-g)

##### Build agents that integrate retrieval, function-calling, and conversation memory

###### QA025 M07-Q01. What is the primary benefit of using Microsoft Foundry Agent Service compared to building agents with standard APIs?

- A. It provides access to more powerful AI models
- B. It requires no Azure subscription
- C. It handles tool calling, state management, and infrastructure automatically **(Correct)**
- D. It only works with the Azure portal

**Correct answer:** C. It handles tool calling, state management, and infrastructure automatically

**Why it is correct:** Agent Service manages tool calling, state and service infrastructure; it does not remove the Azure requirement or merely provide stronger models.

**Why the other options are incorrect:**

- **A. It provides access to more powerful AI models:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Agent Service manages tool calling, state and service infrastructure; it does not remove the Azure requirement or merely provide stronger models.
- **B. It requires no Azure subscription:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Agent Service manages tool calling, state and service infrastructure; it does not remove the Azure requirement or merely provide stronger models.
- **D. It only works with the Azure portal:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Agent Service manages tool calling, state and service infrastructure; it does not remove the Azure requirement or merely provide stronger models.

**Tested concept:** Build agents that integrate retrieval, function-calling, and conversation memory

**Likely exam trap:** Managed agent state/tool execution does not remove least privilege, validation or human approval where risk requires it.

**Sources:**

- [Microsoft Learn — Develop AI agents with Microsoft Foundry and Visual Studio Code assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-azure-vs-code/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=EmBPT_tIs8Y)

###### QA026 M07-Q02. How does Microsoft Foundry Agent Service handle conversation state?

- A. By requiring developers to manually manage conversation history
- B. Through external database connections
- C. Through the Responses API which automatically manages conversation context **(Correct)**
- D. Using local file storage on the client device

**Correct answer:** C. Through the Responses API which automatically manages conversation context

**Why it is correct:** The Responses API can maintain server-side conversation context; it is not local-file state or necessarily an external database.

**Why the other options are incorrect:**

- **A. By requiring developers to manually manage conversation history:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Responses API can maintain server-side conversation context; it is not local-file state or necessarily an external database.
- **B. Through external database connections:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Responses API can maintain server-side conversation context; it is not local-file state or necessarily an external database.
- **D. Using local file storage on the client device:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Responses API can maintain server-side conversation context; it is not local-file state or necessarily an external database.

**Tested concept:** Build agents that integrate retrieval, function-calling, and conversation memory

**Likely exam trap:** Managed agent state/tool execution does not remove least privilege, validation or human approval where risk requires it.

**Sources:**

- [Microsoft Learn — Develop AI agents with Microsoft Foundry and Visual Studio Code assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-azure-vs-code/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=EmBPT_tIs8Y)

###### QA027 M07-Q04. What happens when an agent determines it needs a tool to respond to a user request?

- A. The agent asks the user for permission to use the tool
- B. The agent stops processing and waits for developer input
- C. The agent automatically invokes the tool, processes results, and incorporates them into its response **(Correct)**
- D. The agent sends the request to a separate processing queue

**Correct answer:** C. The agent automatically invokes the tool, processes results, and incorporates them into its response

**Why it is correct:** For supported managed tools, the agent invokes the selected tool, processes the result and incorporates it; separate approval is enforced only when the workflow requires it.

**Why the other options are incorrect:**

- **A. The agent asks the user for permission to use the tool:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: For supported managed tools, the agent invokes the selected tool, processes the result and incorporates it; separate approval is enforced only when the workflow requires it.
- **B. The agent stops processing and waits for developer input:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: For supported managed tools, the agent invokes the selected tool, processes the result and incorporates it; separate approval is enforced only when the workflow requires it.
- **D. The agent sends the request to a separate processing queue:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: For supported managed tools, the agent invokes the selected tool, processes the result and incorporates it; separate approval is enforced only when the workflow requires it.

**Tested concept:** Build agents that integrate retrieval, function-calling, and conversation memory

**Likely exam trap:** Managed agent state/tool execution does not remove least privilege, validation or human approval where risk requires it.

**Sources:**

- [Microsoft Learn — Develop AI agents with Microsoft Foundry and Visual Studio Code assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agents-azure-vs-code/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=EmBPT_tIs8Y)

###### QA028 M10-Q04. Why is it critical to specify retrieval behavior in agent instructions?

- A. Without proper instructions, agents might answer from training data instead of the knowledge base, provide unverifiable responses, or fail to cite sources. **(Correct)**
- B. Instructions determine the semantic ranking algorithm that Foundry IQ applies to search results.
- C. Instructions enable the agent to automatically update knowledge base content when it detects outdated information.

**Correct answer:** A. Without proper instructions, agents might answer from training data instead of the knowledge base, provide unverifiable responses, or fail to cite sources.

**Why it is correct:** Agent instructions must require use and citation of the knowledge base; ranking and data refresh are separate configuration concerns.

**Why the other options are incorrect:**

- **B. Instructions determine the semantic ranking algorithm that Foundry IQ applies to search results.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Agent instructions must require use and citation of the knowledge base; ranking and data refresh are separate configuration concerns.
- **C. Instructions enable the agent to automatically update knowledge base content when it detects outdated information.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Agent instructions must require use and citation of the knowledge base; ranking and data refresh are separate configuration concerns.

**Tested concept:** Build agents that integrate retrieval, function-calling, and conversation memory

**Likely exam trap:** RAG retrieves current evidence; it does not retrain the model or guarantee citation use without instructions/evaluation.

**Sources:**

- [Microsoft Learn — Build knowledge-enhanced AI agents with Foundry IQ assessment](https://learn.microsoft.com/en-us/training/modules/introduction-foundry-iq/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=c9zns7PX0Io)

##### Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

###### QA029 M04-Q01. Which tool should you use when a model needs to answer questions from your own uploaded policy documents?

- A. web\_search
- B. file\_search **(Correct)**
- C. code\_interpreter

**Correct answer:** B. file\_search

**Why it is correct:** `file_search` retrieves from uploaded files; web search uses the web and code interpreter executes sandboxed Python.

**Why the other options are incorrect:**

- **A. web\_search:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `file_search` retrieves from uploaded files; web search uses the web and code interpreter executes sandboxed Python.
- **C. code\_interpreter:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `file_search` retrieves from uploaded files; web search uses the web and code interpreter executes sandboxed Python.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** A tool declaration does not execute code; the application still validates and runs custom functions.

**Sources:**

- [Microsoft Learn — Develop generative AI apps that use tools assessment](https://learn.microsoft.com/en-us/training/modules/use-generative-ai-tools/08-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=N5DcQ-ZNp_M)

###### QA030 M04-Q02. In a function-calling workflow, what should your application do after the model returns a function\_call item?

- A. Wait for the model to run the function automatically
- B. Run the function in your code and send a function\_call\_output back to the model **(Correct)**
- C. Convert the function call into a web\_search request

**Correct answer:** B. Run the function in your code and send a function\_call\_output back to the model

**Why it is correct:** Function calling asks the application to execute the function and return a `function_call_output`; the model does not run application code automatically.

**Why the other options are incorrect:**

- **A. Wait for the model to run the function automatically:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Function calling asks the application to execute the function and return a `function_call_output`; the model does not run application code automatically.
- **C. Convert the function call into a web\_search request:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Function calling asks the application to execute the function and return a `function_call_output`; the model does not run application code automatically.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** A tool declaration does not execute code; the application still validates and runs custom functions.

**Sources:**

- [Microsoft Learn — Develop generative AI apps that use tools assessment](https://learn.microsoft.com/en-us/training/modules/use-generative-ai-tools/08-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=N5DcQ-ZNp_M)

###### QA031 M04-Q03. Which statement about the code\_interpreter tool is correct?

- A. It can run Python code in a sandboxed runtime to help solve tasks **(Correct)**
- B. It can browse external websites directly during code execution
- C. It only supports file uploads and can't perform calculations

**Correct answer:** A. It can run Python code in a sandboxed runtime to help solve tasks

**Why it is correct:** Code interpreter runs Python in a sandbox for calculations/file analysis; it is not a general web browser and is not limited to upload storage.

**Why the other options are incorrect:**

- **B. It can browse external websites directly during code execution:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Code interpreter runs Python in a sandbox for calculations/file analysis; it is not a general web browser and is not limited to upload storage.
- **C. It only supports file uploads and can't perform calculations:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Code interpreter runs Python in a sandbox for calculations/file analysis; it is not a general web browser and is not limited to upload storage.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** A tool declaration does not execute code; the application still validates and runs custom functions.

**Sources:**

- [Microsoft Learn — Develop generative AI apps that use tools assessment](https://learn.microsoft.com/en-us/training/modules/use-generative-ai-tools/08-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=N5DcQ-ZNp_M)

###### QA032 M08-Q01. What are custom tools, and how can they help you develop effective agents with Microsoft Foundry Agent Service?

- A. Callable functions that an agent can use to extend its capabilities. **(Correct)**
- B. Extensions for Visual Studio Code that make it easier to create and deploy agents.
- C. Fine-tuned models that the agent can use to generate custom output.

**Correct answer:** A. Callable functions that an agent can use to extend its capabilities.

**Why it is correct:** Custom tools are callable capabilities exposed to an agent; they are neither editor extensions nor fine-tuned models.

**Why the other options are incorrect:**

- **B. Extensions for Visual Studio Code that make it easier to create and deploy agents.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Custom tools are callable capabilities exposed to an agent; they are neither editor extensions nor fine-tuned models.
- **C. Fine-tuned models that the agent can use to generate custom output.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Custom tools are callable capabilities exposed to an agent; they are neither editor extensions nor fine-tuned models.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Select function, OpenAPI, Azure Functions or code interpreter by where and how the capability actually runs.

**Sources:**

- [Microsoft Learn — Integrate custom tools into your agent assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=uEEjq-yQw_c)

###### QA033 M08-Q02. You need to integrate functionality from an OpenAPI 3.0-based web service into an agent solution. What should you do?

- A. Add the JSON schema of the web service to the agent's instructions.
- B. Rewrite the web service as a Python function and hard-code it in your agent app.
- C. Add the web service as an OpenAPI specification tool to the agent definition **(Correct)**

**Correct answer:** C. Add the web service as an OpenAPI specification tool to the agent definition

**Why it is correct:** An OpenAPI 3.0 service should be added as an OpenAPI specification tool; copying its schema into instructions does not create an integration.

**Why the other options are incorrect:**

- **A. Add the JSON schema of the web service to the agent's instructions.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An OpenAPI 3.0 service should be added as an OpenAPI specification tool; copying its schema into instructions does not create an integration.
- **B. Rewrite the web service as a Python function and hard-code it in your agent app.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An OpenAPI 3.0 service should be added as an OpenAPI specification tool; copying its schema into instructions does not create an integration.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Select function, OpenAPI, Azure Functions or code interpreter by where and how the capability actually runs.

**Sources:**

- [Microsoft Learn — Integrate custom tools into your agent assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=uEEjq-yQw_c)

###### QA034 M08-Q03. Your agent application code includes a local function that you want the agent to call. What kind of tool should you add to the agent's definition?

- A. Function calling **(Correct)**
- B. Code interpreter
- C. Azure Functions

**Correct answer:** A. Function calling

**Why it is correct:** A local application function is exposed through function calling; code interpreter is sandboxed Python and Azure Functions is for a hosted function service.

**Why the other options are incorrect:**

- **B. Code interpreter:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A local application function is exposed through function calling; code interpreter is sandboxed Python and Azure Functions is for a hosted function service.
- **C. Azure Functions:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A local application function is exposed through function calling; code interpreter is sandboxed Python and Azure Functions is for a hosted function service.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Select function, OpenAPI, Azure Functions or code interpreter by where and how the capability actually runs.

**Sources:**

- [Microsoft Learn — Integrate custom tools into your agent assessment](https://learn.microsoft.com/en-us/training/modules/build-agent-with-custom-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=uEEjq-yQw_c)

###### QA035 M09-Q01. What role does the MCP server play in the MCP agent tool integration?

- A. Runs the AI agent and processes user prompts directly.
- B. Manages network connections between multiple agents.
- C. Hosts tool definitions and makes them available for discovery by the client. **(Correct)**

**Correct answer:** C. Hosts tool definitions and makes them available for discovery by the client.

**Why it is correct:** The MCP server publishes/discovers tool definitions and executes the tool protocol; the client or agent handles prompts and orchestration.

**Why the other options are incorrect:**

- **A. Runs the AI agent and processes user prompts directly.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The MCP server publishes/discovers tool definitions and executes the tool protocol; the client or agent handles prompts and orchestration.
- **B. Manages network connections between multiple agents.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The MCP server publishes/discovers tool definitions and executes the tool protocol; the client or agent handles prompts and orchestration.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** MCP standardizes tool discovery/invocation; it is not agent-to-agent routing or a REST generator.

**Sources:**

- [Microsoft Learn — Integrate MCP Tools with Azure AI Agents assessment](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=pQ9yEEcXNeE)

###### QA036 M09-Q02. How does an MCP client retrieve available tools from the MCP server?

- A. By calling `session.list_tools()` to get the current tool catalog. **(Correct)**
- B. By reading a static JSON file from the server directory.
- C. By subscribing to server events via a WebSocket connection.

**Correct answer:** A. By calling `session.list_tools()` to get the current tool catalog.

**Why it is correct:** `session.list_tools()` performs MCP tool discovery; a static file or mandatory WebSocket subscription is not the MCP discovery call.

**Why the other options are incorrect:**

- **B. By reading a static JSON file from the server directory.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `session.list_tools()` performs MCP tool discovery; a static file or mandatory WebSocket subscription is not the MCP discovery call.
- **C. By subscribing to server events via a WebSocket connection.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `session.list_tools()` performs MCP tool discovery; a static file or mandatory WebSocket subscription is not the MCP discovery call.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** MCP standardizes tool discovery/invocation; it is not agent-to-agent routing or a REST generator.

**Sources:**

- [Microsoft Learn — Integrate MCP Tools with Azure AI Agents assessment](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=pQ9yEEcXNeE)

###### QA037 M09-Q03. Why should MCP tools be wrapped in async functions on the client-side?

- A. To allow the agent to wait for user input.
- B. To enable asynchronous invocation so the agent can call tools without blocking. **(Correct)**
- C. To convert the functions into REST API endpoints automatically.

**Correct answer:** B. To enable asynchronous invocation so the agent can call tools without blocking.

**Why it is correct:** Async wrappers let tool calls complete without blocking the agent loop; they do not collect user input or create REST endpoints.

**Why the other options are incorrect:**

- **A. To allow the agent to wait for user input.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Async wrappers let tool calls complete without blocking the agent loop; they do not collect user input or create REST endpoints.
- **C. To convert the functions into REST API endpoints automatically.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Async wrappers let tool calls complete without blocking the agent loop; they do not collect user input or create REST endpoints.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** MCP standardizes tool discovery/invocation; it is not agent-to-agent routing or a REST generator.

**Sources:**

- [Microsoft Learn — Integrate MCP Tools with Azure AI Agents assessment](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=pQ9yEEcXNeE)

###### QA038 M11-Q01. What Azure resource does the Foundry portal automatically create when you publish an agent to Microsoft Teams?

- A. Azure Functions
- B. Azure Bot Service **(Correct)**
- C. Azure Cosmos DB
- D. Azure Logic Apps

**Correct answer:** B. Azure Bot Service

**Why it is correct:** Publishing from Foundry to Teams creates Azure Bot Service as the channel-facing resource; the other services are not the automatic publishing resource.

**Why the other options are incorrect:**

- **A. Azure Functions:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Publishing from Foundry to Teams creates Azure Bot Service as the channel-facing resource; the other services are not the automatic publishing resource.
- **C. Azure Cosmos DB:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Publishing from Foundry to Teams creates Azure Bot Service as the channel-facing resource; the other services are not the automatic publishing resource.
- **D. Azure Logic Apps:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Publishing from Foundry to Teams creates Azure Bot Service as the channel-facing resource; the other services are not the automatic publishing resource.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Publishing creates a new runtime identity; channels/scopes do not inherit every development permission.

**Sources:**

- [Microsoft Learn — Integrate your agent with Microsoft 365 assessment](https://learn.microsoft.com/en-us/training/modules/integrate-foundry-agent-with-m365/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=eWYOZkFoNn4)

###### QA039 M11-Q02. What is the main difference between shared scope and organization scope when publishing an agent?

- A. Shared scope requires more Azure resources
- B. Organization scope requires admin approval before the agent is available to all users **(Correct)**
- C. Shared scope only works in the Foundry playground
- D. Organization scope provides better agent performance

**Correct answer:** B. Organization scope requires admin approval before the agent is available to all users

**Why it is correct:** Organization scope requires administrator approval before broad organizational availability; shared scope is narrower sharing.

**Why the other options are incorrect:**

- **A. Shared scope requires more Azure resources:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Organization scope requires administrator approval before broad organizational availability; shared scope is narrower sharing.
- **C. Shared scope only works in the Foundry playground:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Organization scope requires administrator approval before broad organizational availability; shared scope is narrower sharing.
- **D. Organization scope provides better agent performance:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Organization scope requires administrator approval before broad organizational availability; shared scope is narrower sharing.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Publishing creates a new runtime identity; channels/scopes do not inherit every development permission.

**Sources:**

- [Microsoft Learn — Integrate your agent with Microsoft 365 assessment](https://learn.microsoft.com/en-us/training/modules/integrate-foundry-agent-with-m365/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=eWYOZkFoNn4)

###### QA040 M11-Q03. What happens to tool permissions when you publish an agent from Foundry to Teams?

- A. Permissions are automatically transferred to the published agent
- B. Tools are disabled after publishing
- C. The published agent gets a new identity and needs permissions reassigned **(Correct)**
- D. Permissions only work in organization scope

**Correct answer:** C. The published agent gets a new identity and needs permissions reassigned

**Why it is correct:** The published agent receives a new identity, so tool permissions must be assigned to that identity rather than being transferred automatically.

**Why the other options are incorrect:**

- **A. Permissions are automatically transferred to the published agent:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The published agent receives a new identity, so tool permissions must be assigned to that identity rather than being transferred automatically.
- **B. Tools are disabled after publishing:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The published agent receives a new identity, so tool permissions must be assigned to that identity rather than being transferred automatically.
- **D. Permissions only work in organization scope:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The published agent receives a new identity, so tool permissions must be assigned to that identity rather than being transferred automatically.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Publishing creates a new runtime identity; channels/scopes do not inherit every development permission.

**Sources:**

- [Microsoft Learn — Integrate your agent with Microsoft 365 assessment](https://learn.microsoft.com/en-us/training/modules/integrate-foundry-agent-with-m365/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=eWYOZkFoNn4)

###### QA041 M11-Q04. What is Microsoft Work IQ?

- A. A machine learning model for workplace analytics
- B. A CLI and MCP server that connects AI agents to Microsoft 365 data **(Correct)**
- C. A replacement for Microsoft Teams
- D. A Visual Studio Code extension for building agents

**Correct answer:** B. A CLI and MCP server that connects AI agents to Microsoft 365 data

**Why it is correct:** Microsoft Work IQ is the CLI/MCP-server integration described by the course for Microsoft 365 data; it is not a model, Teams replacement or editor extension.

**Why the other options are incorrect:**

- **A. A machine learning model for workplace analytics:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft Work IQ is the CLI/MCP-server integration described by the course for Microsoft 365 data; it is not a model, Teams replacement or editor extension.
- **C. A replacement for Microsoft Teams:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft Work IQ is the CLI/MCP-server integration described by the course for Microsoft 365 data; it is not a model, Teams replacement or editor extension.
- **D. A Visual Studio Code extension for building agents:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft Work IQ is the CLI/MCP-server integration described by the course for Microsoft 365 data; it is not a model, Teams replacement or editor extension.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Publishing creates a new runtime identity; channels/scopes do not inherit every development permission.

**Sources:**

- [Microsoft Learn — Integrate your agent with Microsoft 365 assessment](https://learn.microsoft.com/en-us/training/modules/integrate-foundry-agent-with-m365/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=eWYOZkFoNn4)

###### QA042 M11-Q05. When should you consider using the Microsoft 365 Agents Toolkit instead of direct publishing from Foundry?

- A. For all production deployments
- B. When you need custom SSO, middleware logic, or multi-environment deployment **(Correct)**
- C. When publishing to shared scope
- D. When your agent doesn't use any tools

**Correct answer:** B. When you need custom SSO, middleware logic, or multi-environment deployment

**Why it is correct:** Microsoft 365 Agents Toolkit is appropriate when custom SSO, middleware or multi-environment deployment is needed beyond direct publishing.

**Why the other options are incorrect:**

- **A. For all production deployments:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft 365 Agents Toolkit is appropriate when custom SSO, middleware or multi-environment deployment is needed beyond direct publishing.
- **C. When publishing to shared scope:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft 365 Agents Toolkit is appropriate when custom SSO, middleware or multi-environment deployment is needed beyond direct publishing.
- **D. When your agent doesn't use any tools:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Microsoft 365 Agents Toolkit is appropriate when custom SSO, middleware or multi-environment deployment is needed beyond direct publishing.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Publishing creates a new runtime identity; channels/scopes do not inherit every development permission.

**Sources:**

- [Microsoft Learn — Integrate your agent with Microsoft 365 assessment](https://learn.microsoft.com/en-us/training/modules/integrate-foundry-agent-with-m365/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=eWYOZkFoNn4)

###### QA043 M13-Q03. How do you add custom functionality to a Microsoft Foundry Agent in the Microsoft Agent Framework?

- A. Configure custom functions in the Azure portal and link them to the agent through connection strings.
- B. Create Python functions with proper type annotations and descriptions, then pass them to the ChatAgent's tools parameter. **(Correct)**
- C. Modify the AI model's architecture to integrate the custom functionality directly.

**Correct answer:** B. Create Python functions with proper type annotations and descriptions, then pass them to the ChatAgent's tools parameter.

**Why it is correct:** Typed, described Python functions are passed in the agent tool collection; the model architecture and portal connection strings are not modified.

**Why the other options are incorrect:**

- **A. Configure custom functions in the Azure portal and link them to the agent through connection strings.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Typed, described Python functions are passed in the agent tool collection; the model architecture and portal connection strings are not modified.
- **C. Modify the AI model's architecture to integrate the custom functionality directly.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Typed, described Python functions are passed in the agent tool collection; the model architecture and portal connection strings are not modified.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Separate client, agent definition and conversation thread; tools are attached capabilities.

**Sources:**

- [Microsoft Learn — Develop an AI agent with Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/develop-ai-agent-with-semantic-kernel/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=WznrISPGx-g)

###### QA044 M17-Q01. What is the primary role of the Azure Language MCP server?

- A. To train and fine-tune custom language models for use by AI agents.
- B. To expose Azure Language text analysis capabilities as MCP tools for agents. **(Correct)**
- C. To deploy and manage large language models in an Azure subscription.

**Correct answer:** B. To expose Azure Language text analysis capabilities as MCP tools for agents.

**Why it is correct:** The Azure Language MCP server exposes Azure Language analysis features as discoverable MCP tools; it does not train or deploy LLMs.

**Why the other options are incorrect:**

- **A. To train and fine-tune custom language models for use by AI agents.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Azure Language MCP server exposes Azure Language analysis features as discoverable MCP tools; it does not train or deploy LLMs.
- **C. To deploy and manage large language models in an Azure subscription.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Azure Language MCP server exposes Azure Language analysis features as discoverable MCP tools; it does not train or deploy LLMs.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Tool discovery does not equal authentication, and agent references are not ordinary model names.

**Sources:**

- [Microsoft Learn — Develop a Text Analysis Agent with the Azure Language MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-text-analysis-agent-language-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=O1tc09coYO4)

###### QA045 M17-Q02. How does an agent determine which Azure Language MCP tool to call when processing a user's prompt?

- A. The developer writes routing logic to direct each prompt to a specific tool.
- B. The agent matches the prompt to tool descriptions received from the MCP server. **(Correct)**
- C. The MCP server analyzes the prompt and automatically routes it to a tool.

**Correct answer:** B. The agent matches the prompt to tool descriptions received from the MCP server.

**Why it is correct:** The agent selects a tool by matching the request to MCP-provided tool descriptions; neither custom routing code nor the server automatically reasons over the prompt.

**Why the other options are incorrect:**

- **A. The developer writes routing logic to direct each prompt to a specific tool.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The agent selects a tool by matching the request to MCP-provided tool descriptions; neither custom routing code nor the server automatically reasons over the prompt.
- **C. The MCP server analyzes the prompt and automatically routes it to a tool.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The agent selects a tool by matching the request to MCP-provided tool descriptions; neither custom routing code nor the server automatically reasons over the prompt.

**Tested concept:** Integrate agent tools, including APIs, knowledge stores, search, content understanding, and custom functions

**Likely exam trap:** Tool discovery does not equal authentication, and agent references are not ordinary model names.

**Sources:**

- [Microsoft Learn — Develop a Text Analysis Agent with the Azure Language MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-text-analysis-agent-language-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=O1tc09coYO4)

##### Implement orchestrated multi-agent solutions

###### QA046 M14-Q01. What's the first step in the Microsoft Agent Framework's unified orchestration workflow?

- A. Select and create an orchestration pattern
- B. Define your agents and describe their capabilities **(Correct)**
- C. Start a runtime to manage execution

**Correct answer:** B. Define your agents and describe their capabilities

**Why it is correct:** Define agents and describe their capabilities before selecting/creating the orchestration pattern and running it.

**Why the other options are incorrect:**

- **A. Select and create an orchestration pattern:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Define agents and describe their capabilities before selecting/creating the orchestration pattern and running it.
- **C. Start a runtime to manage execution:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Define agents and describe their capabilities before selecting/creating the orchestration pattern and running it.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** Choose the orchestration pattern from collaboration/routing behavior, not from the number of agents.

**Sources:**

- [Microsoft Learn — Orchestrate a multi-agent solution using the Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=l3oAcAWySlE)

###### QA047 M14-Q02. For brainstorming and collaborative problem solving among multiple agents, which orchestration pattern is most suitable?

- A. Group Chat **(Correct)**
- B. Magentic
- C. Sequential

**Correct answer:** A. Group Chat

**Why it is correct:** Group Chat is designed for collaborative discussion/brainstorming; Sequential is fixed order and Magentic is a different dynamic planning pattern.

**Why the other options are incorrect:**

- **B. Magentic:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Group Chat is designed for collaborative discussion/brainstorming; Sequential is fixed order and Magentic is a different dynamic planning pattern.
- **C. Sequential:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Group Chat is designed for collaborative discussion/brainstorming; Sequential is fixed order and Magentic is a different dynamic planning pattern.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** Choose the orchestration pattern from collaboration/routing behavior, not from the number of agents.

**Sources:**

- [Microsoft Learn — Orchestrate a multi-agent solution using the Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=l3oAcAWySlE)

###### QA048 M14-Q03. Which pattern dynamically transfers control between agents based on context or rules?

- A. Handoff **(Correct)**
- B. Concurrent
- C. Sequential

**Correct answer:** A. Handoff

**Why it is correct:** Handoff transfers control dynamically between agents; Concurrent runs in parallel and Sequential follows a fixed order.

**Why the other options are incorrect:**

- **B. Concurrent:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Handoff transfers control dynamically between agents; Concurrent runs in parallel and Sequential follows a fixed order.
- **C. Sequential:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Handoff transfers control dynamically between agents; Concurrent runs in parallel and Sequential follows a fixed order.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** Choose the orchestration pattern from collaboration/routing behavior, not from the number of agents.

**Sources:**

- [Microsoft Learn — Orchestrate a multi-agent solution using the Microsoft Agent Framework assessment](https://learn.microsoft.com/en-us/training/modules/orchestrate-semantic-kernel-multi-agent-solution/10-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=l3oAcAWySlE)

###### QA049 M15-Q01. What is the primary role of an A2A server?

- A. It executes business logic for the agent directly.
- B. It routes requests between clients and connected agents. **(Correct)**
- C. It stores static agent responses for reuse.

**Correct answer:** B. It routes requests between clients and connected agents.

**Why it is correct:** An A2A server routes protocol requests between clients and connected agents; business execution remains with the agent/executor.

**Why the other options are incorrect:**

- **A. It executes business logic for the agent directly.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An A2A server routes protocol requests between clients and connected agents; business execution remains with the agent/executor.
- **C. It stores static agent responses for reuse.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An A2A server routes protocol requests between clients and connected agents; business execution remains with the agent/executor.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** A2A agent cards advertise capabilities; executors run agent work and servers route protocol requests.

**Sources:**

- [Microsoft Learn — Discover Azure AI Agents with A2A assessment](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/7-knowledge-check)

###### QA050 M15-Q02. What does the Agent Executor do in an A2A agent?

- A. Manages network connections between clients and servers.
- B. Processes incoming requests and generates responses or events. **(Correct)**
- C. Provides a GUI for monitoring agent activity.

**Correct answer:** B. Processes incoming requests and generates responses or events.

**Why it is correct:** The Agent Executor processes incoming requests and emits responses/events; it is not a transport manager or GUI.

**Why the other options are incorrect:**

- **A. Manages network connections between clients and servers.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Agent Executor processes incoming requests and emits responses/events; it is not a transport manager or GUI.
- **C. Provides a GUI for monitoring agent activity.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Agent Executor processes incoming requests and emits responses/events; it is not a transport manager or GUI.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** A2A agent cards advertise capabilities; executors run agent work and servers route protocol requests.

**Sources:**

- [Microsoft Learn — Discover Azure AI Agents with A2A assessment](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/7-knowledge-check)

###### QA051 M15-Q03. What is an agent card used for in A2A?

- A. It stores the agent's API key for authentication.
- B. It provides metadata about the agent, such as its capabilities and available functions. **(Correct)**
- C. It visualizes the agent's workflow in a GUI dashboard.

**Correct answer:** B. It provides metadata about the agent, such as its capabilities and available functions.

**Why it is correct:** An agent card advertises metadata and capabilities for discovery; it must not store API keys and is not a workflow dashboard.

**Why the other options are incorrect:**

- **A. It stores the agent's API key for authentication.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An agent card advertises metadata and capabilities for discovery; it must not store API keys and is not a workflow dashboard.
- **C. It visualizes the agent's workflow in a GUI dashboard.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An agent card advertises metadata and capabilities for discovery; it must not store API keys and is not a workflow dashboard.

**Tested concept:** Implement orchestrated multi-agent solutions

**Likely exam trap:** A2A agent cards advertise capabilities; executors run agent work and servers route protocol requests.

**Sources:**

- [Microsoft Learn — Discover Azure AI Agents with A2A assessment](https://learn.microsoft.com/en-us/training/modules/discover-agents-with-a2a/7-knowledge-check)

##### Build autonomous or semiautonomous workflows with safeguards and approval flow controls

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Integrate monitoring into deployed agents, evaluate agent behavior, and perform error analysis

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Optimize and operationalize generative AI systems

##### Tune generation behavior, such as prompt engineering and adjusting model parameters

###### QA052 M05-Q01. What is the primary purpose of a system message in a prompt?

- A. To define the model's role, behavior, and output constraints. **(Correct)**
- B. To provide training data that permanently changes the model.
- C. To retrieve data from an external data source.

**Correct answer:** A. To define the model's role, behavior, and output constraints.

**Why it is correct:** A system message defines stable role, behavior and constraints; it neither retrains the model nor retrieves external data.

**Why the other options are incorrect:**

- **B. To provide training data that permanently changes the model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A system message defines stable role, behavior and constraints; it neither retrains the model nor retrieves external data.
- **C. To retrieve data from an external data source.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A system message defines stable role, behavior and constraints; it neither retrains the model nor retrieves external data.

**Tested concept:** Tune generation behavior, such as prompt engineering and adjusting model parameters

**Likely exam trap:** Prompting changes instructions, RAG changes context, fine-tuning changes behavior, and temperature changes sampling.

**Sources:**

- [Microsoft Learn — Optimize generative AI model performance with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Ocx76q4p9ME)

###### QA053 M05-Q03. What does the temperature parameter control in a language model?

- A. The maximum number of tokens the model can generate.
- B. The randomness and creativity of the model's responses. **(Correct)**
- C. The speed at which the model processes requests.

**Correct answer:** B. The randomness and creativity of the model's responses.

**Why it is correct:** Temperature controls sampling randomness/variation, not token limit or processing speed.

**Why the other options are incorrect:**

- **A. The maximum number of tokens the model can generate.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Temperature controls sampling randomness/variation, not token limit or processing speed.
- **C. The speed at which the model processes requests.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Temperature controls sampling randomness/variation, not token limit or processing speed.

**Tested concept:** Tune generation behavior, such as prompt engineering and adjusting model parameters

**Likely exam trap:** Prompting changes instructions, RAG changes context, fine-tuning changes behavior, and temperature changes sampling.

**Sources:**

- [Microsoft Learn — Optimize generative AI model performance with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Ocx76q4p9ME)

###### QA054 M05-Q04. What does fine-tuning optimize in a language model?

- A. The factual accuracy of responses by connecting to external data.
- B. The consistency of the model's behavior, style, and output format. **(Correct)**
- C. The number of tokens the model can process in a single request.

**Correct answer:** B. The consistency of the model's behavior, style, and output format.

**Why it is correct:** Fine-tuning targets learned behavior, style and format consistency; external factual freshness belongs to RAG and context-window size is model-specific.

**Why the other options are incorrect:**

- **A. The factual accuracy of responses by connecting to external data.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Fine-tuning targets learned behavior, style and format consistency; external factual freshness belongs to RAG and context-window size is model-specific.
- **C. The number of tokens the model can process in a single request.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Fine-tuning targets learned behavior, style and format consistency; external factual freshness belongs to RAG and context-window size is model-specific.

**Tested concept:** Tune generation behavior, such as prompt engineering and adjusting model parameters

**Likely exam trap:** Prompting changes instructions, RAG changes context, fine-tuning changes behavior, and temperature changes sampling.

**Sources:**

- [Microsoft Learn — Optimize generative AI model performance with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Ocx76q4p9ME)

###### QA055 M05-Q05. You're building a chat application that needs to answer questions using your company's product catalog while maintaining a specific brand voice. Which combination of strategies is most appropriate?

- A. Prompt engineering only, with detailed system messages.
- B. RAG for the product catalog data, fine-tuning for the brand voice, and prompt engineering for conversation-specific instructions. **(Correct)**
- C. Fine-tuning only, with the product catalog included in the training data.

**Correct answer:** B. RAG for the product catalog data, fine-tuning for the brand voice, and prompt engineering for conversation-specific instructions.

**Why it is correct:** RAG supplies changing catalog facts, fine-tuning can shape stable brand behavior, and prompts carry turn-specific instructions.

**Why the other options are incorrect:**

- **A. Prompt engineering only, with detailed system messages.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG supplies changing catalog facts, fine-tuning can shape stable brand behavior, and prompts carry turn-specific instructions.
- **C. Fine-tuning only, with the product catalog included in the training data.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: RAG supplies changing catalog facts, fine-tuning can shape stable brand behavior, and prompts carry turn-specific instructions.

**Tested concept:** Tune generation behavior, such as prompt engineering and adjusting model parameters

**Likely exam trap:** Prompting changes instructions, RAG changes context, fine-tuning changes behavior, and temperature changes sampling.

**Sources:**

- [Microsoft Learn — Optimize generative AI model performance with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/optimize-generative-ai-model-performance/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Ocx76q4p9ME)

##### Implement model reflection, chain-of-thought evaluations, and self-critique loops

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Set up observability by implementing tracing, token analytics, safety signals, and latency breakdowns

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Orchestrate multiple models, flows, or hybrid LLM and rules engines

> No distinct question from the specified official source assessment sections maps directly to this objective.

### Implement computer vision solutions (10–15%)

#### Design and implement image- and video-generation solutions

##### Implement a solution that generates images from text prompts and reference media

###### QA056 M24-Q01. You want to find a model in Microsoft Foundry to generate images. Which inference task should you filter by?

- A. Text to image **(Correct)**
- B. Image to text
- C. Embeddings

**Correct answer:** A. Text to image

**Why it is correct:** Text-to-image is the relevant model-catalog inference task; image-to-text analyzes images and embeddings create vectors.

**Why the other options are incorrect:**

- **B. Image to text:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Text-to-image is the relevant model-catalog inference task; image-to-text analyzes images and embeddings create vectors.
- **C. Embeddings:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Text-to-image is the relevant model-catalog inference task; image-to-text analyzes images and embeddings create vectors.

**Tested concept:** Implement a solution that generates images from text prompts and reference media

**Likely exam trap:** Filter model catalog by the correct inference task and call the model through its supported API.

**Sources:**

- [Microsoft Learn — Generate images with AI assessment](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=XNeW6L8wj9k)

###### QA057 M24-Q02. Which OpenAI API can you use with image-generation models?

- A. Video
- B. Image **(Correct)**
- C. Graphics

**Correct answer:** B. Image

**Why it is correct:** The OpenAI Images API is the supported image-generation API; “Graphics” is not the API and Video targets video jobs.

**Why the other options are incorrect:**

- **A. Video:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The OpenAI Images API is the supported image-generation API; “Graphics” is not the API and Video targets video jobs.
- **C. Graphics:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The OpenAI Images API is the supported image-generation API; “Graphics” is not the API and Video targets video jobs.

**Tested concept:** Implement a solution that generates images from text prompts and reference media

**Likely exam trap:** Filter model catalog by the correct inference task and call the model through its supported API.

**Sources:**

- [Microsoft Learn — Generate images with AI assessment](https://learn.microsoft.com/en-us/training/modules/generate-images-azure-openai/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=XNeW6L8wj9k)

##### Implement a solution that generates videos from text prompts and reference media

###### QA058 M25-Q01. What video durations does Sora 2 support?

- A. 1 to 20 seconds in 1-second increments
- B. 4, 8, or 12 seconds **(Correct)**
- C. Any duration up to 60 seconds

**Correct answer:** B. 4, 8, or 12 seconds

**Why it is correct:** The course assessment states Sora 2 supports 4-, 8- or 12-second generations; arbitrary 1-second increments or 60 seconds are not the listed controls.

**Why the other options are incorrect:**

- **A. 1 to 20 seconds in 1-second increments:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course assessment states Sora 2 supports 4-, 8- or 12-second generations; arbitrary 1-second increments or 60 seconds are not the listed controls.
- **C. Any duration up to 60 seconds:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course assessment states Sora 2 supports 4-, 8- or 12-second generations; arbitrary 1-second increments or 60 seconds are not the listed controls.

**Tested concept:** Implement a solution that generates videos from text prompts and reference media

**Likely exam trap:** Sora controls are model-specific preview details; do not generalize from image generation.

**Sources:**

- [Microsoft Learn — Generate videos with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/generate-video-with-foundry/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=XNeW6L8wj9k)

###### QA059 M25-Q02. What is required when using a reference image with Sora 2?

- A. The image must be smaller than 1 MB
- B. The image resolution must match the target video size **(Correct)**
- C. The image must contain at least one human face

**Correct answer:** B. The image resolution must match the target video size

**Why it is correct:** A Sora 2 reference image must match the requested target video resolution; file size/face presence are not the stated requirement.

**Why the other options are incorrect:**

- **A. The image must be smaller than 1 MB:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A Sora 2 reference image must match the requested target video resolution; file size/face presence are not the stated requirement.
- **C. The image must contain at least one human face:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A Sora 2 reference image must match the requested target video resolution; file size/face presence are not the stated requirement.

**Tested concept:** Implement a solution that generates videos from text prompts and reference media

**Likely exam trap:** Sora controls are model-specific preview details; do not generalize from image generation.

**Sources:**

- [Microsoft Learn — Generate videos with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/generate-video-with-foundry/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=XNeW6L8wj9k)

##### Configure image-editing workflows, including inpainting, mask‑based edits, and prompt‑driven modifications

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement workflows to edit generated videos

###### QA060 M25-Q03. What is the remix feature used for in Sora 2?

- A. Combining multiple videos into one
- B. Making targeted adjustments to an existing video without regenerating from scratch **(Correct)**
- C. Adding background music to generated videos

**Correct answer:** B. Making targeted adjustments to an existing video without regenerating from scratch

**Why it is correct:** Remix applies targeted changes to an existing generated video; it is not a video concatenation or audio-music feature.

**Why the other options are incorrect:**

- **A. Combining multiple videos into one:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Remix applies targeted changes to an existing generated video; it is not a video concatenation or audio-music feature.
- **C. Adding background music to generated videos:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Remix applies targeted changes to an existing generated video; it is not a video concatenation or audio-music feature.

**Tested concept:** Implement workflows to edit generated videos

**Likely exam trap:** Sora controls are model-specific preview details; do not generalize from image generation.

**Sources:**

- [Microsoft Learn — Generate videos with Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/generate-video-with-foundry/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=XNeW6L8wj9k)

##### Select and apply appropriate generation and editing controls provided by the platform

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Design and implement multimodal understanding workflows

##### Build a solution that analyzes visual context by using multimodal models

###### QA061 M23-Q01. Which kind of model can you use to respond to visual input?

- A. Only OpenAI GPT models
- B. Embedding models
- C. Multimodal models **(Correct)**

**Correct answer:** C. Multimodal models

**Why it is correct:** Multimodal models accept visual and textual input; embedding models produce vectors and GPT is not the only possible model family.

**Why the other options are incorrect:**

- **A. Only OpenAI GPT models:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Multimodal models accept visual and textual input; embedding models produce vectors and GPT is not the only possible model family.
- **B. Embedding models:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Multimodal models accept visual and textual input; embedding models produce vectors and GPT is not the only possible model family.

**Tested concept:** Build a solution that analyzes visual context by using multimodal models

**Likely exam trap:** Vision input belongs in a multipart user message to a multimodal model; embeddings do not answer visual questions.

**Sources:**

- [Microsoft Learn — Develop a vision-enabled generative AI application assessment](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Xlo-VDqYrz4)

###### QA062 M23-Q02. How can you submit a prompt that asks a model to analyze an image?

- A. Submit one prompt with an image-based message followed by another prompt with a text-based message.
- B. Submit a prompt that contains a multi-part user message, containing both text content and image content. **(Correct)**
- C. Submit the image as the system message and the instruction or question as the user message.

**Correct answer:** B. Submit a prompt that contains a multi-part user message, containing both text content and image content.

**Why it is correct:** A single multipart user message can contain both text instruction and image content, preserving their relationship.

**Why the other options are incorrect:**

- **A. Submit one prompt with an image-based message followed by another prompt with a text-based message.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A single multipart user message can contain both text instruction and image content, preserving their relationship.
- **C. Submit the image as the system message and the instruction or question as the user message.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A single multipart user message can contain both text instruction and image content, preserving their relationship.

**Tested concept:** Build a solution that analyzes visual context by using multimodal models

**Likely exam trap:** Vision input belongs in a multipart user message to a multimodal model; embeddings do not answer visual questions.

**Sources:**

- [Microsoft Learn — Develop a vision-enabled generative AI application assessment](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Xlo-VDqYrz4)

###### QA063 M23-Q03. How can you include an image in a message?

- A. As a URL or as binary data **(Correct)**
- B. Only as a URL
- C. Only as binary data

**Correct answer:** A. As a URL or as binary data

**Why it is correct:** Supported image inputs can be supplied by URL or encoded binary/data content; the API is not restricted to only one of these forms.

**Why the other options are incorrect:**

- **B. Only as a URL:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Supported image inputs can be supplied by URL or encoded binary/data content; the API is not restricted to only one of these forms.
- **C. Only as binary data:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Supported image inputs can be supplied by URL or encoded binary/data content; the API is not restricted to only one of these forms.

**Tested concept:** Build a solution that analyzes visual context by using multimodal models

**Likely exam trap:** Vision input belongs in a multipart user message to a multimodal model; embeddings do not answer visual questions.

**Sources:**

- [Microsoft Learn — Develop a vision-enabled generative AI application assessment](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-vision-apps/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=Xlo-VDqYrz4)

##### Configure apps to produce concise or detailed captions for single or multiple images

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement a solution that enables question‑answering grounded in visual evidence

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Configure generation of alt‑text and extended image descriptions aligned to accessibility guidelines

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

###### QA064 M26-Q01. What is the purpose of grounding in Content Understanding?

- A. To connect Content Understanding to Azure storage
- B. To identify the specific regions in content where each value was extracted **(Correct)**
- C. To filter out harmful content from images

**Correct answer:** B. To identify the specific regions in content where each value was extracted

**Why it is correct:** Grounding identifies source regions for extracted values, enabling evidence review; it is unrelated to storage connectivity or safety filtering.

**Why the other options are incorrect:**

- **A. To connect Content Understanding to Azure storage:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Grounding identifies source regions for extracted values, enabling evidence review; it is unrelated to storage connectivity or safety filtering.
- **C. To filter out harmful content from images:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Grounding identifies source regions for extracted values, enabling evidence review; it is unrelated to storage connectivity or safety filtering.

**Tested concept:** Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

**Likely exam trap:** Grounding, confidence and prebuilt analyzer type answer different Content Understanding questions.

**Sources:**

- [Microsoft Learn — Analyze Images with Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-images-with-content-understanding/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PLbh3DdyZS8)

###### QA065 M26-Q02. What does a confidence score of 0.95 indicate for an extracted field?

- A. The extraction failed and needs manual review
- B. The value can be trusted for automated processing **(Correct)**
- C. The field was classified rather than extracted

**Correct answer:** B. The value can be trusted for automated processing

**Why it is correct:** A 0.95 confidence score indicates high extraction confidence suitable for automated processing under the scenario; it does not mean failure or classification.

**Why the other options are incorrect:**

- **A. The extraction failed and needs manual review:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A 0.95 confidence score indicates high extraction confidence suitable for automated processing under the scenario; it does not mean failure or classification.
- **C. The field was classified rather than extracted:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A 0.95 confidence score indicates high extraction confidence suitable for automated processing under the scenario; it does not mean failure or classification.

**Tested concept:** Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

**Likely exam trap:** Grounding, confidence and prebuilt analyzer type answer different Content Understanding questions.

**Sources:**

- [Microsoft Learn — Analyze Images with Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-images-with-content-understanding/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PLbh3DdyZS8)

###### QA066 M26-Q03. Which prebuilt analyzer would you use to extract vendor names and item totals from a purchase receipt?

- A. prebuilt-image
- B. prebuilt-invoice
- C. prebuilt-receipt **(Correct)**

**Correct answer:** C. prebuilt-receipt

**Why it is correct:** `prebuilt-receipt` is designed for receipt vendors/items/totals; invoice and generic image analyzers serve different document/task types.

**Why the other options are incorrect:**

- **A. prebuilt-image:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `prebuilt-receipt` is designed for receipt vendors/items/totals; invoice and generic image analyzers serve different document/task types.
- **B. prebuilt-invoice:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `prebuilt-receipt` is designed for receipt vendors/items/totals; invoice and generic image analyzers serve different document/task types.

**Tested concept:** Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

**Likely exam trap:** Grounding, confidence and prebuilt analyzer type answer different Content Understanding questions.

**Sources:**

- [Microsoft Learn — Analyze Images with Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-images-with-content-understanding/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=PLbh3DdyZS8)

###### QA067 M27-Q01. What kinds of AI solution is Azure Content Understanding designed to help you build?

- A. Chatbots that automatically translate between multiple spoken and written languages.
- B. Analyzers that extract information from documents, images, videos, and audio files. **(Correct)**
- C. Image generators that create visualizations based on descriptions.

**Correct answer:** B. Analyzers that extract information from documents, images, videos, and audio files.

**Why it is correct:** Content Understanding builds analyzers for documents, images, video and audio; it is not a translator or media generator.

**Why the other options are incorrect:**

- **A. Chatbots that automatically translate between multiple spoken and written languages.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Content Understanding builds analyzers for documents, images, video and audio; it is not a translator or media generator.
- **C. Image generators that create visualizations based on descriptions.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Content Understanding builds analyzers for documents, images, video and audio; it is not a translator or media generator.

**Tested concept:** Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

**Likely exam trap:** Content Understanding uses analyzers and schemas; it is neither a search index nor model-training cluster.

**Sources:**

- [Microsoft Learn — Create a multimodal analysis solution with Azure Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)

###### QA068 M27-Q02. Which graphical tool should you use to create an Azure Content Understanding project?

- A. Microsoft Visual Studio.
- B. Azure Machine Learning studio.
- C. Content Understanding Studio. **(Correct)**

**Correct answer:** C. Content Understanding Studio.

**Why it is correct:** Content Understanding Studio is the graphical analyzer-design tool; Visual Studio and Azure Machine Learning studio serve other development tasks.

**Why the other options are incorrect:**

- **A. Microsoft Visual Studio.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Content Understanding Studio is the graphical analyzer-design tool; Visual Studio and Azure Machine Learning studio serve other development tasks.
- **B. Azure Machine Learning studio.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Content Understanding Studio is the graphical analyzer-design tool; Visual Studio and Azure Machine Learning studio serve other development tasks.

**Tested concept:** Implement visual understanding by configuring Azure Content Understanding in Foundry Tools to extract visual characteristics

**Likely exam trap:** Content Understanding uses analyzers and schemas; it is neither a search index nor model-training cluster.

**Sources:**

- [Microsoft Learn — Create a multimodal analysis solution with Azure Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)

##### Implement video analysis workflows to process and interpret video segments

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Configure single‑task and pro‑mode Content Understanding pipelines

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement solutions that identify objects, components, or regions within images or video

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Implement responsible AI for multimodal content

##### Implement filters to classify unsafe or disallowed visual content

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Detect and mitigate indirect prompt injection by using embedded text in images

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Enforce visual policy rules, such as applying watermarks, flagging prohibited symbols, upholding brand usage requirements, and detecting potentially inappropriate content

> No distinct question from the specified official source assessment sections maps directly to this objective.

### Implement text analysis solutions (10–15%)

#### Apply language model text analysis

##### Implement solutions to extract entities, topics, summaries, and structured JSON outputs by using generative prompting and Foundry Tools

###### QA069 M16-Q01. How should you create an application that analyzes news articles and extracts key people, places, and dates that are mentioned for indexing?

- A. Use a generative AI model with a custom function tool that matches strings using a regular expression.
- B. Use Azure Language in Foundry Tools to extract PII entities.
- C. Use Azure Language in Foundry Tools to extract named entities. **(Correct)**

**Correct answer:** C. Use Azure Language in Foundry Tools to extract named entities.

**Why it is correct:** Named entity recognition extracts people, places, dates and other supported entity types; PII is a privacy subset and regex is not the intended prebuilt service.

**Why the other options are incorrect:**

- **A. Use a generative AI model with a custom function tool that matches strings using a regular expression.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Named entity recognition extracts people, places, dates and other supported entity types; PII is a privacy subset and regex is not the intended prebuilt service.
- **B. Use Azure Language in Foundry Tools to extract PII entities.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Named entity recognition extracts people, places, dates and other supported entity types; PII is a privacy subset and regex is not the intended prebuilt service.

**Tested concept:** Implement solutions to extract entities, topics, summaries, and structured JSON outputs by using generative prompting and Foundry Tools

**Likely exam trap:** NER, PII, language detection and generative rewriting are different language tasks.

**Sources:**

- [Microsoft Learn — Analyze text with Azure Language in Foundry Tools assessment](https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/9-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=-Ln7aW38gxI)

##### Configure detection of sentiment, tone, safety issues, and sensitive content

###### QA070 M16-Q02. You want to publish extracts from customer testimonials on a web site. You need to remove personal details from the text before publishing it. What should you do?

- A. Use Azure Language in Foundry Tools to find and redact PII entities. **(Correct)**
- B. Use Azure Language in Foundry Tools to detect the language and publish only the testimonials in English.
- C. Use a gpt-4.1 model to create new AI-generated customer reviews.

**Correct answer:** A. Use Azure Language in Foundry Tools to find and redact PII entities.

**Why it is correct:** PII detection/redaction removes supported personal details before publication; language filtering and fabricated replacement testimonials do not satisfy privacy redaction.

**Why the other options are incorrect:**

- **B. Use Azure Language in Foundry Tools to detect the language and publish only the testimonials in English.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: PII detection/redaction removes supported personal details before publication; language filtering and fabricated replacement testimonials do not satisfy privacy redaction.
- **C. Use a gpt-4.1 model to create new AI-generated customer reviews.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: PII detection/redaction removes supported personal details before publication; language filtering and fabricated replacement testimonials do not satisfy privacy redaction.

**Tested concept:** Configure detection of sentiment, tone, safety issues, and sensitive content

**Likely exam trap:** NER, PII, language detection and generative rewriting are different language tasks.

**Sources:**

- [Microsoft Learn — Analyze text with Azure Language in Foundry Tools assessment](https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/9-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=-Ln7aW38gxI)

##### Build solutions that translate text by using Azure Translator in Foundry Tools or LLM‑powered translation flows

###### QA071 M22-Q01. What function of an Azure Translator **TextTranslationClient** object should you use to convert the Chinese word "你好" to the English word "Hello"?

- A. get\_supported\_language
- B. translate
- C. transliterate **(Correct)**

**Correct answer:** C. transliterate

**Why it is correct:** `translate` converts meaning from Chinese to English; support lookup lists languages and transliteration changes script.

**Why the other options are incorrect:**

- **A. get\_supported\_language:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `translate` converts meaning from Chinese to English; support lookup lists languages and transliteration changes script.
- **B. translate:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `translate` converts meaning from Chinese to English; support lookup lists languages and transliteration changes script.

**Tested concept:** Build solutions that translate text by using Azure Translator in Foundry Tools or LLM‑powered translation flows

**Likely exam trap:** Translation changes language; transliteration changes script; SpeechTranslationConfig selects speech targets.

**Sources:**

- [Microsoft Learn — Translate text and speech assessment](https://learn.microsoft.com/en-us/training/modules/translate-text-speech/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=bnPIZUZjDyA)

###### QA072 M22-Q02. What function of an Azure Translator **TextTranslationClient** object should you use to convert the Russian word "спасибо" in Cyrillic characters to "spasibo" in Latin characters?

- A. get\_supported\_language
- B. translate **(Correct)**
- C. transliterate

**Correct answer:** B. translate

**Why it is correct:** `transliterate` converts Cyrillic “спасибо” to Latin-script “spasibo” without changing language.

**Why the other options are incorrect:**

- **A. get\_supported\_language:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `transliterate` converts Cyrillic “спасибо” to Latin-script “spasibo” without changing language.
- **C. transliterate:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `transliterate` converts Cyrillic “спасибо” to Latin-script “spasibo” without changing language.

**Tested concept:** Build solutions that translate text by using Azure Translator in Foundry Tools or LLM‑powered translation flows

**Likely exam trap:** Translation changes language; transliteration changes script; SpeechTranslationConfig selects speech targets.

**Sources:**

- [Microsoft Learn — Translate text and speech assessment](https://learn.microsoft.com/en-us/training/modules/translate-text-speech/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=bnPIZUZjDyA)

##### Customize language model outputs for domain tasks, such as compliance summarization and domain extraction

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Implement speech solutions

##### Implement workflows to convert speech to text and text to speech for agentic interactions

###### QA073 M18-Q02. Which model can you use to synthesize speech from text?

- A. gpt-4o-mini
- B. gpt-4o-mini-tts **(Correct)**
- C. gpt-4o-mini-transcribe

**Correct answer:** B. gpt-4o-mini-tts

**Why it is correct:** `gpt-4o-mini-tts` synthesizes speech from text; the transcribe model performs the inverse task.

**Why the other options are incorrect:**

- **A. gpt-4o-mini:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `gpt-4o-mini-tts` synthesizes speech from text; the transcribe model performs the inverse task.
- **C. gpt-4o-mini-transcribe:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `gpt-4o-mini-tts` synthesizes speech from text; the transcribe model performs the inverse task.

**Tested concept:** Implement workflows to convert speech to text and text to speech for agentic interactions

**Likely exam trap:** Transcription and synthesis use opposite-purpose audio models.

**Sources:**

- [Microsoft Learn — Develop a speech-capable generative AI application assessment](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-audio-apps/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=C5ZE-mzU1wA)

###### QA074 M19-Q01. What information do you need from your Microsoft Foundry resource to consume it using the Azure Speech SDK?

- A. The endpoint and key **(Correct)**
- B. The primary and secondary keys
- C. The Azure subscription ID and resource group name

**Correct answer:** A. The endpoint and key

**Why it is correct:** The course key-based Speech SDK setup requires endpoint and key; two keys alone or subscription/resource-group identifiers are insufficient for the data-plane call.

**Why the other options are incorrect:**

- **B. The primary and secondary keys:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course key-based Speech SDK setup requires endpoint and key; two keys alone or subscription/resource-group identifiers are insufficient for the data-plane call.
- **C. The Azure subscription ID and resource group name:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course key-based Speech SDK setup requires endpoint and key; two keys alone or subscription/resource-group identifiers are insufficient for the data-plane call.

**Tested concept:** Implement workflows to convert speech to text and text to speech for agentic interactions

**Likely exam trap:** SpeechConfig, AudioConfig and recognizer/synthesizer objects are easily confused.

**Sources:**

- [Microsoft Learn — Create speech-enabled apps with Azure Speech in Microsoft Foundry Tools assessment](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=OQKQtqjZ1Wo)

###### QA075 M19-Q02. Which object should you use to specify that the speech input to be transcribed to text is in an audio file?

- A. SpeechConfig
- B. AudioConfig **(Correct)**
- C. SpeechRecognizer

**Correct answer:** B. AudioConfig

**Why it is correct:** `AudioConfig` selects an audio-file input; `SpeechConfig` configures the service and `SpeechRecognizer` performs recognition.

**Why the other options are incorrect:**

- **A. SpeechConfig:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `AudioConfig` selects an audio-file input; `SpeechConfig` configures the service and `SpeechRecognizer` performs recognition.
- **C. SpeechRecognizer:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `AudioConfig` selects an audio-file input; `SpeechConfig` configures the service and `SpeechRecognizer` performs recognition.

**Tested concept:** Implement workflows to convert speech to text and text to speech for agentic interactions

**Likely exam trap:** SpeechConfig, AudioConfig and recognizer/synthesizer objects are easily confused.

**Sources:**

- [Microsoft Learn — Create speech-enabled apps with Azure Speech in Microsoft Foundry Tools assessment](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=OQKQtqjZ1Wo)

###### QA076 M19-Q03. How can you change the voice used in speech synthesis?

- A. Specify a SpeechSynthesisOutputFormat enumeration in the SpeechConfig object.
- B. Set the speech\_synthesis\_voice\_name property of the SpeechConfig object to the desired voice name. **(Correct)**
- C. Specify a filename in the AudioConfig object.

**Correct answer:** B. Set the speech\_synthesis\_voice\_name property of the SpeechConfig object to the desired voice name.

**Why it is correct:** `speech_synthesis_voice_name` selects the TTS voice; output format and file destination control different settings.

**Why the other options are incorrect:**

- **A. Specify a SpeechSynthesisOutputFormat enumeration in the SpeechConfig object.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `speech_synthesis_voice_name` selects the TTS voice; output format and file destination control different settings.
- **C. Specify a filename in the AudioConfig object.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `speech_synthesis_voice_name` selects the TTS voice; output format and file destination control different settings.

**Tested concept:** Implement workflows to convert speech to text and text to speech for agentic interactions

**Likely exam trap:** SpeechConfig, AudioConfig and recognizer/synthesizer objects are easily confused.

**Sources:**

- [Microsoft Learn — Create speech-enabled apps with Azure Speech in Microsoft Foundry Tools assessment](https://learn.microsoft.com/en-us/training/modules/create-speech-enabled-apps/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=OQKQtqjZ1Wo)

##### Integrate speech as an agent modality, including custom speech models

###### QA077 M20-Q01. What two core capabilities does the Azure Speech MCP server expose to agents?

- A. Language translation and text summarization.
- B. Speech-to-text recognition and text-to-speech synthesis. **(Correct)**
- C. Named entity recognition and sentiment analysis.

**Correct answer:** B. Speech-to-text recognition and text-to-speech synthesis.

**Why it is correct:** The Speech MCP server exposes speech recognition and synthesis; translation/summarization and NER/sentiment belong to other capabilities.

**Why the other options are incorrect:**

- **A. Language translation and text summarization.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Speech MCP server exposes speech recognition and synthesis; translation/summarization and NER/sentiment belong to other capabilities.
- **C. Named entity recognition and sentiment analysis.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Speech MCP server exposes speech recognition and synthesis; translation/summarization and NER/sentiment belong to other capabilities.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** The MCP tool may need both service credentials and storage access; neither alone completes the workflow.

**Sources:**

- [Microsoft Learn — Develop a Speech Agent with the Azure Speech MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-speech-agent-speech-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=mRfkydveXAs)

###### QA078 M20-Q02. Why does the Azure Speech MCP server require an Azure Storage account?

- A. To store the agent's instructions and configuration settings.
- B. To store input audio files and output audio files generated by the speech tools. **(Correct)**
- C. To cache the MCP server's tool definitions for faster discovery.

**Correct answer:** B. To store input audio files and output audio files generated by the speech tools.

**Why it is correct:** Azure Storage holds input and generated audio for the tool workflow; it is not the store for agent instructions or tool discovery metadata.

**Why the other options are incorrect:**

- **A. To store the agent's instructions and configuration settings.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Azure Storage holds input and generated audio for the tool workflow; it is not the store for agent instructions or tool discovery metadata.
- **C. To cache the MCP server's tool definitions for faster discovery.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Azure Storage holds input and generated audio for the tool workflow; it is not the store for agent instructions or tool discovery metadata.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** The MCP tool may need both service credentials and storage access; neither alone completes the workflow.

**Sources:**

- [Microsoft Learn — Develop a Speech Agent with the Azure Speech MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-speech-agent-speech-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=mRfkydveXAs)

###### QA079 M20-Q03. What credentials are needed when connecting the Azure Speech MCP server to a Foundry agent?

- A. An OAuth 2.0 token and a managed identity endpoint URL.
- B. A Foundry resource key and a SAS URL for a blob container. **(Correct)**
- C. A client certificate and the Azure subscription ID.

**Correct answer:** B. A Foundry resource key and a SAS URL for a blob container.

**Why it is correct:** The course connection uses a Foundry resource key plus a blob-container SAS URL; the other credential combinations do not supply both required accesses.

**Why the other options are incorrect:**

- **A. An OAuth 2.0 token and a managed identity endpoint URL.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course connection uses a Foundry resource key plus a blob-container SAS URL; the other credential combinations do not supply both required accesses.
- **C. A client certificate and the Azure subscription ID.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The course connection uses a Foundry resource key plus a blob-container SAS URL; the other credential combinations do not supply both required accesses.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** The MCP tool may need both service credentials and storage access; neither alone completes the workflow.

**Sources:**

- [Microsoft Learn — Develop a Speech Agent with the Azure Speech MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-speech-agent-speech-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=mRfkydveXAs)

###### QA080 M20-Q04. How can you specify a particular voice when using the text-to-speech tool through the agent?

- A. By configuring the voice in the MCP server settings before connecting.
- B. By including the voice name in your natural language prompt to the agent. **(Correct)**
- C. By setting an environment variable in the client application code.

**Correct answer:** B. By including the voice name in your natural language prompt to the agent.

**Why it is correct:** The requested voice can be included in the natural-language prompt/tool arguments; it is not fixed only by server setup or an arbitrary client environment variable.

**Why the other options are incorrect:**

- **A. By configuring the voice in the MCP server settings before connecting.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The requested voice can be included in the natural-language prompt/tool arguments; it is not fixed only by server setup or an arbitrary client environment variable.
- **C. By setting an environment variable in the client application code.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The requested voice can be included in the natural-language prompt/tool arguments; it is not fixed only by server setup or an arbitrary client environment variable.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** The MCP tool may need both service credentials and storage access; neither alone completes the workflow.

**Sources:**

- [Microsoft Learn — Develop a Speech Agent with the Azure Speech MCP Server assessment](https://learn.microsoft.com/en-us/training/modules/develop-speech-agent-speech-mcp/05-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=mRfkydveXAs)

###### QA081 M21-Q01. What are the two authentication methods supported by the Voice Live API?

- A. OAuth 2.0 and JWT (JSON Web Tokens)
- B. Basic authentication and API keys
- C. Microsoft Entra (keyless) and API key **(Correct)**

**Correct answer:** C. Microsoft Entra (keyless) and API key

**Why it is correct:** Voice Live supports Microsoft Entra keyless authentication and API keys; Basic/JWT pairings are not the documented choices.

**Why the other options are incorrect:**

- **A. OAuth 2.0 and JWT (JSON Web Tokens):** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Voice Live supports Microsoft Entra keyless authentication and API keys; Basic/JWT pairings are not the documented choices.
- **B. Basic authentication and API keys:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Voice Live supports Microsoft Entra keyless authentication and API keys; Basic/JWT pairings are not the documented choices.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** Voice Live events/protocol/auth options are exact implementation details worth memorizing from the current module.

**Sources:**

- [Microsoft Learn — Develop an Azure Speech Voice Live Agent in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=FMfX6qo4LII)

###### QA082 M21-Q02. Which protocol is used for avatar streaming integration in Voice Live API?

- A. HTTP/2
- B. WebRTC **(Correct)**
- C. gRPC

**Correct answer:** B. WebRTC

**Why it is correct:** WebRTC is used for avatar streaming integration; HTTP/2 and gRPC are not the selected avatar protocol.

**Why the other options are incorrect:**

- **A. HTTP/2:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: WebRTC is used for avatar streaming integration; HTTP/2 and gRPC are not the selected avatar protocol.
- **C. gRPC:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: WebRTC is used for avatar streaming integration; HTTP/2 and gRPC are not the selected avatar protocol.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** Voice Live events/protocol/auth options are exact implementation details worth memorizing from the current module.

**Sources:**

- [Microsoft Learn — Develop an Azure Speech Voice Live Agent in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=FMfX6qo4LII)

###### QA083 M21-Q03. How do you configure and test Voice Live agent integration in the Foundry Portal?

- A. You can't - Voice Live is only accessible through the REST API or Python SDK.
- B. In the Azure Speech in Foundry Tools Voice Live playground
- C. Enable Voice mode in the agent playground **(Correct)**

**Correct answer:** C. Enable Voice mode in the agent playground

**Why it is correct:** Foundry provides the Azure Speech Voice Live playground; generic agent voice mode or API-only access is not the course path.

**Why the other options are incorrect:**

- **A. You can't - Voice Live is only accessible through the REST API or Python SDK.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry provides the Azure Speech Voice Live playground; generic agent voice mode or API-only access is not the course path.
- **B. In the Azure Speech in Foundry Tools Voice Live playground:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry provides the Azure Speech Voice Live playground; generic agent voice mode or API-only access is not the course path.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** Voice Live events/protocol/auth options are exact implementation details worth memorizing from the current module.

**Sources:**

- [Microsoft Learn — Develop an Azure Speech Voice Live Agent in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=FMfX6qo4LII)

###### QA084 M21-Q04. How can you stop audio playback when a user interrupts the voice agent?

- A. You can't - the user must wait for the agent to finish.
- B. Handle the ServerEventType.INPUT\_AUDIO\_BUFFER\_SPEECH\_STARTED event **(Correct)**
- C. Reset the Voice Live session and clear the conversation history

**Correct answer:** B. Handle the ServerEventType.INPUT\_AUDIO\_BUFFER\_SPEECH\_STARTED event

**Why it is correct:** Handle `INPUT_AUDIO_BUFFER_SPEECH_STARTED` to stop current playback on barge-in; do not reset the entire conversation or force the user to wait.

**Why the other options are incorrect:**

- **A. You can't - the user must wait for the agent to finish.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Handle `INPUT_AUDIO_BUFFER_SPEECH_STARTED` to stop current playback on barge-in; do not reset the entire conversation or force the user to wait.
- **C. Reset the Voice Live session and clear the conversation history:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Handle `INPUT_AUDIO_BUFFER_SPEECH_STARTED` to stop current playback on barge-in; do not reset the entire conversation or force the user to wait.

**Tested concept:** Integrate speech as an agent modality, including custom speech models

**Likely exam trap:** Voice Live events/protocol/auth options are exact implementation details worth memorizing from the current module.

**Sources:**

- [Microsoft Learn — Develop an Azure Speech Voice Live Agent in Microsoft Foundry assessment](https://learn.microsoft.com/en-us/training/modules/develop-voice-live-agent/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=FMfX6qo4LII)

##### Enable multimodal reasoning from audio inputs

###### QA085 M18-Q01. Which model can you use to generate text from speech?

- A. gpt-4o-mini
- B. gpt-4o-mini-tts
- C. gpt-4o-mini-transcribe **(Correct)**

**Correct answer:** C. gpt-4o-mini-transcribe

**Why it is correct:** `gpt-4o-mini-transcribe` is the speech-to-text model; the base model and TTS model serve other roles.

**Why the other options are incorrect:**

- **A. gpt-4o-mini:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `gpt-4o-mini-transcribe` is the speech-to-text model; the base model and TTS model serve other roles.
- **B. gpt-4o-mini-tts:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `gpt-4o-mini-transcribe` is the speech-to-text model; the base model and TTS model serve other roles.

**Tested concept:** Enable multimodal reasoning from audio inputs

**Likely exam trap:** Transcription and synthesis use opposite-purpose audio models.

**Sources:**

- [Microsoft Learn — Develop a speech-capable generative AI application assessment](https://learn.microsoft.com/en-us/training/modules/develop-generative-ai-audio-apps/5-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=C5ZE-mzU1wA)

##### Translate speech into other languages by using language models and Foundry Tools

###### QA086 M22-Q03. Which Azure Speech SDK object should you use to specify the language(s) into which you want speech translated?

- A. SpeechConfig
- B. SpeechTranslationConfig
- C. AudioConfig **(Correct)**

**Correct answer:** C. AudioConfig

**Why it is correct:** `SpeechTranslationConfig` declares target translation languages; SpeechConfig and AudioConfig configure service/audio for other speech workflows.

**Why the other options are incorrect:**

- **A. SpeechConfig:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `SpeechTranslationConfig` declares target translation languages; SpeechConfig and AudioConfig configure service/audio for other speech workflows.
- **B. SpeechTranslationConfig:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: `SpeechTranslationConfig` declares target translation languages; SpeechConfig and AudioConfig configure service/audio for other speech workflows.

**Tested concept:** Translate speech into other languages by using language models and Foundry Tools

**Likely exam trap:** Translation changes language; transliteration changes script; SpeechTranslationConfig selects speech targets.

**Sources:**

- [Microsoft Learn — Translate text and speech assessment](https://learn.microsoft.com/en-us/training/modules/translate-text-speech/6-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=bnPIZUZjDyA)

### Implement information extraction solutions (10–15%)

#### Build retrieval and grounding pipelines

##### Ingest and index content, such as documents, images, audio, and video

###### QA087 M30-Q01. Which component of an Azure AI Search solution is scheduled to extract and enrich data to populate an index?

- A. Indexer **(Correct)**
- B. Projection
- C. Query

**Correct answer:** A. Indexer

**Why it is correct:** An indexer is the scheduled component that reads, enriches and populates an index; projections persist enrichment outputs and queries read the index.

**Why the other options are incorrect:**

- **B. Projection:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An indexer is the scheduled component that reads, enriches and populates an index; projections persist enrichment outputs and queries read the index.
- **C. Query:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: An indexer is the scheduled component that reads, enriches and populates an index; projections persist enrichment outputs and queries read the index.

**Tested concept:** Ingest and index content, such as documents, images, audio, and video

**Likely exam trap:** Indexer, skill, projection and query are separate parts of an Azure AI Search enrichment pipeline.

**Sources:**

- [Microsoft Learn — Create a knowledge mining solution with Azure AI Search assessment](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

##### Configure semantic search, hybrid search, and vector search for grounding

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement enrichment by using custom or built-in skills for text, images, and layout

###### QA088 M30-Q02. Which service supports built-in AI skills in Azure AI Search?

- A. Azure Functions
- B. Foundry Tools **(Correct)**
- C. Azure Cosmos DB

**Correct answer:** B. Foundry Tools

**Why it is correct:** Foundry Tools provides the built-in AI capabilities used by the Search enrichment pipeline in the course; Functions are for custom logic and Cosmos DB is a data source.

**Why the other options are incorrect:**

- **A. Azure Functions:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry Tools provides the built-in AI capabilities used by the Search enrichment pipeline in the course; Functions are for custom logic and Cosmos DB is a data source.
- **C. Azure Cosmos DB:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Foundry Tools provides the built-in AI capabilities used by the Search enrichment pipeline in the course; Functions are for custom logic and Cosmos DB is a data source.

**Tested concept:** Implement enrichment by using custom or built-in skills for text, images, and layout

**Likely exam trap:** Indexer, skill, projection and query are separate parts of an Azure AI Search enrichment pipeline.

**Sources:**

- [Microsoft Learn — Create a knowledge mining solution with Azure AI Search assessment](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

###### QA089 M30-Q03. Which kind of projection results in a relational data schema for extracted fields?

- A. File
- B. Object
- C. Table **(Correct)**

**Correct answer:** C. Table

**Why it is correct:** A table projection creates relational rows/schema; object and file projections produce different shapes.

**Why the other options are incorrect:**

- **A. File:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A table projection creates relational rows/schema; object and file projections produce different shapes.
- **B. Object:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A table projection creates relational rows/schema; object and file projections produce different shapes.

**Tested concept:** Implement enrichment by using custom or built-in skills for text, images, and layout

**Likely exam trap:** Indexer, skill, projection and query are separate parts of an Azure AI Search enrichment pipeline.

**Sources:**

- [Microsoft Learn — Create a knowledge mining solution with Azure AI Search assessment](https://learn.microsoft.com/en-us/training/modules/ai-knowldge-mining/8-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

##### Configure RAG ingestion flow, including documents and using optical character recognition (OCR)

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Connect retrieval pipelines directly to workflows and agent tools

> No distinct question from the specified official source assessment sections maps directly to this objective.

#### Extract content from documents

##### Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction

###### QA090 M29-Q01. You need to extract text and table structure from a set of documents that have varying formats. You don't need to identify specific labeled fields. Which Document Intelligence model should you use?

- A. The read model.
- B. The layout model. **(Correct)**
- C. The invoice model.

**Correct answer:** B. The layout model.

**Why it is correct:** The Layout model extracts text plus tables/structure across varying formats; Read is mainly text and Invoice targets labeled invoice fields.

**Why the other options are incorrect:**

- **A. The read model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Layout model extracts text plus tables/structure across varying formats; Read is mainly text and Invoice targets labeled invoice fields.
- **C. The invoice model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The Layout model extracts text plus tables/structure across varying formats; Read is mainly text and Invoice targets labeled invoice fields.

**Tested concept:** Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction

**Likely exam trap:** Read, Layout, prebuilt, custom, composed and classifier models solve different document-routing/extraction needs.

**Sources:**

- [Microsoft Learn — Extract data with Azure Document Intelligence assessment](https://learn.microsoft.com/en-us/training/modules/extract-data-with-document-intelligence/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

###### QA091 M29-Q02. You're building a custom model in Azure Document Intelligence. What training artifacts are required when training with the REST API?

- A. Only the sample form documents in a blob container.
- B. Sample forms along with ocr.json, labels.json, and fields.json files in a blob container. **(Correct)**
- C. A minimum of 100 labeled forms and a trained classifier.

**Correct answer:** B. Sample forms along with ocr.json, labels.json, and fields.json files in a blob container.

**Why it is correct:** For the REST training workflow in this assessment, sample forms are accompanied by `ocr.json`, `labels.json` and `fields.json`; samples alone are insufficient.

**Why the other options are incorrect:**

- **A. Only the sample form documents in a blob container.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: For the REST training workflow in this assessment, sample forms are accompanied by `ocr.json`, `labels.json` and `fields.json`; samples alone are insufficient.
- **C. A minimum of 100 labeled forms and a trained classifier.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: For the REST training workflow in this assessment, sample forms are accompanied by `ocr.json`, `labels.json` and `fields.json`; samples alone are insufficient.

**Tested concept:** Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction

**Likely exam trap:** Read, Layout, prebuilt, custom, composed and classifier models solve different document-routing/extraction needs.

**Sources:**

- [Microsoft Learn — Extract data with Azure Document Intelligence assessment](https://learn.microsoft.com/en-us/training/modules/extract-data-with-document-intelligence/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

###### QA092 M29-Q03. A company processes both invoices and receipts. They want a single endpoint that routes each document to the correct extraction model. What should they use?

- A. A custom neural model.
- B. A prebuilt read model.
- C. A composed model or a custom classifier paired with extraction models. **(Correct)**

**Correct answer:** C. A composed model or a custom classifier paired with extraction models.

**Why it is correct:** A composed model or classifier-plus-extraction-models routes heterogeneous document types; one neural/read model does not perform that routing requirement.

**Why the other options are incorrect:**

- **A. A custom neural model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A composed model or classifier-plus-extraction-models routes heterogeneous document types; one neural/read model does not perform that routing requirement.
- **B. A prebuilt read model.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A composed model or classifier-plus-extraction-models routes heterogeneous document types; one neural/read model does not perform that routing requirement.

**Tested concept:** Extract information by using multimodal pipelines that combine OCR, layout analysis, and field extraction

**Likely exam trap:** Read, Layout, prebuilt, custom, composed and classifier models solve different document-routing/extraction needs.

**Sources:**

- [Microsoft Learn — Extract data with Azure Document Intelligence assessment](https://learn.microsoft.com/en-us/training/modules/extract-data-with-document-intelligence/7-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=3E7ewqSwO8k)

##### Produce clean, grounded representations to use with agents and RAG by using Content Understanding

> No distinct question from the specified official source assessment sections maps directly to this objective.

##### Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding

###### QA093 M27-Q03. What should you define for the information you want to extract from content?

- A. A schema. **(Correct)**
- B. An index.
- C. A cluster.

**Correct answer:** A. A schema.

**Why it is correct:** A schema defines the fields to extract; an index supports retrieval and a cluster is not the extraction contract.

**Why the other options are incorrect:**

- **B. An index.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A schema defines the fields to extract; an index supports retrieval and a cluster is not the extraction contract.
- **C. A cluster.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: A schema defines the fields to extract; an index supports retrieval and a cluster is not the extraction contract.

**Tested concept:** Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding

**Likely exam trap:** Content Understanding uses analyzers and schemas; it is neither a search index nor model-training cluster.

**Sources:**

- [Microsoft Learn — Create a multimodal analysis solution with Azure Content Understanding assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)

###### QA094 M28-Q01. What configuration values are needed to use the Azure Content Understanding API?

- A. The name of the resource group where the Azure service is deployed.
- B. The Azure subscription ID and tenant ID.
- C. The endpoint and key for the Foundry resource. **(Correct)**

**Correct answer:** C. The endpoint and key for the Foundry resource.

**Why it is correct:** The assessment’s key-based API setup uses the Foundry resource endpoint and key; resource group or subscription/tenant IDs do not authenticate the analysis call.

**Why the other options are incorrect:**

- **A. The name of the resource group where the Azure service is deployed.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The assessment’s key-based API setup uses the Foundry resource endpoint and key; resource group or subscription/tenant IDs do not authenticate the analysis call.
- **B. The Azure subscription ID and tenant ID.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The assessment’s key-based API setup uses the Foundry resource endpoint and key; resource group or subscription/tenant IDs do not authenticate the analysis call.

**Tested concept:** Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding

**Likely exam trap:** Endpoint/key, analyzer name and typed result fields occur at different stages of the client workflow.

**Sources:**

- [Microsoft Learn — Create an Azure Content Understanding client application assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)

###### QA095 M28-Q02. What must be specified when calling the *analyze* method to extract fields from content?

- A. The name of the Foundry resource.
- B. The name of the analyzer. **(Correct)**
- C. The Operation-Location returned when the analyzer was created.

**Correct answer:** B. The name of the analyzer.

**Why it is correct:** The analyze call names the analyzer to apply; the resource name and a prior operation URL do not select the extraction schema.

**Why the other options are incorrect:**

- **A. The name of the Foundry resource.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The analyze call names the analyzer to apply; the resource name and a prior operation URL do not select the extraction schema.
- **C. The Operation-Location returned when the analyzer was created.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: The analyze call names the analyzer to apply; the resource name and a prior operation URL do not select the extraction schema.

**Tested concept:** Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding

**Likely exam trap:** Endpoint/key, analyzer name and typed result fields occur at different stages of the client workflow.

**Sources:**

- [Microsoft Learn — Create an Azure Content Understanding client application assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)

###### QA096 M28-Q03. How are the extracted fields returned?

- A. As type-specific values. **(Correct)**
- B. As a list of strings.
- C. As a single blob.

**Correct answer:** A. As type-specific values.

**Why it is correct:** Extracted fields are returned as type-specific values, preserving semantic types; they are not flattened to strings or one opaque blob.

**Why the other options are incorrect:**

- **B. As a list of strings.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Extracted fields are returned as type-specific values, preserving semantic types; they are not flattened to strings or one opaque blob.
- **C. As a single blob.:** This option has a different role, behavior, or requirement and therefore does not satisfy the scenario. The deciding distinction is: Extracted fields are returned as type-specific values, preserving semantic types; they are not flattened to strings or one opaque blob.

**Tested concept:** Implement analyzers for generating structured or markdown outputs for downstream reasoning by using Content Understanding

**Likely exam trap:** Endpoint/key, analyzer name and typed result fields occur at different stages of the client workflow.

**Sources:**

- [Microsoft Learn — Create an Azure Content Understanding client application assessment](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai-api/06-knowledge-check)
- [Official AI-103 video knowledge check (duplicate source)](https://www.youtube.com/watch?v=tWgf8ODQQv0)
