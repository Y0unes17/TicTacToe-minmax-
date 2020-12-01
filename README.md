<h1>Tic-Tac-Toe-minimax</h1>
<p>
To solve games using AI, we will introduce the concept of a game tree followed by minimax algorithm. The different states of the game are represented by nodes in the game tree, very similar to the above planning problems. The idea is just slightly different. In the game tree, the nodes are arranged in levels that correspond to each player's turns in the game so that the “root” node of the tree (usually depicted at the top of the diagram) is the beginning position in the game. In tic-tac-toe, this would be the empty grid with no Xs or Os played yet. Under root, on the second level, there are the possible states that can result from the first player’s moves, be it X or O. We call these nodes the “children” of the root node.

Each node on the second level, would further have as its children nodes the states that can be reached from it by the opposing player's moves. This is continued, level by level, until reaching states where the game is over. In tic-tac-toe, this means that either one of the players gets a line of three and wins, or the board is full and the game ends in a tie.
</p>

<p align="center">
  <img src="https://github.com/Y0unes17/TicTacToe-minmax-/blob/master/image/1.png?raw=true" width="400" />
  <img src="https://github.com/Y0unes17/TicTacToe-minmax-/blob/master/image/3.png?raw=true" width="400"/>
</p>
<p align="center" >
  <img src="https://github.com/Y0unes17/TicTacToe-minmax-/blob/master/image/4.png?raw=true" />
  </p>
