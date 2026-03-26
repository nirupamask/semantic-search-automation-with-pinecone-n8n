# semantic-search-automation-with-pinecone-n8n
n8n workflow for semantic search using OpenAI embeddings and Pinecone vector database. Automates text embedding, storage, and query-based retrieval for intelligent search.

Semantic Search Automation with n8n & Pinecone
 
**Description**
 
-Automation workflow in n8n for semantic search.
 
-Uses OpenAI embeddings to convert text into vectors.
 
-Stores embeddings in Pinecone vector database.
 
-Retrieves relevant results based on user queries.
 
-Integrates with external APIs via HTTP requests.
 
-Ideal for AI-powered search, chatbots, and knowledge management.

**Workflow Tools / Nodes**
 
-Trigger Node – Starts the workflow on new data or query.
 
-Edit Fields Node – Formats input text or query.
 
-Create Embedding Node – Generates vector embeddings using OpenAI.
 
-Store Vector Node – Saves embeddings in Pinecone.
 
-User Query Node – Accepts semantic search queries.
 
-Query Embedding Node – Converts query into a vector embedding.
 
-Pinecone Query HTTP Node – Finds matching vectors in Pinecone.
 
-HTTP Request Node – Fetches external data or integrates APIs.
 
-Toggle / Conditional Nodes – For branching logic and data manipulation.
 
 
 
---
 
**Workflow Steps**
 
-Receive input text or user query.
 
-Format text using Edit Fields Node.
 
-Create embeddings via OpenAI.
 
-Store embeddings in Pinecone.
 
-Convert user query to embedding.
 
-Search vector database for relevant results.
 
-Fetch additional data if needed via HTTP Request Node.
 
 
 
---
 
**Tech Stack**
 
-n8n – Automation platform
 
-Pinecone – Vector database
 
-OpenAI embeddings – Text representation
 
-HTTP / REST APIs – Integration with external data
 
 
 
---
 
**Setup & Usage**
 
-Clone repo: git clone https://github.com/your-username/semantic-search-automation.git
 
-Install n8n and import workflow (n8n_workflow.json).
 
-Configure .env with:
 
1.OPENAI_API_KEY=your_openai_key
2.PINECONE_API_KEY=your_pinecone_key
3.PINECONE_ENVIRONMENT=your_pinecone_environment
 
-Run workflow and test semantic search queries.
 
-Extend workflow with additional nodes as needed.
 
 
 
![workflow](vector-embeddings-storage.png.png)
)
 
 
 

 
