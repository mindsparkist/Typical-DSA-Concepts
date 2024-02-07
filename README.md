# Typical-DSA-Concepts

# Height of a tree:

- Refers to the longest path from the root node to any leaf node in the tree.
- Measured by the number of edges along that path.
- For an empty tree, the height is 0. For a single-node tree, the height is 1.
# Depth of a node:

- Refers to the distance of a specific node from the root node.
- Measured by the number of edges in the path from the root to that specific node.
- The depth of the root node itself is always 0.

## Here's an analogy to visualize the difference:

Imagine a tree as a family tree, with the root node representing the ancestor and leaves representing descendants.
The height of the tree would be the number of generations from the ancestor to the furthest descendant.
The depth of a specific descendant would be their generation number (e.g., a child of the ancestor has depth 1, a grandchild has depth 2, and so on).

## Technical Documentation 
https://shuvradipchakrabortyportfolio.blogspot.com/2024/01/introducing-ultimate-dsa-concepts.html

# How to calculate if a tree (binary tree) is balanced? 

To calcaulate if a bianry tree is balanced is check if the height of the left subtree - height of the right subtree is < or = to 1.

## Heap 

A heap is a complete binary tree that satifies the heap property 

1 complete binary tree - Every level leaving potentially the last level is completely filled and nodes are filled form left to the right.
2 the heap property - The value of every node is greter that or equal to it`s child node.
