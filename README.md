# AzureSecrets
A Repository for different Azure Secrets and Endpoints

## Virtual Network

https://YourVirtualNetworkGatewayIP:8081/healthprobe (Does not require login) Gateway 

## App Service

https://appservicename.scm.azurewebsites.net (SCM for App Service)  
ftp://waws-prod-am2-xxx.ftp.azurewebsites.windows.net/site/wwwroot (If enabled for App Service FTP for Logs)  
https://nameoffunction.azurewebsites.net/api/nameoffunction?code= Azure Function 

## Azure Resource Manager

https://resources.azure.com/ (Requires login) Resource Explorer 

## Databricks

https://adb-instancenumber.9.azuredatabricks.net/ (Requires login)

## AVD
https://rdbroker-g-us-r0.wvd.microsoft.com/api/health (AVD Broker for US)
https://afdfp-rdgateway-r1.wvd.microsoft.com/api/health (AVD Gateway for US)

## Managed Grafana

https://grafana-prod-01-instancename.weu.grafana.azure.com/?orgId=1

## Storage
https://storageaccountname.blob.core.windows.net/ (Blob)
https://storageaccountname.blob.core.windows.net/?sv=2021-06-08&ss=bfqt&srt=sc&sp=rwdlacupiytfx&se=2022-11-30T06:24:55Z&st=2022-11-29T22:24:55Z&spr=https&sig=ldCWUgntIqwbJhdl2uYUK0nDq85i4Uj0dUIDm3%2FWeH8%3D (Example of Blob with SIG enabled)
https://storageaccountname.file.core.windows.net/ (Files)
https://storageaccountname.queue.core.windows.net/ (Queue)
https://storageaccountname.z6.web.core.windows.net/ (Static Web Page)
https://storageaccountname.dfs.core.windows.net/ (Data Lake)
https://md-ransomwareint.z49.blob.storage.azure.net (Azure Disk Export)

## AKS
https://instancename-random.hcp.region.azmk8s.io (Admin API)

## Log Analytics
https://workspaceid.ods.opinsights.azure.com/<Resource>?api-version=2016-04-01 (Data Collection API)

## Application Insight
https://eastus-2.in.applicationinsights.azure.com (Application Insight) 
