# Odometry-In-Blocks-For-FTC

## Welcome !

This is an example of an autonomous program using odometry in blocks for an FTC robot. I will also explain to you how to set it up.

The programmer (Me) and coaches of teams 18013, Cuivre et Or, and 28444, Or et Cuivre, are the ones who built it. 

## Notice

We used two goBILDA 4-Bar Odometry Pods and the Pinpoint V2 Odometry Computer with this program and didn't tried with other systems of odometry.
As such, the explainations below will be for these.

## Set up 

### Blocks

You will need to have the blocks for odometry, else the program will be full of warnings and not working. You can go to the Blocks Guide from goBILDA for this part : 

https://www.gobilda.com/content/user_manuals/3110-0002-0001%20Blocks%20Guide%20App%20Version%2010-1.pdf?srsltid=AfmBOoqKPiLcW0eiKlhGgq3n4wxlAwLzpu5UYEXKoOoTlBJTkuJ3Kwgq

### Getting it on your robot

To get the program onto your robot, you shall :

1. Download the program (https://github.com/Charlotte1918/Odometry-In-Blocks-For-FTC/blob/main/Exemple%20Auto-Odo%20avec%20Explications.blk)
2. Connect to the robot wifi
3. Go to the OpModes
4. Upload the program

### Offsets

For the program to work, you must get precise offsets. To do so, I encourage following the Odometry Computer User Guide :

https://www.gobilda.com/content/user_manuals/3110-0002-0001%20User%20Guide.pdf?srsltid=AfmBOoolCZSwyMuHyi-De29eOTaPhWy-GbPwBJoOZ0nVouGU2PVgIKZN

Be careful. X is Drive, Y is Strafe, unlike a cartesian plane. 

To test it, get the Telemetry program or the sample code SensorGoBilda and enter your offsets in the setOffsets block in configurePinpoint. Save and start the program on the robot, then turn it on itself for 90° (by hand). 

Check your telemetry and if your X **and** Y is about or below 1 or 2 (it depens on how precise you want it to be), you're good to go. If not, your offsets are probably a little off.

## Using The Program

At this point, the only thing you left to do is opening it and transforming it to your liking.

The INIT and configurePinpoint probably are the first thing you will want to change to adapt to your robot

I highly suggest you read it to understand how it works and the comments are there for that. 


## Needing Help ?

If you have any question, comment or correction, write to charlottedube28@gmail.com.

## Credits

This structure of program has been made with the sample code SensorGoBildaPinpoint and a few brains.
