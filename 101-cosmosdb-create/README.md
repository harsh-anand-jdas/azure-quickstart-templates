# Create an Azure Cosmos DB account for Core (SQL) API, a database, and a container 

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/PublicLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/PublicDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/FairfaxLastTestDate.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/FairfaxDeployment.svg" />&nbsp;

<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/BestPracticeResult.svg" />&nbsp;
<IMG SRC="https://azurequickstartsservice.blob.core.windows.net/badges/101-cosmosdb-create/CredScanResult.svg" />&nbsp;

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-cosmosdb-create%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-cosmosdb-create%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true"/>
</a>

This template will create an Azure Cosmos account for Core (SQL) API, provisioned for two regions, then provision a database, a container with dedicated throughput showing multiple indexing options.

`Tags : CosmosDB`

Below are the parameters which can be user configured in the parameters file including:

- **Consistency Level:** Select from one of the 5 consistency levels: Strong, Bounded Staleness, Session, Consistent Prefix, Eventual. Default is Session.
- **Multi-Region:** Enter locations for primary and secondary regions.
- **Multi-Master:** Select whether to enable multi-master support making both regions fully writable.
- **Automatic Failover:** Select whether to enable automatic failover on the account (Ignored when Multi-Master is enabled).
- **Database Name:** Enter the database name for the account.
- **Container Name:** Enter the name for the container with dedicated throughput.
- **Throughput:** Enter the RU/s for the dedicated container (default is 400).

