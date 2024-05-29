This repository contains all of my lecture contents, practice sheets and other course materials of the course Automata and Computability.

------------------

**Table of Contents**


- [Course Overview](#course-overview)
    - [Course Outline](#course-outline)
    - [Tentative Marks Distribution](#tentative-marks-distribution)
    - [Resources](#resources)
      - [Textbooks](#textbooks)
      - [Other Resources](#other-resources)
    - [Consultation](#consultation)
- [Lecture 1](#lecture-1)
  - [Theory of Computation](#theory-of-computation)
  - [What is Computability theory?](#what-is-computability-theory)
  - [What is Automata theory?](#what-is-automata-theory)
  - [Essential Mathematical Notions and Terminologies](#essential-mathematical-notions-and-terminologies)
    - [Sets and Tuples](#sets-and-tuples)
      - [Subset](#subset)
    - [Strings and Languages](#strings-and-languages)
    - [Regular operations](#regular-operations)
  - [Regular Language and Finite Automata](#regular-language-and-finite-automata)
    - [DFA (Deterministic Finite Automata)](#dfa-deterministic-finite-automata)
    - [Example Problems](#example-problems)
- [Lecture 2](#lecture-2)

# Course Overview
### Course Outline
| Week                                                                       | Theory                                                                                                                                                                                                                | Assessment                                                |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| Week 1<br>May 28-30                                                        | Lecture 1: Alphabets, Strings, Languages, and an Introduction to Deterministic Finite Automata (DFA) and Regular Languages.                                                                                           |                                                           |
| Week 2<br>June 1-6                                                         | Lecture 2: More Examples of DFAs, the Regular Operations.<br><br>Lecture 3: Problem Solving on Designing DFAs.                                                                                                        |                                                           |
| Week 3<br>June 8-13                                                        | Lecture 4: Closure of Regular Languages Under Union: The Cross Product Construction.<br><br>Lecture 5: Introduction to Nondeterministic Finite Automata (NFA), Converting NFAs to DFAs using the Subset Construction. |                                                           |
| Week 4<br>June 15-20<br>Eid-ul-Adha                                        |                                                                                                                                                                                                                       |                                                           |
| Week 5<br>June 22-27                                                       | Lecture 6: More Examples of NFAs, Closure of Regular Languages under the Regular Operations.<br><br>Lecture 7: Introduction to Regular Expressions, Examples of Regular Expressions.                                  |                                                           |
| Week 6<br>June 29-July 4                                                   | Lecture 8: More Examples of Regular Expressions, Converting Regular Expressions to NFAs.<br><br>Quiz 1 (DFAs and the Regular Operations) and Discussion.<br>                                                          | Quiz 1 (DFAs, the Regular Operations)                     |
| Week 7<br>July 6-11                                                        | Lecture 9: Converting DFAs to Regular Expressions using State Elimination.<br><br>Quiz 2 (Regular Expressions, their equivalence with DFAs), and Discussion.                                                          | Quiz 2 (Regular Expressions, their equivalence with DFAs) |
| Midterms Week<br>July 12-21<br>Midterm Exam: Date (Time)                   |                                                                                                                                                                                                                       | Midterm Exam: Date (Time)                                 |
| Week 8<br>July 22-25                                                       | Lecture 10: Nonregular Languages, the Pumping Lemma for Regular Languages.<br><br>\* One Extra Day for Monday Schedule [August 26 makeup]                                                                             |                                                           |
| Week 9<br>July 27-August 1                                                 | Lecture 11: Introduction to Context-Free Grammars (CFG) and Context-Free Languages (CFL).<br><br>Lecture 12: CFGs continued, Parse Trees, Derivations, and Ambiguities.                                               |                                                           |
| Week 10<br>August 3-8<br>                                                  | Lecture 13: Designing CFGs and Discussion.<br><br>Quiz 3 (Context-Free Grammars) and Discussion.                                                                                                                      | Quiz 3 (Context-Free Grammars)                            |
| Week 11<br>August 10-15<br><br>August 15: National Mourning Day (Thursday) | Lecture 14: Putting a Grammar into Chomsky Normal Form.<br><br>Lecture 15: The Cocke-Younger-Kasami Algorithm.                                                                                                        |                                                           |
| Week 12<br>August 17-22<br>                                                | Lecture 16: Introduction to Pushdown Automata (PDA)<br><br>Lecture 17: Designing PDAs and Examples.                                                                                                                   |                                                           |
| Week 13<br>August 14-29<br><br>August 26: Janmashtami (Monday)             | Lecture 18: More PDAs and Review<br><br>Quiz 4 (CNF, CYK, and PDAs)                                                                                                                                                   | Quiz 4 (CNF, CYK, and PDAs)                               |
| Finals Week<br>August 31- September 8<br>Final Exam: Date                  |                                                                                                                                                                                                                       | Final Exam<br>Time<br>Date                                |
### Tentative Marks Distribution
| Marks Distribution     | %  |
| ---------------------- | -- |
| Assignments            | 10 |
| Quiz (Best 3 out of 4) | 20 |
| Attendance             | 10 |
| Mid                    | 25 |
| Final                  | 35 |

### Resources
#### Textbooks
- Sipser, M. ***Introduction to the Theory of Computation.*** [Link](https://drive.google.com/file/d/1Ec1lv0JcvMVUVyQ2Cq9EbsAVatoZSpMC/view?usp=drive_link)
- Hopcroft, J., R. Motwani and J.D. Ullman *Introduction to automata theory, languages and computation.* [Link](https://drive.google.com/file/d/1TmGgNfuc97OqM3BYJSRtz1qDKX81iy2-/view?usp=drive_link)
- Kozen, D.C. *Automata and Computability*. [Link](https://vishub.org/officedocs/13770.pdf)
#### Other Resources
- **[Mursalin Sir's Class Recordings](https://drive.google.com/drive/folders/1PtQaX_Sn47wt11GPSp-7TkgrNdwYvHwV?usp=drive_link)**
- **[Farhan Feroz Sir's Youtube Playlist](https://www.youtube.com/playlist?list=PLBENQsMXh3gz85EJ3ZCSa9l9hnUiOer-H)**
- [MIT Micheal Sipser's Lectures](https://www.youtube.com/playlist?list=PLUl4u3cNGP60_JNv2MmK3wkOt9syvfQWY) {writer of the Text book we follow} (First 4 Lectures only)
- [Easy Theory Youtube Channel](https://www.youtube.com/@EasyTheory/featured)
- [University of California Davis Lectures](https://www.youtube.com/playlist?list=PLslgisHe5tBM8UTCt1f66oMkpmjCblzkt)
- [CS103 Stanford University Lecture Slides](https://web.stanford.edu/class/archive/cs/cs103/cs103.1184/)
- [Professor Harry Potters Playlist](https://www.youtube.com/playlist?list=PLbtzT1TYeoMjNOGEiaRmm_vMIwUAidnQz)
- [Anisul Islam's Playlist](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qw5pu16QgnKNj91Rnjoyd0)

### Consultation
Email: ext.monirul.haque@bracu.ac.bd
Timing Will be added after confirmation of my routine.

# Lecture 1
## Theory of Computation
Theory of Computation deals with the fundamental mathematical properties of computer hardware, software, and certain applications. In researching this topic, we want to know what can and cannot be computed, how quickly, with how much memory, and on what type of computational model. Traditionally the central three areas of Theory of Computation are: automata, computability, and complexity.

<p align="center">
  <img src="Media/Lecture1/lec1fig1.png" />
</p>

I know some of you might be interested in mathematical stuffs but some of you here are out of choice. You may just want to obtain a degree in Computer Science, and a course in theory is required—God knows why. After all, isn’t theory arcane, boring, and worst of all, irrelevant?
Well, theory can be sometimes boring and tiresome but it is fun to solve Automata problems (you'll see shortly).

<p align="center">
  <img src="Media/Lecture1/lec1fig2.png" />
</p>

Also, theory is not totally irrelevant and useless. Here's an idea of how the theory you learn here will be of useful for you in practice:
* Designing a new programming language for a specialized application? 
  You need **Context free grammar (CFG)**.
* Dealing with string searching and pattern matching? 
   You need **finite automata (DFA, NFA)** and **regular expressions** (Example: python regex)
* You want to do Parts of Speech (POS) Tagging in Natural Language Processing (NLP)?
   You need **CFG, Chomsky normal form,  parsing trees, Cocke–Younger–Kasami algorithm (CYK)** etc.
* Markov chains are probabilistic counterpart of finite automata.

If you think you will not work on any of those use cases, solving Automata can increase your problem solving skills as  .So, let's start learning.

## What is Computability theory?
Have you noticed that computer can not determine whether a mathematical statement is true or false? Similarly, there are countless mathematical functions that can not be computed by the computer. 
In mathematical theory a lot of problems can be solved but in computability theory we prove whether these problems can be solved using computer or not. Basically, Computability is a subject where we  study and prove what the fundamental capabilities & limitations of computers are.

## What is Automata theory?
Automata is the definitions and properties of mathematical models of computation. It is the study of abstract machines/computers. An automaton is an abstract computer/machine. 
Automata theory has applications in programming language design, compiler construction, text processing, software verification, and natural language processing etc.

## Essential Mathematical Notions and Terminologies
### Sets and Tuples
* A set is a group of objects represented as a unit. Example: S = {7, 21, 57}      
* Those objects are called elements or members of that set.

A set of Natural Numbers, N = {1, 2, 3…}	[Often 0 is considered Natural too]
A set of Integers, Z = {…-3, -2, -1, 0, 1, 2, 3…}	
A set of Real Numbers, R = {…-3, … , -2.5, … , 0, …, 1.12957…}
The set with zero members is called the empty set and is written ∅.
A set with two members is called an unordered pair.

Example of a set,
S = {n| n = m2 for some m ∈ N} 	
   = {1, 4, 9, 16...}					
Here, **|** symbol means **"such that"** and **∈** means **"element of"** or **"belongs to"**.              
We can write, 7 ∈ {7, 21, 57} and 8 ∉ {7, 21, 57} 

* Elements order does not matter in sets.
* Finite Sequences are called tuples. Example: (7, 21, 57)
* A set can contain tuples for example, S = {(a, b), (1, c)}

#### Subset
* A is a subset of B, written A ⊆ B, if every member of A also is a member of B. 
* A is a proper subset of B, written A⊂B, if A is a subset of B and not equal to B.
Example: 
If  A = {1, 2, 3}; 	B = {1, 2, 3}    Then, A ⊆ B  and A⊂B
If  A = {1, 2}; 	B = {1, 2, 3}    Then, A ⊆ B  and A⊂B

### Strings and Languages
* Symbol: a character
  Example: a, c, Z, 0, 9, α, ক
* Alphabet: a finite set of symbols 
  *We generally use capital Greek letters capital sigma Σ or capital gamma Γ to designate alphabets*
* String: a finite sequence of symbols over an alphabet set. 
  *An empty string is represented using epsilon, ε*
  *Any part of a string is called substring*
* Language: a set of strings
Example: 
Σ = {0,1} 			
01001 is a string over Σ   		
{0, 01, 10, 01001} is a language over Σ  

### Regular operations
Suppose, 
A = {1, 3, 4}	  
B = {3, 4, 6}   
Universal set, U = {1, 2, 3, 4, 5, 6}

<p align="center">
  <img src="Media/Lecture1/lec1fig3.png" />
</p>
 
**Compliment** of A = **A̅**= {2, 5, 6}
**Union** of A and B = **A ∪ B** = {1, 3, 4, 6}
**Intersection** of A and B = **A ∩ B** = {3, 4}

Suppose,
String P = "Bangla"
String Q = "desh"

**Concatanation** of P and Q = **P◦Q** = {xy| x ∈ P and y ∈ Q} = "Bangladesh"
**Kleene Closure** of Q = Q* = {x<sub>1</sub>x<sub>2</sub> . . . x<sub>k</sub>| k ≥ 0 and each x<sub>i</sub> ∈ Q} = ε, desh, deshdesh, deshdeshdesh...

## Regular Language and Finite Automata
* Finite automata are mathematical models for computers with an extremely limited amount of memory.
* Automata is a plural form of Automaton. So, a single model is called a finite automaton or a finite state machine.
* A language is called a regular language if some finite automaton recognizes it.


<p align="center" weight="bold">
Regular Language for the given automaton should be, </br>
<b>L = {w ∈ {0, 1}* | w has a substring 11}</b>
</p>

<p align="center">
  <img src="Media/Lecture1/lec1fig4.png" />
  <i>Source: MIT Lecture of Micheal Sipson</i>
</p>

<p align="center">
  <img src="Media/Lecture1/lec1fig5.png" />
  <i>Source: Micheal Sipson' book page 35-36</i>
</p>

Types of finite automata: 
- Deterministic finite automata **(DFA)** 
- Non-deterministic finite automata **(NFA)**

The example we saw above is a DFA.

### DFA (Deterministic Finite Automata)
* A DFA accepts or rejects an input string based on whether a regular language reaches a final/accept state or not. 
* From each state a transition leads to a unique state.

* What we can’t do in DFA design:
  * Multiple starting states (Remember it can have multiple accept states)
  * Empty/null/epsilon (ε) transitions
  * Multiple different transitions for a single symbol
  * Any state with no transitions or partial transitions
### Example Problems

  


# Lecture 2
To be added.


