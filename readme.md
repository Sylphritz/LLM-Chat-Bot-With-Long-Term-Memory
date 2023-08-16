# Python LLM Q&A Bot with Long-Term Memory

This is a Jupyter Notebook showcasing a Large Language Model GPT chat bot with the ability to retain long-term memory by utilizing a vector database.

## Tools and Frameworks Used In This Project

- **Language:** Python
- [**ChromaDB**](https://www.trychroma.com/) - An open-source vector database you can host on your machine.
  - You can also use other vector database like [Pinecone](https://www.pinecone.io/), [Milvus](https://milvus.io/), and etc. But for simplicity's sake, I will use Chroma's transient storage to store the data.
- [**LangChain**](https://python.langchain.com/docs/get_started/introduction.html) - A framework that makes it much easier to work with LLMs and vector database. It basically acts as a bridge between language models and vector database. It also provides many functionalities that help prompt generation and query processing.
- [**OpenAI**](https://openai.com/) - This will be our LLM bot that convert the data queried from the database into proper sentences.

```terminal
pip install -q openai langchain python-dotenv tiktoken chromadb wikipedia
```
