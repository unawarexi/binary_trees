# C - Binary Trees

# Binary Tree Readme

This readme provides answers to common questions about binary trees.

## What is a binary tree?

A binary tree is a data structure in which each node has at most two children, referred to as the left child and the right child. It is a hierarchical structure commonly used in computer science and programming for organizing and manipulating data efficiently.

## What is the difference between a binary tree and a Binary Search Tree?

A binary tree is a general tree structure where each node can have zero, one, or two children. In contrast, a Binary Search Tree (BST) is a specific type of binary tree where the left subtree of a node contains only nodes with values less than the node's value, and the right subtree contains only nodes with values greater than the node's value. This property makes BSTs useful for efficient searching and sorting.

## What is the possible gain in terms of time complexity compared to linked lists?

In terms of time complexity, binary trees offer significant advantages over linked lists for certain operations. Searching, insertion, and deletion in a balanced Binary Search Tree can achieve a time complexity of O(log n), where n is the number of elements. In contrast, linked lists typically require O(n) time for these operations. Binary trees provide faster access and manipulation of data when compared to linked lists.

## What are the depth, the height, the size of a binary tree?

- Depth: The depth of a node in a binary tree is the length of the path from the root node to that node. The depth of the root node is 0, and it increases as you move away from the root.

- Height: The height of a binary tree is the length of the longest path from the root to a leaf node. It represents the maximum depth in the tree.

- Size: The size of a binary tree is the total number of nodes in the tree, including the root and all its descendants.

## What are the different traversal methods to go through a binary tree?

There are three common methods for traversing a binary tree:

1. Inorder Traversal: In this method, you first visit the left subtree, then the current node, and finally the right subtree. It produces elements in ascending order in a Binary Search Tree.

2. Preorder Traversal: Here, you visit the current node first, then the left subtree, and finally the right subtree.

3. Postorder Traversal: In this method, you visit the left subtree, then the right subtree, and finally the current node. It is often used for deleting nodes in a tree.

## What is a complete, a full, a perfect, a balanced binary tree?

- Complete Binary Tree: A binary tree in which every level, except possibly the last, is completely filled, and all nodes are as left as possible.

- Full Binary Tree: A binary tree in which every node has either 0 or 2 children. In other words, there are no nodes with only one child.

- Perfect Binary Tree: A binary tree in which all internal nodes have exactly two children, and all leaf nodes are at the same level.

- Balanced Binary Tree: A binary tree in which the depth of the left and right subtrees of every node differ by at most one. It helps maintain efficient operations on the tree, such as searching.

These terms describe different properties and characteristics of binary trees.
