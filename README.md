## Programming Camp Syllabus 

### Basic Geometry/Euclidean Geometry/Coordinate Geometry/[3-D variants of everything]
- **1. Computational Geometry**
  - **Graham Scan algorithm for Convex Hull**: O(n \* log(n))
  - **Online construction of 3-D convex hull**: O(n^2)
  - **Bentley Ottmann algorithm**: List all intersection points of n line segments in O((n + I) \* logn)
    - **Suggested Reading**: [Link](http://softsurfer.com/Archive/algorithm_0108/algorithm_0108.htm)
  - **Rotating Calipers Technique**
    - **Suggested Reading**: [Link](http://cgm.cs.mcgill.ca/~orm/rotcal.html)
    - **Problems**: Refer to the article for a list of problems that can be solved using the Rotating Calipers technique.
  - **Line Sweep/Plane Sweep algorithms**
    - **Area/Perimeter of Union of Rectangles**
    - **Closest pair of points**
    - **Suggested Reading**: [Link](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=lineSweep)
    - **Problems**: Follow the tutorial for a list of problems.
    - **Area of Union of Circles**
  - **Delaunay Triangulation of n points**: O(n \* logn)
  - **Voronoi Diagrams of n points**: O(n \* logn) using Fortune’s algorithm
  - **Point in a polygon problem**
    - O(n) solution without preprocessing
    - O(logn) algorithm with O(n \* logn) preprocessing for convex polygons
  - **Problems on computational geometry**:
    - BSHEEP, BULK, SEGVIS, CONDUIT, RUNAWAY, DIRVS, RAIN1, SHAMAN, TCUTTER, LITEPIPE, RHOMBS, FSHEEP, FLBRKLIN, CERC07P, BAC, ALTARS, CERC07C, NECKLACE, CH3D, RECTANGL, POLYSSQ, FOREST2, KPPOLY, RAIN2, SEGMENTS, ARCHPLG, BALLOON, CIRCLES, COMPASS, EOWAMRT, ICERINK on SPOJ
    - CultureGrowth, PolygonCover on Topcoder
  - **Suggested Reading**: 
    - *Computational Geometry: Algorithms and applications* by Mark De Burg

- **String Algorithm**
  - **Knuth-Morris-Pratt algorithm**
  - **Problems**: NHAY, PERIOD on SPOJ
  - **Suggested Reading**:
    - Cormen chapter on Strings
    - [Link](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=stringSearching)
  - **Aho-Corasick algorithm**

 ### Problems
- **2. WPUZZLES on SPOJ**

### Suffix Arrays
- **O(n^2 \* logn)**: Naive method of suffix array construction
- **O(n \* logn^2)**: Method of suffix array construction
- **O(n \* log n)**: Method of suffix array construction
- **O(n)**: Method of suffix array construction
- **O(n)**: LCA preprocess on Suffix Arrays to solve a variety of string problems

### Suffix Trees
- **O(n)**: Construction of Suffix Trees using Ukkonen’s algorithm
- **O(n)**: Construction of Suffix Trees if provided with Suffix Arrays using Farach’s algorithm

### Suffix Automata
- **O(n)**: Suffix Automaton construction

### Dictionary Of Basic Factors (DBF)
- **O(n \* log n)**: Method of DBF construction using Radix Sort

### Manacher’s Algorithm
- Find length of palindromic substring of a string centered at a position for each position in the string
- **Runtime**: O(n)

### Regular Expressions
- Searching and preprocessing Regular Expressions consisting of `?`, `*`
- Multi-dimensional pattern matching

### Problems on Strings [can be solved with a variety of techniques]
- DISUBSTR, PLD, MSTRING, REPEATS, JEWELS, ARCHIVER, PROPKEY, LITELANG, EMOTICON, WORDS, AMCODES, UCODES, PT07H, MINSEQ, TOPALIN, BWHEELER, BEADS, SARRAY, LCS, LCS2, SUBST1, PHRASES, PRETILE on SPOJ
- [String Algorithms on Algorithmist](http://www.algorithmist.com/index.php/Category:String_algorithms)

### 3. Basic Graphs [Beginner]
- **Representation of graphs** as adjacency list, adjacency matrix, incidence matrix, and edge list
  - Uses of different representations in different scenarios
- **Breadth First Search**
  - **Problems**: PPATH, ONEZERO, WATER on SPOJ
- **Depth First Search**
- **Strongly Connected Components**
  - **Problems**: TOUR and BOTTOM on SPOJ
- **Biconnected Components**: Finding articulation points and bridges
  - **Problems**: RELINETS, PT07A on SPOJ
- **Dijkstra algorithm**
  - **Problems**: SHPATH on SPOJ
- **Floyd-Warshall algorithm**
  - **Problems**: COURIER on SPOJ
- **Minimum Spanning Tree**
  - **Problems**: BLINNET on SPOJ
- **Flood-fill algorithm**
- **Topological Sort**
- **Bellman-Ford algorithm**
- **Euler Tour/Path**
  - **Problems**: WORDS1 on SPOJ

### Suggested Reading for Graph Algorithms
- [Topcoder Graph Algorithms Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=graphsDataStrucs1)
- Cormen, Chapters 22 to 24
- Refer to the tutorial for problems concerning these techniques

### 4. Flow Networks/Matching (Intermediate/Advanced)
- **Maximum Flow using Ford Fulkerson Method**
  - **Suggested Reading**: [Maximum Flow Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=maxFlow)
  - **Problems**: TAXI, POTHOLE, IM, QUEST4, MUDDY, EN, CABLETV, STEAD, NETADMIN, COCONUTS, OPTM on SPOJ
- **Maximum Flow using Dinic’s Algorithm**
  - **Problems**: PROFIT on SPOJ
- **Minimum Cost Maximum Flow**
  - **Successive Shortest Path Algorithm**
  - **Cycle Cancelling Algorithm**
  - **Suggested Reading**: [Minimum Cost Flow Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=minimumCostFlow1)
- **Maximum Weighted Bipartite Matching (Kuhn-Munkres Algorithm/Hungarian Method)**
  - **Problems**: GREED, SCITIES, TOURS on SPOJ | [Problem Statement on Topcoder](http://www.topcoder.com/stat?c=problem_statement&pm=8143)
- **Stoer-Wagner Min-Cut Algorithm**
- **Hopcroft-Karp Bipartite Matching Algorithm**
  - **Problems**: ANGELS on SPOJ
- **Maximum Matching in General Graph (Blossom Shrinking)**
- **Gomory-Hu Trees**
  - **Problems**: MCQUERY on SPOJ
- **Chinese Postman Problem**
  - **Problems**: [Problem on UVa](http://acm.uva.es/archive/nuevoportal/data/problem.php?p=4039)
  - **Suggested Reading**: [Chinese Postman Problem Resource](http://eie507.eie.polyu.edu.hk/ss-submission/B7a/)
- **Suggested Reading for the Full Category**:
  - *Network Flow: Algorithms and Applications* by Ahuja
  - Cormen, Chapter 25


### 5. Dynamic Programming (DP)
- **Suggested Reading**: Dynamic Programming (DP) as a Tabulation Method
  - Cormen, Chapter on DP
- **Standard Problems**: (You should really feel comfortable with these types)
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=8570&rd=12012&rm=269199&cr=7581406)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=10765&rd=14183)
- **State Space Reduction**
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=10902)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=3001)
  - [Problem Statement on Topcoder 3](http://www.topcoder.com/stat?c=problem_statement&pm=8605&rd=12012&rm=269199&cr=7581406)
- **Solving in the Reverse**: Easier characterizations looking from the end
  - [Problem on SPOJ](http://www.spoj.pl/problems/MUSKET)
  - [Problem Statement on Topcoder](http://www.topcoder.com/stat?c=problem_statement&pm=5908)
- **Counting/Optimizing Arrangements Satisfying Some Specified Properties**
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=8306)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=784)
- **Strategies and Expected Values**
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=10765&rd=14183)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=10806)
  - [Problem Statement on Topcoder 3](http://www.topcoder.com/stat?c=problem_statement&pm=7828)
  - [Problem Statement on Topcoder 4](http://www.topcoder.com/stat?c=problem_statement&pm=7316)
- **DP on Probability Spaces**
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=7422)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=2959)
  - [Problem Statement on Topcoder 3](http://www.topcoder.com/stat?c=problem_statement&pm=10335)
- **DP on Trees**
  - [Problem Statement on Topcoder 1](http://www.topcoder.com/stat?c=problem_statement&pm=10800)
  - [Problem Statement on Topcoder 2](http://www.topcoder.com/stat?c=problem_statement&pm=10737)
  - [Problem Solution on Topcoder](http://www.topcoder.com/stat?c=problem_solution&rm=266678&rd=10958&pm=8266&cr=7581406)
- **DP with Data Structures**
  - [Problem on SPOJ 1](http://www.spoj.pl/problems/INCSEQ/)
  - [Problem on SPOJ 2](http://www.spoj.pl/problems/INCDSEQ/)
  - [Problem on SPOJ 3](http://www.spoj.pl/problems/LIS2/)
  - [Problem Statement on Topcoder](http://www.topcoder.com/stat?c=problem_statement&pm=1986)
- **Symmetric Characterization of DP State**
  - [Problem Statement on Topcoder](http://www.topcoder.com/stat?c=problem_statement&pm=8610)
- **A Good Collection of Problems**:
  - [Codeforces Blog](http://codeforces.com/blog/entry/325)
  - [Problem Classifier](http://problemclassifier.appspot.com/index.jsp?search=dp&usr=)
 
### 6. Greedy
- **Suggested Reading**:
  - Chapter on Greedy Algorithms in Cormen
  - [Greedy Algorithms Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=greedyAlg)
  - **Problems**: Refer to the Topcoder tutorial

### 7. Number Theory
- **Modulus Arithmetic**: Basic postulates (Including modular linear equations, continued fraction, and Pell's equation)
  - **Suggested Reading**:
    - Chapter 1 from *Number Theory for Computing* by SY Yan (Recommended)
    - Cormen Sections 31.1, 31.3, and 31.4
    - [Prime Numbers Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=primeNumbers)
  - **Problems**:
    - [Project Euler Problem 64](http://projecteuler.net/index.php?section=problems&id=64)
    - [Project Euler Problem 65](http://projecteuler.net/index.php?section=problems&id=65)
    - [Project Euler Problem 66](http://projecteuler.net/index.php?section=problems&id=66)
    - [Topcoder Problem 6408](http://www.topcoder.com/stat?c=problem_statement&pm=6408&rd=9826)
    - [Topcoder Problem 2342](http://www.topcoder.com/stat?c=problem_statement&pm=2342)

- **Fermat's Theorem, Euler’s Totient Theorem** (Totient function, order, primitive roots)
  - **Suggested Reading**:
    - Sections 1.6, 2.2 from *Number Theory* by SY Yan
    - Cormen Sections 31.6, 31.7
  - **Problems**:
    - [Project Euler Problem 70](http://projecteuler.net/index.php?section=problems&id=70)
    - [NDIVPHI on SPOJ](http://www.spoj.pl/problems/NDIVPHI/)

- **Chinese Remainder Theorem**
  - **Suggested Reading**:
    - Cormen Section 31.5
    - Section 1.6 from *Number Theory* by SY Yan
  - **Problems**:
    - Project Euler Problem 271
    - [Topcoder Problem 10551](http://www.topcoder.com/stat?c=problem_statement&pm=10551&rd=13903)

- **Primality Tests**
  - **Deterministic**: O(sqrt(n)) approach
  - **Probabilistic**: Fermat Primality Test, Miller-Rabin Primality Test
  - **Suggested Reading**:
    - [Primality Testing Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=primalityTesting)
    - Cormen Section 31.8
    - Section 2.2 from *Number Theory* by SY Yan
  - **Problems**:
    - PON, PRIC, SOLSTRAS on SPOJ
    - [Topcoder Problem 4515](http://www.topcoder.com/stat?c=problem_statement&pm=4515)

- **Prime Generation Techniques**: Sieve of Eratosthenes
  - **Suggested Problems**: PRIME1 on SPOJ

- **GCD using Euclidean Method**
  - **Suggested Reading**: Cormen Section 31.2
  - **Problems**:
    - GCD on SPOJ
    - [Problem on UVa](http://uva.onlinejudge.org/external/114/11424.html)

- **Logarithmic Exponentiation**
  - **Suggested Reading**: [Primality Testing Tutorial on Topcoder](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=primalityTesting)

- **Integer Factorization**
  - **Naive**: O(sqrt(n)) method
  - **Pollard Rho Factorization**
  - **Suggested Reading**:
    - Section 2.3 from *Number Theory* by SY Yan
    - Cormen Section 31.9
  - **Problems**:
    - [Topcoder Problem 2986](http://www.topcoder.com/stat?c=problem_statement&pm=2986&rd=5862)
    - [DIVSUM2 on SPOJ](http://www.spoj.pl/problems/DIVSUM2/)
    - [Topcoder Problem 4481](http://www.topcoder.com/stat?c=problem_statement&pm=4481&rd=6538)

- **Stirling Numbers**
- **Wilson's Theorem**
- **nCr % p in O(p) preprocess and O(log n) query**
- **Lucas Theorem**

### Suggested Reading for Number Theory
- *Number Theory for Computing* by Song Y Yan (Simple book describing concepts in detail)
- Concepts are also superficially covered in Chapter 31 of *Introduction to Algorithms* by Cormen
- [Number Theory Tutorial on CodeChef](http://www.codechef.com/wiki/tutorial-number-theory)
- [Number Theory Category on Algorithmist](http://www.algorithmist.com/index.php/Category:Number_Theory)

### Problems on Number Theory
- [Number Theory Category on Algorithmist](http://www.algorithmist.com/index.php/Category:Number_Theory)
- [Problem Classifier for Number Theory](http://problemclassifier.appspot.com/index.jsp?search=number&usr=)


### 8. Math (Probability, Counting, Game Theory, Group Theory, Generating Functions, Permutation Cycles, Linear Algebra)

#### Probability
- **Syllabus**:
  - Basic probability and Conditional probability
- **Suggested Problems**:
  - [CT16E on SPOJ](http://www.spoj.pl/problems/CT16E/)
  - [CHICAGO on SPOJ](http://www.spoj.pl/problems/CHICAGO/)
- **Random Variables and Probability Generating Functions**
- **Mathematical Expectation + Linearity of Expectation**
  - **Suggested Problems**:
    - [FAVDICE on SPOJ](http://www.spoj.pl/problems/FAVDICE/)
    - [Topcoder Problem 10744](http://www.topcoder.com/stat?c=problem_statement&pm=10744)
- **Special Discrete and Continuous Probability Distributions**
  - Bernoulli, Binomial, Poisson, Normal distribution
  - **Suggested Problem**:
    - [SGU Problem 498](http://acm.sgu.ru/problem.php?contest=0&problem=498)
- **Suggested Readings**:
  - Cormen Appendix C (very basic)
  - [Topcoder Probability Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=probabilities)
  - [Wikipedia: Random Variable](http://en.wikipedia.org/wiki/Random_variable)
  - [Wikipedia: Expected Value](http://en.wikipedia.org/wiki/Expected_value)
  - *An Introduction to Probability Theory and Its Applications* by William Feller

#### Counting
- **Syllabus**:
  - Basic Principles: Pigeonhole Principle, Addition and Multiplication Rules
- **Suggested Problems**:
  - [Timus Problem 1690](http://acm.timus.ru/problem.aspx?space=1&num=1690)
  - [Topcoder Problem 10805](http://www.topcoder.com/stat?c=problem_statement&pm=10805)
- **Suggested Readings**:
  - [Wikipedia: Combinatorial Principles](http://en.wikipedia.org/wiki/Combinatorial_principles)
  - [Topcoder Combinatorics Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=combinatorics)
  - [MAA Pigeonhole Principle](http://www.maa.org/editorial/knot/pigeonhole.html)
- **Inclusion-Exclusion Principle**
  - **Suggested Readings**:
    - [Wikipedia: Inclusion-Exclusion Principle](http://en.wikipedia.org/wiki/Inclusion–exclusion_principle)
  - **Suggested Problems**:
    - [Topcoder Problem 4463](http://www.topcoder.com/stat?c=problem_statement&pm=4463&rd=6536)
    - [Topcoder Problem 10238](http://www.topcoder.com/stat?c=problem_statement&pm=10238)
- **Special Numbers**:
  - Stirling, Eulerian, Harmonic, Bernoulli, Fibonacci Numbers
  - **Suggested Readings**:
    - [Stirling Number](http://en.wikipedia.org/wiki/Stirling_number)
    - [Eulerian Numbers](http://en.wikipedia.org/wiki/Eulerian_numbers)
    - [Harmonic Series](http://en.wikipedia.org/wiki/Harmonic_series_(mathematics))
    - [Bernoulli Number](http://en.wikipedia.org/wiki/Bernoulli_number)
    - [Fibonacci Numbers](http://en.wikipedia.org/wiki/Fibonnaci_numbers)
    - *Concrete Mathematics* by Knuth
  - **Suggested Problems**:
    - [Topcoder Problem 1643](http://www.topcoder.com/stat?c=problem_statement&pm=1643)
    - [Topcoder Problem 8202](http://www.topcoder.com/stat?c=problem_statement&pm=8202&rd=11125)
    - [Topcoder Problem 8725](http://www.topcoder.com/stat?c=problem_statement&pm=8725)
    - [Topcoder Problem 2292](http://www.topcoder.com/stat?c=problem_statement&pm=2292&rd=10709)
- **Advanced Counting Techniques**:
  - Polya Counting, Burnside Lemma
  - **Suggested Reading**:
    - [Wikipedia: Burnside's Lemma](http://en.wikipedia.org/wiki/Burnside's_lemma)
    - [Burnside's Lemma by Petr Mitrichev](http://petr-mitrichev.blogspot.com/2008/11/burnsides-lemma.html)
  - **Suggested Problems**:
    - [Topcoder Problem 9975](http://www.topcoder.com/stat?c=problem_statement&pm=9975)
    - [TRANSP on SPOJ](http://www.spoj.pl/problems/TRANSP/)

#### Game Theory
- **Syllabus**:
  - Basic Principles and Nim Game
  - Sprague Grundy Theorem, Grundy Numbers
- **Suggested Readings**:
  - [Wikipedia: Sprague-Grundy Theorem](http://en.wikipedia.org/wiki/Sprague%E2%80%93Grundy_theorem)
  - [Topcoder Games Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=algorithmGames)
  - [AMS Feature Column on Games](http://www.ams.org/samplings/feature-column/fcarc-games1)
  - [CodeChef Game Theory Tutorial](http://www.codechef.com/wiki/tutorial-game-theory)
- **Suggested Problems**:
  - [Topcoder Problem 3491](http://www.topcoder.com/stat?c=problem_statement&pm=3491&rd=6517)
- **Hackenbush**:
  - **Suggested Readings**:
    - [Wikipedia: Hackenbush](http://en.wikipedia.org/wiki/Hackenbush)
    - [AMS Feature Column on Partizan Games](http://www.ams.org/samplings/feature-column/fcarc-partizan1)
  - **Suggested Problems**:
    - [Caltech IPSC Problem G](http://www.cs.caltech.edu/ipsc/problems/g.html)
    - [PT07A on SPOJ](http://www.spoj.pl/problems/PT07A/)

#### Linear Algebra
- **Syllabus**:
  - Matrix Operations
    - Addition and Subtraction of Matrices
  - **Suggested Reading**:
    - Cormen 28.1
  - **Multiplication (Strassen's Algorithm), Logarithmic Exponentiation**
    - **Suggested Reading**:
      - Cormen 28.2
      - *Linear Algebra* by Kenneth Hoffman, Section 1.6
    - **Problems**:
      - [UVa Problem 11149](http://uva.onlinejudge.org/external/111/11149.html)
  - **Matrix Transformations** (Transpose, Rotation of Matrix, Representing Linear Transformations Using Matrix)
    - **Suggested Reading**:
      - *Linear Algebra* by Kenneth Hoffman, Sections 3.1, 3.2, 3.4, 3.7
    - **Problems**:
      - [Topcoder Problem 6877](http://www.topcoder.com/stat?c=problem_statement&pm=6877)
      - JPIX on SPOJ
  - **Determinant, Rank, and Inverse of Matrix** (Gaussian Elimination, Gauss-Jordan Elimination)
    - **Suggested Reading**:
      - Cormen 28.4
      - *Linear Algebra* by Kenneth Hoffman, Chapter 1
    - **Problems**:
      - [Topcoder Problem 8174](http://www.topcoder.com/stat?c=problem_statement&pm=8174)
      - [Topcoder Problem 6407](http://www.topcoder.com/stat?c=problem_statement&pm=6407&rd=9986)
      - [Topcoder Problem 8587](http://www.topcoder.com/stat?c=problem_statement&pm=8587)
      - HIGH on SPOJ
  - **Solving System of Linear Equations**
    - **Suggested Reading**:
      - Cormen 28.3
      - *Linear Algebra* by Kenneth Hoffman, Chapter 1
    - **Problems**:
      - [Topcoder Problem 3942](http://www.topcoder.com/stat?c=problem_statement&pm=3942&rd=6520)
  - **Using Matrix Exponentiation to Solve Recurrences**
    - **Suggested Reading**:
      - [Topcoder Feature on Matrix Exponentiation](http://www.topcoder.com/tc?module=Static&d1=features&d2=010408)
    - **Problems**:
      - REC, RABBIT1, PLHOP on SPOJ
      - [Topcoder Problem 6386](http://www.topcoder.com/stat?c=problem_statement&pm=6386)
      - [Topcoder Problem 7262](http://www.topcoder.com/stat?c=problem_statement&pm=7262)
      - [Topcoder Problem 6877](http://www.topcoder.com/stat?c=problem_statement&pm=6877)
  - **Eigenvalues and Eigenvectors**
    - **Problems**:
      - [Topcoder Problem 2423](http://www.topcoder.com/stat?c=problem_statement&pm=2423&rd=4780)

#### Polynomials
- **Roots of a Polynomial**:
  - Prime Factorization of a Polynomial, Integer Roots of a Polynomial, All Real Roots of a Polynomial
  - **Problems**:
    - [Topcoder Problem 8273](http://www.topcoder.com/stat?c=problem_statement&pm=8273&rd=10798)
    - POLYEQ, ROOTCIPH on SPOJ
- **Lagrange Interpolation**
  - **Problems**:
    - [Topcoder Problem 10239](http://www.topcoder.com/stat?c=problem_statement&pm=10239)
    - [Topcoder Problem 8725](http://www.topcoder.com/stat?c=problem_statement&pm=8725)

#### Permutation Cycles
- **Suggested Reading**:
  - *Art of Computer Programming* by Knuth Vol. 3
  - **Problems**:
    - ShuffleMethod, Permutation, and WordGame on Topcoder

#### Group Theory
- **Burnside Lemma, Polya’s Theorem**:
  - **Suggested Reading**:
    - *Topics in Algebra* by Herstein
    - [Burnside's Lemma by Petr Mitrichev](http://petr-mitrichev.blogspot.com/2008/11/burnsides-lemma.html)
  - **Problems**:
    - TRANSP on SPOJ
    - [Topcoder Problem 9975](http://www.topcoder.com/stat?c=problem_statement&pm=9975)

#### Generating Functions
- **Suggested Reading**:
  - *Generatingfunctionology* by Herbert Wilf
  - *Combinatorial Analysis* by Robert Sedgewick and Flajoulet


### 9. Data Structures

#### Basic

##### Arrays/Stacks/Queues
- **Problems**:
  - [STPAR on SPOJ](https://www.spoj.pl/problems/STPAR/)
  - [SHOP on SPOJ](https://www.spoj.pl/problems/SHOP/)
  - [WATER on SPOJ](https://www.spoj.pl/problems/WATER/)
- **Reading**:
  - CLRS: Section 10.1
  - [Topcoder Data Structures Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=dataStructures)

##### Singly/Doubly Linked List
- **Problems**:
  - [POSTERS on SPOJ](https://www.spoj.pl/problems/POSTERS/)
- **Reading**:
  - CLRS: Section 10.2
  - *Data Structures and Algorithm Analysis in C++* by Mark Allen Weiss, Chapter 3

##### Hash Tables
- **Problems**:
  - [HASHIT on SPOJ](https://www.spoj.pl/problems/HASHIT/)
  - [CUCKOO on SPOJ](https://www.spoj.pl/problems/CUCKOO/)
- **Reading**:
  - CLRS: Chapter 11
  - *Data Structures and Algorithm Analysis in C++* by Mark Allen Weiss, Chapter 5

##### Circular Linked List / Queue
- **Problems**:
  - [CTRICK on SPOJ](https://www.spoj.pl/problems/CTRICK/)

##### Binary/n-ary Trees
- **Reading**:
  - CLRS: Section 10.4
  - CLRS: Chapter 12
  - *Data Structures and Algorithm Analysis in C++* by Mark Allen Weiss, Chapter 4
  - [Topcoder Tutorial on Binary Search Trees and Red-Black Trees](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binarySearchRedBlack)

##### Heaps
- **Problems**:
  - [PRO on SPOJ](https://www.spoj.pl/problems/PRO/)
  - [EXPEDI on SPOJ](https://www.spoj.pl/problems/EXPEDI/)
- **Reading**:
  - *Data Structures and Algorithm Analysis in C++* by Mark Allen Weiss, Chapter 6

#### Advanced

##### Trie (Keyword Tree)
- **Problems**:
  - [MORSE on SPOJ](https://www.spoj.pl/problems/MORSE/)
  - [EMOTICON on SPOJ](https://www.spoj.pl/problems/EMOTICON/)

##### Interval Trees / Segment Trees
- **Problems**:
  - [ORDERS on SPOJ](https://www.spoj.pl/problems/ORDERS/)
  - [FREQUENT on SPOJ](https://www.spoj.pl/problems/FREQUENT/)

##### Fenwick (Binary Indexed) Trees
- **Problems**:
  - [MATSUM on SPOJ](https://www.spoj.pl/problems/MATSUM/)
- **Reading**:
  - [Topcoder Binary Indexed Trees Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binaryIndexedTrees)

##### Disjoint Data Structures
- **Problems**:
  - [BLINNET on SPOJ](https://www.spoj.pl/problems/BLINNET/)
  - [CHAIN on SPOJ](https://www.spoj.pl/problems/CHAIN/)
- **Reading**:
  - [Topcoder Disjoint Data Structures Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=disjointDataStructure)
  - *Data Structures and Algorithm Analysis in C++* by Mark Allen Weiss, Chapter 8

##### Range Minimum Query (RMQ)
- **Problems**:
  - [GSS1 on SPOJ](https://www.spoj.pl/problems/GSS1/)
- **Reading**:
  - [Topcoder Lowest Common Ancestor Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=lowestCommonAncestor)

##### Customized Interval/Segment Trees (Augmented Data Structures)
- **Problems**:
  - [GSS3 on SPOJ](https://www.spoj.pl/problems/GSS3/)
  - [RRSCHED on SPOJ](https://www.spoj.pl/problems/RRSCHED/)
- **Reading**:
  - CLRS: Chapter 14 (Augmented Data Structures)

##### AVL Trees
- **Problems**:
  - [ORDERS on SPOJ](https://www.spoj.pl/problems/ORDERS/)

#### Miscellaneous (Not to be Covered)
- Splay Trees
- B/B+ Trees
- k-d Trees
- Red-black Trees
- Skip List
- Binomial/Fibonacci Heaps

#### Exercises
- [LAZYPROG on SPOJ](https://www.spoj.pl/problems/LAZYPROG/) (Hint: Heaps)
- [HELPR2D2 on SPOJ](https://www.spoj.pl/problems/HELPR2D2/) (Hint: Interval Trees)
- [SAM on SPOJ](https://www.spoj.pl/problems/SAM/) (Hint: Heaps)
- [PRHYME on SPOJ](https://www.spoj.pl/problems/PRHYME/) (Hint: Trie)
- [HEAPULM on SPOJ](https://www.spoj.pl/problems/HEAPULM/) (Hint: Interval Trees)
- [CORNET on SPOJ](https://www.spoj.pl/problems/CORNET/) (Hint: Disjoint Data Structures)
- [EXPAND on SPOJ](https://www.spoj.pl/problems/EXPAND/)
- [WPUZZLES on SPOJ](https://www.spoj.pl/problems/WPUZZLES/)
- [LIS2 on SPOJ](https://www.spoj.pl/problems/LIS2/)

### Search Techniques/Bruteforce Writing Techniques/Randomized Algorithms

#### Backtracking - [Beginner]
- **Problems**:
  - N Queens Problem
  - Knight’s Tour
  - Sudoku Problem
  - Tiling Problem
  - 15 Puzzle
- **Dancing Links and Algorithm X by Knuth - [Advanced]**
  - **Problems**:
    - PRLGAME, SUDOKU, NQUEEN on SPOJ
  - **Suggested Reading**:
    - [Dancing Links by Donald Knuth](http://www-cs-faculty.stanford.edu/~uno/papers/dancing-color.ps.gz)

#### Binary Search - [Beginner]
- **Problems**:
  - AGGRCOW on SPOJ
  - Finding all real roots of a polynomial using binary search [Intermediate]
- **Suggested Reading**:
  - [Topcoder Binary Search Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binarySearch)

#### Ternary Search - [Intermediate]
- **Problems**:
  - [KPPOLY on SPOJ](http://www.spoj.pl/problems/KPPOLY/)
  - [K1 on CodeChef](http://www.codechef.com/DEC09/problems/K1/)
  - [Topcoder Problem 4705](http://www.topcoder.com/stat?c=problem_statement&pm=4705&rd=7993)
  - [Topcoder Problem 7741](http://www.topcoder.com/stat?c=problem_statement&pm=7741&rd=10671)
  - [Topcoder Problem 6464](http://www.topcoder.com/stat?c=problem_statement&pm=6464&rd=9994)
  - [Topcoder Problem 3501](http://www.topcoder.com/stat?c=problem_statement&pm=3501&rd=6529)
  - [Topcoder Problem 4567](http://www.topcoder.com/stat?c=problem_statement&pm=4567&rd=6539)

#### Meet in the Middle - [Intermediate]
- **Problems**:
  - [MAXISET on SPOJ](http://www.spoj.pl/problems/MAXISET/)

#### Hill Climbing - [Advanced]

#### Regular Iteration to Reach a Fixed Point - [Advanced]

#### Newton-Raphson Method to Find Root of a Mathematical Function

#### Iterations to Solve Linear Non-Homogeneous System of Equations

### General Programming Issues in Contests

#### Arithmetic Precision - [Beginner]
- **Suggested Reading**:
  - [Topcoder Arithmetic Precision Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=integersReals)

#### Representing Sets with Bitmasks and Manipulating Bitmasks - [Beginner]
- **Suggested Reading**:
  - [Topcoder Bit Manipulation Tutorial](http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=bitManipulation)
- **Problems**:
  - Refer to the tutorial link in Suggested Reading section.
