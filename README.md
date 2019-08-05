
### Deploy to Azure 
[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkrishnaji%2Fapp-service-linux-docker-arm%2Fmaster%2Ftemplate.json)

### Deployt to Azure using [Azure CLI](https://shell.azure.com) 

``` git clone https://github.com/krishnaji/app-service-linux-docker-arm.git ```

Update the parameters.json file.

``` az group deployment create -g <resource-group-name> --template-file template.json --parameters parameters.json ```
