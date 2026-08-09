#  Topic1 - Exam A
https://www.examtopics.com/exams/microsoft/ai-103/view/


## Question #1
HOTSPOT -

Case Study -
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

## Question #2
Case Study -
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

## Question #3
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

## Question #4
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

## Question #5
DRAG DROP -
You have a Microsoft Foundry project that processes procurement documents submitted by suppliers.
You need to implement two pipelines by using Azure Content Understanding in Foundry Tools. The solution must meet the following requirements:
Include a pipeline named Pipeline1 that supports cost-effective, high-volume processing of standalone PDF invoices.
Include a pipeline named Pipeline2 that supports cross-document validation by using multi-step reasoning and reference data.
How should you configure each pipeline? To answer, drag the appropriate configurations to the correct pipelines. Each configuration may be used once, more than once, of not at all. You may need to drag the split bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-6.png)

 
> Correct Answer: ![alt text](image-7.png)

## Question #6
HOTSPOT -
You have a Python application named App1 that integrates with a Microsoft Foundry project named Project1.
You need to ensure that App1 meets the following requirements:
Authenticates by using a Microsoft Entra managed identity
Sends prompts to a deployed model by using the Azure OpenAI Responses API
How should you complete the Python code? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-8.png)

 
> Correct Answer: ![alt text](image-9.png)

## Question #7
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

## Question #8
HOTSPOT -
You have a Microsoft Foundry project that contains a customer support agent built by using the Foundry Agent Service.
The agent uploads user-provided screenshots to Azure Storage through a ticketing tool and receives a blob URL for additional reasoning.
You need to use image moderation during agent runs and prevent harmful content from being returned during runs. Azure AI Content Safety must access the images by using the blob URL. The solution must follow the principle of least privilege.
What should you configure for Content Safety? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-12.png)

 
> Correct Answer: image12

## Question #9
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


## Question #10
You have a Microsoft Foundry project that contains an agent. The agent uses Azure Speech in Foundry Tools.
You fine-tune a baseline speech to text model for the en-us locale and publish the model.
The agent calls the Speech to text REST API and returns an error message indicating that the project ID is invalid.
You need to set the project property to the correct ID.
To what should you set the project property?

A. the project URL

> B. the custom speech project ID Most Voted

C. the project ID

D. the custom speech endpoint URL

## Question #11
HOTSPOT -
You have a Microsoft Foundry project that contains an agent named PaymentAgent.
PaymentAgent includes a function tool that issues customer refunds by using an external API.
You are creating a workflow in YAML.
You need to ensure that the workflow pauses for human approval and continues with the refund step only after approval is granted.
How should you complete the workflow definition? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-14.png)

 
> Correct Answer: ![alt text](image-15.png)

## Question #12
You have an Azure Speech in Foundry Tools resource that hosts a custom speech to text model deployed to a custom endpoint. An agent uses the endpoint to perform real-time speech recognition.
You are approaching the expiration date of the custom speech to text model.
What is the expected behavior when the model expires?

A. Speech recognition requests will return a 4xx error until a new custom model is deployed.

B. Speech recognition requests will continue to use the expired custom model until the model is removed manually.

> C. Speech recognition requests will fall back to the most recent base model for the same locale. Most Voted

D. The custom model will be deleted automatically when the model expires.


## Question #13
You have a Microsoft Foundry project that contains a model deployment.
You have an application that calls the deployment by using the Azure OpenAI v1 API and DefaultAzureCredential.
The developers at your company receive HTTP 403 errors when they send inference requests, even after running az login.
You need to ensure that the developers can perform model inference. The solution must follow the principle of least privilege.
Which role-based access control (RBAC) role should you assign to the developers?

A. Cognitive Services User

> B. Cognitive Services OpenAI User Most Voted

C. Contributor

D. Cognitive Services Data Reader
 

## Question #14
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

## Question #15
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

## Question #16
You have a Microsoft Foundry project named Project1 that contains an agent. The agent uses an OpenAPI 3.0 specification to call an external weather service.
The weather service requires a key to be passed in an HTTP header. The key value is stored as a connection in Project1.
You need to ensure that the key value from the connection is included automatically whenever the OpenAPI tool is invoked.
What should you configure in the OpenAPI specification?

A. a header parameter defined for each operation

B. an Azure Key Vault connection

> C. an API key security scheme Most Voted

D. a Bearer token security scheme
 
## Question #17
You have a Microsoft Foundry project that serves a high-volume chat app.
Most requests are simple FAQs, but some require advanced reasoning.
You need to reduce costs and latency for common queries, without degrading the quality of the responses to complex questions.
What should you do?

A. Route all the requests to a smaller model.

> B. Use a model cascade that routes the requests to different models. Most Voted

C. Increase the value of the max_tokens parameter for all the requests.

D. Route all the requests to the most capable model.
 

## Question #18
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

## Question #19
You have a Microsoft Foundry project that contains a high-traffic agent.
After a recent update, operational costs increase significantly.
Monitoring confirms that the volume of user traffic to the agent remains unchanged.
You suspect that changes to the request or response characteristics are causing the increase. You need to identify whether the additional costs are driven by the model input size, the model output size, or expanded tool usage.
Which observability capability should you use?

A. latency

B. evaluation metrics

C. run success rate

> D. token usage Most Voted
 
## Question #20
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


## Question #21
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

## Question #22
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
 
## Question #23T
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure a prompt shield for user prompts.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #24
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure image moderation to block unsafe content before processing the images.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #25
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure a prompt shield for documents.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #26
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a multimodal AI generative model that accepts image uploads and uses extracted image text to generate responses.
You discover that users can upload unsafe images and embed hidden instructions into images to manipulate the model.
You need to implement controls to mitigate the risk.
Solution: You configure protected material detection.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #27
Case Study -
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
 
## Question #28
Case Study -
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
 
## Question #29
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
 
## Question #30
DRAG DROP -
You have a Microsoft Foundry project that contains a deployed ticket-triage agent.
You discover that sometimes the agent responds without calling any tools, even when a tool is required.
You need to ensure that the agent calls a tool during execution.
How should you complete the Python code? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.
NOTE: Each correct selection is worth one point.
![alt text](image-22.png)

 
Correct Answer: ![alt text](image-23.png)

## Question #31
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
 
##Question #32
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

## Question #33
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
 
## Question #34
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

## Question #35
HOTSPOT -
You have a Microsoft Foundry project that contains a deployed chat model.
You have a Python service that sends API requests to the model. The service is integrated with an automated validation system that compares generated outputs against approved response patterns.
Stakeholders report that small wording differences are causing validation mismatches.
You need to update the request parameters to improve output stability. The solution must maximize reasoning quality.
How should you complete the Python code? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-26.png)

 
> Correct Answer: ![alt text](image-27.png)

## Question #36
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
 
## Question #37
HOTSPOT -
You need to recommend a plan to create a customer support agent by using the Microsoft Foundry Agent Service. The agent must meet the following requirements:
Retain user preferences across multiple conversations.
Enable users to provide contextual grounding by directly uploading documents during a chat.
Which Foundry capability should you recommend for each requirement? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-28.png)

 
> Correct Answer: ![alt text](image-29.png)

## Question #38
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
You need to improve response completeness. The solution must be implemented in the logic of the application code before responses are returned.
What should you do?

> A. Add a retry evaluation before the responses are returned. Most Voted

B. Decrease the value of the max_tokens parameter.

C. Switch to Retrieval Augmented Generation (RAG).

D. Replace the model with a smaller deployment.
 
## Question #39
You have a customer support agent built by using the Microsoft Foundry Agent Service. The agent calls an Azure OpenAI model deployment.
During load testing, calls intermittently fail and return an HTTP 429 rate limit exceeded error.
You need to handle throttling to reduce call failures and improve reliability under load. The solution must remain within the service and model limits.
What should you do?

A. Create a new thread and retry the calls immediately.

B. Reduce the number of registered tools.

> C. Implement a retry policy that uses exponential backoff and jitter. Most Voted
D. Spit uploaded content into smaller files.

## Question #40
HOTSPOT -
You have a Microsoft Foundry project that contains an agent.
You use a GitHub Actions workflow for CI/CD.
You need to configure the workflow to automatically evaluate the agent when a pull request (PR) is created and prevent branches from merging if the evaluation results do NOT meet the defined thresholds.
How should you configure the workflow? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-30.png)
 
> Correct Answer: ![alt text](image-31.png)

## Question #41
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You increase the value of the max_tokens parameter.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #42
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You add a reflection pass that regenerates the response if the required clauses are missing.
Does this meet the goal?

> A. Yes Most Voted

B. No
 
## Question #43
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You increase the value of the temperature parameter.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #44
Note: This section contains one or more sets of questions with the same scenario and problem. Each question presents a unique solution to the problem. You must determine whether the solution meets the stated goals. More than one solution in the set might solve the problem. It is also possible that none of the solutions in the set solve the problem.
After you answer a question in this section, you will NOT be able to return. As a result, these questions do not appear on the Review Screen.
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.
Users report that some responses omit required regulatory clauses, even when the clauses are present in the retrieved content.
You need to improve response completeness.
Solution: You run an evaluation flow that scores responses for completeness and blocks responses that fall below a defined threshold.
Does this meet the goal?

A. Yes

> B. No Most Voted
 
## Question #45
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
 
## Question #46
You have a Microsoft Foundry project that generates product marketing images from text prompts.
After publishing several images, the legal team at your company identifies a competitor’s logo on a sign in the background of an image.
You need to remove only the logo, while preserving the rest of the image.
What should you do?

> A. Apply a mask-based inpainting edit to the part of the image that contains the logo. Most Voted

B. Increase the prompt guidance strength.

C. Modify the original prompt to exclude brand names.

D. Rerun the prompt by using a different random seed.
 
## Question #47
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
 
## Question #48
You have a Microsoft Foundry project that contains an agent and an image generation model deployment.
The agent generates original images from user-supplied product photos.
You need to ensure that the generated images maintain the product identity and visual characteristics of the provided photo.
What should you do?

> A. Set the input_fidelity parameter to high. Most Voted

B. Apply a groundedness detection filter.

C. Include a prompt and input image in the request.

D. Decrease the value of the temperature parameter.
 
## Question #49
HOTSPOT -
You have a Microsoft Foundry project that contains an agent.
The agent accepts user-uploaded screenshots and uses a multimodal chat model.
Some screenshots contain potentially malicious embedded text.
You need to prevent a prompt injection attack and ensure that third-party content is treated as lower trust.
How should you configure prompt shields for document attacks? To answer, select the appropriate options in the answer area.
NOTE: Each correct selection is worth one point.
![alt text](image-32.png)

 
> Correct Answer: ![alt text](image-33.png)

## Question #50
You are deploying a support agent that enables users to upload photos.
You need to automatically classify uploaded images for harmful content. The solution must block content based on severity levels.
What should you do?

A. Apply keyword scanning to optical character recognition (OCR) output by using Azure Vision in Foundry Tools.

B. Enable prompt shields.

C. Use blocklists.

>D. Implement image moderation. Most Voted
 

## Question #51
You have an app named App1 that uses a Microsoft Foundry multimodal model deployment.
App1 runs optical character recognition (OCR) on uploaded images and appends the OCR output to the prompt as additional context.
Some uploaded images contain embedded text.
You need to prevent potentially malicious instructions from being processed by the model.
What should you use?

A. image moderation

> B. prompt shields for documents Most Voted

C. protected material text

D. prompt shields for user prompts
 
## Question #52
You have a Microsoft Foundry project that contains an agent.
You need to process mixed-format documents that contain scanned text, tables, and multicolumn layouts. The extracted content must preserve the document structure and be converted into the Markdown format for downstream reasoning.
What should you configure first?

A. an Azure Language in Foundry Tools text analysis model deployment

B. a generative chat completion request

C. an Azure OpenAI Responses API call that uses a multimodal model

> D. an Azure Content Understanding in Foundry Tools analyzer Most Voted
 
## Question #53
You have an application that processes scanned PDF invoices. The invoices have varied layouts and include multipage tables.
You have a pipeline that uses optical character recognition (OCR) and extracts totals and invoice numbers. The results are often incorrect because the document structure is ignored.
You need to implement a solution that provides OCR, layout analysis, and template-generalizing field extraction. The solution must NOT require training a custom model. The solution must minimize administrative effort.
What should you include in the solution?

A. Azure Language in Foundry Tools

> B. Azure Content Understanding in Foundry Tools Most Voted

C. an Azure Machine Learning model
 
## Question #54
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
 
## Question #55
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
 
## Question #56
Case Study -
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

## Question #57
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
 
## Question #58
You are building a speech processing solution in Microsoft Foundry for a customer support platform.
The platform will transcribe live phone calls, so that supervisors at your company can view call transcripts and detect issues while the calls are in progress. The call audio will arrive as a continuous stream from the telephony system.
You need to ensure that the call transcripts appear within only a few seconds of the audio stream.
What should you do?

A. Use text to speech by using a custom neural voice.

B. Use speech translation to generate the transcripts into multiple languages.

C. Run a batch transcription job on recorded audio files.

> D. Use real-time speech to text to process streaming audio input. Most Voted
 
## Question #59
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
 
## Question #60
You have an application named App1 that uses Azure Speech in Foundry Tools to transcribe live calls.
Transcript segments often contain both English and Spanish. App1 sends each segment to Azure Translator in Foundry Tools to translate to another language.
Sometimes, mixed-language segments result in incomplete or incorrect translations.
You need to reduce translation errors. The solution must ensure that the entire transcript is translated successfully.
What should you do before sending the segments to Translator?

A. Use document translation to translate the entire transcript as a single document.

> B. Split the mixed-language segments into single-language segments and translate each segment separately. Most Voted

C. Enable automatic language detection for the translation request.

D. Specify English as the source language in the translation request for all the segments.
 
## Question #61
Case Study -
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
 
## Question #62
Case Study -
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
 
## Question #63
You have a Microsoft Foundry project named Project1.
Project1 contains an application that processes PDF vendor invoices.
You need to configure Azure Document Intelligence in Foundry Tools to generate a Markdown output that preserves the sections and table structure of the PDFs. The solution must minimize development effort.
What should you do?

A. Configure output=figures when you analyze the PDF.

B. Configure content=markdown when you analyze the document.

C. Increase the confidence threshold.

> D. Set the output_content_format=ContentFormat.MARKDOWN value.
 
## Question #64
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
 
## Question #65
You have a Microsoft Foundry project that uses Azure AI Search to ground an agent in internal documentation.
After a recent content update, users report that the agent’s answers have become less accurate.
You need to identify whether the retrieved content is negatively influencing the model’s generated responses.
Which observability signal should you review?

A. indexer status and failure history

B. latency breakdown traces

C. prediction drift metrics

> D. groundedness evaluation metrics
 
## Question #66
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

## Question #67
Case Study -

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
 
## Question #68
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


You need to ensure that Agent1Dev Team can access Agent1. The solution must meet the security and compliance requirements.

How should you complete the Python code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-36.png)

 
Correct Answer: ![alt text](image-37.png)

## Question #69
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
 
## Question #70
You have a Microsoft Foundry project that contains a support-ticket triage agent built by using the Foundry Agent Service.

The agent uses tool to classify the ticket type and sot the ticket priority.

Sometimes, the same support case continues across multiple sessions over several days.

You need to persist state by using a durable ID to ensure that the agent can automatically reuse the full interaction history. The solution must preserve previous user messages, tool calls and tool outputs across turns and sessions.

Which runtime component should you use?

A. output item

B. agent

> C. conversation

D. response
 
## Question #71
HOTSPOT
-

You have a Microsoft Founcy project that contains a Retrieval Augmented Generation (RAG) solution.

You need to run a pre-production evaluation by using labeled CSV dataset that contains the query, context, response and ground truth. The evaluation must measure the following:

• Whether responses address the user query
• Whether responses are supported by the provided context
• Whether responses contain sensitive or proprietary information

Which AI quality evaluation metrics should you use? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-38.png)

 
> Correct Answer: ![alt text](image-39.png)

Question #72
You plan to configure an evaluation in Microsoft Foundry for a Retrieval Augmented Generation (RAG) chat app.

You need to provide scores for groundedness, relevance, and harmful content categories.

Which two evaluation categories can you use? Each correct answer presents a complete solution.

NOTE: Each correct selection is worth one point.

> A. risk and safety metrics

B. fluency evaluator

C. similarity evaluators

D. AI quality (NLP) metrics

> E. AI quality (AI assisted) metrics
 
## Question #73
You have a Microsoft Foundry project that contains an agent. The agent uses two tools to perform the following actions:

• Use Azure AI Search to retrieve answers from a private product documentation index.
• Use the web search tool to retrieve public information on the internet.

You need to ensure that for a specific run, the agent deterministically retrieves information only from the internet.

To what should you set tool_choice?

> A. {“type”: “bing_grouding”}

B. {“type”: “azure_ai-search”}

C. “auto”

D. “required”
 
## Question #74
You have a Microsoft Foundry project that contains a customer support agent built on a deployed chat model.

The agent responses are validated by using an automated testing system that compares generated answers to stored expected outputs. Identical prompts must return consistent response to prevent automated test failures.

You need to reduce response variability, without modifying the prompt or reducing factual accuracy.

What should you do for the model?

A. Increase the max_tokens parameter.

B. Remove stop sequences from the requests.

> C. Decrease the temperature parameter.

D. Increase the temperature parameter.
 
## Question #75
You are developing prompts for a Micosoft Foundry project that classifies incoming support tickets by category.

You need to improve accuracy by showing the model how correct classifications look, without retaining the model or storing knowledge permanently.

Which prompt engineering approach should you use?

A. Retrieval Augmented Generation (RAG)
B. zero-shot learning

C. chain of thought

> D. few-shot learning
 
## Question #76
You have a Microsoft Foundry project that contains an agent for a customer support chat app. The agent uses a memory store and a memory search tool.

You need to ensure that the conversation history does NOT persist across separate sessions.

To what should you set the scope of the memory tool?

> A. session

B. {{$conversationId}}

C. {{$userId}}

D. global
 
Correct Answer: A 🗳️

## Question #77
DRAG DROP
-

You have a Microsoft Foundry project that contains an agent.

You need to enable long-term memory to ensure that the agent can recall user preferences across separate conversations. Stored memories must be isolated per authenticated user without the client application manually generating user IDs.

How should you complete the Python code? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all.

NOTE: Each correct selection is worth one point.

![alt text](image-40.png)

 
> Correct Answer: ![alt text](image-41.png) 

## Question #78
You have a web app named App1 that processes user prompts by integrating with a Microsoft Foundry project named Project1. App1 performs the following actions:

• Sends prompts directly to a model by using the Azure OpenAI Responses API
• Invokes the Azure AI Content Safety tool by using a Foundry connection within the same request

You need to configure end-to-end visibility into each step of the request workflow.

What should you do?

A. Enable logging by using the client SDK for Content Safety.

B. Enable logging by using Foundry Local.

> C. Enable application tracing in Project1.

D. Route requests through the Azure OpenAI endpoint.
 
## Question #79
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

## Question #80
You have a Microsoft Foundry project that contains an agent named Agent1.

Agent runs successful, but Foundry Control Plane does NOT display values for error rates, runs, and token usage, and the Traces tab is empty.

You need to ensure that Found Control Plane displays the appropriate values for Agent1.

What should you do?

A. Update Agent1 to a new version.

B. Restart Agent from Foundry Control Plan

C. Assign to a Log Analytics workspace to Agent1.

> D. Enable Application Insights for Agent1.
 
## Question #81
You have a Microsoft Foundry project that contains an agent.

The agent uses Azure Content Understanding in Foundry Too to process vendor onboarding packets. The packs include digital PDFs that contain tables and hyperlinks.

The extracted content is indexed for search and provided to a downstream agent in the Markdown format.

You need to generate a Markdown output that has a layout and a semantic structure optimized for Retrieval Augmented Generation (RAG) workflows.

Which built-in analyzer should you use?

A. prebuilt-documentFieldSchema

> B. prebuilt-documentSearch

C. prebuilt-read

D. prebuilt-layout
 
## Question #82
You have a Microsoft Foundry project that contains an agent.

The agent uses Azure AI Search for Retrieval Augmented Generation (RAG).

You plan to ingest and index PDF product manuals.

You need to build a solution that supports semantic similarity matching. The solution must ensure that the agent retrieves relevant data when user questions use different wording than the product manuals.

Which indexing approach should you use?

> A. vector search

B. semantic ranking

C. suggesters

D. analyzers
 
## Question #83
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
 
## Question #84
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
 
## Question #85
You are building an Azure AI Search indexing pipeline named Pipeline1 that ingests invoices stored in Azure Blob Storage. The invoices are stored as scanned images.

You need to enable users to search invoice data across the invoice fields.

Which built-in skill should you add to the skillset of Pipeline1?

A. Text Split

B. Text Translation

> C. optical character recognition (OCR)

D. Image Analysis
 
## Question #86
DRAG DROP
-

You have a Microsoft Foundry project that uses Azure Content Understanding in Foundry Tools to analyze marketing videos.

Video segmentation is enabled.

You need to configure an analyzer to output a generated JSON field that describes the color scheme of each video segment.

How should you configure the analyzer? To answer, drag the appropriate values to the correct targets. Each value may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content.

NOTE: Each correct selection is worth one point.

![alt text](image-44.png)

 
> Correct Answer: ![alt text](image-45.png)

## Question #87
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
 
## Question #88
You have a Microsoft Foundry project that generates short promotional product videos.

After several clips are approved, reviewers notice a small watermark in the top-right corner of some videos.

You need to remove the watermark without regenerating the videos.

What should you do?

A. Modify the original prompt to exclude watermarks.

B. Crop the video by using the size parameter.

C. Increase the guidance scale.

> D. Apply a mask-based inpainting edit to the affected part of the video.
 
## Question #89
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
 
## Question #90
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
 
## Question #91
You have a Microsoft Foundry project that contains an agent and uses a GitHub repository. The repository contains a YAML file named File1 that defines the evaluation settings of the agent.

You need to create a GitHub Actions workflow that runs the evaluation defined in File1 when a pull request (PR) is opened. How should you configure the workflow?

A. Set project-endpoint to the endpoint of the project.

> B. Set evaluation-config to the path of the YAML file.

C. Set model-deployment-name to the deployed model.

D. Set tenant-id to the Microsoft Entra tenant ID
 
## Question #92
HOTSPOT
-

You have a Microsoft Foundry project that contains an agent.

The agent uses a stored access key to retrieve secrets from an Azure key vault, which violates a keyless-credentials requirement.

You need to ensure that the agent can retrieve the secrets. The solution must follow the principle of least privilege.

What should you configure? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-46.png)

 
> Correct Answer: ![alt text](image-47.png) 

## Question #93
HOTSPOT
-

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

## Question #94
DRAG DROP
-

You have a Microsoft Foundry project that contains a multi-agent solution. The agents use tool calling to query internal systems.

You need to implement responsible AI auditing to meet the following requirements:

• Capture all the nested operations across the entire agent run.
• Record tool invocation arguments and retuned results as metadata.

What should you use for each requirement? To answer, drag the appropriate options to the correct targets Each option may be used once, more than once, or not at all. You may need o dag the split bar between panes or scroll to view content.

NOTE: Each correct selection is worth one point.

![alt text](image-49.png)

 
> Correct Answer: ![alt text](image-50.png)

## Question #95
DRAG DROP
-

You have a Microsoft Foundry project that contains an agent. The agent uses threads and file uploads and calls an Azure OpenAI model deployment.

During load testing, calls intermittently fall and return an HTTP 429 rate limit exceeded error. Some user uploads fail and generate an HTTP 400 file size exceeded error.

You need to mitigate the errors and reduce call failures. The solution must remain within the service and model limits.

What should you do to resolve each error? To answer, drag the appropriate actions to the correct errors. Each action may be used once, more than once or not at all. You may need to drag the split bar between panes or scroll to view content.

NOTE: Each comet selection is worth one point.

![alt text](image-51.png)

 
> Correct Answer: ![alt text](image-52.png) 

## Question #96
You have a Microsoft Foundry project.

You need to deploy a model from the model catalog to support a search solution for internal policy documents. The model must generate vector representations of the text in the documents and of user queries.

Which type of model should you use?

> A. an embedding model

B. an image generation model

C. a large language model (LLM)

D. a small language model (SLM)

## Question #97
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
 
## Question #98
HOTSPOT
-

You plan to create a Microsoft Foundry project named Project1 that will contain an agent and use an Azure key vault named KV1.

You need to configure a connection from Project1 to KV1.

How should you complete the Bicep code? To answer, select the appropriate options in the answer area?

NOTE: Each correct selection is worth one point.

![alt text](image-53.png)

 
> Correct Answer: ![alt text](image-54.png) 

## Question #99
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

## Question #100
You have a Microsoft Foundry project that contains an agent. The agent generates summaries from retrieved policy documents.

You need to improve response completeness. The solution must be implemented in the logic of the application code before responses are returned.

What should you do?

> A. Add a retry evaluation before the responses are returned.

B. Decrease the value of the temperature parameter.

C. Increase the value of the presence_penalty parameter

D. Replace the model with a smaller deployment.

## Question #101
HOTSPOT
-

You develop a test method to verify the results retrieved from a call to the Azure Vision in Foundry Tools API. The call is used to analyze the existence of company logos in images. The call returns a collection of brands named brands.

You have the following code segment:
![alt text](image-57.png)


For each of the following statements, select Yes if the statement is true. Otherwise, select No.

NOTE: Each correct selection is worth one point.

![alt text](image-58.png)

 
> Correct Answer: ![alt text](image-59.png) 

## Question #102
You have an Azure subscription.

You plan to build an app that will use the Azure AI DALL-E model.

You need to deploy the model.

What should you use?

A. the Azure SDK for Python and PowerShell cmdlets.

B. the Azure SDK for JavaScript and Azure Machine Learning Studio.

> C. Microsoft Foundry and the Azure Command Line Interface (CLI)

D. the Azure portal and Microsoft Graph API
 
## Question #103
HOTSPOT
-

You have an Azure subscription.

You need to create a new resource that will generate fictional stores in response to user prompts. The solution must ensure that the resource uses a customer-managed key to protect data.

How should you complete the script? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-60.png)

 
> Correct Answer: ![alt text](image-61.png)

## Question #104
HOTSPOT
-

You have a Python application collects customer comments before posting them to a public forum.

You need to send a text comment to Azure AI Content Safety and return the self-harm severity from the response.

How should you complete the code? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-62.png)

 
> Correct Answer: ![alt text](image-63.png) 

## Question #105
You have a custom named entity recognition (NER) project in Azure Language in Foundry Tools for support tickets. The schema for the project contains an entity type named ContactInfo.

In tagged training files, ContactInfo is used for phone numbers, email addresses, and social media handles.

Model evaluation shows low precision for ContactInfo, including false positives in which nearby text is extracted as ContactInfo.

You need to improve the precision of the project.

What should you do before retraining the model?

A. Lower the confidence threshold for ContactInfo.

B. Trigger an auto-labeling job.

C. Add more support tickets as training data and label more ContactInfo entities.

> D. Replace ContactInfo by using Phone, Email, and SocialMedia entities. Relabel every matching span.
 
## Question #106
You are building a text-to-speech solution that uses Azure Speech in Foundry Tools to read instructions from the script in a text file.

You discover that the solution often pronounces technical terms incorrectly.

You need to prevent the incorrect pronunciations. The solution must minimize development effort.

What should you do?

A. From Speech Studio, train a custom neural voice

> B. Use Speech Synthesis Markup Language (SSML) to specify phonemes.

C. Use Speech Synthesis Markup Language (SSML) to apply say as rules.

D. Use Speech Synthesis Markup Language (SSML) to adjust the prosody of the voice.

E. From Azure OpenAI use the Whisper model.
 
## Question #107
HOTSPOT
-

You have a Python application that redacts sensitive information before sending prompt text to a language model. The application has the following code:

![alt text](image-64.png)

For each of the following statements, select Yes if the statement is true. Otherwise, select No.

NOTE: Each correct selection is worth one point.

![alt text](image-65.png)

 
> Correct Answer: ![alt text](image-66.png)

## Question #108
DRAG DROP
-

You are developing an application that will detect faulty components produced on a factory production line. The components are specific to your business.

You need to use the Azure Custom Vision API to help detect common faults.

Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order.


![alt text](image-67.png)
 
> Correct Answer: ![alt text](image-68.png)

## Question #109
You are developing a new sales system that will process user-generated video and text from a public-facing website.

You plan to notify users that their data has been processed by the sales system.

Which responsible AI principle does this help meet?

A. fairness

> B. transparency

C. inclusiveness

D. reliability and safety
 
## Question #110
You are designing a content management system.

You need to ensure that the reading experience is optimized for users who have reduced comprehension and learning differences, such as dyslexia. The solution must minimize development effort.

Which Azure service should you include in the solution?

A. Azure Document Intelligence in Foundry Tools

B. Azure Language in Foundry Tools

> C. Azure AI Immersive Reader

D. Azure Translator in Foundry Tools
 
## Question #111
You have an Azure subscription that contains an Azure App Service app named App1.

You provision a Microsoft Foundry Service resource named CSAccount1.

You need to configure App1 to access CSAccount1. The solution must minimize administrative effort.

What should you use to configure App1?

> A. the endpoint URI and subscription key

B. the endpoint URI and an OAuth token

C. the endpoint URI and a shared access signature (SAS) token

D. a system assigned managed identity and an X.509 certificate
 
Question #112
DRAG DROP
-

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

## Question #113
HOTSPOT
-

You need to create a new resource that will be used to perform sentiment analysis and optical character recognition (OCR). The solution must meet the following requirements:

• Use a single key and endpoint to access multiple services.
• Consolidate billing for future services that you might use.
• Support the use of Azure Vision in Foundry Tools in the future.

How should you complete the HTTP request to create the new resource? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.



 
Correct Answer: 

Question #114
HOTSPOT
-

You are building a model to detect objects in images.

The performance of the model based on training data is shown in the following exhibit.

![alt text](image-73.png)

Use the drop-down menus to select the answer choice that completes each statement based on the information presented in the graphic.

NOTE: Each correct selection is worth one point.

![alt text](image-71.png)

 
> Correct Answer: ![alt text](image-72.png)

## Question #115
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
 
## Question #116
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
 

## Question #117
HOTSPOT
-

You are creating an enrichment pipeline that will use Azure AI Search. The knowledge store contains unstructured JSON data and the text from scanned PDF documents.

Which projection type should you use for each data type? To answer, select the appropriate options in the answer area.

NOTE: Each correct selection is worth one point.

![alt text](image-74.png)

 
> Correct Answer: ![alt text](image-75.png)
