To play, go to:
https://xlicoe.github.io/klotski-state-space-tutorial/

This is a Klotski state space tutorial for computational ENR 145 at Coe.


## Background info:

https://en.wikipedia.org/wiki/Klotski

Klotski (from Polish: klocki, lit. 'wooden blocks') is a sliding block puzzle. The blocks are sliding inside a frame, and typically, there's a special one to be moved to the designated location.

![Simple schematics of Klotski the game](/../main/graphs/Klotski_rules.png)

In this tutorial, we are interested in visualizing the "state space", where all the possible moves are connected to their neighboring moves to show dimensional patterns or structures.

**The goal is to provide a quick demo, allowing students in class to output state space coordinates and create a better 3D visualization on their own.**

## How does this tutorial work:

### 1) Build your block board:

First, pick blocks and put them on the board. Unlike the real game, the blue 1x2 block cannot move horizontally, green not vertically. The yellow one can move in either direction. Once you are done placing the blocks, hit the Play button:

![](/../main/graphs/block_placing.png)

### 2) Cover all state space:

Select and use WASD/Arrow keys to move all the blocks around. The state space panel will record all the unquic position(s) the blocks visited, i.e. the state space.
The "Find All States" button will do it automatically.
![](/../main/graphs/state_space_mapping.png)

### 3) Visualize the state space networks:

All state space has neighbor(s). If we use nodes to represent all the state spaces, and use line to connect them, we will generate a gragh of networks. For a single 1x2 block, the graph looks like a line.

![](/../main/graphs/state_space_mapping.png)
![](/../main/graphs/visual.png)

But it sure will get more complicated with more possibilies on the board!
![](/../main/graphs/more_blocks.png)
![](/../main/graphs/more_visual.png)

### 4) Feel free to explore and build a visual tool and even a solver in your own project.
