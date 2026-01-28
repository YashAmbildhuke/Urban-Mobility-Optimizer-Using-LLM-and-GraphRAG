#### **Urban Mobility Optimizer using LLM and GraphRAG**



* ###### **Project Overview**

The Urban Mobility Optimizer using LLM and GraphRAG is an intelligent urban travel analysis system designed to help users choose the most suitable transportation mode within a city environment, specifically Hyderabad.



**The system combines:**

\- Graph-based city modeling (Neo4j)

\- Large Language Models (LLMs)

\- Graph Retrieval-Augmented Generation (GraphRAG)



to deliver data-driven, explainable, and context-aware mobility recommendations.



---



* ###### **Key Features**

\- Shortest-path route computation using city road graphs

\- Real-time weather integration (Open-Meteo)

\- Cost and travel-time estimation for Car, Bus, and Metro

\- Transport availability detection using spatial graph queries

\- GraphRAG-based explanations grounded in city graph context

\- Interactive Streamlit dashboard with charts and maps



---



* ###### **Architecture**

User → Streamlit UI → Orchestrator Agent →

\- Route Agent (Graph shortest path)

\- Weather Agent (real-time weather)

\- Cost Agent (cost \& time estimation)

\- Transport Agent (bus/metro availability)

\- GraphRAG Context Builder (Neo4j graph context)

\- LLM (Ollama – Gemma)



---



* ###### **Technologies Used**

\- Python

\- Streamlit

\- Neo4j (Graph Database)

\- Ollama (Local LLM – Gemma)

\- OpenStreetMap / OSMnx

\- Open-Meteo API

\- Matplotlib






