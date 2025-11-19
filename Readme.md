## Project Title: AD 331 Implementing a Simple Retrieval-Augmented Generation (RAG) System
#### By: Amde Wubshet

### LLM Used: 
GPT-2

### Embedding Model Used
 all-MiniLM-L6-v2 
 
### Test Cases 
| Test Case || Chunks Recieved |  Query |  Analysis |
|---|---|---|---|
| 1 | Chunk 2 | "What is the primary function of the Baku?" | The knowledge chunk returned is what was expected, although the LLM still ended up hallucinated |
| 2 | Chunk 1 | "How are you supposed to cook sausages?" | What was returned from the LLM and the RAG system was not as ideal since the question isn't in the KB. |
| 3 | Chunk 2, Chunk 3 | "Which creature has a powerful sense of smell, and which creature is known for consuming dreams?" | Top 2 chunks ended up as expected, although the LLM is still hallucinating. |