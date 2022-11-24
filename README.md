# DAA-TA
<H1>PROGRAMMING ASSIGNMENT- DESIGN AND ANALYSIS OF ALGORITHMS</H1>
<B>TOPIC: GREEDY ALGORITHMS</B><BR><BR>
<B> PROBLEM STATEMENT </B><BR><BR>
<P><B>Step 1:</B> Input “n” from user</P>
<P><B>Step 2:</B> Create a “nxn” matrix and populate the matrix using i>=0 values such that (0<=i<=10).  Ensure minimum 40% of elements such that a[i,j]=a[j,i] must be “zero”. This is called as “Conditional Randomization”.</P>
<P><B>Step 3:</B> Restructure the matrix and replace all the diagonal elements to “zero”</P>
<P><B>Step 4: </B>Create a minimum cost spanning tree using the matrix</P>
<P><B>Step 5: </B>Accept V1 and V2 as two vertices and print the spanning tree between two vertices.</P>
<P><B>Step 6: </B>The user is allowed to enter input “q”, for example q=3, then perform step 7 for “q” number of times. For example “q=3”, then step 7 will be performed for three times.</P>
<P><B>Step 7: </B>The user is allowed to add and delete the edges in the existing graph, using indicator: “0” or “1”.
If user enters “0”, [2,5]: then the edge between vertex 2 and vertex 5, is deleted.
If user enters “1” [3,5,7]: then an edge is added between vertex 3 and vertex 5 with cost </P>

<P><B>Step 8:</B> Repeat step 5 for the same vertices V1 and V2.</P>

<P><B>Step 9: </B>Comment on the cost of minimum cost spanning tree [cost increased/cost decreased]</P>
<H1><P><P><B>EXPLANATION:</P></B></H1>

<P>Prim's Algorithm is a greedy algorithm that is used to find the minimum spanning tree from a graph. Prim's algorithm finds the subset of edges that includes every vertex of the graph such that the sum of the weights of the edges can be minimized.</P>

<P>Prim's algorithm starts with the single node and explores all the adjacent nodes with all the connecting edges at every step. The edges with the minimal weights causing no cycles in the graph got selected.</P>
<hr>

![T1](https://user-images.githubusercontent.com/56405230/203822570-6a880f5b-6e8f-45f1-975f-6b40ad7d7503.jpg)<BR>
![image](https://user-images.githubusercontent.com/56405230/203823714-f03e451f-1620-4794-aa42-5ddec9647ddd.png)<BR>
![image](https://user-images.githubusercontent.com/56405230/203824516-7ca25fa6-6f1b-4ffa-88a9-f96d3bcae36f.png)
<HR>
  <H1><P>OBSERVATION ON COST</P></H1>
  <P>
    Cost in increasing if we delete the previous shortest path from a particular source to destination.
    And if we insert the new path from one node to another and newly inserted path's cost is less than previous then the cost is decreasing.
    
    
