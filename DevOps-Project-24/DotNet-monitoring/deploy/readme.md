# Deploy into Azure

To deploy as a Azure Container App, a Bicep template is provided

Set resource group and region vars:

```bash
RES_GRP=demoapps
REGION=northeurope
```

Create resource group:

```bash
az group create --name $RES_GRP --location $REGION -o table
```

Deploy Azure Container App

```bash
az deployment group create --template-file container-app.bicep --resource-group $RES_GRP
```

Optional deployment parameters, each one maps to an environment variable (see [main docs](../#configuration) for details):

- **weatherApiKey**
- **appInsightsInstrumentationKey**
- **azureAdClientId**
- **azureAdClientSecret**
- **azureAdTenantId**
- **azureAdInstance**


## 🛠 Author

This project is maintained by **[Syed Ikramuddin Kirmani](https://github.com/iikram42)** 💡.  
Your feedback and contributions are welcome!

📧 *Connect with me:*
- *GitHub*: [@iikram42](https://github.com/iikram42)
- *LinkedIn*: [Syed Ikramuddin Kirmani](https://www.linkedin.com/in/ikramkirmani/)

---

## ⭐ Support the Project

If you found this project helpful, please consider:
- *Starring* ⭐ the repository  
- *Sharing* it with your network  
- *Contributing* to its improvement

> [!Important]  
> This documentation is continuously evolving. For the latest updates, please check the repository regularly.
