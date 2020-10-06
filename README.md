# Copy any repo onto Azure Machine Learning Service Notebook






Get Started and Documentation
-----------------------------


# Azure Machine Learning Service 
[Azure Machine Learning service](https://azure.microsoft.com/en-us/services/machine-learning-service/) provides a cloud-based environment to prep data, train, test, deploy, manage, and track machine learning models. This service fully supports open-source technologies such as PyTorch, TensorFlow, and scikit-learn and can be used for any kind of machine learning, from classical ML to deep learning, supervised and unsupervised learning.

Learn how Azure Machine Learning can help you streamline the building, training, and deployment of machine learning models. Start free today.

# Getting Started

### Start training on the notebook
#### Owner of the subscription
[![Deploy(Owner) On Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnaraymad1%2Faz-copy-github-ml-notebook%2Fmaster%2F.cloud%2FazuredeployGitClone.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://raw.githubusercontent.com/naraymad1/az-copy-github-ml-notebook/master/.cloud/azuredeployGitClone.json)

#### Contributor of the subscription
Ask the owner of subscription to create a managed identity on the resource group and assign contributor role to this identity, 
owner may use the following template  to create managed identity for the resource group and assign role.

[![Deploy(Owner) On Azure-identity](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnaraymad1%2Faz-copy-github-ml-notebook%2Fmaster%2F.cloud%2FazuredeployManagedIdentity.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://raw.githubusercontent.com/naraymad1/az-copy-github-ml-notebook/master/.cloud/azuredeployManagedIdentity.json)

Deploy the repo 

[![Deploy(Contributor) On Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnaraymad1%2Faz-copy-github-ml-notebook%2Fmaster%2F.cloud%2FazuredeployGitClone2.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://raw.githubusercontent.com/naraymad1/az-copy-github-ml-notebook/master/.cloud/azuredeployGitClone2.json)


This ARM template creates a code job in Azure Machine Learning workspace.

If you are new to Azure Machine Learning, see:

- [Azure Machine Learning service](https://azure.microsoft.com/services/machine-learning-service/)
- [Azure Machine Learning documentation](https://docs.microsoft.com/azure/machine-learning/)
- [Azure Machine Learning template reference](https://docs.microsoft.com/azure/templates/microsoft.machinelearningservices/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/)
