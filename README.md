# CSC-485B-578B-Assignment-1-solution

Download Here: [CSC 485B/578B: Assignment 1 solution](https://jarviscodinghub.com/assignment/csc-485b-578b-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

10 Question 1
11 There are two quantities to measure the distance between nodes in a network. One is the diameter
12 of the network, which is defined as the maximum distance between any pair of nodes in the network.
13 The other is the average distance, which is defined as the average distance over all pair of nodes in
14 the graph. The two measures in most networks are close to each other. But in some situation they
15 are quite different.
16 1. (15%, 15%) Describe an example of a network where the diameter is more than three times
17 as large as the average distance.
18 2. (10%, 10%) Describe how you could extend your construction to produce networks in which
19 the diameter exceeds the average distance by as large a factor as you would like, i.e., for every
20 positive number c, can you produce a network in which the diameter is more than c times as
21 large as the average distance?
22 Warning: Please carefully check the definitions in the course lecture notes before
23 you work on this problem.
24 Problem 2
25 Implement a naive algorithm in Java to find the diameter of a network based on the Floyd-Warshall
26 algorithm. Use your code to calculate the diameter of an anonymized personal Facebook network
27 described with Personal-May8-Anonymous.gephi, which could be downloaded from Connex → Re28 source.
1
29 1. (20%, 15%) Submit your java source code into connex dropbox.
30 2. (15%, 10%) How many isolated nodes in the network? An isolated node means there is no
31 link between this edge and other nodes.
32 3. (10%, 10%) Clearly, when a network is disconnected, its diameter is infinity. Nevertheless,
33 when you use Gephi to calculate the diameter of Personal-May8-Anonymous.gephi, you will
34 get a number which is obviously not infinity. Find out how the network diameter is calcu35 lated in Gephi. If your code returns a different result compared to Gephi, modify your code
36 accordingly.
37 4. (0%, 15%) Assume that you are allowed to introduce four new edges in the network. Which
38 four new edges would you introduce into the network so that clustering coefficient of your
39 network represented by Personal-May8-Anonymous.gephi is minimized?. In practice, if you
40 want your personal network to be a closely-knit group, the new edges captures the “problems”
41 among your friends that you might want to put efforts to fix.
42 Note: (1) Please treat the network as a directed network. (2) You can build your
43 code over the gephi platform or simply implement your standalone java program. The
44 structure of Personal-May8-Anonymous.gephi is easy to understand if you open the
45 file with a text editor.
46 Problem 3
47 (10%, 10%) Consider the social network represented in the following figure. Suppose that this social
48 network was obtained by observing a group of people at a particular point in time and recording all
49 their friendship relations. Now suppose that we come back at some point in the future and observe
50 it again. According to the theories based on empirical studies of triadic closure in networks, which
51 new edge is most likely to be present? Provide a brief explanation for your answer.
Figure 1: The network in Problem 3
52 Problem 4
53 (20%, 15%) Together with some anthropologists, you are studying a sparely populated region of a
54 rain forest, where 50 farmers live along a 50-mile-long stretch of river. Each farmer lives on a tract
2
55 of land that occupies a 1-mile of the river bank, so their tracts exactly dived up the 50 miles of river
56 bank that they collectively cover. The farmers all know each other, and after interviewing them,
57 you have found that each farmer is friends with all the other farmers that live at most 20 miles
58 from him or her, and is enemies with all the farmers that live more than 20 miles from him or her.
59 Build the signed complete graph corresponding to this social network. If the network structurally
60 balanced or not? Explain your answer.

