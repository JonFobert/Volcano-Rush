Desert Rush
=================

This is a short side scrolling game. The objective is to jump over the zombies as the appear from the righ side of the screen. 1 Point is awarded for each baddie you jump over. If the player collides with a zombie the game is over.

Acknowledgments
---------------

Character art from Kenney.nl
Background art from OpenGameArt.org

## Optimizations
3 canvases: static background, dynamic background, and game sprites
turned off text rendering
turned off transparency on static background
get rid of floats, especially when drawing images
only use clearRect on necessary areas
