# groupproject-team-1-spacey
Comp 55 final group project, tank game.
Part 1:
This screen will be showing statistics of the level/levels, like how many times did the player shoot projectiles, how many of them did the player hit, how many times did enemies shoot and how many did they hit.


Part 2:

Make two variables for number of shots fired by player and number of shots hit by player
If player shoots
	Increment number of shots fired by player variable
		If bullets hit enemy
			Increment number of shots hit by player
			
		endif
endif

Make two variables for number of shots fired by enemy and number of shots hit by enemy
If enemy shoots
	Increment number of shots fired by enemy variable
		If bullets hit player
			Increment number of shots hit by enemy
			
		endif
endif

Add section for showing bullets fired by player and number of shots hit by player in score screen
Add section for showing bullets fired by enemy and number of shots hit by enemy in score screen
Get number of shots fired by player and number of shots hit player variables and output them on the allocated screen space in score screen
Get number of shots fired by enemy and number of shots hit enemy variables and output them on the allocated screen space in score screen


Part 3:

I made a couple of variables (enemyHitNum,playerHitNum,enemyShotNum,playerShotNum) that would count total number of bullets that was fired and number of bullets that hit the enemy/player. I added these variables for both player and enemies. I modified some of the functions that were responisble for generating a bullet each time the player/enemy shoots and the functions that were responsible for detecting bullets hitting the enemy/player. Each time the shots were fired the values of enemyShotNum/playerShotNum would increase, and each time the bullets hit the enemy/player the values of enemyHitNum/playerHitNum would increase. I also modified some functions that were resposible for generating the scoreboard and I used GLabel to add the information about total number of shots, number of hits and number of misses. And I also added these informations to lose/win screens.

At first, there were no variable for total number of shots, instead I just made a variable that would count the number of times the player/enemy misses but there were some issues with it, like the correct information not being shown, specifically total number of shots and number of misses. Then I just removed the problematic variable and made the playerShotNum and enemyShotNum variables. When displaying info about the missed shots, I just calculate it like misses=total-hit. Also, at first I wanted to make a new screen that would show these informations about hits/misses but I changed my mind about it because there were already a scoreboard present and it made more sense to me to put these info in there somewhere rather than having an additonal screen. Another thing, the professor suggested for me to add a button that would give players option to clear these stats, but the game only stores the information for that game session and it gets resseted when closing the game so i thought it would not be so useful to the player and i chose to not add it.

Also, the variable names stand for:
enemyHitNum- number of times player hit the enemies
enemyShotNum- number of times player tried to shoot the enemies
playerHitNum- the number of times enemies hit the player
playerShotNum- the number of times enemies tried to shoot the player




