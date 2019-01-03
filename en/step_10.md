## Collect coins

Your `player` sprite should have be able to collect coins as it moves through the world.

--- task ---
Add a new variable valled `coins`{:class="blockdata"} to your project.
--- /task ---

--- task ---
Right-click on the `coin` sprite and choose **show**.

![screenshot](images/coin.png)
--- /task ---

--- task ---
Add code to your `coin` sprite so that it only appears in room 1.
![screenshot](images/coin.png)
![blocks_1546523759_839185](images/blocks_1546523759_839185.png)
--- /task ---


--- task ---

Add code to your `coin` sprite so that the sprite `hides`{:class="blocklooks"} and `1`{:class="blockdata"} is added to the `coins`{:class="blockdata"} variable once the `player` sprite touches the `coin` sprite to 'pick it up'.

![coin](images/coin.png)

![blocks_1546523762_4305282](images/blocks_1546523762_4305282.png)

The code `stop other scripts in sprite`{:class="blockcontrol"} is needed so that the `coin` sprite stops being displayed in room 1 once it's been collected.

--- /task ---

--- task ---
Now add code to the Stage to set your `coins`{:class="blockdata"} variable to `0`{:class="blockdata"} at the start of the game.

![stage](images/stage.png)
![blocks_1546523764_0361698](images/blocks_1546523764_0361698.png)
--- /task ---

--- task ---
Test your game. Collecting a coin should change your `coins` score to `1`{:class="blockdata"}.
--- /task ---

