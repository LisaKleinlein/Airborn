# Airborn

Buttons in the Game:
Left Thumbstick: Left and right is movement to the left or right
                 Up and Down is the movement forward or backward
Right Thumbstick: Left and right moves the camera, max rotation is 45° to each side
                  Up and Down is zoom in and zoom out

Keyboard and Mouse movement is also possible. A,W,S,D is for the movement and Mouse movement to left or right is camera rotation. Mouse Wheel is the camera zoom

_________________________________________________________________________________________________________________________________________________________________

Variables to play with in Development (can change with the development):

In the BP_ThirdPersonCharacter: zoomMultiplier: changes the speed in which the player can zoom in or out
                                MovementSpeed: changes the speed of the movement of the player
                                
In the Windtunnel Blueprint: RangeX, RangeY and RangeZ: changes the dimensions of the Windtunnel 
                             DistanceBetweenForceLines: The Blueprint works with raytracing and this variable determines how close the traces are and how many of them                                                           are there. A low number results in more traces and more computing power.
                             MaxForce: The strength of the "wind" that blows the player into the air.
