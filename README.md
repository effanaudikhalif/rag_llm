# RAG LLM

Retrieval Augmentation Generation tool that leverages OpenAI's machine learning models to process and analyze data from PDF documents. The tool first uploads a PDF, then automatically segments the text into manageable chunks, creates vector embeddings via OpenAI, and stores these in a Chroma database for efficient retrieval. When I pose a query, it swiftly retrieves the most relevant sections, utilizes an OpenAI model to generate a structured and insightful answer, and neatly arranges the data in a pandas DataFrame.
