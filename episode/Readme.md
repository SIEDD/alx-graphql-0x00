# Episode Details Query with GraphQL

This project demonstrates how to use GraphQL to retrieve details of specific episodes from the **Rick and Morty API**. The queries utilize the `episode(id: ID!)` field to fetch data such as the episode ID, name, air date, and episode code.

---

## Objective

The main objective of this project is to:
- Write GraphQL queries to fetch episode details from the Rick and Morty API.
- Save the queries and their corresponding outputs in separate files for documentation and review.

---

## API Information

- **API Endpoint**: [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql)
- **Field Used**: `episode(id: ID!)`

### Fields Retrieved
Each query fetches the following fields:
- `id`: The unique identifier for the episode.
- `name`: The title of the episode.
- `air_date`: The release date of the episode.
- `episode`: The episode code (e.g., `S01E01`).

---

## Project Structure

```plaintext
alx-graphql-0x00/
└── episode/
    ├── README.md
    ├── episode-id-1.graphql
    ├── characters-page-1-output.json
    ├── characters-page-2.graphql
    ├── characters-page-2-output.json
    ├── ...

