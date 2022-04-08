# SUDOKU SOLVER



#RULE OF SUDOKO

    Rule 1 - Each row must contain the numbers from 1 to 9, without repetitions
    
    Rule 2 - Each column must contain the numbers from 1 to 9, without repetitions
    
    Rule 3 - The digits can only occur once per block (nonet)
    
   
#Key concept 
       
    Backtracking algorithm to solve a sudoku in cpp.
#Input
      We have taken two array board,board2  of 9x9
      
   #1  board
   
   
        int board[9][9] = {
                                {5,3,0,0,7,0,0,0,0},
                                {6,0,0,1,9,5,0,0,0},
                                {0,9,8,0,0,0,0,6,0},
                                {8,0,0,0,6,0,0,0,3},
                                {4,0,0,8,0,3,0,0,1},
                                {7,0,0,0,2,0,0,0,6},
                                {0,6,0,0,0,0,2,8,0},
                                {0,0,0,4,1,9,0,0,5},
                                {0,0,0,0,8,0,0,7,9}
                             };
                             
  #2  board2     
      
                                 int board2[9][9] = {
                                {8,0,0,0,0,0,0,0,0},
                                {0,0,3,6,0,0,0,0,0},
                                {0,7,0,0,9,0,2,0,0},
                                {0,5,0,0,0,7,0,0,0},
                                {0,0,0,0,4,5,7,0,0},
                                {0,0,0,1,0,0,0,3,0},
                                {0,0,1,0,0,0,0,6,8},
                                {0,0,8,5,0,0,0,1,0},
                                {0,9,0,0,0,0,4,0,0}
                              };
  
                               
