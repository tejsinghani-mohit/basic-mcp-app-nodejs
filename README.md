# basic-mcp-app-nodejs

A minimal Node.js sample app used for MCP / hands-on exercises.

## What this is

Small example app with a `server.js` entrypoint and a lightweight test file (`test.js`). Suitable for local development and demonstrations.

## Prerequisites

- Node.js (recommended >= 14)
- npm (bundled with Node.js)

## Install

Install dependencies:

```bash
npm install
```

## Run

Try the npm start script (if present) or run the server directly:

```bash
npm start
# or, if no start script is defined
node server.js
```

The server listens on the port configured in the code (often via `process.env.PORT`).

## Tests

If a test script exists in `package.json`, run:

```bash
npm test
```

Or run the included `test.js` manually:

```bash
node test.js
```

## Environment

Put local environment variables in a `.env` file (this repo includes `.gitignore` entries to avoid committing `.env`).

## Contributing

Small changes and fixes are welcome. Open a PR against `main`.

## License

MIT (or your preferred license)
