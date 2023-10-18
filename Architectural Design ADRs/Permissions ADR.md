# Title

Transportation App: UI Framework
Date: 2023-10-14
William Black, Robert Carlson, Paul Sholter

## Status

Approved, combination of dynamic and granular permissions.

## Context

We are tasked with developing a mobile app for a modern transportation company, which involves multiple critical features, including geolocation services, real-time location tracking, payment processing, authentication, and more. The decision regarding how we handle permissions within the app is a crucial architectural consideration that will impact user experience and security.

## Decision

It seems most realistic to build this app by using a Hybrid App architecture. Hybrid apps provide us with the best balance of accessibility and maintainability. Since they support highly documented and common programming langauges like Javascript and Typescript, programmers will be able to easily make updates for future iterations and security enhancements. As well it is crucial that this app will reach people on both major operating systems(Android and IOS) which is best achieved using Hybrid Apps. Furthermore, since we will need to implement APIs, it will be most useful to have an app architecture that supports programming languages that have easy API integration, which Hybrid Apps have plenty of.

## Consequences

Implementing a dynamic and granular permissions system ensures that users have control over their data and provides transparency in how and when their information is accessed. This approach respects user privacy and builds trust, especially in a transportation app that handles sensitive data and real-time tracking. It requires clear user communication to explain why certain permissions are necessary, making the app more user-friendly. By following best practices for security and data protection, we ensure the app complies with industry standards and keeps user data secure.
