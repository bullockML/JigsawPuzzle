# JigsawPuzzle
Assist in solving a jigsaw puzzle

My mother purchased a difficult jigsaw puzzle of toilet paper rolls. The puzzle contains mostly white pieces with a few shades of darker gray. She was able to solve the edges and draker gray pieces in a few days, but the white pieces are taking much longer. Also, she wants to frame the puzzle but doesn't care who finishes it. Therefore, I set out to write a Python program to assist in solving this puzzle.

I start with an image containing the puzzle in its current state and all of the unconnected pieces on an even-colored background. The unconnected pieces are outside the border of the partially completed puzzle, are randomly rotated, and are not touching on another.

investigate.py is a shell script to see how the following tasks might be completed:
1. locate and define features of unconnected puzzle pieces
2. locate and define features of empty slots in the partially completed puzzle
3. match features between unconnected puzzle and the correct empty slot

