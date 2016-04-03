# ReversiAlpha
A school-project.  Implements Reversi with some abstract methods and such.  Really overkill.  

Code is copyrighted © 2016 by Miles B Huff and Preston Sheppard per LGPL3.0 (The Lesser GNU Public License version 3.0).  

Other materials are copyrighted © 2016 by Miles B Huff and Preston Sheppard per CC-BY-SA 4.0 Int'l (Creative Commons Attribution-ShareAlike version 4.0 International)

# Usage
<code>$ java Reversi <i>$1</i> <i>$2</i></code>
<!--
<code>$ java Reversi [Human|RandomComputerPlayer|IntelligentComputerPlayer] [Human|RandomComputerPlayer|IntelligentComputerPlayer]</code>
  -->

As seen above, you must pass 2 arguments to the program.  The 1st argument determines the behaviour of the Dark player (represented by an 'X' on the game-board), and the 2nd determines the behaviour of the Light player (represented by an 'O' on the game-board).  Dark always goes first.  These arguments must be any of the following (and no, we didn't get to name them ourselves):  
* <code>Human</code>:  This player is a human player.  
* <code>RandomComputerPlayer</code>:  This player is a CPU-player, and is to move randomly.  
* <code>IntelligentComputerPlayer</code>:  This player is a CPU-player, and is to move pseudo-intelligently.  

Lastly, this programme requires a terminal emulator to properly enjoy, as it is lacking any sort of a proper GUI.  This is because we are amateurs.  

# Instructions
This link is only useful for us coders:  
https://gist.github.com/mepcotterell/3564a8eaa32f49e3d460
