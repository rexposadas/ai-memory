# How I made it work 

1. I beefed up the system_prompts
2. Summary object now contains the summary of the entire conversation and the summarized parts. This is what we did with appending the user prompts and passing it to the LLM. 

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