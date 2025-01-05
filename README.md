Stardew Valley Query Assistant
A LangFlow-powered AI workflow for answering questions about Stardew Valley. This project uses Datastax Astra DB as a vector store to search and retrieve information from a custom knowledge base, enabling users to interactively explore game mechanics, locations, and tips.

Features
Interactive Query Handling: Accepts user questions about Stardew Valley.
Astra DB Integration: Leverages Datastax Astra DB for fast and efficient vector-based searches.
Custom Prompt Generation: Dynamically creates prompts tailored to user queries.
Data Parsing and Display: Processes retrieved data into readable responses.
File and Text Handling: Supports file uploads and large text processing for ingestion.
Use Case
Designed as a chatbot assistant for Stardew Valley players, this tool can:

Help users find items or locations (e.g., "Where are all the walnuts on Ginger Island?").
Provide detailed strategies or tips for gameplay.
Act as an interactive guide to improve the overall gaming experience.
Tech Stack
LangFlow: Streamlines the creation of AI workflows.
Astra DB: Provides a scalable vector database for storing and retrieving embeddings.
Python: Core scripting language for workflow logic.
LangChain: Powers the AI's reasoning and retrieval capabilities.
Getting Started
Clone the repository.
Set up your Astra DB instance and update the configuration.
Run the LangFlow pipeline to start querying the Stardew Valley knowledge base.
Before adding to Langflow, search "INSERT YOUR API KEY HERE" and replace with your OpenAI API Key.
