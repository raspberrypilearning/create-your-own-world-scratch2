## Doors and keys

No you are going to add code so that some of the doors in your game world are locked, and the player must find the key to open them and get to the next room.

--- task ---
Switch to the `key` sprite. Right-click on it and choose **show** so that it appears on the Stage.
--- /task ---

--- task ---
Edit the `key` sprite's costume so that it is blue.
--- /task ---

--- task ---
Switch your Stage backdrop to room 3, and place the `key` sprite somewhere difficult to reach!

 ![screenshot](images/world-key.png)

--- /task ---

--- task ---
Add code to the `key` sprite to make it only visible in room 3.
--- /task ---

--- task ---
Create a new list called `inventory`{:class="blockdata"} to store the items your `player` sprite collects.

[[[generic-scratch-make-list]]]
--- /task ---

--- task ---
The code you need to add for collecting the key is very similar to the code for collecting coins. The difference is that you add the key to the `inventory`{:class="blockdata"}.

![key](images/key.png)

![blocks_1546523765_599872](images/blocks_1546523765_599872.png)
--- /task ---

--- task ---
Add code to your Stage to empty your inventory at the start of the game.

![blocks_1546523767_2075996](images/blocks_1546523767_2075996.png)

--- /task ---

--- task ---
Test out your game to check whether you can collect the `key` sprite and add it to your inventory.
--- /task ---

--- task ---
Now add the locked door. Right-click on the `door-blue` sprite and select **show**, then position the sprite across the gap in the two walls.

![screenshot](images/world-door.png)
--- /task ---

--- task ---
Add code to the `door-blue` sprite so that it is only visible in room 3.
--- /task ---

--- task ---
Add code to the `door-blue` sprite so that, when the key is in the `inventory`{:class="blockdata"}, the sprite `hides`{:class="blocklooks"} to allow your `player` sprite to pass.

![door](images/door.png)

![blocks_1546523768_773816](images/blocks_1546523768_773816.png)
--- /task ---

--- task ---
Test out your game and see if you can collect the blue key to open the door!
--- /task ---
