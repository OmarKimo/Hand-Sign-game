# Hand Sign game
## In this game:
* The player must make special hand signs quickly at specific blocks of the screen.<br>
* The game will use the webcam to read the user’s movements.<br>
* The screen will be split into **NBlock** * **NBlock** areas. (The user selects **NBlock** before the beginning of the game)<br>
* The player will be given a chain of hand signs to make as well as where to place their hand (in only one area of the screen).<br>
* The player should do the earliest sign of the chain, any sign except the earliest one will not be counted.<br>
* The Player's score will be stored. Every correct hand sign adds points and the sign will disappear.<br>
* There are no Time Limit or End of the chain, the speed of signs (the chain) will increase by increasing of the player's points.<br>
* The Game will end if the player missed **MaxMiss** signs. (The user selects **MaxMiss** before the beginning of the game)<br>
* The final score for any game = ceil( (points * **NBlock**/**MaxMiss**)<sup>(2 - steptime)</sup> * 100 ).<br>
