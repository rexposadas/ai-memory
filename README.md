This is a proof of concept demonstrating how to use previous conversations as context when querying a large language model (LLM) like OpenAI. It represents a simplified version of implementing a RAG (Retrieval-Augmented Generation) system behind a conversational app.


# Key points to get memory working for the AI

1. I added very descriptive prompts.
2. Summary object now contains the summary of the entire conversation and the summarized parts. 

# Sample output

```base

> make memory
python memory.py
Chat started. Type 'exit' to end the conversation.

You: My name is Rex

Agent: Okay, Rex.  How can I help you today?


You: What is my name?

Agent: Your name is Rex.
```
