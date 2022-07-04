# Class-15:

### Trees:
There is three types of trees:
- Binary tree.
- Binary search tree.
- k-ary tree.

A tree contain these things:
- Node - A Tree node is a component which may contain its own values, and references to other nodes.
- Root - The root is the node at the beginning of the tree.
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary  tree, k = 2.
- Left - A reference to one child node, in a binary tree.
- Right - A reference to the other child node, in a binary tree.
- Edge - The edge in a tree is the link between a parent and child node.
- Leaf - A leaf is a node that does not have any children.
- Height - The height of a tree is the number of edges from the root to the furthest leaf.

### Traversals:
Traversing a tree allows us to search for a node, print out the contents of a tree, and when it comes to trees there are two categories of travesals:
- Depth first.
- Breadth first.

Depth first: is where we prioritize going through the depth (height) of the tree first.
Three methods of depth first:
- Pre-order: root >> left >> right
- In-order: left >> root >> right
- Post-order: left >> right >> root

Breadth first: iterates through the tree by going through each level of the tree node-by-node.