## Signs

Now add signs to your world to guide players on their journey.

Your project includes a `welcome sign` sprite:

![screenshot](images/world-sign.png)

--- task ---
The `welcome sign` sprite should only be visible in room 1, so add some code to the sprite to make sure that this happens:

--- hints --- --- hint ---
`When the flag is clicked`{:class="blockevents"}, in a `forever`{:class="blockcontrol"} loop, check `if`{:class="blockcontrol"} the `room is 1`{:class="blockdata"} and in that case `show`{:class="blocklooks"} `welcome sign` sprite, `else`{:class="blockcontrol"} `hide`{:class="blocklooks"} the sprite.
--- /hint --- --- hint ---
Here are the blocks you need:

![sign](images/sign.png)

![blocks_1545216559_9596496](images/blocks_1545216559_9596496.png)
--- /hint --- --- hint ---
Here is the complete code:

![sign](images/sign.png)

![blocks_1545216561_0821772](images/blocks_1545216561_0821772.png)
--- /hint --- --- /hints ---


--- /task ---

--- task ---
Test the code for your `welcome sign` sprite by moving between rooms. The sign should only be visible in room 1.

![screenshot](images/world-sign-test.png)
--- /task ---

--- task ---
A sign isn't much good if it doesn't say anything! Add some more code to display a message if the `welcome sign` sprite is touching the `player` sprite:

![sign](images/sign.png)

![blocks_1545216562_2208133](images/blocks_1545216562_2208133.png)
--- /task ---

--- task ---
Test your `welcome sign` sprite again. You should now see a message when the `player` sprite touches the `welcome sign` sprite.

![screenshot](images/world-sign-test2.png)
--- /task ---
