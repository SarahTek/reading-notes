# Trees

Common terminology

- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

There are two categories of traversals when it comes to trees

- Depth first traversal is where we prioritize going through the depth (height) of the tree first

  - Pre-order: root >> left >> right
  - In-order: left >> root >> right
  - Post-order: left >> right >> root

- Breadth first traversal uses a queue (instead of the call stack via recursion) to traverse or search the width/breadth of the tree node.
