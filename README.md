# Rock Paper Scissors
 
You against a friend. You move first, then your friend's turn
 
## How to play
 
1. Click roll and you can keep clicking it until you either roll a '1' or you press hold which saves the score
2. Alternate turns with your friend and try to win
3. Someone wins when they score up to the target number
 
## What I added
 
- Win condition for either player (Used variables instead of using two if-statements so it is one if-statement that can be interchanged for either player)
- Adjustable target score that locks when starting game using textfield (It is a topic that we haven't learnt yet, but I can explain how it works and what it does)
- Reset button after a win & disabled other buttons once game is over (Used !gameIsOver{} to disable buttons once game is actually over)
- Win credits (e.g "PLAYER ONE WINS") (Used V-Stacks & H-Stacks to create text right where I want it on the screen)
 
## Credits
 
- The starting game was written by Mr. Gordon.
- Used Gemini to fix broken code/ errors

##Testing updates

1. 

Test: Image location

Chosen input: Used a HStack to make the "party poppers" image where I want it.

Should happen: Puts the images on both sides of the "PLAYER 1 WINS/PLAYER 2 WINS" text

Did happen: Puts the images on both sides of the "PLAYER 1 WINS"/"PLAYER 2 WINS" text

STATUS: SUCCESS

2. 

Test: Textfield 

Chosen input: Any number 

Should happen: It should change the winning score to be whatever number is in the textfield box

Did happen: Changed the winning score to be whatever number is in the textfield box

Status: SUCCESS

3.

Test: Total player wins text and variable under player scores

Chosen input: Won for player 1 multiple times

Should happen: It should change the P1 total wins up by 1 every time that player wins

Did happen: Changed the P1 total wins up by 1 every time that player wins

STATUS: SUCCESS
