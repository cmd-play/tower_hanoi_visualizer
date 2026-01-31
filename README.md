# tower_hanoi_visualizer

Visualizer for the Tower of Hanoi problem using basic HTML, CSS and JavaScript. It supports up to 5 discs and shows you how to solve the puzzle in the minimum number of moves.

Live demo

You can visit the deployed version here: https://tower-of-hanoi-visualizer.netlify.app/

How it works

The visualizer uses a simple recursive function (commonly named move) to generate the sequence of moves. In short, the algorithm:

1. Moves the top n-1 discs from the source peg to the auxiliary peg using the destination as temporary storage.
2. Moves the largest (nth) disc from the source peg to the destination peg.
3. Moves the n-1 discs from the auxiliary peg to the destination peg using the source as temporary storage.

The app runs this recursive function to produce the list of moves, then animates each move in the UI so you can watch the solution step-by-step.

Features

- Interactive visual animation of each move
- Supports up to 5 discs
- Shows the minimum sequence of moves required
- Controls for play, pause, reset, and (where implemented) speed adjustment

Technologies

- HTML, CSS, JavaScript

Run locally

1. Clone the repository:
   git clone https://github.com/cmd-play/tower_hanoi_visualizer.git
2. Open index.html in your browser, or serve the folder with a simple HTTP server, e.g.:
   python -m http.server 8000
   then visit http://localhost:8000

Contributing

Contributions, issues, and suggestions are welcome. Feel free to open a PR or an issue.

Author

- cmd-play
