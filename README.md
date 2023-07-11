# Leetcode 863. All Nodes Distance K in Binary Tree (Medium)

# Problem 

Given the root of a binary tree, the value of a target node target, and an integer k, return an array of the values of all nodes that have a distance k from the target node.

You can return the answer in any order.

# Solution O(N)

Using BFS first populate a parent map for each node. Thne traverse from the target node using bfs, checking both children if they exist and its parent, once you have passed k iterations append all the next nodes to check to the return list and return.
