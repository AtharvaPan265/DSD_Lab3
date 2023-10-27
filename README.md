# DSD_Lab3
## Game
### Sword Logic
The Sword_FSM.bdf shows the is a finite state machine with 2 states for the Sword Logic
### Game Logic
The ROOM_FSM.bdf shows the is a finite state machine with 7 states for the Room Logic
### Top File
The Lab3.bdf is the Top File bringing together the two FSMs as black boxes in a top/header file
## Output
wihtin the SimWinLoss.png we can see the outcomes of the game
- The first reset starts the game
  - Here we see an example of winning
- The second reset resets after the win and allows for a re-run
  - Here we see an example of Losing
- The third reset clears everything and goes back to state0
