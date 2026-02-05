## Make a hat follow the top of your head

Pick an accessory sprite (like a hat) and make it stick to your head, resize with you, and rotate when you tilt.

--- task ---

Choose a sprite:

- Either keep the default sprite, or delete it (right-click the sprite > **delete**)
- Click **Choose a Sprite**
- Pick something like a **hat** (or paint your own)

--- /task ---

--- task ---

Add code to the accessory sprite to make it follow your face:

when green flag clicked
forever
  go to [top of head v]        (Face Sensing)
  set size to face size        (Face Sensing)
  point in direction of face tilt   (Face Sensing)

--- /task ---

--- task ---

Test: Click the green flag and move your head around.

- Does the hat stay on your head?
- Does it rotate when you tilt your head?

--- /task ---
