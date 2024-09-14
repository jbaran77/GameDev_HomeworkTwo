John Baran
CSC 3150 Game Development Homework 2
Answers to questions 3 and 5

## Question 3
The use of Time.deltaTime in Forza ensures that some user experiences are even accross machines. For things like car speed and movement, or camera tracking, Time.deltaTIme allows the object to move consistently regardless of the machinen frame rate. If it were not used, some of the movement in the game could feel jittery or jumpy instead of smooth. Even though the machines with higher frame rates will provide a better experience, machines with low frame rates will still provide consistent and reliable gameplay.

## Question 5

**Mesh Renderer**: used to render 3D objects in game in 2D representation. Uses geometric attributes of the object or environment to do so. <br>
**Box Collider**: defines box shaped collision area around object. Used to simulate physical interactions between components. Similar to a 'hitbox' in a shooting game. <br>
**Input.GetAxis Method**: used to detect input from joysticks, controllers, or even just the keyboard. Allows user to interact with an object to move it within the game. <br>
**Rigid Body**: enables object to act under Unity's physics engine. The object is able to respond to collision, gravity, and other outside forces. <br>
