# Conversational-RAG-Application-with-LangChain-and-OpenAI-LLM
I recently built a Conversational Retrieval-Augmented Generation (RAG) Chatbot that enhances information retrieval by leveraging LangChain and OpenAI's LLMs. This chatbot processes and extracts relevant insights from uploaded documents (e.g., CVs, reports, PDFs), enabling intelligent and context-aware conversations

1️⃣ Project Setup
2️⃣ Load and Process Documents (PDFs) :- This step helps extract meaningful text data from the document.
3️⃣ Split Text into Chunks :- This improves retrieval accuracy by breaking content into manageable pieces.
4️⃣ Create a Vector Store with ChromaDB :- This allows semantic search by retrieving relevant content based on meaning rather than keywords.
5️⃣ Define the Chatbot's Behavior :- This ensures that responses use only relevant document data, avoiding hallucinations.
6️⃣ Create RAG Pipeline :- The chatbot retrieves relevant information before generating answers, ensuring accuracy.
7️⃣ Test the Chatbot :- This checks if the chatbot retrieves the right information from the document.
8️⃣ Add Conversational Memory (Context Awareness) :- This ensures that follow-up questions stay in context.
9️⃣ Create a Conversational RAG Chain :- This enables a session-based chat, where users can continue conversations seamlessly.
🔟 Final Test with Conversation Memory :- The chatbot remembers past interactions and improves responses.


