Liquid Glass Chess Game
A beautiful, fully-functional chess game with a frosted glass aesthetic. This is a single HTML file that can be easily embedded on your GitHub Pages website or any static hosting platform.

Features
Game Mechanics:

	•	Full chess rule implementation including pawn movement, piece captures, and en passant considerations
	•	Check and checkmate detection
	•	Stalemate detection for draw scenarios
	•	Move validation for all piece types (pawns, rooks, knights, bishops, queens, kings)
	•	Undo move functionality
	•	Complete move history tracking

User Interface:

	•	Frosted glass morphism design with premium aesthetics
	•	Responsive layout that works on desktop and mobile devices
	•	Real-time game status display (whose turn, check warnings, game over conditions)
	•	Live piece count statistics
	•	Move history with algebraic notation
	•	Smooth animations and hover effects
	•	Electric cyan accent colors against deep charcoal backgrounds
	•	Glowing highlights for selected pieces and valid moves

Visual Design:

	•	Animated gradient background with subtle cyan and blue glows
	•	Glass-effect panels with backdrop blur
	•	Piece selection highlighting with cyan glow
	•	Valid move indicators with pulsing animations
	•	Check warning with red highlight
	•	Smooth piece movement animations with cubic-bezier easing

How to Use
Option 1: Direct File Usage
	1.	Download the `chess-game.html` file
	2.	Open it directly in any modern web browser
	3.	Start playing immediately - no installation required

Option 2: GitHub Pages Integration
	1.	Copy `chess-game.html` to your GitHub Pages repository
	2.	Rename it to `index.html` or any desired name
	3.	Access it via your GitHub Pages URL (e.g., `https://username.github.io/chess-game.html`)

Option 3: Embed in Existing Website

￼
How to Play
Starting a Game:

	•	The game begins with white pieces at the bottom and black pieces at the top
	•	White always moves first

Making Moves:

	1.	Click on a piece you want to move
	2.	The square will highlight in cyan, and valid moves will be indicated with pulsing blue borders
	3.	Click on a valid destination square to move the piece
	4.	The game automatically switches to the opponent’s turn

Game Controls:

	•	New Game: Reset the board to the starting position
	•	Undo Move: Take back the last move (works for both players)

Game Status Indicators:

	•	The game status panel shows whose turn it is
	•	If your king is in check, the square will highlight in red
	•	When checkmate occurs, the game announces the winner
	•	Stalemate situations are also detected and announced

Move History:

	•	All moves are recorded in algebraic notation
	•	The move list shows the sequence of all moves made
	•	Scroll through the history to review the game

Technical Details
File Size: ~27 KB (single file, no external dependencies)

Browser Compatibility:

	•	Chrome/Chromium 90+
	•	Firefox 88+
	•	Safari 14+
	•	Edge 90+
	•	Any modern browser with CSS Grid, Flexbox, and ES6 JavaScript support

Performance:

	•	Optimized for smooth gameplay
	•	No external libraries or frameworks required
	•	Runs entirely in the browser with no server needed
	•	Minimal memory footprint

Chess Rules Implemented
Piece Movement:

	•	Pawns move forward one square (or two on first move), capture diagonally
	•	Rooks move any number of squares horizontally or vertically
	•	Knights move in an L-shape (2 squares in one direction, 1 in perpendicular)
	•	Bishops move diagonally any number of squares
	•	Queens move like rooks or bishops combined
	•	Kings move one square in any direction

Game Conditions:

	•	Check: King is under attack
	•	Checkmate: King is in check and has no legal moves (current player loses)
	•	Stalemate: King is not in check but player has no legal moves (draw)
	•	Move validation prevents illegal moves

Customization
The chess game can be easily customized by editing the HTML file:

Change Colors:

	•	Edit the CSS color values (look for `#00ffc8` for cyan, `#0a0e27` for dark background)
	•	Modify the gradient colors in the `body` background property

Adjust Layout:

	•	Change the `grid-template-columns` value in `.container` to modify the sidebar width
	•	Modify `max-width` in `.chess-board` to change board size

Modify Animations:

	•	Edit the `@keyframes` sections to change animation speeds
	•	Adjust `transition` properties for different animation effects

Troubleshooting
Game not responding:

	•	Refresh the page
	•	Clear browser cache if using an older version
	•	Try a different browser

Pieces not displaying correctly:

	•	Ensure your browser supports Unicode chess symbols
	•	Check that JavaScript is enabled in your browser

Performance issues:

	•	Close other browser tabs
	•	Disable browser extensions
	•	Try a different browser

License
This chess game is provided as-is for personal and educational use. Feel free to modify and distribute as needed.

Support
For issues or suggestions, you can:

	•	Review the game logic in the JavaScript section of the HTML file
	•	Test in different browsers to isolate compatibility issues
	•	Check browser console (F12) for any error messages

Enjoy your games!