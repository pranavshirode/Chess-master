API Reference (summary)

This file summarizes public functions/classes of the engine. For exact signatures consult src/ files.

Engine
- createBoard([fen?]) -> Board
- generateMoves(board, color) -> Move[]
- applyMove(board, move) -> Board
- isCheck(board, color) -> boolean
- isCheckmate(board, color) -> boolean
- evaluate(board, color) -> number

Persistence
- loadPGN(pgnString) -> Game
- exportPGN(game) -> string
- loadFEN(fenString) -> Board
- exportFEN(board) -> string

AI
- search(board, depth, options) -> bestMove
- evaluatePosition(board) -> score

Notes
- All engine functions are pure (they return new Board objects, not mutate in place) — check src/ for exactly implemented behavior.
- Exceptions: I/O helpers may throw on invalid input.
