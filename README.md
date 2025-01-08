# GenAI Q&A Chatbot

A Q&A Chatbot project that demonstrates the implementation of both proprietary (OpenAI) and open-source (Ollama) Large Language Models using LangChain framework and Streamlit for the user interface.

# Key Features
• Interactive web interface built with Streamlit
• Support for multiple LLM models: OpenAI models (GPT-4, GPT-4 Turbo), Open-source models (Llama, Mistral, Gamma-2)
• Configurable model parameters (temperature, max tokens)
• LangSmith integration for monitoring and debugging
• Environment variable management for API keys


# Technical Implementation

**Core Components:**

• LangChain for LLM integration
• Streamlit for web interface
• LangSmith for monitoring
• Chat prompt templates for structured interactions

**Architecture:**

• Frontend: Streamlit web application with model selection and parameter configuration
• Backend: LangChain framework handling LLM interactions
• Monitoring: LangSmith integration for tracking performance and debugging

This project serves as a foundation for more complex implementations like RAG applications and SQL integration while demonstrating best practices in LLM application development.
