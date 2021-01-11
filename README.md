# Traveling Salesmen Problem Solving by Dynamic Programming & GVNS (TSP)

>In this project we shall discuss on the Travelling Salesman Problem (TSP) a very famous NP-hard problem and will take a few attempts to solve it, using Dynamic programming, or by using approximation algorithms (GVNS) and work on the corresponding python implementations.
<br/>
## How to use the application ?

<ol>
<li>Clone the project on your machine with :<br/>
<pre><code>
git clone https://github.com/zakariamejdoul/tsp_solving_dp_gvns.git
</code></pre>
</li>
<li>Run all cells in Jupyter Notebook file named <strong>main-app.ipynb</strong>.</li>
<li>Put the instance path (you can use the instances provided in the folder named <strong>instances</strong>).</li>
<li>Put your choice : <strong>1</strong> for dynamic programming method and <strong>2</strong> for GVNS metaheuristic method.</li>
<li>Put your source city (the numbering order of cities starts with 1).</li>
<li>If you have selected the choice 2 (GVNS method) you must provide the maximum execution time<br/> of the program in minutes.</li>
<li>Enjoy the results !</li>
</ol>
<br/><br/>

> **Results include the optimal path, the optimal distance and the target plot.**

<pre><code>
Your matrix : 

   0,   12,   10,   19,    8
  12,    0,    3,    7,    2
  10,    3,    0,    6,   20
  19,    7,    6,    0,    4
   8,    2,   20,    4,    0

TSP solver

******* Menu *******
Please choose one of these methods :
(1) Solve with dynamic programming 
(2) Solve with GVNS


OPTIMAL POLICY : [3, 1, 5, 4, 2, 3]
OPTIMAL VALUE : 32



Generated coordinates of cities : 

[[32 33]
 [23 32]
 [38 21]
 [16 21]
 [10 32]] 
</code></pre>
<img src = "plots\plot exampe.png" title = "plot example" alt = "Plot Example">
