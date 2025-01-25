##  RAG on WFA Specifications using OpenAI Embeddings and Chroma Vector Store 

This project uses RAG (Retrieval Augmented Generation) to build a question/answering assistant. I have used WFA specifications as base for these documents, but this can be expanded to any other set of documents.

This project demonstrates how to build a conversational AI system using OpenAI's language model with memory and a vector-based retrieval mechanism for Retrieval-Augmented Generation (RAG). It enables context-aware, dynamic conversations with enhanced retrieval capabilities for domain-specific knowledge.

-----------

Features -

Conversational Context Memory: Tracks the history of exchanges for continuity in multi-turn conversations.

Retrieval-Augmented Generation (RAG): Integrates a vector database for efficient retrieval of relevant documents or context.

OpenAI GPT Integration: Leverages OpenAI's language models (e.g., GPT-3.5 or GPT-4) for generating high-quality responses.

-----------

Example -

Input Prompt: what is GAS initial response frame

Output: The GAS Initial Response Frame is a type of action frame used in the Generic Advertisement Service (GAS) as defined in the Wi-Fi Direct® Specification. It is part of the communication process between devices, particularly in peer-to-peer (P2P) networking scenarios.

The frame includes several fields such as the Category field (which indicates it is a Public Action Frame), Action field (set to a specific value for a GAS Initial Response), Dialog Token (copied from the corresponding GAS Initial Request), and various other fields that provide details about the response, such as status codes, query response length, and any advertisement protocol information.

In essence, the GAS Initial Response Frame is sent by a device in response to a GAS Initial Request from another device, facilitating the exchange of information related to services and capabilities available within the network.

-----------

This was better response than ChatGPT. When ChatGPT was asked "what is GAS initial response frame". It gave an irrelevant response:
 
The GAS Initial Response Frame typically refers to the structured approach used in emergency response or incident management systems to establish an organized and effective initial reaction to emergencies or critical incidents. GAS might stand for a specific organization or methodology depending on the context (e.g., Gasoline Emergency Response or a General Assessment Strategy), but without additional context, I’ll outline a general framework often applied in emergency management scenarios:

https://chatgpt.com/share/679543e5-9464-8000-975c-2142132bf737
