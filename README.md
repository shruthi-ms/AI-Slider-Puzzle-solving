# AI-Slider-Puzzle-solving
Given a start state , the code solves slider puzzle to reach the goal state.

##############
final_heuristic1.c is the file with f(n) = g(n) + h(n); where g(n)=num of moves till now and h(n)=num of misplaced tiles
final_heuristic2.c is the file with f(n) = g(n) + h(n); where g(n)=num of moves till now and h(n)=num of moves till goal state is reached
These files take in random generation for the start state board. 
To check, manual input in the code is commented and can be verified. 
If manual input is given: shuffle_state(goal_state) must be commented.
