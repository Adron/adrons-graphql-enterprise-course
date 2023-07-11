# Section 2: GraphQL Schema Definition Language (SDL)

## 2.1 Scalar types (String, Int, Float, Boolean, etc.)

- Explanation of scalar types available in GraphQL
- String, Int, Float, Boolean, ID, and custom scalar types
- Example scenario:
    - Defining scalar types for fields like name (String), age (Int), rating (Float), and isActive (Boolean)

## 2.2 Object types and fields

- Definition of object types and their role in GraphQL schemas
- Creating object types with fields and their types
- Example scenario:
    - Creating User and Post object types with fields like id (ID), name (String), and content (String)

## 2.3 Query and mutation types

- Explanation of query and mutation types in GraphQL
- Defining queries and mutations as entry points for data retrieval and modification
- Example scenario:
    - Adding a query type with fields like getUser(id: ID) and getAllPosts
    - Defining a mutation type with fields like createPost(content: String) and updateUser(id: ID, name: String)

## 2.4 Input types

- Introduction to input types in GraphQL
- Defining input types to pass complex arguments to mutations
- Example scenario:
    - Creating an input type called PostInput with fields like content (String) and userId (ID) to pass as an argument to createPost mutation

## 2.5 Enum types

- Overview of enum types in GraphQL
- Defining enums to represent a restricted set of values
- Example scenario:
    - Adding an enum type called UserRole with values like USER and ADMIN to represent user roles

## Example Scenario: Blogging Platform

Consider a blogging platform where users can create and manage blog posts. The GraphQL API allows users to query for user details, fetch blog posts, create new posts, and update user information.

## 2.1 Scalar types (String, Int, Float, Boolean, etc.)

- Explanation: Scalar types in GraphQL represent primitive data types, such as strings, integers, floating-point numbers, booleans, and IDs.
- Example: Defining scalar types for fields like title (String), views (Int), rating (Float), and isActive (Boolean) in the Post object type.

## 2.2 Object types and fields

- Explanation: Object types in GraphQL represent entities with specific fields that define their structure.
- Example: Creating User and Post object types with fields like id (ID), name (String), email (String), and posts ([Post]).

## 2.3 Query and mutation types

- Explanation: Query and mutation types serve as entry points for fetching and modifying data in a GraphQL schema.
- Example: Defining a query type with fields like getUser(id: ID) to fetch user details and getAllPosts to retrieve all blog posts. Creating a mutation type with fields like createPost(title: String, content: String) to create a new blog post and updateUser(id: ID, name: String) to update user information.

## 2.4 Input types

- Explanation: Input types allow passing complex arguments to mutations in a structured format.
- Example: Creating an input type called PostInput with fields like title (String), content (String), and userId (ID) to pass as an argument to the createPost mutation.

## 2.5 Enum types

- Explanation: Enum types define a restricted set of values that a field can take.
- Example: Adding an enum type called UserRole with values like USER and ADMIN to represent the role of a user in the system.

By covering these curriculum topics and providing examples within the context of a blogging platform, students will gain a solid understanding of GraphQL schema definition language (SDL).