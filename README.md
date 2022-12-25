# One2PlayerGame

Control:
- Currently using `TestGraphic` to render.
- `void init()`: Set players' initial positions and draw them. Call after `Graphic` and map are initialized.
- `int move()`: Wait until a key is pressed, then move player accordingly.
	- 0 for valid move.
	- 1 for quit (`Q`).

### TODO

Rodent's revenge but with two player.

WASD and arrow key for two characters.

Reach the same goal.

Can push a bunch of boxes if there is no 1) terrain 2) the other character.

## TODO

- Graphics
	- Methods to draw objects
	- Object
		- Array bit of Blocks with different pattern

- Players
	- [done] Basic control with WASD and arrow keys.
	- [done] Players moving inside border without overlapping.
	- Refactor code (move to a separate file)
	- Maybe we need to make basic structures for maps.

- Maps
	- Tutorials
	- Free map
	- Challenges

- Main

- Game
	- Reset & Counter

- Level
	- Coordinate of 2 players
### Spec
// Blocks are 16x16 because Array(16) is easier

Blocks are 16x16.
- Black
- White
- Terrain
- Goal
- Immovable

16h * 32w max
