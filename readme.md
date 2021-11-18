## Dynamic Programming
 DP is such a powerful algorithm to solve optimal problems that you need to have a master level understanding of its mechanism, as well as be proficient with the implementation

 ## Key Features of DP
 * Solution of current problem could be derived from the solution(s) of sub-problem(s)
 * There are overlap calculation among the sub-problems

 ## Intuition of Identifying DP Problem
 * Optimal Problem. You need to find the MIN or MAX number of something. Like what is the MAX ways to form a string from a given set of characters.
 * You have other clue :) to solve it.

 ## DP v.s. Greedy Algorithm
 * DP could guarantee the optimal solution, while a greedy algorith can not.
 * With a greedy algorithm, we make whatever choice that seems the best for the current situation, and in the hope (while, no guarantee), that it will lead to the global optimal solution.
 * Greedy algorithm is normally considered faster than DP since the former can only go forward and never look back.
 * DP normally takes more space as well since it considers all possible solutions.
 ## Typical DP Implementation
 * Bottom up
 * Top down with a memorized table