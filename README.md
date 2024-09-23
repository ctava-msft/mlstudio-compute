---
description: This template sets up Azure ML Studio workspace with connected resources and compute.
page_type: sample
products:
- azure
- azure ml studio
- azure-resource-manager
urlFragment: mlstudio-compute
languages:
- arm
- json
---
# Setup Azure ML Studio with GPU Compute and other resources

[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fctava-msft%2Fmlstudio-compute%2Fmain%2Fazuredeploy.json)

This template sets up Azure ML Studio with a workspace, storeage account, keyvault and compute.

*** IMPORTANT: Standard_NC40ads_H100_v5 or similiar GPU quota is needed in your Azure region.

## Resources

The following table describes the resources created in the deployment:

| Provider and type | Description |
| - | - |
| `Microsoft.Compute` | `An Azure VM Compute` |
| `Microsoft.MachineLearningServices` | `An Azure ML Hub` |


## Learn more

If you are new to Azure Machine Learning, see:

- [Azure Machine Learning service](https://azure.microsoft.com/services/machine-learning-service/)
- [Azure Machine Learning documentation](https://docs.microsoft.com/azure/machine-learning/)
- [Azure Machine Learning compute instance documentation](https://docs.microsoft.com/azure/machine-learning/concept-compute-instance)
- [Azure Machine Learning template reference](https://docs.microsoft.com/azure/templates/microsoft.machinelearningservices/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/)
