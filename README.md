# Influence-Maximisation in Social Networks using Node Connectivity, Activity and Recency.
Influence maximization has attracted a lot of attention due to its numerous applications, including diffusion of social movements, the spread of news, viral marketing and outbreak of diseases. The objective is to discover a group of users that are able to maximize the spread of influence across a network through social network analysis.

 This project detects k-size subset of nodes in a social network that can maximize the influence spread in the network using node connectivity, node activity and node recency. Node connectivity is the measure of the connection between the nodes and how does that connection contribute in influence spread. Node activity tells about the actions of the particular node and in the same way node recency tells about how recently the node has interacted in the past.

We have tried to use efficient heuristics to incorporate the above three parameters. We have applied the UAC Rank algorithm for finding the top seed nodes in terms of connectivity and activity. Further we have used the time factor to find out the nodes with the most recent interactions.
