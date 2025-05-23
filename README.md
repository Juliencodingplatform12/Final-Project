# Final-Project
# Final Project: Rabbit and Fox Chasing Game
I worked on planning with my dad a bit he majored in comp science all the work is mine he just helped me a bit with planning and taught me a few new things for coding so I could really end my final project on a strong note.
## Description  
A simple predator-prey game where the player can control the person and has to run away from the other players

## Things I am modeling  
- A `Rabbit` class that represents the player-controlled rabbit.
- A `Fox` class representing autonomous chasing enemies that seek the rabbit.
- A `Zone` class representing hiding spots where the rabbit can be safe temporarily.

## Other variables and data structures  
- An array of `Fox` objects to represent multiple enemies.
- A single `Rabbit` object for the player to move around and play as.
- An array of `Zone` objects which are the green zones the hiding spots
- Variables to track game state like score and time

## Setup plan  
- Create the canvas.
- Start the `Rabbit` player in the middle.
- Create a lot of enemies in diffrent postions chasing the rabbit
- Create hiding zones at random locations

## Flow of `draw()`  
- Draw hiding zones.
- Update and draw the rabbit.
- Update and draw all foxes.
- check the contact between the foxes and rabbit
- Update game so that when you die it says game over and you have to press a key to start again
- Display score on the screen somewhere 


### Rabbit  
- Properties: position, velocity, speed, radius  
- Actions: being able to move using arrow keys
### Fox  
- Properties: position, velocity, maxSpeed, radius  
- Actions: seek the rabbit if visible if so chase after it

### Zone  
- Properties: position, radius  
- Actions: draw, make sure the rabit is inside and there are boundaries. 
