# Architecture Decision Record: Data Storage and Control
## Status
Accepted 
## Context
The Retail application is built upon native mobile application. The app will hence be built to work both online and offline giving the data being used per time. Our team will implement the offline-enabled architecture. There are several ways to configure the pattern of these technologies but we will use "full synchronization" on this moblile application. This will work in favor of allowing the customer to use offline features which is stored locally in a database, and with the access of internet connection, RESTApi's and other synchronization features will communicate with the server.
## Rationale
- Pros:
-- **Offline Support**: The data storage solution should support offline mode which will help user browse store items and build carts before paying online. 
-- **Performance**: The chosen data storage solution should be able to handle large amounts of data efficiently, ensuring smooth performance for users.
-- **Scalability**: The data storage solution should be scalable to accommodate changes in features, designs and requirements for data storage.

- Cons:
-- **Complexity**: Some data storage solutions may be complex to implement and maintain.
-- **Cost**: Certain data storage solutions may involve high costs, both in terms of initial setup and ongoing maintenance.
-- **Compatibility**: The data storage solution should be compatible with the app's other components and technologies to ensure seamless integration, which might pose problems accross different android platforms.

## Consequences
This so called offline-enables architeture syncronization technology will go a long way to enabling good user experience. The choice of data storage solution will impact the app's performance, scalability, and maintenance. It hence meets the requirements of working applications outside internet connection.
