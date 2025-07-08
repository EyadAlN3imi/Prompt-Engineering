Conversational Memory with LLaMA 3 (3B)
This notebook demonstrates how to use the meta-llama/Llama-3.2-3B-Instruct model with LangChain to enable a simple conversational interface that maintains memory across interactions.

Contents
Loads the LLaMA 3.2 3B Instruct model and tokenizer from Hugging Face.

Sets up a text generation pipeline using transformers.

Wraps the pipeline with HuggingFacePipeline for compatibility with LangChain.

Uses """ConversationBufferMemory""" to store and reuse chat history.

Defines a custom prompt template to format the conversation between the user and the model.

Runs sample inputs where the model answers questions and remembers previous context.

Requirements
-transformers
-langchain
-langchain_community
-accelerate
-bitsandbytes

