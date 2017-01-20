# CrashyPlane
Game like Flappy Bird. Pass through rocks to survive and score.

The Game has been build with help of tutorial and assets. There were some bugs in the tutorial which have been corrected and the game has been working fine.
If you have played Flappy Bird the procedure is same. Else the game play is:

****** Tap and avoid collision. ******

1. Tutorial is from: https://www.hackingwithswift.com/read/36/0/introduction
2. Assests are from: https://kenney.itch.io/kenney-donation

Note: 
From the tutorial I have observed that there is certain increase in score points when the player hits the scorebar. This was happening due to multiple contact point and thus the function was called multiple time. That has been solved by using (rectangleof: size) instead of (playerTexture.size()).
