# Hand Sign game
#### This is an image processing project for our third year at Computer department in Faculty of Engineering Cairo University.
## In this game:
* The player must make special hand signs quickly.<br>
* The game will use the webcam to read the user’s movements.<br>
* The screen will be split into NBlock*NBlock areas.<br>
* The player will be given a chain of hand signs to make as well as where to place their hand (in only one area of the screen).<br>
* The player should do the earliest sign of the chain, any sign except the earliest will not count.<br>
* The Player's score will be stored. Every correct hand sign adds points and the sign will disappear.<br>
* There are no Time Limit or End of the chain, the speed of signs (the chain) will increase by increasing of the player's points.<br>
* The Game will end if the player missed MaxMiss signs.<br>
* The final score for any game =int(round(((points*NBlock/Miss)power(2-steptime))*100)), player can choose NBlock and MaxMiss.<br>
