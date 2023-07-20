# GraphQL Constituent Parts

The basic building blocks of GraphQL are the schema, queries, mutations, and subscriptions. These components define the structure and functionality of a GraphQL API.

1. Schema:
    - The schema is a central piece of a GraphQL API. It defines the available types, fields, and operations that clients can query or mutate.
    - The schema is written using the GraphQL Schema Definition Language (SDL) or can be defined programmatically using a GraphQL schema library.
    - The schema consists of two main components: object types and root types.
        - Object types represent the entities in the API, such as users, posts, or products. They define the fields that can be queried or mutated.
        - Root types define the entry points for querying and mutating data. The two main root types are Query and Mutation.
    - The schema acts as a contract between the server and the clients, ensuring that both sides understand and agree on the available data and operations.
2. Queries:
    - Queries are used to fetch data from a GraphQL API. They specify the fields and relationships that clients want to retrieve in their response.
    - Queries are structured similarly to the shape of the desired response. Clients can request specific fields and traverse related data in a hierarchical manner.
    - The entry point for queries is typically the Query root type defined in the schema. Clients can perform multiple queries in a single request to retrieve the required data efficiently.
3. Mutations:
    - Mutations are used to modify data on the server. They allow clients to create, update, or delete data in the GraphQL API.
    - Like queries, mutations are defined in the schema as fields within the Mutation root type.
    - Mutations take input arguments to specify the data to be modified. They can return values to provide feedback on the outcome of the mutation, such as the updated data or success/error messages.
4. Subscriptions:
    - Subscriptions enable real-time communication between the server and clients. They allow clients to subscribe to specific events or data changes and receive updates in real-time.
    - Subscriptions are defined in the schema as fields within the Subscription root type.
    - Clients establish a persistent connection with the server, and when a subscribed event occurs, the server pushes the corresponding data to the subscribed clients.
    - Subscriptions are commonly used for implementing real-time features like live notifications, chat applications, or collaborative editing.

By combining these building blocks, GraphQL provides a powerful and flexible way to define and interact with APIs. The schema defines the available types and operations, queries fetch data, mutations modify data, and subscriptions enable real-time updates. This modular and declarative approach makes GraphQL a versatile choice for designing APIs to cater to specific client needs efficiently.
