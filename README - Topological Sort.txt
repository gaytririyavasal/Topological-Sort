
PROJECT DESCRIPTION AND GUIDELINES PROVIDED ON ASSIGNMENT INSTRUCTIONS

In this assignment, you will implement the Topological Sort and run it on a graph.

You will complete the topo.txt file that will be used as input for your program. The first couple of edges are given.

•The first line in topo.txt will be a single integer v. This number will denote the number of vertices to follow.

•The next v lines will be the labels for the vertices in alphabetical order.

•There will be one label to a line. The labels are unique.

•The next line after the labels for vertices will be a single number e. This number will denote the number of edges to follow. There will be one edge per line.

•Each edge will be of the form - fromVertex and toVertex. Assign a default weight of 1 to each edge.

Here is the outline of the code that we developed in class that you will be modifying. You will use
topo.txt instead of graph.txt as your input file. You can add an Edge class if you want to. You may use any
of the functions that you wrote for graph traversal in your last assignment. You can add more functions as
needed. You will first test if the given Graph does not contain a cycle and then do a topological sort on that Graph. For your output, the vertices on a given level must be printed in alphabetical order.

Input:

14
m
n
o
p
q
r
s
t
u
v
w
x
y
z
21
m q
m r
m x
n o
n q
n u
. . .

Output:

For the data file given, your output will look as follows:

The Graph does not have a cycle.

List of vertices after toposort
[ ’m ’ , ’ n ’ , ’ p ’ , ’ o ’ , ’ q ’ , ’ s ’ , ’ r ’ , ’ u ’ , ’ y ’ , ’ t ’ , ’ v ’ , ’w ’ , ’ x ’ , ’ z ’ ]
