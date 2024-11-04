# pdfQuery_Langchain

# Pre-requisites: 
To run this notebook, you need a Serverless Cassandra with a Vector Search database on [Astra DB](https://accounts.datastax.com/session-service/v1/login). As outlined in more detail [here](https://docs.datastax.com/en/astra-db-serverless/get-started/quickstart.html#_prepare_for_using_your_vector_database), you should get a DB Token with the role Database Administrator and copy your Database ID. These connection parameters are needed momentarily.

You also need an [OpenAI API Key](https://cassio.org/start_here/#astra-db) for this notebook to work.

# Setup: 
import dependencies, provide secrets, create the LangChain vector store;

Run the notebook to retrieve the relevant headlines and have an LLM construct the answer.
