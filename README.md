# RubikCubeSolverAssignmentFromEducaseIndia


1. Object-Oriented Cube Representation

RubiksCube class with proper face representation
Each face has 9 squares with color coding (r=red, g=green, b=blue, y=yellow, o=orange, w=white)
Methods for cloning, checking if solved, and getting cube state

2. Manual Rotation System

All 12 basic moves implemented: F, F', R, R', U, U', L, L', D, D', B, B'
Each rotation properly updates the face and adjacent edges
Real-time visual updates after each move

3. Cube Generation

"Generate Scrambled Cube" button creates a solvable scrambled state
Uses 25 random moves to ensure good scrambling
Resets to solved state option available

4. Solving Algorithm

CubeSolver class implementing a simplified layer-by-layer approach
Solves: bottom cross → bottom corners → middle layer → top cross → top corners → final orientation
Records all moves used in the solution
Displays step-by-step solution with move sequences

5. Visual Display

Uses the provided getCubeSvg() method for cube visualization
Shows all 6 faces in an unfolded cube format
Color-coded squares with clear face labels (F, R, B, L, U, D)
Real-time updates during solving

6. User Interface

Generate/Reset/Solve buttons
Manual control buttons for all 12 moves
Solution steps display with grouped moves
Status indicator showing if cube is solved or scrambled

*How to Use:

Generate a Scrambled Cube: Click to create a random scrambled state
Manual Controls: Use the toggle button to show/hide manual rotation buttons
Solve: Click "Solve Cube" to automatically solve using the algorithm
Watch Solution: The solution is applied step-by-step with visual feedback

Technical Notes:

Algorithm: This is a basic solving approach focused on functionality rather than optimality
Performance: The solver may take 50-150 moves (not optimal, but functional)
Visualization: Smooth step-by-step application of solution moves
Error Handling: Basic error handling for edge cases

The implementation prioritizes functionality over optimization, as requested. The solver will find a solution (though not the shortest one), and the code is structured, documented, and ready for presentation. The algorithm demonstrates programming problem-solving skills while maintaining a working, interactive interface.
