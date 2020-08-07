## puzzle
A simple HTML5 puzzle

### Instructions
* Download the puzzle.html page to your desktop and open it in your browser with JavaScript enabled.
* Use the mouse to drag a puzzle piece to new location; the piece that was at the new location swaps with the first piece.
* When all of the pieces are arranged correctly, a congratulation message appears at the bottom.

### Modifications
* The number of puzzle pieces can be changed by changing the PUZZLE_DIFFICULTY constant in puzzle.html. PUZZLE_DIFFICULTY is the number of pieces on a side.
* The completion message can be changed by changing the COMPLETION_MESSAGE array in puzzle.html. The array can have from one to three phrases corresponding to the lines of the completion message.
* The puzzle image can be changed by changing the IMAGE constant in puzzle.html. Replace the base64 code by the code for another image.

### Converting an image file to base64
* Linux: $ cat StandardModel.jpg | base64 -w 0
* There are free pages online to convert files to base64
