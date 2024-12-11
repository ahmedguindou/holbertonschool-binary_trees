Binary Trees
What is a Binary Tree?
A binary tree is a hierarchical data structure in which each node has at most two children, referred to as the left and right child. Each node contains a value and pointers (or references) to its left and right children. The top node is called the root.

Difference Between a Binary Tree and a Binary Search Tree (BST)
Binary Tree: There is no specific ordering of the nodes. Each node can have any value.
Binary Search Tree (BST): In a BST, the nodes are arranged in such a way that for any given node:
All values in the left subtree are less than the node's value.
All values in the right subtree are greater than the node's value.
This ordering allows for efficient search, insert, and delete operations.

Time Complexity Comparison: Binary Tree vs Linked List
Linked List: Operations like search, insert, and delete take O(n) time, as it requires traversing the list.
Binary Tree: Operations like search, insert, and delete can take O(log n) time on average in a balanced binary tree, as the search space is divided into two subtrees with each level.
In the best-case scenario (a balanced tree), the binary tree provides significant time complexity improvements compared to a linked list.

Depth, Height, and Size of a Binary Tree
Depth of a node: The number of edges from the root to the node.
Height of a node: The number of edges on the longest path from the node to a leaf node.
Height of the tree: The height of the root node.
Size of the tree: The total number of nodes in the tree.
Traversal Methods of a Binary Tree
There are several ways to traverse a binary tree:

In-order: Traverse the left subtree, visit the node, then traverse the right subtree.
Pre-order: Visit the node, then traverse the left and right subtrees.
Post-order: Traverse the left and right subtrees, then visit the node.
Level-order: Traverse the tree level by level from top to bottom.
Types of Binary Trees
Complete Binary Tree: Every level, except possibly the last, is completely filled, and all nodes are as far left as possible.
Full Binary Tree: Every node has either 0 or 2 children (no node has only one child).
Perfect Binary Tree: A binary tree where all interior nodes have two children, and all leaf nodes are at the same level.
Balanced Binary Tree: A binary tree where the height of the left and right subtrees of every node differ by at most 1. This ensures efficient operations.