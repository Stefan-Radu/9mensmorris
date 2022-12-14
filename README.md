# Nine Men's Morris đšī¸

### About âšī¸

Implementation of the classic "Nine Men's Morris" game in Python đ, using
[pygame](https://www.pygame.org/news) as part of the AI course @UniBuc đī¸.
Features multiple options of play, including Player vs Player and against an AI
with multiple levels of difficulty.

<div style="margin: 10px;">
    <img src='./assets/game_table.png' alt='table' width=100px align=right>
</div>

The code is written in a single file and the result is _rough around the edges_
because it was written only in **one day** âĄ, since (for me) it was a last minute
assignment.

The resulting performance is satisfactory đđŧ. I cannot win even on **medium**
difficulty, not to mention **hard**.


### Algorithm đĨ

The AI's "brain" đ§  is based on a decision tree, the
[minmax](https://en.wikipedia.org/wiki/Minimax) algorithm and the [alpha-beta
pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning) optimization.

### Demo đŊ

<div align="center">
    <img src='./assets/demo.gif' alt='demo' width=350px>
</div>
