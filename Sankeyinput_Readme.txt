There are two parts of the Sankey:

Node:
The parameters define the position of the nodes

label: labels of the name of the nodes
x: x position of each node, in the order of the label (the larger the righter value between 0 and 1)
y: y position of each node, in the order of the label (the larger the lower value between 0 and 1)
color: color of the node


Link:
The lines between nodes: the number do not have to be the same as the number of nodes

source: the index of the node defined above (start node)
target: the index of the node defined above (end node)
value: the size of the link
color: the color of the link


