# AI-projects

All testing command for search project:

python pacman.py --layout testMaze --pacman GoWestAgent<br/>
python pacman.py --layout tinyMaze --pacman GoWestAgent<br/>
python pacman.py -h<br/>
python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch<br/>
python pacman.py -l tinyMaze -p SearchAgent<br/>
python pacman.py -l mediumMaze -p SearchAgent<br/>
python pacman.py -l bigMaze -z .5 -p SearchAgent<br/>
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs<br/>
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5<br/>
python eightpuzzle.py<br/>
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs<br/>
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent<br/>
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent<br/>
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic<br/> 
python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem<br/>
python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem<br/>
python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5<br/>
python pacman.py -l testSearch -p AStarFoodSearchAgent<br/>
python pacman.py -l trickySearch -p AStarFoodSearchAgent<br/>
python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5<br/>
