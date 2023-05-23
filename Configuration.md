# Configuration

## API Configuration

| Key | Default Value | Detail |
| --- | --- | ------------- |
|OpenAiKey|4588cf7bbad5490ea3d9a0e9fb5f139f|  <br>You can get the OpenAI Key from Azure Portal for your deployed OpenAI service.
|OpenAiService|azccogadvance12aoai|
|OpenAiEndPoint|https://azccogadvance12aoai.openai.azure.com/ <br>(https://<yourresource>.openai.azure.com/)|
|OpenAiVersion|2022-12-01|API Version of the Azure OpenAI
|OpenAiDavinci|davinci|Deployment name of text-davinci-003 <br>model in Azure OpenAI
|OpenAiEmbedding|text-embedding-ada-002|Deployment name of <br>text-embedding-ada-002 model in Azure OpenAI
|MaxTokens|500|Maximum Tokens
|Temperature|0.3|Temperature
|OpenAiChat|chat|Deployment name of gpt-35-turbo model in <br>Azure OpenAI
|PineconeKey|key|Pinecone Key
|PineconeEnv|env|Pinecone Environment
|VsIndexName|oaiembed|Pinecone Index name
|RedisPassword|Password|Redis Password
|RedisAddress|localhost|Redis URI
|RedisPort|6379|Redis Port
|OpenAiDocStorName|azccogadvance12funcsa|
|OpenAiDocStorKey|wAtPvesoFDY07cwOHiVcOu7quoUB0F5V3zSVKtN1BeqVgkO7fiCXSJQFTsLXTdq0QW2IT7yBVK45+AStkdZxkw==|
|OpenAiDocContainer|chatpdf|Document storage container name
|SearchService|azccogadvance12azs|
|SearchKey|jK6qdjnfkQz967LYV77nBgACQf0MUzvdFGmGUjB2bJAzSeDDMKNE|
|SecDocContainer|secdoc|Document Storage container to <br>store SEC documents
|SynapseName||Name of the SQL for SQL NLP (Azure SQL, Synapse)
|SynapsePool||Database or SQL Pool Name
|SynapseUser||SQL User name
|SynapsePassword||SQL Password
|UploadPassword|Bless123|
|AdminPassword|Blessed23|
|DOCGENERATOR_URL|Optional Settings|Required only if you are planning to use the AWS Integration.
|*PROMPTS*||Default Prompts for Speech Analytics Use-case. <br>26 Keys with different prompt.

## Application Configuration

| Key | Default Value | Detail |
| --- | --- | ------------- |
AGENTQA_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
BLOB_CONNECTION_STRING|DefaultEndpointsProtocol=https;AccountName=azccogadvance12stor;AccountKey=gOyO9wsnQ6VRAHrCdU53OYt8/MNuTiqch7+ag5YMOWNFuCFNY1hDrmHAXyRjjQG/3XZGdlqodRIy+AStapGRDQ==;EndpointSuffix=core.windows.net|
BLOB_CONTAINER_NAME|chatpdf|
CHAT3_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
CHAT_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
DOCGENERATOR_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
INDEXMANAGEMENT_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
QA_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
SECSEARCH_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
SPEECH_KEY|920c4c6fa1f045daaefe6f55305be1e5|
SPEECH_REGION|westeurope| <br> (i.e. eastus, southcentralus)
SQLCHAIN_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==|<br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
SQLCHAT_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==| <br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
SUMMARIZER_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==| <br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
SUMMARYQA_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==| <br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
TASKAGENTQA_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==| <br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
TEXTANALYTICS_KEY|cf8ec222ebb84ac6a835a93dbc7a97ee|Text Analytics(Language) 
TEXTANALYTICS_REGION|westeurope| <br> (i.e. eastus, southcentralus)
VERIFYPASS_URL|https://azccogadvance12func.azurewebsites.net/api/AgentQa?code=afGBbjOZHxUOAH5GK8snL5rVVdvu249pm_OASZOWkvhcAzFuJrW7Lw==| <br> (https://<yourfunction>.azurewebsites.net/api/AgentQa?code=<yourcode>)
