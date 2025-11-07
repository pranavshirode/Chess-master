Usage

Run the application
- Development server / CLI:
  npm start
  or
  node ./src/index.js

Basic commands
- Start a local game (CLI): npm run play
- Load a FEN: npm run play -- --fen "<FEN_STRING>"
- Export PGN: use the UI or engine API to generate PGN from move history.

Configuration
- Config file: config/default.json (or project equivalent). Contains settings for difficulty, UI mode, and logging.

Examples
- Start a new game (CLI):
  npm run play

- Run engine tests:
  npm test
