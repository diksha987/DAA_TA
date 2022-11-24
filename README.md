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
<H1><P><P><B>TESTCASES</P></B></H1>
<B>TESTCASE NO. 01 </B><BR><BR>
![image](https://user-images.githubusercontent.com/56405230/203818354-9f7882fb-ade1-472a-a205-389be842ae7b.png)

<HR>
<B>TESTCASE NO. 02 </B><BR><BR>
![image](https://user-images.githubusercontent.com/56405230/203818406-ea6dcb02-cb1d-46b8-82c0-2fa1ea4e8659.png)

<HR>
<B>TESTCASE NO. 03 </B><BR><BR>
![image](https://user-images.githubusercontent.com/56405230/203819184-995ce14e-6e1e-4dd5-921f-f2e7e13f5b2b.png)

<HR>
