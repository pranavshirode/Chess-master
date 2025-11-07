Testing

Test types
- Unit tests: engine rules, move generation, helpers.
- Integration tests: full game flows and PGN import/export.
- Regression tests: critical FEN positions.

Run tests
- npm test
- npm run test:watch (if configured)

Coverage
- npm run coverage (if configured). Aim for high coverage on engine logic.

Writing tests
- Small focused tests.
- Include FEN for board setup when testing specific positions.
- Assert legal move lists and resulting board states.
