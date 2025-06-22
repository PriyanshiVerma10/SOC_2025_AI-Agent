# SOC_2025_AI-Agent

This project implements a Retrieval-Augmented Generation based AI agent. It enhances large language models with domain-specific knowledge by retrieving relevant context from external documents before generating a response.

Working Steps -
1. User Input - Natural language question is received.
2. Retrieval - The agent searches a document store or vector database for relevant context.
3. Augmentation - Retrieved passages are combined with the input query.
4. Generation- The final answer is generated using an LLM with the context attached.
