---
layout: post
title: Game of Life
published: true
categories: [project, coding]
tags: [game of life]
excerpt: This is a simple implementation of the Game of Life in Java. I coded this because I wanted something quick and simple to implement as I have been working recently and didn’t have time to work on anything large. You can download a executable jar here to try it out. Or you can find a video of the program running.
---

This is a simple implementation of the Game of Life in Java. I coded this because I wanted something quick and simple to implement as I have been working recently and didn’t have time to work on anything large. You can download a executable jar here to try it out. Or you can find a video of the program running.

Conway’s Game of Life
---------------------
The Game of Life can be envisioned as a two dimensional grid that contains cells. Each cell can be in a dead or alive state and at the start of each lifecycle, whether a cell is alive or dead is dependant on its number of alive neighbours. A neighbour can be horizontally, vertically or diagonally adjacent  and the querying happens simultaneously for all cells. The rules are as follows according to Wikipedia:

1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
2. Any live cell with two or three live neighbours live on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overcrowding.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The most fun aspect of this for me is starting with a clean slate and then drawing the alive cells onto the screen to see how they change. If you run this code I strongly recommend giving it a go.

<br>

<div class="row">

	<div class="col-lg-12">

		<img src="/assets/img/game_of_life.png" class="img-responsive" alt="Reponsive image">

	</div>

</div>
