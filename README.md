# Solving Crime Puzzles Using Graph Theory
Made a code on Python, which allowed one to solve complicated crime puzzles with the help of graph theory. This project uses an adjacency matrix to solve the crime puzzles.

## Table of Contents
* [Motivation](#Motivation)
* [Methodology](#Methodology)

## Motivation
With the advent of computers, algorithms and other mathematical models have been used to understand the behaviour of criminals. These models help the authorities expedite the investigation process by reducing the time in decision making or to develop different strategies to catch the criminals. Graph theory is one of the methods employed by law enforcement agencies to help fight crime. Graph theory is readily used in crime-solving or for logical puzzles, especially those which include different scenarios. One of the most useful applications of graph theory is in forensics to identify fingerprints. Another example of the use of graph theory to fight crime was when an FBI team implemented a version of the Floyd-Warshall Algorithm to help predict the location of a bomber in Los Angeles, USA.

## Methodology
To solve the above-given problem using graph theory, let’s suppose each individual person can be represented using a node or vertex in space. A vertex is drawn from the accuser to the person they are accusing. B accuses A of being the thief; this can be represented as a directed edge from B to A. Both A, and C, say that they are not the thief; this can be seen as the equivalent of accusing everyone other than themselves and can be represented as a directed edge to all the other nodes.

The indegree at every node gives the number of people accusing that person of being the thief. For node A, the indegree is 2; therefore, 2 people are accusing A of being the thief. But only 1 person can be telling the truth, so A cannot be the thief. For node B, the indegree is 2; therefore, 2 people are accusing B of being the thief. But only 1 person can be telling the truth, so B cannot be the thief. For node C, the indegree is 1; therefore, only 1 person is accusing C of being the thief, so C is the thief. 
