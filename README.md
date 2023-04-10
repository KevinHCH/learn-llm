# RESOURCES TO LEARN AND UNDERSTAND LLM

- video with the basic concepts: https://youtu.be/LbT1yp6quS8

## BASIC CONCEPTS
- [blog example](https://www.python-engineer.com/posts/langchain-crash-course/)
- [chat-langchain-example](https://github.com/hwchase17/chat-langchain)

- models: stablished models inside this tool which we can access
  - llm: large language model
    - this large models allows us to use the different API from openai or hugging face
- prompt template: allow us to create the different steps as a prompt and get better responses, also allow us to replace the "search terms" / placeholders
- chains: allos us to combine multiple prompts and models to have the proper response
- agents and tools: allow you to chain and send the response to the proper tools when you need it.
  - Example: you need to know when a movie was release and how many years it pass until now. To do that the llm will need to check the wikipedia and do the maths with some librabry, in that case u need to chain 2 tools and that should give you the proper response
- memory: allows u to create a context with the chain, so the the model and chain it should not forget the context of the conversation
- document loaders: allows u to load the data to train your models from multiple sources such as:
  - pdf
  - txt
  - databases (vector databases)
- indexes: 
  - embeddings: numerical representation of a piece of information (text, docs, images, pdf)
  - text splitter: when u need to load and operate with long pieces of information
  - vectorstores: store and index vector embeddings from NLP models to understand the meaning of the context (for more accurate results)
