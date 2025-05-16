# Release Notes

### 12 May 2025
- Issue Description: During Lab 1, Exercise 1, we encountered an issue while testing the Echo API within the API Management (APIM) service. Specifically, the GET request for the Echo API's retrieve resource operation was returning a "404 Not Found" error.

- Resolution: Upon investigation with Microsoft support, it was identified that the endpoint associated with the Echo API has recently been migrated. However, as the migration process by Microsoft is still ongoing, the new endpoint is not yet fully reflected in the system. To address this, a new Echo API was created using the updated endpoint, which successfully returned the expected response.

- Content Updates: Accordingly, the lab guide for Lab 1 has been updated to include steps for creating a new Echo API using the current, valid endpoint.

### 31 December 2024

- Major Updates

    - **Exercise 9, Task 3: API Proxy to Serverless**  
        - The **Functions** option in the Function App is no longer available.  
        - Updated the lab guide to include detailed steps for creating a function and deploying it to the **Function App** using **Visual Studio Code**.

- Minor Updates

    - Enhanced lab guide instructions to improve clarity and usability for participants.  
    - Updated screenshots across the lab guide to reflect the latest UI changes, ensuring a consistent and intuitive user experience.

