## Lab: Numpy Arrays

### Feature Tasks and Requirements
* Your job is to render out chess boards with red and blue queens on them.

* We’re keeping it really basic here so the only pieces are queens and each queen is represented by a blue or red square.

* Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

* Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

### Implementation Notes
* Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)
* should have add_red method that accepts a row and column as input which colors corresponding cell.
* should have add_blue method that accepts a row and column as input which colors corresponding cell.
* should have render method that displays the chess board on screen with red and blue shown in correct locations
* should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally
### User Acceptance Tests
* queens on same row should be “under attack”
* queens on same column should be “under attack”
* queens on same diagonal should be “under attack”
* queens with any other coordinates should NOT be “under attack”


## Table Of Content

| PR | Links                                                     |
| -------- | --------------------------------------------------------- |
| Lab: 11 - Numpy  | [PR (1)](https://github.com/YazanAhmad18/chess-board/pull/1) |