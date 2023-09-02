# A-star
 A* search algorithm is a heuristic-based search algorithm that finds the shortest path from a start node to a goal node in a graph by considering both the cost to reach the current node and an estimated cost to reach the goal. It works like--
1.	Initialization:
•	Choose a start node and a goal node.
•	Initialize two lists: an open list and a closed list.
•	Add the start node to the open list with an initial cost of 0.
2.	Main Loop:
•	While the open list is not empty:
•	Select the node with the lowest combined cost (cost to reach the node + heuristic estimate to the goal) from the open list.
•	If the selected node is the goal node, the algorithm terminates, and the path is reconstructed.
•	Otherwise, move the selected node from the open list to the closed list.
3.	Expand Node:
•	Generate the successors (neighbours) of the selected node.
•	For each successor:
•	If the successor is in the closed list, skip it.
•	If the successor is not in the open list, calculate its cost and heuristic and add it to the open list.
•	If the successor is already in the open list, compare its current cost with the new cost. If the new cost is lower, update the cost and parent.
4.	Termination:
•	If the open list becomes empty and the goal node hasn't been reached, there is no path to the goal, and the algorithm terminates.

