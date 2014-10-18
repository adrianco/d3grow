d3grow
======

Example force directed graph that lets you cleanly add nodes and edges as you go rather than creating a static graph. It starts with 20 nodes and random connections. Click on "More" to add a node. Each new node will connect to one or two nodes at random. Half the time the second link will be to the first node, so it ends up looking like a core with random fan-out links. The node size increases with the square root of the number of links to it. The link length increases with the size of the nodes at each end. You can grab and drag nodes.

[Run it by clicking here](http://rawgit.com/adrianco/d3grow/master/d3grow.html)

After clicking on "More" a bunch of times, and wiggling the big node around it will move and look like a jellyfish:
![screenshot](https://github.com/adrianco/d3grow/raw/master/jellyfish.png)
