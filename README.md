# Vector search test using Cosmos Db

Adjust the following values to your environment in the .env file:

```
AOAI_ENDPOINT="https://<your azure openai instance>.openai.azure.com"
AOAI_API_KEY="Azure openai API key"
EMBEDDING_DEPLOYMENT_NAME="text-embedding-3-large"
COSMOSDB_CONN_STR="AccountEndpoint=https://<your cosmos db>.documents.azure.com:443/;AccountKey==;"
COSMOSDB_DB_NAME="EmbeddingsDB"
COSMOSDB_CONTAINER_NAME="hotpotqase"
```