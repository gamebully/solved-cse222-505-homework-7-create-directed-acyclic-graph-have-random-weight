Download Link: https://assignmentchef.com/product/solved-cse222-505-homework-7-create-directed-acyclic-graph-have-random-weight
<br>



<strong>Homework 07 </strong>

<strong>Q1:</strong> Create directed acyclic graph have random weight (v=10, e=20), plot this graph using plot_graph function. Prove that using is_undirected and is_acyclic_graph functions. Then run shortest_path function on this graph, use least 3 different label pair (shortest_path(g,v1,v2), shortest_path(g,v3,v4), ……)

<strong>Q2: </strong>Create​ undirected and acyclic graph have no weight (v=15), plot this graph using plot_graph function. Prove that using is_undirected and is_acyclic_graph functions. Then run is_connected function on this graph, use least 3 different label pair ( is_connected(g,v1,v2), is_connected(g,v3,v4), ……)

<strong>Q3:</strong> Create undirected and cyclic graph have no weight (v=10), plot this graph using plot_graph function. Prove that using is_undirected and is_acyclic_graph functions. Then run DepthFirstSearch and BreathFirstSearch functions on text book and plot spanning trees.

<strong>Q4: </strong>This​ answer of this question should be <strong>only</strong>​<strong> 1 page</strong>.​ Explain what is the differencies of BFS and DFS. (usage areas, advantages, …). Consider the undirected graph below which is represented by its adjacency matrix.

<ol>

 <li>Run the DFS algorithm starting from vertex 1, and draw the DFS tree.</li>

 <li>Run the BFS algorithm starting from vertex 1, and draw the BFS tree.</li>

</ol>

<ul>

 <li><strong>Input – </strong>​<strong>g</strong>, a graph object; ​ ​<strong>v1</strong>, a vertex label in ​   ​g; ​​<strong>v2</strong>, a vertex label in ​ ​g.​</li>

 <li><strong>Output – </strong>​<strong>TRUE</strong> if there is a path from ​ ​v1 to ​ ​v2 in g,​ ​​<strong>FALSE</strong> if not.​</li>

 <li>Description – Determine if there is any path between vertex v1​ and vertex ​v2 in graph ​g​. If v1 or ​ ​v2 are not in g then throw an error.​</li>

</ul>

Function – ​shortest_path

<ul>

 <li><strong>Input – </strong>​<strong>g,</strong>​ graph object; ​ ​<strong>v1</strong>, a vertex label in ​   ​g; ​​<strong>v2</strong>, a vertex label in ​ ​g.​</li>

 <li><strong>Output – path,</strong> a vector of the names of vertices that make up the shortest path, in order. If there is no path between the vertices then return an empty vector; <strong>distance</strong>​ ,​ total weight of path.</li>

 <li>Description – Find the shortest path from vertex v1​ to vertex ​v2 using Dijkstra’s algorithm. Note that there may not be a unique solution for any given graph, you are only required to return one path.</li>

</ul>

Function – ​is_undirected

<ul>

 <li><strong>Input – </strong>​<strong>g</strong>, a graph object.​</li>

 <li><strong>Output – </strong>​<strong>TRUE</strong> if ​ ​g is undirected, ​ ​<strong>FALSE</strong> if not.​</li>

 <li>Description – Check if the graph object is undirected, this is true if all directed edges have a complementary directed edge with the same weight in the opposite direction.</li>

</ul>

Function – ​is_acyclic_graph

<ul>

 <li><strong>Input – </strong>​<strong>g</strong>, a graph object.​</li>

 <li><strong>Output – </strong>​<strong>TRUE</strong> if ​ ​g is undirected, ​ ​<strong>FALSE</strong> if not.​</li>

 <li>Description -The graph may or may not have cycles. To check do a graph traversal (BFS or DFS).</li>

</ul>

Function – ​plot_graph

<ul>

 <li><strong>Input – </strong>​<strong>g,</strong>​ a graph object​</li>

 <li><strong>Output – </strong>plot showing all vertices (labeled) and edges.​</li>

 <li>Description – This function should be able to take any graph object and produce a reasonably attractive visual representation of that graph. Your algorithm should make use edge weights to layout the distance between vertices.</li>

</ul>




Book Student source code:

<u>http://bcs.wiley.com/he-bcs/Books?action=resource&amp;bcsId=5643&amp;itemId=0470128704&amp;reso urceId=21295</u>




Note:

<ul>

 <li>Obey OOP principles and clean code standarts.</li>

 <li>Write a main and maintest for each function</li>

 <li>Your submission is studentnumber.zip and include following files:</li>

 <li>o intelliJ project file</li>

</ul>

○    Q1 folder

○    Q2 folder

○    Q3 folder

<ul>

 <li>o Report.pdf</li>

 <li>o Javadoc</li>

 <li>The report must be in format “ReportFormat_hw7”</li>

</ul>




<strong> </strong>


