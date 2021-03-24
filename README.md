# cpsc481-proj1-py
[CPSC 481 - AI] Project 2 - Heuristics for Pacman.

Spring 2021 CPSC 481-04
	Winnie Pan
	Jianxi Xu
	Josh Ibad

Files included, and functions implemented:
	search.py - File containing main algoritmhs
	 - aStarSearch(problem, heuristic) - A* search algorithm using heuristic specified
	
	searchAgents.py - File containing state space implmentation and heuristics
	 - CornerProblem - State space implementation for the Corners Problem
		- __init__(startingGameState) - Constructor for the class, stores corners visited, cost function, and start state
		- getStartState() - Returns starting state
		- isGoalState(state) - Evaluates whether a state is a goal state of the Corners problem
		- getSuccessors(state) - Returns a list of states adjacent to the inptu state,
			in the form of a 3-typle (state, action, cost).
