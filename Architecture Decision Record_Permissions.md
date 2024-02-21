# Architecture Decision Record: Permissions and Access
## Status
Accepted
## Context
Permissions play a crucial role in the security and usability especially when using native app development. Determining the appropriate permissions for different user roles and features is essential for ensuring that the app functions correctly and securely. We shall be using a push notification technology for mobile applications. An example will be irebase Cloud Messaging (FCM) for androids. This gives the application ability to display information or notifications for the users like insights, purchases, deals, etc.
## Rationale
- Pros:
-- **Security**: Push notifications are used for authentication in apps and sites with sensitive information, like online banking or healthcare platforms.
-- **User Experience**: Permission features enhance the users experience for examlple, providing access to relevant features and content based on the user's role or preferences.
-- **Compliance**: Permissions can help ensure compliance with regulatory requirements and industry standards.

- Cons:
-- **Complexity**: Implementing and managing permissions can add complexity to the app's codebase and administration.
-- **User Confusion**: Poorly implemented permissions can confuse users and lead to frustration.


## Consequences

- Push notifications are valuable because they let users get information when and how they want it. This helps prevent users from feeling overwhelmed by notifications and encourages app creators to provide useful content. 
- For organizations, push notifications are useful for sending timely updates and personalized information. This hence tackes the requirement of permissions and access from the application to the user.
