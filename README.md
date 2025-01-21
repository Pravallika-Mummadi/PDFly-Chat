# PDFly-Chat
Our project aims to revolutionize document interaction through the development
of a LangChain-powered PDF chatbot. By integrating advanced generative AI
and contextual understanding, users can engage in natural language conversations to extract, summarize, and interact with PDF content effortlessly. Our
chatbot will provide seamless navigation, enabling users to ask questions, retrieve key information, and annotate documents with ease. Through overcoming
the limitations of traditional LLMs, we aim to empower users across various
domains to harness the full potential of conversational AI within the realm of
PDF documents

Steps Involved
1. PDF File: The process begins with a PDF document that contains the data
or context of interest.
2. Extract data/Context: The content of the PDF is extracted to get the
textual data.
3. Split in Chunks: The extracted text is then split into smaller pieces, referred to as chunks.
4. Text Chunk - 1 to Text Chunk - 10: These are the individual text
segments created from the original document.
5. Embedding - 1 to Embedding - 10: Each text chunk is converted into
an embedding.
6. Build Semantic Index: The embeddings are used to create a semantic
index.
7. Knowledge Database: This is the storage where the indexed data is kept.
8. User: This is the person interacting with the system.
9. Question: The user poses a question to the system.
10. Query Embeddings: The question is converted into an embedding.
11. Semantic Search: The query embedding is used to perform a semantic
search.
12. Ranked Results: The results of the semantic search are ranked.
13. LLM Generative AI: This is the AI model that generates responses.
14. User (feedback loop): The re
