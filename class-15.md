## Trees
A tree data structure is a hierarchical structure that is used to represent and organize data in a way that is easy to navigate and search. It is a collection of nodes that are connected by edges and have a hierarchical relationship between the nodes

## Trees data structure component
Node: A component of a tree that contains values and references to other nodes.
Root: The starting node of the tree.
K: The maximum number of children any node can have in a k-ary tree. For binary trees, k = 2.
Left: A reference to the left child node in a binary tree.
Right: A reference to the right child node in a binary tree.
Edge: The link between a parent and child node.
Leaf: A node without any children.
Height: The number of edges from the root to the furthest leaf.

## Traversals Trees
There are two categories of tree traversals:

## Depth-First Traversal:
Prioritizes going through the depth (height) of the tree first. Three methods for depth-first traversal are:

Pre-order: Root -> Left -> Right.
In-order: Left -> Root -> Right.
Post-order: Left -> Right -> Root.
Links to an external site.Breadth-First Traversal:
Iterates through the tree level by level, going node-by-node.

### Example Walkthrough:
Let's consider an example of a family tree represented using a tree data structure in Python. We start with a root node representing the family name and add child nodes for each family member. Each node can store additional information, such as the person's name, age, and relationship to other nodes. By traversing the tree, we can access and analyze the family structure efficiently.
## Quiz:
What is a tree data structure? a) A collection of leaves b) A hierarchical data structure c) A sequence of nodes d) A type of flower

What is the root node in a tree? a) The node at the top of the tree b) The node with no children c) The node with the most children d) The node with the highest value

How are nodes connected in a tree? a) By arrows b) By branches c) By leaves d) By fruit

## Vocabulary:
Tree: A hierarchical data structure composed of nodes connected by edges.
Node: An element in a tree that can store data and have child nodes.
Root: The topmost node in a tree with no parent node.
Child Node: A node directly connected to another node.
Parent Node: A node that has child nodes.
Leaf: An end node in a tree with no children.
Edge: A connection between nodes in a tree.