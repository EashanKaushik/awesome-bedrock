# Awesome Bedrock [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p class="center">
    <img src="/images/bedrock-logo.png"/>
</p>

A curated list of awesome [Amazon Bedrock](https://aws.amazon.com/bedrock/) code samples, community driven repositories, guides, blogs, and other resources.

> [!TIP]
> This list is not officially maintained by Amazon Web Services (AWS), but is a community driven initiative to accelerate getting started on Amazon Bedrock.

:exclamation: :exclamation: Official AWS provided code samples are published on [awslabs](https://github.com/awslabs) or [aws-samples](https://github.com/aws-samples).

:exclamation: :exclamation: Official AWS provided blogs are published on [AWS Blogs](https://aws.amazon.com/blogs/).

## Contents

- [Amazon Bedrock](#amazon-bedrock)
- [Amazon Bedrock Agents](#amazon-bedrock-agents)
- [Amazon Bedrock Knowledge Bases](#amazon-bedrock-knowledge-bases)
- [Amazon Bedrock Guardrails](#amazon-bedrock-guardrails)
- [Amazon Bedrock Evaluation](#amazon-bedrock-evaluation)
- [Amazon Bedrock Custom Models](#amazon-bedrock-custom-models)
- [Amazon Bedrock Model Catalog](#amazon-bedrock-model-catalog)
- [Amazon Bedrock Studio](#amazon-bedrock-studio)
- [Amazon Bedrock Flows](#amazon-bedrock-flows)
- [Amazon Bedrock Invocation Logging](#amazon-bedrock-invocation-logging)
- [Amazon Bedrock Inference](#amazon-bedrock-inference)
- [Amazon Bedrock Security](#amazon-bedrock-security)
- [Foundational Models on Amazon Bedrock](#model-providors-on-amazon-bedrock)
- [Additional Projects and Guides](#additional-projects)
- [Customer Success Stories](#customer-success-stories)

## Amazon Bedrock

- Amazon Bedrock Samples - [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples)
- Amazon Bedrock Agents Samples - [awslabs](https://github.com/awslabs/amazon-bedrock-agent-samples)
- Amazon Bedrock Workshop - [aws-samples](https://github.com/aws-samples/amazon-bedrock-workshop)
- Amazon Bedrock Recipes - [Guide](https://aws-samples.github.io/amazon-bedrock-samples/)
- Open Source Multi-Agentic Collaboration powered by Amazon Bedrock - [Workshop](https://aws-samples.github.io/amazon-bedrock-samples/workshop/open-source-l400/01_usecase_introduction/)
- Amazon Bedrock or Amazon Sagemaker - [Decision Guide](https://docs.aws.amazon.com/decision-guides/latest/bedrock-or-sagemaker/bedrock-or-sagemaker.html)
- Choosing a generative AI service - [Decision Guide](https://docs.aws.amazon.com/decision-guides/latest/generative-ai-on-aws-how-to-choose/guide.html)

## Amazon Bedrock Agents

### Features

|                            Feature                             |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| -------------------------------------------------------------- | ---------------- | ---------------- | --------------------- |
| Amazon Bedrock Agents                                          | [awslabs](https://github.com/awslabs/amazon-bedrock-agent-samples/tree/main/examples/amazon-bedrock-agents) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-how.html) |
| Amazon Bedrock multi-agent collaboration | [awslabs](https://github.com/awslabs/amazon-bedrock-agent-samples/tree/main/examples/amazon-bedrock-multi-agent-collaboration) | [AWS Blog](https://aws.amazon.com/blogs/aws/introducing-multi-agent-collaboration-capability-for-amazon-bedrock/) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-multi-agent-collaboration.html) |
| Conversational Builder - Create and Configure Agents using Natural Language | | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-create-cb.html) |
| Create Amazon Bedrock Agents with Function Defination          | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/01-create-agent-with-function-definition) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-action-function.html) |
| Create Amazon Bedrock Agents with Open API Schema              | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/02-create-agent-with-api-schema) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-api-schema.html) |
| Amazon Bedrock Agents - Return of Control                      | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/03-create-agent-with-return-of-control) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-returncontrol.html)  |
| Amazon Bedrock Agents - User Confirmation                      | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/11-create-agents-with-action-user-confirmation)| | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-userconfirmation.html) |
| Associate Amazon KnowledgeBase to Amazon Bedrock Agents        | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/05-create-agent-with-knowledge-base-and-action-group) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-kb-add.html) |
| Inline Amazon Bedrock Agents                                   | [aws-samples](https://aws-samples.github.io/amazon-bedrock-samples/agents-and-function-calling/bedrock-agents/features-examples/15-invoke-inline-agents/inline-agent-api-usage/) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-create-inline.html) |
| Configure agent to request information from user | | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-user-input.html) |
| Prompt and Session Attributes                                  |                  | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/06-prompt-and-session-attributes) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-session-state.html) |
| Amazon Bedrock Agent with custom orchestration | [aws-samples](https://aws-samples.github.io/amazon-bedrock-samples/agents-and-function-calling/bedrock-agents/features-examples/14-create-agent-with-custom-orchestration/custom_orchestration_example/) | [AWS Blog](https://aws.amazon.com/blogs/machine-learning/getting-started-with-amazon-bedrock-agents-custom-orchestrator/) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-custom-orchestration.html) |
| Advanced Prompt and Custom Parser                        | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/agents-and-function-calling/bedrock-agents/features-examples/07-advanced-prompts-and-custom-parsers/07-custom-prompt-and-lambda-parsers.ipynb) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/advanced-prompts.html)|
| Create Amazon Bedrock Agents with Amazon Bedrock Guardrails    | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/08-create-agent-with-guardrails) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-guardrail.html) |
| Amazon Bedrock Agents with Memory                              | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/09-create-agent-with-memory) | [AWS Blog](https://aws.amazon.com/blogs/aws/agents-for-amazon-bedrock-now-support-memory-retention-and-code-interpretation-preview/) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-memory.html) |
| Amazon Bedrock Agents with Code Interpreter                    | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/10-create-agent-with-code-interpreter) | [AWS Blog](https://aws.amazon.com/blogs/aws/agents-for-amazon-bedrock-now-support-memory-retention-and-code-interpretation-preview/) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-code-interpretation.html) |
| Optimized vs "not yet" optimized FMs for Amazon Bedrock Agents | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/agents-and-function-calling/bedrock-agents/features-examples/12-models-not-yet-optimized-for-bedrock-agents) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/working-with-models-not-yet-optimized.html) |
| Optimize performance for Amazon Bedrock agents using a single knowledge base | | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-optimize-performance.html) |

### Projects and Resources

- Amazon Bedrock multi-agent collaboration - [Research Paper](https://arxiv.org/pdf/2412.05449)
- Build generative AI agents with Amazon Bedrock, Amazon DynamoDB, Amazon Kendra, Amazon Lex, and LangChain - [aws-samples](https://github.com/aws-samples/generative-ai-amazon-bedrock-langchain-agent-example)
- Multi-Agent Orchestrator - [awslabs](https://github.com/awslabs/multi-agent-orchestrator)

## Amazon Bedrock Knowledge Bases

### Features

|                            Feature                             |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| -------------------------------------------------------------- | ---------------- | --------------- | -------------------- |
| Improve the relevance of query responses with a reranker model using Amazon SageMaker  | [aws-samples](https://github.com/aws-samples/amazon-bedrock-samples/tree/main/rag/knowledge-bases/features-examples/03-advanced-concepts/reranking) | [AWS Blog](https://aws.amazon.com/blogs/machine-learning/improve-ai-assistant-response-accuracy-using-knowledge-bases-for-amazon-bedrock-and-a-reranking-model/) | |
| Improve the relevance of query responses with a reranker model in Amazon Bedrock  | | [AWS Blog 1](https://aws.amazon.com/blogs/machine-learning/cohere-rerank-3-5-is-now-available-in-amazon-bedrock-through-rerank-api/) [AWS Blog 2](https://aws.amazon.com/blogs/aws/new-apis-in-amazon-bedrock-to-enhance-rag-applications-now-available/) | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/rerank.html) |
| Chat with your document | [aws-sample](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/rag/knowledge-bases/features-examples/00-zero-setup-chat-with-your-document/chat_with_document_kb.ipynb) | | [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/knowledge-base-chatdoc.html) |
| Custom prompting with RetrieveAndGenerate API | [aws-sample](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/rag/knowledge-bases/features-examples/01-rag-concepts/02_managed_rag_custom_prompting_and_no_of_results.ipynb) | | |
| Hybrid Search | [aws-sample](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/rag/knowledge-bases/features-examples/01-rag-concepts/03_customized-rag-retreive-api-hybrid-search-claude-3-sonnet-langchain.ipynb) | | |
| Evaluate responses using RAGAS framework | [aws-sample](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/rag/knowledge-bases/features-examples/01-rag-concepts/04_customized-rag-retreive-api-langchain-claude-evaluation-ragas.ipynb) | | |
| Amazon Bedrock Data Automation as parser | | | |
| Foundation models as a parser | | | |
| Custom transformation during ingestion via AWS Lambda function | | | |
| Custom connectors and ingestion of streaming data | | | |
| Metadata filtering | | [AWS Blog](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-knowledge-bases-now-supports-metadata-filtering-to-improve-retrieval-accuracy/) | |
| Metadata with CSV files | | | |
| Autogenerated Metadata filtering | | | |
| Dynamic Metadata filtering (tool use) | | | |
| Query Reformulation | | | |
| Contextual Grounding | | | |
| Binary Embeddings | | [AWS Blog](https://aws.amazon.com/blogs/machine-learning/build-cost-effective-rag-applications-with-binary-embeddings-in-amazon-titan-text-embeddings-v2-amazon-opensearch-serverless-and-amazon-bedrock-knowledge-bases/) | |

### Chunking

|           Chunking          |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| ---------------------- | ---------------- | --------------- | -------------------- |
|       Custom     | | | |
| Default Chunking | | | |
| Sematic Chunking | | | |
| Hierarchical Chunking | | | |



### 1. Build a knowledge base by connecting to a unstructured data source and Vector Stores

|           API          |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| ---------------------- | ---------------- | --------------- | -------------------- |
|       Retrieve API     | | | |
| RetrieveAndGenerate API|  | | |

|       Data Source         |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| ------------------------- | ---------------- | --------------- | -------------------- |
|       Amazon S3           | | | |
|      Confluence           | | | |
|      Sharepoint           | | | |
|      Salesforce           | | | |
|      Web Crawler          | | | |
|        Custom             | | | |

|       Vector Database         |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| ------------------------------| ---------------- | --------------- | -------------------- |
|  Amazon OpenSearch Serverless | 
| Amazon Neptune Analytics (GraphRAG) |
|       Amazon Aurora           |
|       MongoDB Atlas           |
|         Pinecone              |
|    Redis Enterprise Cloud     |

### 2. Build a knowledge base by connecting to a structured data source

|           API          |    Code Sample   |    AWS Blog     |    Bedrock Guide     |
| ---------------------- | ---------------- | --------------- | -------------------- |
|   GenerateQuery API    | | | |


### 3. Build an Amazon Bedrock knowledge base with an Amazon Kendra GenAI index

### Projects and Resources

- New Amazon Bedrock capabilities enhance data processing and retrieval - [AWS Blog](https://aws.amazon.com/blogs/aws/new-amazon-bedrock-capabilities-enhance-data-processing-and-retrieval/)

## Amazon Bedrock Guardrails

### Features

|           Feature              |       Code Sample      |         AWS Blog        |       Bedrock Guide         |
| ------------------------------ | ---------------------- | ----------------------- | --------------------------- |
| Content filters | | | |
| Denied topics | | | |
| Word filters | | | |
| Sensitive information filters | | | |
| Contextual grounding check | | | |
| Image content filters | | | |
| Automated Reasoning checks | | | |
| Apply tags to user input to filter content | | | |
| Configure streaming response behavior to filter content | | | |
| Include a guardrail with Converse API | | | |
| Use the ApplyGuardrail API in your application | | | |

## Amazon Bedrock Evaluation

### Features

|           Feature              |       Code Sample      |         AWS Blog        |       Bedrock Guide         |
| ------------------------------ | ---------------------- | ----------------------- | --------------------------- |
| Automatic model evaluation jobs | | | |
| Model evaluation jobs that use human workers | | | |
| Model evaluation jobs that use a judge model | | | |
| Knowledge Base evaluations that use Large Language Models (LLMs) | | | |
| Required Cross Origin Resource Sharing (CORS) permissions on S3 buckets | | | |


## Amazon Bedrock Custom Models

### Features

|           Feature              |       Code Sample      |         AWS Blog        |       Bedrock Guide         |
| ------------------------------ | ---------------------- | ----------------------- | --------------------------- |
| Fine-tuning | | | |
| Continued pre-training | | | |
| Model distillation | | | |
| Custom model import | | | |

## Amazon Bedrock Model Catalog

### Features

- Use Amazon Bedrock tooling with Amazon SageMaker JumpStart models - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/use-amazon-bedrock-tooling-with-amazon-sagemaker-jumpstart-models/)

## Amazon Bedrock Studio

- Build a Generative AI App in Minutes with Amazon Bedrock Studio | Step-by-Step Tutorial - [:movie_camera:](https://www.youtube.com/watch?v=ZxAQXpSFwKk)

## Amazon Bedrock Flows and Amazon Bedrock Prompt Management

- Build an end-to-end generative AI workflow with Amazon Bedrock Flows - [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/flows.html)
- Construct and store reusable prompts with Prompt management in Amazon Bedrock - [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-management.html)
- Amazon Bedrock Flows is now generally available with enhanced safety and traceability - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-flows-is-now-generally-available-with-enhanced-safety-and-traceability/)
- Automate document processing with Amazon Bedrock Prompt Flows - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/automate-document-processing-with-amazon-bedrock-prompt-flows-preview/)
- Streamline generative AI development in Amazon Bedrock with Prompt Management and Prompt Flows - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/streamline-generative-ai-development-in-amazon-bedrock-with-prompt-management-and-prompt-flows-preview/)
- Evaluating prompts at scale with Prompt Management and Prompt Flows for Amazon Bedrock - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/evaluating-prompts-at-scale-with-prompt-management-and-prompt-flows-for-amazon-bedrock/)
- Prompts Evaluation with Prompt Management & Prompt Flows - [aws-sample](https://github.com/aws-samples/amazon-bedrock-samples/blob/main/articles-guides/prompt-engineering/Prompt_Management_Flows/Prompts_evaluation_with_Prompt_Management_Flows.ipynb)
- Amazon Bedrock Prompt Management is now available in GA - [AWS Blog](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-prompt-management-is-now-available-in-ga/)
- Video Demo - [:movie_camera:](https://www.youtube.com/watch?v=c9y9K8LsHq8)

## Amazon Bedrock Invocation Logging

### Features

|           Feature              |       Code Sample      |         AWS Blog        |       Bedrock Guide         |
| ------------------------------ | ---------------------- | ----------------------- | --------------------------- |
| Monitor model invocation using CloudWatch Logs | | | |
| Monitor knowledge bases using CloudWatch Logs | | | |
| Monitor Amazon Bedrock Guardrails using CloudWatch Metrics | | | |
| Monitor Amazon Bedrock Studio using CloudWatch Logs | | | |
| Amazon Bedrock runtime metrics | | | |
| CloudWatch metrics for Amazon Bedrock | | | |
| Monitor Amazon Bedrock job state changes using Amazon EventBridge | | | |
| Monitor Amazon Bedrock API calls using CloudTrail | | | |

## Amazon Bedrock Inference

### Features

| Feature  | Code Sample | Blog | 
| ------------- | ------------- |
| Invoke Model API | | | |
| Converse API | | | |
| Batch Inferece | | | |
| Cross Region Inference | | | |
| Provisioned Throughput | | | |

## Amazon Bedrock Security

- Amazon Bedrock abuse detection - [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/abuse-detection.html)

## Foundational Models on Amazon Bedrock

### Features

| Feature  | Code Sample | Blog | 
| ------------- | ------------- |
| Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  |


## Additional Projects and Guides

- Prompt engineering concepts - [User Guie](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-engineering-guidelines.html)
- Tagging Amazon Bedrock resources - [User Guie](https://docs.aws.amazon.com/bedrock/latest/userguide/tagging.html)
- Troubleshooting Amazon Bedrock API Error Codes - [User Guie](https://docs.aws.amazon.com/bedrock/latest/userguide/troubleshooting-api-error-codes.html)
- Create Amazon Bedrock resources with AWS CloudFormation - [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/creating-resources-with-cloudformation.html)

## Customer Success Stories


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
