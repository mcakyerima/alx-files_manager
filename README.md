# Files Manager 📁

[![Coverage Status](https://coveralls.io/repos/github/B3zaleel/alx-files_manager/badge.svg?branch=main)](https://coveralls.io/github/B3zaleel/alx-files_manager?branch=main)

Welcome to Files Manager, a robust API designed for efficient file management, leveraging the power of Express, MongoDB, Redis, Bull, and Node.js.

## Requirements 🛠️

### Applications

- **Node.js**: The runtime environment for executing JavaScript code.
- **Yarn**: A package manager and resource negotiator for managing project dependencies.

### APIs

To enhance functionality, ensure the presence of a Google API configured with at least an email sending scope. The API should have a valid redirect URI, such as `http://localhost:5000/`. Don't forget to store the `credentials.json` file in the project's root directory.

### Environment Variables

To customize the server's behavior, utilize environment variables stored in a `.env` file. Each line should adhere to the format `Name=Value`. Key variables include:

- **GOOGLE_MAIL_SENDER**: The email address responsible for sending emails to users.
- **PORT**: (Optional, Default: `5000`) The port at which the server should listen.
- **DB_HOST**: (Optional, Default: `localhost`) The host address of the database.
- **DB_PORT**: (Optional, Default: `27017`) The port of the database.
- **DB_DATABASE**: (Optional, Default: `files_manager`) The name of the database.
- **FOLDER_PATH**: (Optional, Default: `/tmp/files_manager` on Linux and Mac OS X, `%TEMP%/files_manager` on Windows) The local folder for storing files.

## Installation ⚙️

- Clone this repository and navigate to the cloned directory.
- Install project dependencies using `yarn install` or `npm install`.

## Usage 🚀

Start the Redis and MongoDB services on your system, then initiate the server by running `yarn start-server` or `npm run start-server`.

## Tests 🧪

For robustness verification, follow these steps:

- Create a separate `.env` file for testing named `.env.test`.
- Populate the file with appropriate environment variables for testing.
- Execute end-to-end tests with `yarn test` or `npm run test`.

With Files Manager, streamline your file management operations effortlessly!