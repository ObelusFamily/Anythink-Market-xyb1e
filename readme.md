# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repository
2. Make sure Docker is running.
3. Run docker-compose up from the project root directory.
4. Navigate to http://localhost:3000/api/ping in your browser to test the backend.
5. Navigate to http://localhost:3001/register in your browser to register a new account.
