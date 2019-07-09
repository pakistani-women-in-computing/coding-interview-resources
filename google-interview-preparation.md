# INTERVIEW PROCESS AT GOOGLE
The interview process generally looks like below
 
0. Preparation time, study & practice → for experienced SWE (4-12 weeks), for beginners (6-12 months)
1. Hangouts Screening Technical Interview (1-2 interview x 45 mins) - Software Engineering Position
   For two different programming languages probably more than 1x screening interview.
2. Onsite Interviews (4-5 interviews x 45 mins at a Google office)
    2 x for C++ and 2 x for C# (or your primary working language)
    Until this stage there is no team allotted and only after successful onsite we look for a team for the candidate.
3. Team Matching (~1 week) 
4. EMEA Hiring Committee review (~1 week)
5. US Hiring Committee & Offer Review (~1-2 weeks)

## Preparing for Software Engineering Position:

### How much time you need?
- Experienced SWE - 4 to 12 weeks 
- Beginner SWE - 6 to 12 months
- Study & practice everyday 3 hrs and weekends 6 hrs
- Train your muscle to solve problems with countdown time (~30 mins)

### Initial Study Plan 
* First read the Cracking the Coding Interview (CTCI) 6th Ed. Book Chapters without thinking too much about the solutions of problems. Try to get as much theory knowledge as you can from the book related to various topics. The problems in interview maybe similar to some problem you know but high chances are they will occur as new to you, there you'll need this theoretical knowledge to break problem down. 
Once the theory is covered,goto exercise section and try to understand the question. It is more important to understand the problem question than actually even solving it. Intially try to make a Brute Force attempt to solve problem and improve the solution gradually. If you are not able to  solve it, take hints, search a little bit about problem, get a brief break-down. If still no luck, then download solutions and read it carefully to understand its logic and concept. If you dint write algorithm yourself, then do practice the one you downloaded on paper.

* Use white board and a temporary marker to solve problems, this will be the actual tool you will get to solve problems during onsite  interviews.

* If you are not understanding a solution that you have downloaded from github better google the problem and get a geeksforgeeks solution’s pseudocode and try to code it yourself. 

* Use C++ solutions and later practice in C# (or your prefered primary language).

* Once CTCI problems are done practice leetcode.com , hackerrank or algoexperts problems of Easy, Medium and Hard level. 
Maybe you will need to do CTCI problems few times to get grasp on those.

* Don’t forget to go through the advanced topics section in CTCI.

* You should have a last 2 x days revision plan before the interview date and also plan for InFlight/Interview morning topics ready on tips cards. These are the things you think are hard to remember, so you would like to see them as last thing before interview.

### What to Study Topics
First, the absolute must-haves, in order:
- Trees (especially Binary Search Trees)
- Big O Notation
- Hash Tables
- Object Oriented Design/Systems Design
- Algorithms: Breadth First Search/Depth First Search, Binary Search, Merge Sort and Quicksort
 
### Problem Analysis Methods
- Brute Force
- Divide and Conquer
- Recursion
- Dynamic Programming
- Greedy Algorithms

### All Topics to cover
(You'll need to to talk about how they're implemented and why you'd choose one implementation or data structure instead of another.)

##### General Topics
- Recursion
- Iterative Algorithm
- Dynamic Programming
- Pointers in C++
- Big O, you must be able to derive the complexity without actually coding an algo.
- Array, ArrayList, Dynamic Arrays, 2D Arrays, Vectors

#### Hashtable
- Hashing Function
- Collisions, Methods to avoid Collisions
- Clustering in Hash-tables
- Set, Hashset, Bags

#### LinkedList
- Singly
- Double
- Circuler
- Cycle Detection in Linked-List

#### Stack and Queues

#### Trees
- Binary Tree
- Binary Search Tree
- Ternary Tree
- Red Black Tree
- AVL Tree
- Tree Balancing
- Minimum Spanning Tree
- Tree Traversal
- N-ary Tree
- Trie Tree
- Balanced Tree
- Min/Max Heap

#### Graphs
- Shortest path on unweighted Graph
- Breadth First Search & Depth First Search

#### Paths
- All pairs shortest path
- Single Source Shortest path
- Dijkstra
- A*

#### Bellman Ford

#### Bit Manipulation

#### Regular Expressions

#### Basic Discrete Mathematics and Maths from CTCI Book

#### Operating System Concepts

- Scheduling

- Context Switching

- Threads

- Deadlocks

### General Sorting and Searching

#### Sorting: 
- Bubble Sort
- Quick Sort
- Merge Sort
- Radix Sort
- Heap Sort
- Insert Sort
- Search : 
- Binary Search

***You must know and discuss tradeoff of using them on different type of input data***

#### Time Complexity of Sorts
- Insert Sort -> O(n^2) [Insert into a new array at sorted position] [Better than selection sort]
- Selection Sort -> O(n^2) [First loop to run n times and second to find the min and then swap at first loops index]
- Bubble Sort -> O(n^2) use for loop and keep swapping between each pair of elements till list get sorted
- Quick Sort -> O(n log n) Worst O(n^2) Take a pivot from middle using filter, sort left and right using recursive algos. 
- Merge Sort -> O(n log n) all cases, split array into two and use three while looped merge to combine
- Heap Sort -> (n log n) use selection sort on a heap instead of an array
- Counting Sort -> O(n+K) Create an array with 0s to Max number and fill it with occurrences and then add the previous index to current, at last just reduce the countArray to -1 and take the counting array element and place it in sorted array Got it? Of Course No
- Radix Sort -> O(n+K)  : Use counting sort to solve 

***Most importantly you'll need to be able to pick the right data structure and algorithm for a specific problem.***

### Test Cases
* Edge case occurs at an extreme (maximum or minimum) operating parameter.
* Corner case occurs outside of normal operating parameters, specifically when multiple environmental variables or conditions are simultaneously at extreme levels, even though each parameter is within the specified range for that parameter. (The "outside normal operating parameters" obviously means something like "outside typical combination of operating parameters", not strictly "outside allowed operating parameters". That is, you're still within the valid parameter space, but near its corner.)
* Boundary case occurs when one of inputs is at or just beyond maximum or minimum limits.
* Base case is where Recursion ends

---------------------------------
### Preparing for technical interview
- Algo Expert: https://www.algoexpert.io  (Premium member - 65 questions)
- LeetCode: https://leetcode.com/problemset/algorithms/
- GeekForGeeks: https://www.geeksforgeeks.org 
- Youtube-codes: https://github.com/mission-peace/interview/tree/master/src/com/interview
- Byte by Byte: https://www.youtube.com/channel/UCWSYAntBbdd2SLYUqPIxo0w
- Topcoder: https://www.topcoder.com
- Codechef: https://www.codechef.com/
- Hackerrank: https://www.hackerrank.com
- Interviewbit: https://www.interviewbit.com/
- CodeJam: https://codingcompetitions.withgoogle.com/codejam
- Daily Coding Problem: https://dailycodingproblem.com/
- Project Euler: https://www.hackerrank.com/contests/projecteuler/challenges

### Google Style Guides for programming languages
- http://rkpprogramming.wordpress.com/
- http://paultyma.blogspot.com/2007/03/howto-pass-silicon-valley-software.html
- http://www.karrels.org/Ed/ACM/
- http://www.cs.oswego.edu/~mohammad/contest/f05/Problems.htm
- https://ioinformatics.org/?r=301

### Life at Google Videos
- Watch How we hire https://www.youtube.com/watch?v=k-baHBzWe4k&t=7s
- Watch How to Prepare for a Technical Interview https://www.youtube.com/watch?v=ko-KkSmp-Lk
- Watch Example of a coding interview https://www.youtube.com/watch?v=XKu_SEDAykw&feature=em-subs_digest
- Watch Interview tips from Google Software Engineers https://www.youtube.com/watch?v=XOtrOSatBoY
- Watch Candidate Interviewing Practice for Google https://www.youtube.com/watch?v=oWbUtlUhwa8&feature=youtu.be

### Useful Blogs
- Google Interview Preparation http://blog.gainlo.co/index.php/category/google-interview-preparation/
- Top 10 Algos for Coding Interview http://www.programcreek.com/2012/11/top-10-algorithms-for-coding-interview/
- Steve Yegge Blogpost https://medium.com/@nick.ciubotariu/ace-the-coding-interview-every-time-d169ce1fd3fc
- Big O Notations http://bigocheatsheet.com/ 
- System Design https://gist.github.com/vasanthk/485d1c25737e8e72759f 
- Graphs  https://www.youtube.com/channel/UCZLJf_R2sWyUtXSKiKlyvAw
- Graphs and Topological Sort https://www.youtube.com/watch?v=ddTC4Zovtbc 
 
### Online Univeristy Courses
Google hires a lot of graduates from Stanford and MIT, but you don’t have to attend these colleges to benefit from their courses. You can find the MIT Computer Science courses through free Opencourseware. 
Here’s just a selection:
- 6.006: Introduction to Algorithms https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-spring-2008/
- 6.033: Computer System Engineering https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/
- 6.172: Performance Engineering of Software Systems https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-172-performance-engineering-of-software-systems-fall-2010/
- 6.717: Software Engineering for Web Applications https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-171-software-engineering-for-web-applications-fall-2003/
 
### Useful Books
- "Cracking the Coding Interview" 6th Ed. by Gayle Laakmann McDowell
- "Introduction to Algorithms" 3rd Ed. by Thomas H. Cormen
- “The Algorithm Design Manual, 2nd Ed. - Steven Skiena -  Algorist
- Programming Pearl by Jon Bentley 2nd Ed.
- Recommended Books for specific language: C++
- Effective C++ Vol. 1 by Scott Meyers
- More Effective C++ by Scott Meyers
- Programming Interviews Exposed: “Secrets to Landing Your Next Job” By John Mongan, Eric Giguere, Noah Suojanen, Noah Kindler

--------------------------------- 
### Tips for Interview Topics [Source:Google]
#### Coding practice:
You can find sample coding questions on sites like CodeLab, Quora, and Stack Overflow. The book “Cracking the Coding Interview” is also a good resource. Be sure to test your code and ensure it’s easily readable without bugs. Don’t stress about small syntactical errors like which substring to use for a given method (e.g. start, end or start, length) — just pick one and let your interviewer know.
####  Coding:
You should know at least one programming language really well, preferably Objective C, Swift C++, Java, Python. You will be expected to know APIs, Object Oriented Design and Programming, how to test your code, as well as come up with corner cases(occurs outside of normal operating parameters) and edge cases (occurs at an extreme of operating parameters). Note that we focus on conceptual understanding rather than memorization. Try to write it in an elegant way. This should be clean, rich, robust code. There will be no auto-correction – so please practice that. Time balance is well appreciated. Sometimes the code might be very good, but it takes way too much time to a candidate to create it. 
#### Algorithms: 
Approach the problem with both bottom-up and top-down algorithms. You will be expected to know the complexity of an algorithm and how you can improve/change it. Algorithms that are used to solve Google problems include sorting (plus searching and binary search), divide-and-conquer, dynamic programming/memoization, greediness, recursion or algorithms linked to a specific data structure. Know Big-O notations (e.g. run time) and be ready to discuss complex algorithms like Dijkstra and A*. We recommend discussing or outlining the algorithm you have in mind before writing code.
#### Sorting:
Be familiar with common sorting functions and on what kind of input data they’re efficient on or not. Think about efficiency means in terms of runtime and space used. For example, in exceptional cases insertion-sort or radix-sort are much better than the generic QuickSort/MergeSort/HeapSort answers.
#### Data Structures: 
You should study up on as many data structures as possible. Data structures most frequently used are arrays, linked lists, stacks, queues, hash-sets, hash-maps, hash-tables, dictionary, trees and binary trees, heaps and graphs. You should know the data structure inside out, and what algorithms tend to go along with each data structure.
#### Mathematics: 
Some interviewers ask basic discrete math questions. This is more prevalent at Google than at other companies because counting problems, probability problems and other Discrete Math 101 situations surround us. Spend some time before the interview refreshing your memory on (or teaching yourself) the essentials of elementary probability theory and combinatorics. You should be familiar with n-choose-k problems and their ilk.
#### Graphs:
Consider if a problem can be applied with graph algorithms like distance, search, connectivity, cycle-detection, etc. There are three basic ways to represent a graph in memory (objects and pointers, matrix, and adjacency list) — familiarize yourself with each representation and its pros and cons. You should know the basic graph traversal algorithms, breadth-first search and depth-first search. Know their computational complexity, their tradeoffs and how to implement them in real code.
#### Recursion:
Many coding problems involve thinking recursively and potentially coding a recursive solution. Use recursion to find more elegant solutions to problems that can be solved iteratively.
 
### Additional Tips:
- You need to know Big O complexity analysis really well - it’s OK to quickly come up with a brute force solution, but that’s never going to be the answer - always look for an O(n*logn) solution or ideally a linear one
- Hash tables - be able to implement one using only arrays
- Trees - know tree construction, traversal, and manipulation algorithms. Familiarize yourself with binary trees, n- ary trees and trie- trees, and at least one type of balanced binary tree
- Mathematics relating to statistics and probability is also useful to know
- Sample topics: construct/ traverse data structures, implement system routines, distill large data sets to single values, transform one data set to another
 
 
### General Interview Tips 
The following are a few details that can make an interview go more smoothly:
 
- Always practice doing the coding questions on a whiteboard, not on a computer.  Ask clarifying questions and make sure you know exactly what you are building before you start writing code.
- Make sure you practice Design questions like : Design Twitter, design a url shortening service, Design Dropbox etc.  There is a ton of content on YouTube on this.  These questions can be a make or break situation for many candidates, so spend some extra time on these.
- Be ready to explain in details some of the complex problems you have solved in your earlier positions with tradeoffs, design decisions you took.  Were there any lessons you learned and how did you fix the issues?
- Take your own dry erase markers with a fine tip for Interview.  It helps you draw and write clean code.
- Do not assume all numbers are ints. Ask for clarification if necessary.
- Do know how to use some sort of map data structure from the standard library of your language of choice; e.g. java.util.HashMap in Java.
- Do know how to use a good sorting algorithm from the standard library of your preferred language; e.g. Collections.sort() and Arrays.sort() in Java.
- Do know how to copy and resize an array if necessary. (Arrays.copyOfRange in Java).
- Try to avoid mutating arguments in your solution.
- Once you've got a solution, try to walk though the code with some small input. E.g. if you're asked to calculate the nearest integer to a square root of an integer without using floating point numbers, try your solution with 1, with 3, with 4. Talk it out with your interviewer as you do this.
 
### Common follow up questions from Google Interviewer (once you have a solution)
- What's the performance? (e.g. O(N^2), N lg N, etc.) Can you do better?
- How do you test the solution?
- Is this thread safe? If not, can you make it so?
- How do you distribute the solution for very large data sets?
 
### Common Mistakes to avoid during the Interview 
- Not thinking  through the solutions clearly
- Relying too much on interviewer hints. 
- Working at a very slow pace, not clear when expressing the thoughts.
- Not checking bugs in the code.
- Getting nervous.
- Not Managing to design or produce working algorithm for the problem.
- Not deep understanding of analyzing data structures
- Not being able to solve the problem with pseudocode  and not understanding the objections.
- Not asking clarifying questions to the interviewer(if something remains unclear)

---------------------------------

## Google Interview Process [Source:Google]

### Hangouts Technical Interview
This is a 45 minutes Technical Interview with a Google Software Engineer over Hangouts. The interviewer will share with you a Google Doc and will be interested in your knowledge of computer science principles (for this step, you should know Big-O really well, along with data structures, searching and sorting algorithms, trees and hash tables,  lists, maps, stacks, priority queues, binary trees, graphs, bags, and sets.) and how it is applied in your solutions. Our engineers want you to demonstrate that you can comprehend and solve the problem quickly with clean, efficient, optimal code. 
 
### Interview Questions
Interview topics may cover anything from coding questions, building and developing complex algorithms and analyzing their performance characteristics, logic problems, systems design and core computer science principles. Computer Science fundamentals are a prerequisite for all engineering roles at Google, due to the complexities and global scale of the projects you would end up participating in. 
 
We suggest that you use hands-free headset so you can type freely during the conversation.
 
#### What you can usually expect during the interview
It might be or not a quick introduction depends on the interviewer,
Warm-up questions: you can be asked to write something simple – as “hello world” – and  if it is a simple task – please, keep it simple, no need for 50 lines ... 
Complex questions: it will be a problem-solving task. 
For example, write an algorithm to solve the SUDOKU. Or: Travel tasks: Three friends are traveling for a weekend – one is paying for a hotel, one for food, one for a flights – after the weekend they need to know who has to pay what and to whom. - your role is to find an algorithm to solve this challenge. 
First and the most important  is to understand the problem, then - come up with an algorithm, translate it into actual code (in shared document) and test your code. The questions asked by the interviewer will be open-ended questions. If you don’t feel you have understand questions/ tasks -  ask clarifying questions. “I am writing in assuming…,.....”
 
One of the keys to success is to understand the task.
 
For algorithms you'll want to know greedy algorithms, divide and conquer, dynamic programming, recursion, and brute force search. You'll definitely want to be conversant with big O notation, time space complexity, and real world performance of all of this. Most importantly you'll need to be able to pick the right data structure and algorithm for a specific problem.
Also, when explaining the algorithm that will solve the problem (in natural language) Try to be clear on your idea and  the steps you are following e.g. you can explain saying “I am going to code it down first and review for smaller mistakes afterwards”…
 
The communication during the interview is also important.  
At the end you may ask some questions to the interviewer – Technical questions (that I will not be able to response, I can response regarding e.g. about the process or benefits) Actually - it’s your opportunity to talk to a Google Engineer.

### System Design Interview
One of the onsite interview will likely focus on System Design. Several tips are below:
- You need to be able to do back of the envelope calculations!
- Know your powers of 2 (binary)
- Be able to express mega/giga/etc. in binary and/or scientific notation
- Explain and justify your assumptions
- Don’t be afraid of dealing with huge numbers!
- Know a variety of searching and sorting algorithms (Quicksort, Mergesort, Hash Tables,etc.) - know more than one O(n*logn) sorting algorithm - how they work
- System design questions are a test of your problem solving skills - ask qualifying questions - make sure you explain your thought process - explain and justify your assumptions
- A recommended video is: 
Building Software Systems at Google https://www.youtube.com/watch?v=modXC5IWTJI

### The Large Scale Design Interview
System Design - Questions are used to assess a candidate's ability to combine knowledge, theory, experience and judgement toward solving a real-world engineering problem. In other words, can a candidate "design policies, processes, procedures, methods, tests, and/or components from ground up.

Sample topics include: features sets, interfaces, class hierarchies, distributed systems, designing a system under certain constraints, simplicity, limitations, robustness and tradeoffs. You should also have an understanding of how the internet actually works and be familiar with the various pieces (routers, domain name servers, load balancers, firewalls, etc.). 
Other topics include: traverse a graphs, run-time complexity of graphs, distributed hash table system, resource estimation with real systems, big product design picture, translation of an abstract problem to a system, API discussions, binary trees, cache, mapreduce, for loop problems, index, reverse link-list, compilers, memory cache, networks and also common topics.

Operating Systems - You should understand processes, threads, concurrency issues, locks, mutexes, semaphores, monitors and how they all work. Understand deadlock, livelock and how to avoid them. Know what resources a process needs and a thread needs. Understand how context switching works, how it's initiated by the operating system and underlying hardware. Know a little about scheduling. We are rapidly moving towards multi-core, so know the fundamentals of "modern" concurrency constructs.

### Behavioural Interview
This topic is broad, search about it on youtube and relate it to story of your life. 
For a starter check out this article: https://www.byte-by-byte.com/behavioral-interviews/

---------------------------------
- Document compilation Credits:
Asema Hassan and Nasir Mahmood

- Source: 
Google, YouTube, Recruiter Tips
