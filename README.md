## Setup
You'll need [a Last.fm API account](https://www.last.fm/api/account/create)!

  * Run `yarn` to download the required libraries.
  * Copy `.env` to `.env.development.local` and fill in the required constants.
  * Docker and Docker Compose are required to run the API server locally.

## Development
Just start the application with `yarn start` (it will launch both the API server and the React application).
A database debug utility will be available on [localhost:8080](http://localhost:8080).

## Building
The `build` script should be enough! :)

## Deployment
It may depend on your target server; but just as a quick note, be sure to initialize the database using the [provided SQL file](./assets/db/openspyfm.sql).