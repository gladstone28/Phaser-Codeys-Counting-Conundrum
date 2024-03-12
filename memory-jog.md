At this point completed step 17 of 22 and to go onto step 18

18. Now let’s go to EndScene.js.

Depending on the player’s score, we want to display two different animations. If it’s greater than or equal to 70, we want to use the 'happy' sprite sheet. Otherwise, we’ll use the 'sad' sprite sheet.

We’ll start with the 'happy' sprite. Inside the if statement of create(), call this.add.sprite(220, 220, 'happy') and assign it to gameState.win.
