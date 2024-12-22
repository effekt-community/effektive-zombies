# Simple Zombie Top-Down Survival

A Top-Down Game with a GUI, where the player is in the center of the map (= window)
and zombies (or some other enemy idk yet) spawn at the edges, trying to attack the player.
The player has a gun, with which he can aim and shoot at the zombies, ensuring his survival.

## Must-have

- Main Menu with Play and Quit Button
- Player can move around the map
- Player can shoot by aiming with his mouse and pressing left-klick
- More Enemies spawn over time/different waves of enemies
- Score/Wave Count

## Can-have

- Different types of enemies: Faster/more Health/Boss with special attack (slamming on the ground
in a line or smth like that)
- Shop in which the player can upgrade his gun or buy one time usables like shields/grenades etc.
- Skin selection in main menu? xD
- Health Kit spawns

## Will-not-have

- AI that will play the game as the player optimally

## Effects and handlers

- getTime(): Int to get the delta time for the physics in the game loop
- render(GameObjects): Unit to render onto the window 

## FFI and libraries

Node GUI and js event listeners for user input, and some way to get current time? I don't really need anything else, Physics etc. can be done in Effekt.
