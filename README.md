# CoTARAG v0.12.0 📊💭➡️⚙️

CoTARAG (Cognitive Thought and Retrieval Augmented Generation) is an advanced AI agent framework that combines two powerful engines:

1. **CoTAEngine**: A Chain-of-Thought-Action engine that combines Chain-of-Thought (CoT) with ReAct prompting
2. **AcceleRAG**: A high-performance RAG framework focused on speed, accuracy, and modularity

<p align="center">
  <img src="./cotarag_logo.png" alt="CoTARAG" length = "400" width="400"/>
</p>

# SUNSETTING

This project is going to be sunsetting. 

- Dependency on closed-source vendors is a barrier to adoption
- Refactoring to use Ollama has proved far more challenging than expected. 
- CoTARAG PyPI package will be gracefully removed
- Impractical to meaningfully refactor into a useable framework for production grade agents. 


This project was undertaken to become an alternative LangChain framework where users could seamlessly build modular RAG pipelines, and leverage a concept of "thought-actions" for agent planning. 

The RAG framework (AcceleRAG) modularized all the core components of indexing, retrieving, query processing, and ranking so that users could swap out any or all components for an easily extendable workflow. 

The "Chain-of-thought-action" or "CoTA" was designed to partially decouple thoughts/reasoning from actions, but allow them to be treated as individual units for complex workflow. 

This was intended to improve traceback errors, easily measure how close an agent is to reaching a goal and more. 

Together, AcceleRAG and CoTA would work to create robust, reliable agents. 

**Thanks for everyone who supported this project, and hopefully some of the ideas here the reader will find useful!**

## ARCHIVED README IN PROJECT ROOT DIRECTORY
==============================================================

