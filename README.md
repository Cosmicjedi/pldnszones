# pldnszones

Azure commercial - Deploy all PrivateLink Private DNS Zones

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Febizzity%2Fpldnszones%2Fmain%2Fazuredeploy.json)

This template deploys the zones found here: 
[[Azure PL Docs]](https://docs.microsoft.com/en-us/azure/private-link/private-endpoint-dns#azure-services-dns-zone-configuration)

This template deploys the following zones by default:

* privatelink.database.windows.net
* privatelink.blob.core.windows.net
* privatelink.table.core.windows.net
* privatelink.queue.core.windows.net
* privatelink.file.core.windows.net
* privatelink.web.core.windows.net
* privatelink.dfs.core.windows.net
* privatelink.documents.azure.com
* privatelink.postgres.database.azure.com
* privatelink.mysql.database.azure.com
* privatelink.mariadb.database.azure.com
* privatelink.vaultcore.azure.net
* privatelink.REGION.azmk8s.io
* privatelink.azurecr.io

You can uncomment any of the zones that are not listed above to have them deployed.