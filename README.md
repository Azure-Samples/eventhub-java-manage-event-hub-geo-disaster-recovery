---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Eventhubs
  platforms: java
---

# Getting Started with Eventhubs - Manage Event Hub Geo Disaster Recovery - in Java #


  Azure Event Hub sample for managing geo disaster recovery pairing -
    - Create two event hub namespaces
    - Create a pairing between two namespaces
    - Create an event hub in the primary namespace and retrieve it from the secondary namespace
    - Retrieve the pairing connection string
    - Fail over so that secondary namespace become primary.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/eventhub-java-manage-event-hub-geo-disaster-recovery.git

    cd eventhub-java-manage-event-hub-geo-disaster-recovery

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
