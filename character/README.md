# ALX GraphQL Task: Fetch Character by ID

This task demonstrates how to write and execute GraphQL queries to retrieve specific character information from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

## 📌 Objective

To write GraphQL queries using the `character(id: ID!)` field to fetch details about characters with IDs: **1, 2, 3, and 4**.

## 🔍 Fields Fetched

For each character, the following fields were retrieved:

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## 📁 Files in the `character` directory

| File Name                    | Description                      |
| ---------------------------- | -------------------------------- |
| `character-id-1.graphql`     | GraphQL query for character ID 1 |
| `character-id-1-output.json` | Output result for character ID 1 |
| `character-id-2.graphql`     | GraphQL query for character ID 2 |
| `character-id-2-output.json` | Output result for character ID 2 |
| `character-id-3.graphql`     | GraphQL query for character ID 3 |
| `character-id-3-output.json` | Output result for character ID 3 |
| `character-id-4.graphql`     | GraphQL query for character ID 4 |
| `character-id-4-output.json` | Output result for character ID 4 |

## ✅ How Queries Were Run

All queries were executed using the [Rick and Morty GraphQL Explorer](https://rickandmortyapi.com/graphql).

Each `.graphql` file contains one query, and the corresponding `.json` file contains the result of that query.

## 🚀 Example Query

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
```
