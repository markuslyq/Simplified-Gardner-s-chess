# Simplified Gardner's chess
The function `studentAgent()` takes in a parameter gameboard that is a dictionary of positions
(Key) to the tuple of piece type and its colour (Value). It represents the current pieces left on
the board. Example gameboard:

`{(′a′, 0) : (′Queen′,′White′), (′d′, 10) : (′Knight′,′ Black′), (′g′, 25) : (′Rook′,′White′)}`
  
When the `studentAgent()` function is executed, the program should return a valid move in the
following format:

`(pos1, pos2)`

The values pos1 and pos2 represent a grid index tuple, **(x, y)**, where x is the column index (i.e., a
string), and y is the row index (i.e., an integer), such that **(x, y)** corresponds to a specific grid cell
on the board that we wish to reference. The move returned from the program signifies a move of a specific
piece from **pos1** to **pos2**.

An example of the function output is shown below:  
  
`print(studentAgent(gameboard))`

Sample output (representing moving a White Queen at a0 to b1):
`((′a′, 0), (′b′, 1))`
