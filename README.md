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
