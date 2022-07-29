---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Storage
  platforms: java
---

# Getting Started with Storage - Manage Storage Account Customer Managed Key - in Java #


  Azure Storage sample for managing storage accounts with customer-managed key.
  - Create a storage account with system assigned managed service identity
  - Create a key vault with purge protection enabled and access policy for managed service identity of storage account
  - Create a RSA key
  - Create diagnostic setting for audit logs
  - Update storage account to enable encryption with customer-managed key
  - Revoke customer-managed key
 
  {@see http://aka.ms/storagecmkconfiguration}
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/storage-java-manage-storage-accounts-customer-managed-key.git

    cd storage-java-manage-storage-accounts-customer-managed-key

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
