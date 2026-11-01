# Binary Search Tree Analysis

## Core operations

Students should analyze the following BST operations:

- insertion;
- search;
- deletion;
- traversal;
- minimum/maximum lookup;
- subtree height.

## Required discussion

Provide a short analysis comparing the complexity of the following operations:

- best-case vs. worst-case behavior: Operations are faster in a balanced tree and slower in a skewed tree.
- average-case behavior for a balanced BST: A balanced BST usually takes O(log n) for insertion, search, and deletion.

- worst-case behavior for a skewed tree: Operations can take O(n) because the tree acts like a linked list.
- recursive vs. iterative implementations: Recursive methods use function calls, but iterative methods use loops. Both can have similar time complexity.
- how tree height affects search cost: A shorter tree makes searching faster because fewer nodes need to be checked.

## Expected Big-O summary

Students should identify the Big-Oh complexity for:

- `insert`
- `search`
- `remove`
- `inorderTraversal`
- `height`

insert: O(log n) on average and O(n) in the worst case.

search: O(log n) on average and O(n) in the worst case.

remove: O(log n) on average and O(n) in the worst case.

inorderTraversal: O(n) because it visits every node.

height: O(n) because it needs to check every node to find the tree's height.

A Binary Search Tree (BST) stores values in order, with smallest values on the left and larger values on the right. The main operations include insertion, searching, and deletion. Traversals visit all nodes in different orders, and minimum and maximym find the smallest and largest values. 
A balanced BST usually has `O(log)` time complexity for insertion, searh, and deletion. But if the tree becomes skewed, these operations can take `O(n)` time. Traversals and finding the height take `O(n)` because they might need to visit every node. 
Recursive implemention use function calls to move through the tree, but iterative implementation use loops. Tree hegit affects performance because a shorter tree makes searching faster. 
