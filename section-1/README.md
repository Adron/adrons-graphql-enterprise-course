# Section 1: Introduction to GraphQL

## 1.1 What is GraphQL and why is it useful?

- [Definition of GraphQL as a query language for APIs](00-intro-to-graphql.md)
- [Advantages of using GraphQL over REST](01-graphql-and-rest.md)
- [Benefits of declarative data fetching](02-schema-mutations-and-subscriptions.md)

## 1.2 Comparison with REST APIs

- Highlighting the differences between GraphQL and REST
- Discussing the challenges of over-fetching and under-fetching with REST
- Demonstrating how GraphQL solves these challenges

## 1.3 Building blocks: Schema, Queries, Mutations, and Subscriptions

- Explanation of the GraphQL schema as the contract between the client and server
- Overview of queries, mutations, and subscriptions as the three main operation types
- Example scenario:
    - Defining a schema for a social media application with User and Post types
    - Creating queries to fetch user profiles and post details
    - Introducing mutations to create new posts and update user information
    - Describing subscriptions to receive real-time updates on post comments

Example Scenario: Social Media Application

Consider a social media application where users can create posts and comment on them. The GraphQL API allows users to retrieve user profiles, post details, create new posts, and receive real-time updates on post comments.

## 1.1 What is GraphQL and why is it useful?

- Explanation: GraphQL is a query language for APIs that enables clients to request specific data from the server in a flexible and efficient manner. It allows clients to avoid over-fetching or under-fetching of data.
- Example: Comparing a GraphQL query that requests only the required fields for a user profile to a REST API endpoint that returns all user data, including unnecessary fields.

## 1.2 Comparison with REST APIs

- Explanation: GraphQL addresses common challenges faced with REST APIs, such as over-fetching and under-fetching of data, by allowing clients to request precisely what they need.
- Example: Comparing a REST API response that returns a list of posts with all fields, including author details, to a GraphQL query that retrieves only the necessary post fields without fetching the author data.

## 1.3 Building blocks: Schema, Queries, Mutations, and Subscriptions

- Explanation: The GraphQL schema acts as a contract between the client and server, defining the available types and operations. Queries are used to fetch data, mutations for creating/updating data, and subscriptions for real-time updates.
- Example: Defining a GraphQL schema for the social media application with User and Post types. Demonstrating queries to fetch user profiles, post details, mutations to create new posts, and subscriptions to receive real-time updates on post comments.

By providing this curriculum material, students will gain a solid understanding of the fundamentals of GraphQL, its advantages over REST, and the basic building blocks used in GraphQL APIs. The example scenario of a social media application will help them grasp the concepts through a practical and relatable context.
