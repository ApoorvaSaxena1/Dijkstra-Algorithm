# Dijkstra-Algorithm

Code is written in Python 3

Input format:
1) times: List[List[int]];
2) N: int;
3) K: int;

Output format:
1)rtype: int
       

Applying Dijkstra Algorithm on a network delay problem.There are N network nodes, labelled 1 to N.
Given times, a list of travel times as directed edges times[i] = (u, v, w), where u is the source node, v is the target node, and w is the time it takes for a signal to travel from source to target.

Now, we send a signal from a certain node K. How long will it take for all nodes to receive the signal? If it is impossible, return -1.

Note:
->N will be in the range [1, 100].
->K will be in the range [1, N].
->The length of times will be in the range [1, 6000].
->All edges times[i] = (u, v, w) will have 1 <= u, v <= N and 0 <= w <= 100.
