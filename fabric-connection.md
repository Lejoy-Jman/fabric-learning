# **Connection settings in Fabric**

**Access control for the Gateway**
* Open Fabric -> Settings -> Manage connections and gateways
* ![image](https://github.com/user-attachments/assets/a116a4ef-644e-4342-b3fd-ec1f6ac445a0)

* **Create a New Connection**
    * Select the Connections tab
    * Tap the New button
    * Select On-premises in the New connection dialog
    * Select the name of the on-premises gateway (the name you gave it when you installed the software on the gateway machine in your on-prem environment).
    * Provide a name for the new connection (which users will use to select the gateway when connecting to data).
    * Select the Connection type – in this example an on-prem SQL Server 2022 instance.
    * Complete the connection information that will be passed to the gateway as it makes connections to the on-premises data.
    * <img width="470" alt="image" src="https://github.com/user-attachments/assets/28d92ed8-3dd1-4ee0-adff-8095bae2b291">

**Adding Users to the Connection**
* Users from our organization can now be added to the gateway without needing to know the credentials or creating their own connections.
    * Select the On-premises data gateways tab
    * <img width="490" alt="image" src="https://github.com/user-attachments/assets/631855b8-79a3-4cca-967a-ca4848cde9dd">
    * From the ... menu, select Manage users
    * Search for a user or security group to authorize to access the gateway
    * Select the user or group just added to the ACL
    * Select the appropriate level of authorization for them.
    * ![image](https://github.com/user-attachments/assets/f75ebac1-c836-46e2-b533-5687ce22ab8a)

