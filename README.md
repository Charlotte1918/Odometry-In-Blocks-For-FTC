# Odometry-In-Blocks-For-FTC

## Welcome / Bienvenue !

This is an example of an autonomous program using odometry in blocks for an FTC robot. I will also explain to you how to set it up.

The programmer (Me) and coaches of teams 18013, Cuivre et Or, and 28444, Or et Cuivre, are the ones who built it. 

.

Ceci est un exemple d'un programme autonome en blocks utilisant de l'odométrie pour un robot FTC. Je vais aussi vous expliquer comment le mettre en place.

La programmeuse (Moi) et les coachs des équipes 18013, Cuivre et Or, et 28444, Or et Cuivre, sont ceux qui l'ont construit.

## Notice / Attention

We used two goBILDA 4-Bar Odometry Pods and the Pinpoint V2 Odometry Computer with this program and didn't tried with other systems of odometry.
As such, the explainations below will be for these.

.

Nous avons utiliser deux 4-Bar Odometry Pods de goBILDA et le Pinpoint V2 Odometry Computer avec ce programme et n'avons essayé avec d'autres systèmes d'odometrie.

## Set up / Mise en place

### Blocks

You will need to have the blocks for odometry, else the program will be full of warnings and not working. You can go to the Blocks Guide from goBILDA for this part : 

.

Vous allez avoir besoin des blocks pour l'odométrie, sinon le programme va être plein d'erreurs et ne fonctionnera pas. Vous pouvez aller au guide de Blocks de goBILDA pour cette partie :

.

https://www.gobilda.com/content/user_manuals/3110-0002-0001%20Blocks%20Guide%20App%20Version%2010-1.pdf?srsltid=AfmBOoqKPiLcW0eiKlhGgq3n4wxlAwLzpu5UYEXKoOoTlBJTkuJ3Kwgq

### Getting it on your robot / Le mettre sur votre robot

To get the program onto your robot, you shall :

1. Download the program (https://github.com/Charlotte1918/Odometry-In-Blocks-For-FTC/blob/main/Example%20Auto-Odo%20with%20Explanations%20in%20English.blk)
2. Connect to the robot wifi
3. Go to the OpModes
4. Upload the program

.

Pour avoir le programme sur le robot, vous allez devoir :

1. Télécharger le programme (https://github.com/Charlotte1918/Odometry-In-Blocks-For-FTC/blob/main/Exemple%20Auto-Odo%20avec%20Explications%20en%20Français.blk)
2. Connecter sur le wifi du robot
3. Aller à l'onglet OpModes
4. Upload le programmme

### Offsets

For the program to work, you must get precise offsets. To do so, I encourage following the Odometry Computer User Guide :

https://www.gobilda.com/content/user_manuals/3110-0002-0001%20User%20Guide.pdf?srsltid=AfmBOoolCZSwyMuHyi-De29eOTaPhWy-GbPwBJoOZ0nVouGU2PVgIKZN

Be careful. X is Drive, Y is Strafe, unlike a cartesian plane. 

To test it, get the Telemetry odometrie program or the sample code SensorGoBilda (You will need to add it Telemetry for this one) and enter your offsets in the setOffsets block in configurePinpoint. Save and start the program on the robot, then turn it on itself for 90° (by hand). 

Check your telemetry and if your X **and** Y is about or below 1 or 2 (it depens on how precise you want it to be), you're good to go. If not, your offsets are probably a little off.

.

Pour que le programme fonctionne, vous allez avoir besoin d'offsets précis. Pour les trouver, je recommande suivre le Odometry Computer User Guide :

https://www.gobilda.com/content/user_manuals/3110-0002-0001%20User%20Guide.pdf?srsltid=AfmBOoolCZSwyMuHyi-De29eOTaPhWy-GbPwBJoOZ0nVouGU2PVgIKZN

Faites attention. X est Drive, Y est Strafe, contrairement à un plan cartésien.

Pour le tester, utilisez Telemetry odometrie ou le sample code SensorGoBilda (Vous allez devoir ajouter de la télémétrie pour celui là) et entrer vos offsets dans le block set Offsets dans configurePinpoint. Sauvegardez et partez le programme, puis tourner le robot sur lui-même à 90° (à la main).

Checkez la télémétrie et si X **et** Y est environ ou en dessous de 1 ou 2 (Dépendamment de à quel point vous voulez que ce soit précis), vous êtes prêt à partir. Sinon, vos offsets sont probablement un peu décalés.

## Using The Program / Utiliser le programme

At this point, the only thing you left to do is opening it and transforming it to your liking.

The INIT and configurePinpoint probably are the first things you will want to change to adapt to your robot

I highly suggest you read the program thoroughly to understand how it works. Comments are there to help you. 

.

À ce stade, la seule chose restante à faire est de l'ouvrir et de le modifier à votre convenance.

L'INIT et configurePinpoint sont probablement les premières choses que vous aller vouloir modifier pour adapter votre robot.

Je suggeste fortement que vous lisez le programme entièrement pour comprendre comment il fonctionne. Des commentaires sont là pour vous aider.

## Need to contact me ? / Besoin de me contacter ?

If you have any question, comment, correction or something else that you want to share to me, write to charlottedube28@gmail.com.

.

Si vous avez une question, un commentaire, une correction, ou autre que vous voudriez me partager, écrivez moi à charlottedube28@gmail.com

## Credits / Crédits

This program has been made with the sample code SensorGoBildaPinpoint, time, patience and a few brains.

.

Le programme a été fait avec le sample code SensorGoBildaPinpoint, du temps, de la patience et quelques cerveaux.
