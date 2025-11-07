Architecture Overview

Goals
- Correct, testable chess rules implementation.
- Clear separation: engine, UI, AI, data models, and utilities.
- Easy to extend and instrument.

High-level modules
- Engine: board representation, legal move generation, move application, FEN import/export.
- Rules: checks, checkmate, stalemate, special moves (castling, en passant, promotion).
- AI: pluggable search module (minimax/alpha-beta) and evaluation function.
- UI: CLI and optional GUI adapters.
- Persistence: save/load games and PGN support.
- Tests: unit tests for engine and integration tests for flows.

Data model
- Board: 8x8 array or bitboard (project default indicated in src/README).
- Piece encoding: type, color, metadata (hasMoved).
- Move representation: from, to, promotion (optional), flags.

Design patterns
- Pure functions for rule checks where possible.
- Separation of side-effects (I/O) from pure engine logic.
- Dependency injection for AI and UI for easy testing.
