# B-Trees

B-tree is a special type of self-balancing search tree in which each node can contain more than one key and can have more than two children. It is a generalized form of the binary search tree.

## Table of content
 - b-trees/
     - [Why do we need a b-tree data structure?](#why-do-we-need-a-B-tree-data-structure?)

Also known as a height-balanced m-way tree.
![image](https://user-images.githubusercontent.com/46763901/164933769-0947b957-a252-4375-bac5-83244fc9f77b.png)

## Why do we need a B-tree data structure?
The need arose with the rise in the need for lesser time in accessing the physical storage media (like a hard disk).
The secondary storage devices are slower with a larger capacity. The need for such data structure was to minimize the disk accesses.

Other data structures such as BST, AVL tree, red-black tree, etc. can only store one ket in one node. If you need to store a large number of key, then the height of such trees becomes very large and the access time increases.

B-trees, on the otherhand, can store many keys in a single node and can have multiple child nodes. This decreases the height significantly allowng faster disk accesses.

## Properties




references: 
- https://www.programiz.com/dsa/b-tree
- 
