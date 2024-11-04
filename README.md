# pdfQuery_Langchain
# Querying PDF With Astra and LangChain
# Pre-requisites:
# You need a Serverless Cassandra with Vector Search database on Astra DB to run this demo. As outlined in more detail here, you should get a DB Token with role Database Administrator and copy your Database ID: these connection parameters are needed momentarily.

# You also need an OpenAI API Key for this demo to work.

# What you will do:
# Setup: import dependencies, provide secrets, create the LangChain vector store;
# Run a Question-Answering loop retrieving the relevant headlines and having an LLM construct the answer.
