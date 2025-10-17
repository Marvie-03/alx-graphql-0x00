# Character API Project

This project contains a set of GraphQL queries to fetch details of characters from the Rick and Morty API. Each character is identified by a unique ID, and the queries retrieve specific fields related to the characters.

## Project Structure

- **README.md**: Documentation for the project.
- **character-id-1.graphql**: GraphQL query for character ID 1.
- **character-id-1-output.json**: JSON output for character ID 1.
- **character-id-2.graphql**: GraphQL query for character ID 2.
- **character-id-2-output.json**: JSON output for character ID 2.
- **character-id-3.graphql**: GraphQL query for character ID 3.
- **character-id-3-output.json**: JSON output for character ID 3.
- **character-id-4.graphql**: GraphQL query for character ID 4.
- **character-id-4-output.json**: JSON output for character ID 4.

## Characters (paginated) Queries

This folder also includes paginated queries that fetch lists of characters using the `characters(page: Int)` field. Each query file selects `id`, `name`, `status`, and `image` for every character returned on that page.

Files added:

- `characters-page-1.graphql` — query for page 1
- `characters-page-1-output.json` — example output for page 1
- `characters-page-2.graphql` — query for page 2
- `characters-page-2-output.json` — example output for page 2
- `characters-page-3.graphql` — query for page 3
- `characters-page-3-output.json` — example output for page 3
- `characters-page-4.graphql` — query for page 4
- `characters-page-4-output.json` — example output for page 4

## GraphQL Queries

Each `.graphql` file contains a query structured to fetch the following fields for the respective character IDs:

- **id**
- **name**
- **status**
- **species**
- **type**
- **gender**

This allows for a comprehensive overview of each character's details as provided by the API.