# Advanced Expert System Framework with LLMs and Graph Databases

## Project Overview

This repository contains the implementation of an advanced expert system framework that integrates Large Language Models (LLMs) with graph databases. The goal is to create a system capable of emulating human-like reasoning and decision-making, enhancing contextual understanding, adaptability, and scalability. This project was developed as part of the MSDS 490: Enterprise Generative AI course at Northwestern University.

## Project Team

- Tom Hargrove
- Carl Koster
- Hantao Lin
- Allen Wang

## Objectives

The primary objectives of this project include:

1. **Development of Named Entity Relationships (NER):** Enhance contextual understanding and inference capabilities within a graph database.
2. **Dynamic Memory System:** Implement a memory system that retains LLM conversations, improving the system's ability to provide rich context in future queries.
3. **Mixture-of-Agents Approach:** Combine the strengths of multiple specialized models to refine the quality of outputs.
4. **Multi-Modal Integration:** Explore the potential for integrating text, images, and structured data.
5. **Explainability Module:** Create a module that explains the system’s reasoning process, increasing transparency and user trust.

## Methodology

The methodology followed a structured pipeline for processing PDF documents, extracting meaningful insights, and populating a graph database:

1. **PDF Summarization:** Summarize large volumes of text using transformer-based models like Facebook's BART-large-cnn.
2. **NER Extraction:** Extract named entities and relationships using LangChain's LLMGraphTransformer and OpenAI's GPT-3.5-turbo.
3. **Graph Database Population:** Populate a Neo4j graph database with the extracted entities and relationships, enabling advanced contextual reasoning.

## Key Components

- **PDF Summarization Script:** This script summarizes PDF files and saves the summaries to disk.
- **NER Extraction Script:** Extracts named entities and relationships, creating nodes and relationships in a Neo4j graph database.
- **Chatbot Implementation:** A conversational AI chatbot leveraging LLMs and graph databases to provide contextually aware responses.

## Results

The project successfully developed a Minimal Viable Product (MVP) that demonstrated the integration of LLMs with graph databases. The system produced a knowledge graph with 55,766 entities (nodes) and 84,136 relationships, showcasing the potential for advanced AI-driven decision-making.

## Future Work

Future enhancements will focus on:

- **Vector Database Integration:** Enabling stateful memory of queries and results.
- **Multi-Modal Data Integration:** Processing additional file types and integrating web-based data.
- **Mixture-of-Experts Approach:** Distributing tasks across specialized sub-models or agents.
- **Explainability Features:** Enhancing transparency in the system's decision-making processes.

## References

The project builds upon various research papers and technologies, including works on Retrieval-Augmented Generation (RAG), Knowledge Graphs, and Mixture-of-Experts models.

For more detailed information, please refer to the full project report included in this repository.

## Contact

For any questions or further information, please contact the project team members.

---

*This project was developed under the guidance of Professor Bhardwaj at Northwestern University.*
