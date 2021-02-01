# HoloFluidBall
This is a take on something akin to a ferrofluid running on the Hololens 2. So far, the nodules can be extended with the hands and are rendered in a similar fashion to metaballs. To spawn the actual interactive ball, look at your palm to activate the menu and click the "Spawn Ball" button. You can also use this button to move the ball around.

The scene itself is simple to put all focus on the ball.

![HoloFluidBall](https://github.com/JIoffe/HoloFluidBall/blob/main/Screenshots/screen1.png?raw=true)

## Environment

 - Unreal Engine 4.26
 - Visual Studio 2019

## Notes
 - Tracks the index, thumb and pinky of each hand
 - Uses ray marching with a sphere for the main blob and rounded cones for the nodules

## References

 [Inigo Quilez 3D SDF (https://iquilezles.org/www/articles/distfunctions/distfunctions.htm)](https://iquilezles.org/www/articles/distfunctions/distfunctions.htm)
An extremely good resource and much of this code is based on here.