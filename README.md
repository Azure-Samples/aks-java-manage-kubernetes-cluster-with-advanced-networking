---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Kubernetescluster
  platforms: java
---

# Getting Started with Kubernetescluster - Managed Kubernetes Cluster With Advanced Networking - in Java #


  Azure Container Service (AKS) sample for managing a Kubernetes cluster.
    - Create a Virtual Network with two subnets.
    - Create a SSH private/public key
    - Create an Azure Container Service (AKS) with managed Kubernetes cluster and advanced networking
    - Update the number of agent virtual machines in the Kubernetes cluster
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aks-java-manage-kubernetes-cluster-with-advanced-networking.git

    cd aks-java-manage-kubernetes-cluster-with-advanced-networking

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.