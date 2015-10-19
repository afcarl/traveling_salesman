Torch implementation of traveling salesman problem using A star search.

A star search:-
- In Terminal.app run `th distances2coordinates.lua` to convert distances to xy coordinates.
- Run `th tsp.lua` to run the a star search algorithm and output the path: ![th visualize_word_vectors.lua](https://github.com/vivanov879/traveling_salesman/blob/master/tsp_solution.png)

Kruskal algorithm:
- Run `th kruskal_run.lua`


Dijkstra algorithm:
- Run `th dijkstra.lua` which contains dijkstra algorithm


A star search for a maze:
- `th a_star_closed.lua` using closed set.
- `th a_star_no_closed.lua` without closed set.




Traveling salesman solution is specified at http://www.public.asu.edu/~huanliu/AI04S/project1.htm. Heuristic function = distance to the nearest unvisited city from the current city + estimated distance to travel all the unvisited cities (MST heuristic used here) + nearest distance from an unvisited city to the start city. Note that this is an admissible heuristic function.
Data is taken from http://people.sc.fsu.edu/~jburkardt/datasets/tsp/tsp.html, `data.txt` contains distances between each pair of cities.

Ds

