Theo Chitayat
Jackson Mandeville
Alexander Booth


It can only be run directly in the Haskell interpreter by commenting out the calls to printFPS and aliveCellCount, due to a font issue.
Instead we have included a compiled version for speed and simplicity. It was compiled on a Debian based Linux system.
In order to compile the code, the Gloss graphics package will need to be installed. 

To compile it use the following command:
ghc -o game_of_life Game_of_Life.hs -O3

Then run it using:
./game_of_life


CONTROLS:

	Use the 1,2,3,4,5, and 6 keys to load our premade start states. The 0 key loads an empty scene.
	
	Use the mouse to add new cells to the scene. Clicking in an empty square adds a cell. Clicking in a square with a cell deletes that cell.

	Press spacebar to start or stop the emulation, or press s to step it.

	Press the up or down keys to increase and decrease the emulation speed (use lower FPS for more complex scenes).
	
	Press c to toggle the coloring effects.
