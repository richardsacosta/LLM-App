# LLM-App using OpenAI embeddings and Vector search in Pinecone
Large Language Model using Open AI embeddings in a vector database (PineCone), to query and retrieve responses from a PDF document.
To conduct this project, below are a list of steps implemented to succesfully complete this project.
- Load Envoriment which contains the OpenAI Key used to create the vectors
- Read PDF document
- Divide the document into chunks of 800 size
- Use Embedding Technique of OpenAI to convert Text into Vectors (high-dimensional nmeric representation)
- Initialize Pinecone and create Index to store the data into the Vector DB
- Implement LLM model "text-davinci-003" and Q&A Chain
- Implement retrieve_query (using similarity search) and retrieve_answers functions
- Prompt our query and print the answer
