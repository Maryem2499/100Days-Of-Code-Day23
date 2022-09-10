#  The Turtle Crossing Capstone Project :
## Step 1 : check out how the game play works 
1- A turtle moves forwards when you press the "Up" key. It can only move forwards not back, left or right.
2- Cars are randomly generated along the Y-axis and will move from the right edge of the screen to the left edge.
3- When the turtle hits the top edge of the screen, it moves back to the original position and the player levels up. On the next level, it's game over and everything stops.
## Step 2 : Break down the problem 
1- Create a turtle player that starts at the bottom of the screen and listen for the "Up" keypress to move the turtle north(Step 3).
2- Create cars that are 20px hight by 40px width that are randomly generated and move to the left edge of the screen (step 4).
3- Detect when the turtle player collides with a  car and stop the game if this happens (step 5).
4- Detect when the turtle player  has reached the top edge of the screen.(FINISH_LINE_Y) when this happens, return to the starting position and increase the speed of the cars.(MOVE_INCREMENT) (ste p 6).
5- Create a scoreboard that keeps track of width level the user is on . Every time the turtle player does successful crossing, the level should increase. When the turtle hit a car "Game Over" (step 7).
## Step 3: Create the player behaviour 
1ére etape : consiste à deplacer la tortue en appuiyant sur une touche ==> la tortue ne peut aller que vers l'avant, jusqu'a ce qu'elle atteinte l'autre coté de l'écran.
2éme étape :  ammener cette tortue à se déplacer vers le haut, chaque fois que nou appuiyons sur la touche "Up".
## Step 4 :  Create the CarBehaviour 
Créer et déplacer les voiturs.  Qu'ils doivent déplacer de droite à gauche  et générer de maniére aléatoire, ils vont etre de 20px par 40px.
## Step 5 : Detect whenn the turtle collides with a car 
Lorsque la tortue frappe une voiture, nous pouvons arreter le jeu et empecher d'autres voitures de circuler.
## Step 6 : Detect whennhe player has reached to other side
Nous allons trouver comment nous pouvons détecter quand la tortue atteint l'autre coté de l'écran pour qu'une fois que notre tortue aura réussi sa traversée, nous pouvons alors rammener la tortue à sa position de départ et accélérer tous les voitures.
## Step 7 : Add the scoreboard and Game Over sequence 
C'est l'étape finale qui consiste à créer un tableau d'affichage permettant de savoir à quel niveau se trouve la tortue, et aussi lorsq'elle frappe l'un des voitures le mot "Game Over" sera affiché au centre de l'écran.
