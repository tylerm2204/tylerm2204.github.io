---
layout: post
title: "My Game - Final Submission"
date: 2019-03-08
---
https://www.wescheme.org/view?publicId=zqqqm5XXCB
Game Title: 
Kirby’s Adventure
Describe your game, characters and setting: 
The player is a Peter Griffin version of kirby. The setting is on a minecraft field. The purpose of the game is to get as many maxim tomatoes(Target) as you can while also dodging Marx(Danger). 
Choose one of either the onscreen?, update-player, distance, or collide? functions. Copy and paste the entire function including contract, purpose statement, examples and definition. 
0. ; onscreen? : Number -> Boolean
1. ; Determines if the coordinate is on the screen

2. ;; EXAMPLEs:
3. (EXAMPLE (onscreen? 500) true)
4. (EXAMPLE (onscreen? -200) false)

5. (define (onscreen? x)
6. (and(> x -40)(< x 680)))
Describe every line in the pasted code above.
Line 0 is the contract. It explains that Onscreen?(the function) puts in a number and gets a boolean. It is a comment so it doesn’t affect the game. Line 1 is what the function actually does. In this case, it determines if the coordinates of the target or danger is off screen. Line 2 is the examples. These examples are what checks if the code is written correctly and sees if it works. Line 3 is the first example. It says if the target or danger is at the coordinate 500, then it means it is onscreen, making the function true. Line 4 is the second example. It says if the target or danger is at the coordinate -200, then it is not onscreen, making the function false. Line 5 and 6 is the actual code to make onscreen work in the game. It defines the function onscreen? On the x coordinate plane. If the target or danger is between the x coordinates of -40 and 680, then it is onscreen.
Describe the role of the function in the video game program.
The role of this function is important to the video game because it makes the danger and target respawn on their side of the screen, making the game continue on like it is supposed to. If it wasn’t in my code, it would be a mess of a game because the sprites would continue on into the side.
