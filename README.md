# ntttcp-linux-aci
Azure ARM template to deploy an "ntttcp for linux" container, listening in 5 ports (1 control + 4 data)

```
~ $ git clone https://github.com/PedroPerezMSFT/ntttcp-linux-aci
~ $ az group deployment create --resource-group netperftest --template-file .\ntttcp-linux-aci\azuredeploy.json
```

The above assumes you have a resource group called "netpertest" on your region of choice.
