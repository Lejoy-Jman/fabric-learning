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

**Testing the new connection** 
* Create a simple copy data activity to test the new connection.
     1. Add a **Copy Data** task using the Copy Assistant.
       ![image](https://github.com/user-attachments/assets/88949091-61ee-4c31-8693-6078c4408d03)
     2. Select the appropriate data source type (e.g., SQL Server), and click **Next**.
       ![image](https://github.com/user-attachments/assets/90bda502-e2da-4649-8479-78015ee94662)
     3. Choose **Existing Connection**.  
     4. Open the drop-down menu to view the available connections.  
     5. Select the connection to the gateway created, and click **Next**.
       ![image](https://github.com/user-attachments/assets/4077e43f-d562-43a3-b56e-c3fd9a6a5586)
     6. Open the **Database** drop-down menu.  
     7. Select the desired source database (e.g., on the remote SQL1 server), and click **Next**.
       <img width="565" alt="image" src="https://github.com/user-attachments/assets/c0d8b232-103c-4b64-9c61-5102c73ab6c9" />
     8. Select the desired table from the list.
     9. Select the target lakehouse.
     10. ![image](https://github.com/user-attachments/assets/7b66f096-5983-4332-aeda-5ec3a4c6aa5a)

   

  

