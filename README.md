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



## Tries.
In data structures and algorithms (DSA), a trie (pronounced "try") is a tree-like data structure used to store a dynamic set of strings or keys where the keys are usually sequences, such as words in a dictionary. The term "trie" comes from the word retrieval, and it is also sometimes referred to as a digital tree, radix tree, or prefix tree.
1.  **Nodes:**
    
    -   Each node in a trie contains a character and may have pointers to its children nodes.
    -   Nodes at the same level represent different characters in the strings.
2.  **Root:**
    
    -   The topmost node is called the root, representing an empty string or the common prefix of all the strings.
3.  **Edges:**
    
    -   Edges represent the characters in the strings, and the edges leading to child nodes are labeled with those characters.
4.  **Leaf Nodes:**
    
    -   Leaf nodes typically represent the end of a string or key.
5.  **Advantages:**
    
    -   Tries are efficient for searching, insertion, and deletion operations on a set of strings.
    -   They provide fast lookups and have a space advantage when many strings share common prefixes.
6.  **Use Cases:**
    
    -   Tries are commonly used in applications where a fast search or autocomplete functionality is required, such as spell checkers, IP routers (for routing table lookups), and various string-related problems.
7.  **Complexity:**
    
    -   The time complexity for searching, insertion, and deletion in a trie is often proportional to the length of the key being operated on.

### Time and space complexity.
O(log n) / O(L)
For insertion, it is like 
O(L) - Insertion
O(L) -  Deletion

  ![Alt Text](https://github.com/mindsparkist/Typical-DSA-Concepts/raw/main/image_2024-03-04_09-47-44.png)



