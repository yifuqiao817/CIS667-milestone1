# CIS667-milestone1
CIS667 course project milestone1 - Yifu Qiao (yqiao08)

To start the game, just run yqiao08_Milestone1.py. 
At the beginning, it will ask you to choose the game size. 
If you type in "1" (without space), it will start a normal game with 8x8 chessboard. 
If you type in "2", it will start a mini game with 4x4 chessboard and only pieces of Kings, Queens and Rooks. 

After the game starts, for every player's turn, you will be provided 3 options for different operations: 
If you type in "1" (without space), you will be able to move one of your piece. 
  You will be asked to type in the piece you want to move and the expected destination of the move. 
  
  Piece format: 
    'WR1' is short for Rook piece one in the White pieces. 
    'BQ' is short for the Queen piece in the Black pieces. 
    (type without any space)
    Example for all the black pieces: 
      King: BK
      Queen: BQ
      Pawn: BP1, BP2, BP3, BP4, BP5, BP6, BP7, BP8
      Rook: BR1, BR2
      Bishop: BB1, BB2
      Knight: BN1, BN2
    For white pieces, only need to change the first 'B' into 'W'. 
   
   Destination format: 
    The rows of the chessboard are labeled by numbers, starting from 1. 
    The columns of the chessboard are labeled by letters, starting from A. 
    The correct format is like 'A3', 'E5'. 
    
If you type in "2", you will be asked to type in two pieces that you want to swap. 
If you type in "3", it will quit the game. 

Every time you enter the wrong format or invalid operation, it will bring you back to operation selection for this turn. 

The game lasts for at most 50 turns, if no one wins in 50 turns, the outcome will be a draw. 
