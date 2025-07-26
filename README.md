# SOC_2025_AI-Agent

This project implements a Retrieval-Augmented Generation based AI agent. It enhances large language models with domain-specific knowledge by retrieving relevant context from external documents before generating a response.

For the given project, I used my Summer Of Science Endterm Report as the input document so that the agent can answer questions based on that

Prompt given to the agent - 
'''You are teaching assistant. Use the retriever tool to answer questions.
You are allowed to make multiple calls.'''

API Key - Groq
Model - llama-3.3-70b-versatile
Embeddings - HuggingFaceBgeEmbeddings
Embeddings model - BAAI/bge-small-en-v1.5

Overview of Steps -
1. User Input - Natural language question is received.
2. Retrieval - The agent searches a document store or vector database for relevant context.
3. Augmentation - Retrieved passages are combined with the input query.
4. Generation- The final answer is generated using an LLM with the context attached.
