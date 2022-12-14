# notion-integrations

This project was built as a way to familiarize the user with building custom Notion APIs.

The user can add a new database item to an existing Notion database.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install dependencies.

```bash
npm install
```

## Available Scripts

### Add Item to Notion Database

In the project directory, you can run:

```bash
node index.js
```

## Packages

To link the project to a specific Notion page:

Create a .env file to store your NOTION_KEY and NOTION_DATABASE_ID. When you run the project script, the [dotenv package](https://www.npmjs.com/package/dotenv) will read the .env file and set up the environment variables.

This ensures the new database item is sent to the appropriate Notion page.

## Roadmap

This project is a work in progress!\
Going forward I'd like to add:

More database modifications.
