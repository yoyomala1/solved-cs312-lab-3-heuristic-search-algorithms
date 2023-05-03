Download Link: https://assignmentchef.com/product/solved-cs312-lab-3-heuristic-search-algorithms
<br>
<span class="kksr-muted">Rate this product</span>

Task 3: Heuristic Search Algorithms

Domain: Uniform Random-4-SAT is a family of SAT problems distributions obtained by randomly generating 3-CNF formulae in the following way: For an instance with n=4 variables and k=5 clauses, each of the k clauses is constructed from 3 literals which are randomly drawn from the 2n possible literals (the n variables and their negations) such that each possible literal is selected with the same probability of 1/2n. Clauses are not accepted for the construction of the problem instance if they contain multiple copies of the same literal or if they are tautological (i.e., they contain a variable and its negation as a literal). Each choice of n and k thus induces a distribution of Random-4-SAT instances. Uniform Random-4-SAT is the union of these distributions over all n and k.

Firstly generate your formula for N = 4 and k = 5. Please write your clauses in the text file and each clause should be written in a different line of the text file. Then input the formula to three algorithms.

Implement:

<ol>

 <li>Variable neighborhood descent : Modify Hill-Climbing Search to switch to a denser neighborhood function when stuck at a local optimum.</li>

 <li>Beam Search : Code for different beam lengths</li>

 <li>Tabu Search : Implement tabu search and find an optimum tabu tenure value for the domain.</li>

</ol>

Report Format :

<ol>

 <li>Brief description about the domain:

  <ol>

   <li>State space</li>

   <li>Start node and goal node</li>

  </ol>III. MOVEGENandGOALTESTalgorithm</li>

 <li>Heuristic functions considered</li>

 <li>Beam search analysis for different beam lengths</li>

 <li>Tabu search for different values of tabu tenure</li>

 <li>Comparison of Variable neighborhood descent, Beam Search, Tabu Search: Nodes exploredby each</li>

</ol>

Evaluation Criteria: