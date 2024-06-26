## OpenAI Assistant with Access to Tools

> _We've been merging with tools since the beginning of human evolution, and arguably, that's one of the things that makes us human beings_.
      -- Franklin Foer


**Open AI Assistants**
- Multimodal
- Persistent
- File search
    - Upload upto 10,000 documents
    - Embedding
    - Vector store
    - Page rank
- Python interpreter
- Tools
    - Access external APIs, databases, graphQL
    - Up to 1000 tools
    - Able to use mulitple tools to accomplish tasks


Chat bots are great at returning data from a knowledge base (RAG), but even more powerful if they can access curated data from an API, query a database to perform operations on the data, or do calculations on the fly with data using the python interpreter.  

Importantly, there is no conditional logic in the code, the LLM chooses when and how to use the tools.


As a proof of principle -- a blue devil bot:

**Blue Devil Bot**
- File Search
    - Faculty handbook
    - DGS manual
    - DGSA manual
- Python interpreter
- Tools
    - Duke Directory
    - Scholars 
    - Additional tech demonstrations
        - Chinook Music Database (SQL queries)
        - Star Wars SWAPI (GraphQL queries) 




