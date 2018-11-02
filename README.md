# impossible-tic-tac-toe

#How it works:
  1. The middle box is marked as X to make this game impossible
  2. When the player places a mark, the AI checks if there are any rows without player's mark, **AND** includes AI's mark, this provides the AI the fastest step to winning
  3. The AI checks whether or not it is winning, if so, AI will place a mark to win the game
  4. If the AI is not winning, and the player is winning, the AI will place a mark to prevent the player from winning
  5. A code will check for the winner every time after player places a mark. Either win, loss or tie, the game will end and neither of them can place a mark
  6. A message will pop up indicating win, loss or tie.

*Please note that the X is placed before the game starts due to the complexity of the game. There are more than 50 ways of winning the game, and each method has its unique solution. Therefore machine learning is needed. Hard coded solutions would cause lag spikes.*
