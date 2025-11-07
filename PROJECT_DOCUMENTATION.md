# Java Project Documentation
Version: 1.0.0

## Description
A Java project

## Project Structure
```docs\script.js
docs\type-search-index.js
docs\tag-search-index.js
docs\search.js
docs\search-page.js
docs\package-search-index.js
docs\module-search-index.js
docs\member-search-index.js
docs\script-dir\jquery-ui.min.js
docs\script-dir\jquery-3.6.1.min.js
src\main\java\com\amirhn\Pieces\Knight.java
src\main\java\com\amirhn\Pieces\Piece.java
src\main\java\com\amirhn\Pieces\Pawn.java
src\main\java\com\amirhn\Pieces\King.java
src\main\java\com\amirhn\Pieces\Bishop.java
src\main\java\com\amirhn\Players\Player.java
src\main\java\com\amirhn\Main.java
src\main\java\com\amirhn\Moves\Walk.java
src\main\java\com\amirhn\Moves\ShortCastling.java
src\main\java\com\amirhn\Moves\Promotion.java
src\main\java\com\amirhn\Moves\PawnPromotion.java
src\main\java\com\amirhn\Moves\MoveType.java
src\main\java\com\amirhn\Moves\Move.java
src\main\java\com\amirhn\Moves\LongCastling.java
src\main\java\com\amirhn\Pieces\Rook.java
src\main\java\com\amirhn\Moves\EnPassant.java
src\main\java\com\amirhn\Pieces\Queen.java
src\main\java\com\amirhn\Pieces\PieceType.java
src\main\java\com\amirhn\Moves\Castling.java
src\main\java\com\amirhn\Moves\Capture.java
src\main\java\com\amirhn\GUI\Constants.java
src\main\java\com\amirhn\GUI\ChessMenuController.java
src\main\java\com\amirhn\GUI\ChessMenuBar.java
src\main\java\com\amirhn\GUI\ChessFrame.java
src\main\java\com\amirhn\GUI\ChessController.java
src\main\java\com\amirhn\GUI\Listeners\LocationListener.java
src\main\java\com\amirhn\Game\Status.java
src\main\java\com\amirhn\Game\Scene.java
src\main\java\com\amirhn\Game\Location.java
src\main\java\com\amirhn\Game\Color.java
src\main\java\com\amirhn\GUI\Components\TablePanel.java
src\main\java\com\amirhn\Game\Chess.java
src\main\java\com\amirhn\GUI\Components\PiecePanel.java
src\main\java\com\amirhn\Game\Board.java
src\main\java\com\amirhn\GUI\Components\PieceImageIcon.java
src\main\java\com\amirhn\GUI\Components\LocationState.java
src\main\java\com\amirhn\GUI\Components\LocationPanel.java
src\main\java\com\amirhn\GUI\Components\BoardPanel.java
src\test\java\com\amirhn\Moves\CaptureTest.java
src\test\java\com\amirhn\Game\BoardTest.java
```

## Dependencies
No dependencies found.

## File Documentation
### script.js
- `loadScripts`: Function
- `createElem`: Function
- `makeComparable`: Function
- `toggleStyle`: Function
- `sortTable`: Function
- `toggleGlobal`: Function
- `show`: Function
- `updateTabs`: Function
- `switchTab`: Function
- `indexFilesLoaded`: Function
- `copySnippet`: Function
- `copyToClipboard`: Function
- `switchCopyLabel`: Function

### type-search-index.js
No functions documented.

### tag-search-index.js
No functions documented.

### search.js
- `checkUnnamed`: Function
- `escapeHtml`: Function
- `getHighlightedText`: Function
- `getURLPrefix`: Function
- `getURL`: Function
- `createMatcher`: Function
- `findMatch`: Function
- `isUpperCase`: Function
- `isLowerCase`: Function
- `rateNoise`: Function
- `doSearch`: Function
- `getPrefix`: Function
- `useQualifiedName`: Function
- `searchIndex`: Function
- `_scrollIntoView`: Function
- `collapse`: Function

### search-page.js
- `setSearchUrlTemplate`: Function
- `copyLink`: Function
- `renderResults`: Function
- `renderResult`: Function
- `selectTab`: Function
- `renderTable`: Function
- `renderItem`: Function
- `schedulePageSearch`: Function
- `doPageSearch`: Function
- `setSearchUrl`: Function

### package-search-index.js
No functions documented.

### module-search-index.js
No functions documented.

### member-search-index.js
No functions documented.

### jquery-ui.min.js
- `n`: Function
- `o`: Function
- `t`: Function
- `i`: Function
- `T`: Function
- `A`: Function
- `W`: Function

### jquery-3.6.1.min.js
- `b`: Function
- `w`: Function
- `p`: Function
- `se`: Function
- `ue`: Function
- `e`: Function
- `le`: Function
- `ce`: Function
- `fe`: Function
- `pe`: Function
- `de`: Function
- `he`: Function
- `ge`: Function
- `ye`: Function
- `ve`: Function
- `me`: Function
- `xe`: Function
- `be`: Function
- `we`: Function
- `Te`: Function
- `Ce`: Function
- `Ee`: Function
- `A`: Function
- `j`: Function
- `O`: Function
- `R`: Function
- `M`: Function
- `I`: Function
- `n`: Function
- `l`: Function
- `U`: Function
- `X`: Function
- `G`: Function
- `Z`: Function
- `se`: Function
- `le`: Function
- `ye`: Function
- `ve`: Function
- `xe`: Function
- `we`: Function
- `Te`: Function
- `Ce`: Function
- `Ee`: Function
- `Se`: Function
- `je`: Function
- `De`: Function
- `qe`: Function
- `Le`: Function
- `He`: Function
- `Oe`: Function
- `Be`: Function
- `_e`: Function
- `e`: Function
- `t`: Function
- `Ve`: Function
- `Je`: Function
- `Ke`: Function
- `Ze`: Function
- `et`: Function
- `st`: Function
- `ut`: Function
- `lt`: Function
- `ct`: Function
- `ft`: Function
- `yt`: Function
- `vt`: Function
- `mt`: Function
- `jt`: Function
- `Ft`: Function
- `l`: Function
- `Bt`: Function
- `l`: Function

### Knight.java
No functions documented.

### Piece.java
- `getLocation`: Function
- `setLocation`: Function
- `setLocationBack`: Function
- `removeLocation`: Function
- `hasMoved`: Function
- `equals`: Function
- `hashCode`: Function
- `toString`: Function
- `isAllowedToMove`: Function
- `canBeCapturedBy`: Function
- `getSymbol`: Function
- `copy`: Function

### Pawn.java
- `isBeforeLastRank`: Function

### King.java
- `canBeCapturedBy`: Function

### Bishop.java
No functions documented.

### Player.java
- `getColor`: Function
- `getKing`: Function
- `getKingSideRook`: Function
- `getQueenSideRook`: Function
- `isThreatening`: Function

### Main.java
No functions documented.

### Walk.java
- `applyOnBoard`: Function
- `undoOnBoard`: Function
- `isValidApplyOnBoard`: Function
- `getStartpointLocation`: Function
- `getEndpointLocation`: Function
- `toString`: Function

### ShortCastling.java
- `toString`: Function

### Promotion.java
- `applyOnBoard`: Function
- `undoOnBoard`: Function
- `isValidApplyOnBoard`: Function
- `getEndpointLocation`: Function
- `getStartpointLocation`: Function
- `toString`: Function

### PawnPromotion.java
- `isValidApplyOnBoard`: Function
- `isAllowed`: Function

### MoveType.java
No functions documented.

### Move.java
- `isAllowed`: Function
- `isValidApplyOnBoard`: Function

### LongCastling.java
- `toString`: Function

### Rook.java
No functions documented.

### EnPassant.java
- `applyOnBoard`: Function
- `undoOnBoard`: Function
- `isValidApplyOnBoard`: Function
- `isAllowed`: Function
- `toString`: Function
- `getEndpointLocation`: Function

### Queen.java
- `setLocation`: Function
- `setLocationBack`: Function
- `removeLocation`: Function

### PieceType.java
- `getSymbol`: Function

### Castling.java
- `isAllowed`: Function
- `applyOnBoard`: Function
- `undoOnBoard`: Function
- `isValidApplyOnBoard`: Function
- `getEndpointLocation`: Function
- `getStartpointLocation`: Function

### Capture.java
- `applyOnBoard`: Function
- `undoOnBoard`: Function
- `isValidApplyOnBoard`: Function
- `toString`: Function
- `getEndpointLocation`: Function
- `getStartpointLocation`: Function

### Constants.java
No functions documented.

### ChessMenuController.java
No functions documented.

### ChessMenuBar.java
- `actionPerformed`: Function

### ChessFrame.java
- `keyTyped`: Function

### ChessController.java
- `initialize`: Function
- `addPiece`: Function
- `applyRandomMove`: Function
- `makeMove`: Function
- `playMoveSound`: Function
- `applyMove`: Function
- `draw`: Function
- `locationSelected`: Function
- `locationGrabbed`: Function
- `locationDropped`: Function
- `isLocationDraggable`: Function
- `checkForFinish`: Function
- `newGame`: Function
- `loadFEN`: Function
- `undoMove`: Function

### LocationListener.java
No functions documented.

### Status.java
No functions documented.

### Scene.java
- `getBoard`: Function
- `getTurn`: Function
- `equals`: Function

### Location.java
- `byOffset`: Function
- `isLight`: Function
- `toString`: Function
- `equals`: Function
- `hashCode`: Function

### Color.java
- `opposite`: Function

### TablePanel.java
- `getLocationPanel`: Function
- `getLocationPanel`: Function
- `resetLocationStates`: Function
- `pointOf`: Function
- `locationOf`: Function

### Chess.java
- `setupFEN`: Function
- `setPiece`: Function
- `getBoard`: Function
- `getTurnPlayer`: Function
- `getOpponentPlayer`: Function
- `getPlayer`: Function
- `getRandomMove`: Function
- `isAllowed`: Function
- `applyLegalMove`: Function
- `applyMove`: Function
- `isInCheck`: Function
- `isCheckmate`: Function
- `isStalemate`: Function
- `isThreefoldRepetition`: Function
- `is50MoveRule`: Function
- `isDraw`: Function
- `getStatus`: Function
- `undoMove`: Function
- `moveFromString`: Function
- `toString`: Function

### PiecePanel.java
No functions documented.

### Board.java
- `setupFEN`: Function
- `isValidLocation`: Function
- `isOccupied`: Function
- `getPiece`: Function
- `setPiece`: Function
- `removePiece`: Function
- `isValidPiece`: Function
- `toString`: Function
- `copy`: Function
- `equals`: Function

### PieceImageIcon.java
No functions documented.

### LocationState.java
No functions documented.

### LocationPanel.java
- `setState`: Function

### BoardPanel.java
- `setLocationListener`: Function
- `addPiecePanel`: Function
- `removePiecePanels`: Function
- `resetLocationStates`: Function
- `setLocationState`: Function
- `mouseDragged`: Function
- `mouseMoved`: Function
- `mouseClicked`: Function
- `mousePressed`: Function
- `mouseReleased`: Function
- `mouseEntered`: Function
- `mouseExited`: Function

### CaptureTest.java
No functions documented.

### BoardTest.java
No functions documented.



## Libraries and Frameworks
TBD: Add information about libraries and frameworks used in the project.

## Installation Instructions
TBD: Include steps to install and set up the project locally.

## Usage Guide
TBD: Provide instructions on how to use the software.

## API Documentation
TBD: Detail API endpoints, request/response formats.

## Contributing Guidelines
TBD: Provide guidelines for developers who wish to contribute.

## Testing
TBD: Information on how to run tests and the tools used.

## License
TBD: Specify the project's license.

## Acknowledgments
TBD: Credit contributors and acknowledge any resources or inspiration.
