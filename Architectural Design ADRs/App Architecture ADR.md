# Title

Transportation Company: Hybrid app architecture
Date: 2023-10-14
William Black, Robert Carlson, Paul Sholter

## Status

Approved, select Hybrid App Architecture

## Context

Creating an transport app requires users from both mobile operating systems(Android + IOS) to be able to download and use the app. The app must be created with an architecture that fulfill this requirement. This will ensure the largest demographic can be reached when the app is launched. Choosing the app architecture will also be important when planning which programming language to use, since heavy implementation of APIs will be necessary due to all the real-time map updates and database management.

## Decision

It seems most realistic to build this app by using a Hybrid App architecture. Hybrid apps provide us with the best balance of accessibility and maintainability. Since they support highly documented and common programming langauges like Javascript and Typescript, programmers will be able to easily make updates for future iterations and security enhancements. As well it is crucial that this app will reach people on both major operating systems(Android and IOS) which is best achieved using Hybrid Apps. Furthermore, since we will need to implement APIs, it will be most useful to have an app architecture that supports programming languages that have easy API integration, which Hybrid Apps have plenty of.

## Consequences

Although performance may be harder to obtain with Hybrid Apps, since they do not run natively on the operating system, we do believe updating and maintenance will be easier. As well, providing services to users across all platforms is crucial, which will only be obtained on Hybrid Apps. However, since integration with the native operating system will not be seamless like it would on a Native App architecture, it may run the risk of being less secure and perform less effeciently. This is a major concern due to requirements surrounding payment transaction and secure networking between riders/drivers. Hopefully, using APIs and know security techniques will curve this setback.
