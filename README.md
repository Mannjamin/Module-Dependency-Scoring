# Module-Dependency-Scoring
A basic script to get the maximum and minimum relationships of nodes

## Module Dependency Graph
A Module Depenedency Graph is a symmetrical directed graph which represents the relationships within software classes within a software system. Given a list of all known relationships (such as Main.java and ArrayList.java) and so on, you can take those relationships to make a basic Module Dependency Graph.

Example:

Relationships:

Module Dependency Graph Equivalent:


## Maximum Relationship:
To calculate the maximum relationships, assuming every, node, has a relationship. The following equation can be used. 


## Minimum Relationship:
To calculat ethe minimum relationships, assuming every node is independent, the following equation can be used.

## Accuracy:
These equations do not represent accurate estimations of coupling or cohesion. They merely demonstrate the abosolute possible max and minimum. They do not inheritly represent any optimisation strategies maximum or minimum scores. They do however, provide insight into how accurate, or how poor a Software System can be if every node was connected, and every node was independent. Despite this, it is unlikely you will ever find a software system with absolute independence between classes unless all the code was within 1 class, and even so, that would still be considered either a maximum or minimum score of 0. 
