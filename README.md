This project uses recursion to implement the "bucket-fill" feature in a painting program. The paint program will show a blank canvas. A toolbar along the right side lets you select a pen color for drawing. By left-clicking with the mouse within the canvas, you can draw a picture. By default, Painter uses a 16x zoom factor. The program allows the user to right-click within the canvas to "bucket-fill" with the current pen color. Th left-clicks allows the user to draw one pixel at a time.

Visually, the bucket-fill operation is very intuitive. If we pour red paint onto a white area, then first the spot where we poured the paint should turn red. Then next, the red paint should spread out in all directions, filling in the entire white area, only stopping when it reaches the edge of the canvas or a "wall" made of some other color, i.e. any color except white. Likewise, if we pour blue paint onto a yellow area, then first the spot where we poured the paint should turn blue. Then next, the blue paint should spread out in all directions, filling in the entire yellow area, only stopping when it reaches the edge of the canvas or a "wall" made of some other color, i.e. any color except yellow.

Collaborations: I was provided with most of the code through my school and I added the code for bucket-fill, respond to right clicks and fixed some bugs with the other mouse clicks as well. 

https://mathcs.holycross.edu/~csci131/assn/p4/example.gif

